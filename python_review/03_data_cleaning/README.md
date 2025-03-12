# Data Cleaning

In this repository you will work through an example of how to clean data. Since data cleaning is an important part of every EDA, the containing notebook will help you with your first project.


## Environment

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

```sh
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```


If you are working on Windows type the following commands in the PowerShell:

```Bash
python -m venv .venv
.venv\Scripts\Activate.ps1
```

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the data cleaning notebook.

## Data

The dataset for the notebook is stored in the `data.zip` folder. To unzip the data folder directly in the terminal run

```sh
unzip data.zip
```

