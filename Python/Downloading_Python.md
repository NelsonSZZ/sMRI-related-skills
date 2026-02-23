# 🐍 Python

> A summary of what I've learned from [kcho](https://www.youtube.com/@kchox). He hasn't posted in a while, but I'll keep these notes as up to date as I can. Check out his YouTube channel for more nuanced explanations beyond what's covered here.

---

## 📥 Downloading Python (via Anaconda)

```bash
# If Homebrew is installed on Mac, use wget to download the installer
wget [python link]

# Alternatively, use curl to download
curl -LO [python link]

# Run the installer — press yes to accept the licence
bash Anaconda3-2025.06-1-MacOSX-x86_64.sh
```

---

## ⚙️ Setting Up Conda

Once installed, navigate to conda and initialise it.

```bash
# Initialise conda for zsh — restart your terminal after running this
~/anaconda3/bin/conda init zsh

# Activate the base environment (you should see '(base)' appear in your prompt)
conda activate
# or explicitly:
conda activate base

# Check which Python is being used
which python

# Check the conda version
conda --version

# If you have multiple Python installations, switch between them like so:
source ~/miniconda/bin/activate  # change folder name to match your install
```

---

## 📓 Installing & Opening Jupyter Notebook

```bash
# Install Jupyter via conda
conda install jupyter

# Verify the install location
which jupyter

# Launch Jupyter Notebook in your browser
jupyter notebook
```

---

## 🔑 Quick Reference

| Command | Description |
|---------|-------------|
| `wget [link]` | Download a file |
| `curl -LO [link]` | Download a file (alternative) |
| `conda init zsh` | Initialise conda for zsh shell |
| `conda activate` | Activate the base environment |
| `which python` | Show which Python is active |
| `conda --version` | Check conda version |
| `conda install jupyter` | Install Jupyter Notebook |
| `jupyter notebook` | Launch Jupyter Notebook |
