# Exercise 1 (Jupyter Setup)
## Installation of Python:
I've downloaded the Python from the official website: https://www.python.org/downloads/ . To check that I have Python installed or not in my system I've used the following command in my command prompt. `python --version` 
#### Result: `Python 3.12.0`

##  Installation of pip:
 pip is usually bundled with Python when installing Python itself. To ensure that I have pip (Python package manager) installed I had to check by running the following command in my command prompt or terminal. `pip --version`
#### Result: `pip 23.3.1 from C:\Users\Dell\AppData\Local\Programs\Python\Python312\Lib\site-packages\pip (python 3.12)`

## Installation of pipenv:
I've installed pipenv using the following command `pip install pipenv` and to check whether it's installed or not I've used the command `pipenv --version`
#### Result: `pipenv, version 2023.10.24`

## Installation of Jupyter Notebook using pip
I've installed the Jupyter Notebook with the following command `pip install notebook`

## Installation of Libraries:
Installed the libraries that I need for data engineering and analysis, including Pandas for data manipulation, and visualization libraries like **Matplotlib, Plotly, Nbval, etc.**: `pip install nbQA nbval matplotlib plotly numpy pandas`

### Flowing commands for checking and results-

#### nbQA: On the command prompt
`nbqa --version` Result: `nbqa 1.7.0`

#### nbval: On the command prompt
`pip show nbval` Result: `Version: 0.10.0`

#### matplotlib: On the command prompt
`python -c "import matplotlib; print(matplotlib.__version__)" ` Result: `3.8.1`

#### plotly: On the command prompt
`python -c "import plotly; print(plotly.__version__)" ` Result: `5.18.0`

#### numpy: On the command prompt
`python -c "import numpy; print(numpy.__version__)" ` Result: `1.26.1`

#### pandas: On the command prompt
`python -c "import pandas; print(pandas.__version__)" ` Result: `2.1.2`
