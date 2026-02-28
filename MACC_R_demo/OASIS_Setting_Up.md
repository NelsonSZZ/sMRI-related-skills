# Intro 

Every statistical test is a linear model asking: "does knowing X help me predict Y, beyond chance?"
> with this, all statistical test answers the same question, just different data shapes. 

# First section
## Free R Environment and Loading OASIS

```R

install.packages(c("tidyverse", "lme4", "lmerTest", "car", "readxl"))

# load packages

library(tidyverse)
library(readxl)
library(lme4)
library(lmerTest)
library(car)
library(readxl)

oasis <- read_excel("MACC_OASIS_DATA/oasis_cross_sectional.xlsx")

# First look - Make sure to do this everytime before anything else

str(oasis) 
summary(oasis) 
head(oasis, 11) # Returns the first 11 rows 

# Prepare data

oasis <- oasis %>% rename(gender = 2) #Rename gender column (2nd column) as the slash can be awkward

# Convert categorical columns to factors, this makes sure that statistical models interpret the variables as distinct groups, rather than a continuous numbers
# Multiple transformation here

oasis <- oasis %>%
  mutate(
    gender = as.factor(gender),
    CDR_f = factor(CDR, levels = c(0, 0.5, 1, 2), ordered = TRUE), 
    Educ_f = factor(Educ, levels = 1:5, ordered = TRUE),
    # Create binary dementia variable for logistic regression later
    demented = ifelse(CDR > 0, 1, 0)
  )

# To check how many demented vs not-demented (excluding NA's) - We do this to avoid misfitting our logistic regression to a mislabeled target

table(oasis$demented, useNA = 'always')

```




