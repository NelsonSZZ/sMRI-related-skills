#  Python
This page is a summary of what i've learned from [kcho](https://www.youtube.com/@kchox). I will keep this page UTD as much as I can. Please follow his youtube as there are more nuanced information there.

Python is a programming language that is widely used in science and in this case neuroimaging, as it is free, and less complicated compared to other languages. 

## Downloading Python
First we run `wget [python link]` in bash if homebrew is installed on mac. If not `curl -L0 [python link]` would do. Second is running the installer using `bash Anaconda3-2025.06-1-MacOSX-x86_64.sh`. Press yes to accept the liscense.

we then navigate to the conda to initiate it `~/anaconda3/bin/conda init zsh`. After which we restart out shell and reopen it.

We use `conda activate` or `conda activate base` to activate base; It should show `(base) ...`. If it already shows, we can use `which python` to check which python we are using. Additionally we can use `conda --Version` to check which version it is. 

To change which python we are using (e.g., `source ~/miniconda/bin/activate`)

## Jupyter Notebook
To install jupyter : `conda install jupyter`. Open Jupyter, type `which Jupyter` and `jupyter notebook`.

##Shorcuts in jupyter


