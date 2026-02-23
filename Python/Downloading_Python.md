#  Python
This page is a summary of what i've learned from [kcho](https://www.youtube.com/@kchox). He hasn't posted for awhile now, but I will keep this page UTD as much as I can. Please follow his youtube as there are more nuanced information there.

## Downloading Python

```bash
# if homebrew is installed on mac
wget [python link]

# would download the file (e.g., anaconda file) you want on bash
curl -LO [python link]

# second is running the installer. Press yes to accept the liscense.
bash Anaconda3-2025.06-1-MacOSX-x86_64.sh 
```

We  then navigate to conda to initiate it
```bash
# initiating, and we can restart bash after this command and reopen it.
~/anaconda3/bin/conda init zsh

# to activate base, and it should show 'base'... after activation
conda activate # or `conda activate base`

# check which python we are using
which python

# checking which version
conda --version

# to change which python we are using (incase you have diff pythons🐍 )
source ~/miniconda/bin/activate # this is just an example you can change the folder name
```

To install jupyter 
```bash
# to install
conda install jupyter

# to open
which Jupyter

jupyter notebook
```





