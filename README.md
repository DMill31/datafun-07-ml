# datafun-07-ml

This repository is for Project 7 of Data Analytics Fundamentals where we will be using machine learning to build a model that can make predictions

## How to Install and Run the Project

First you must clone the project to your local machine.

1. Copy the URL of the GitHub Repository you would like
2. Open Powershell and run the following commands

```shell
cd \
cd Projects
git clone https://github.com/**account**/**repo-name**
cd **repo-name**
code . 
```

If .gitignore and/or requirements.txt aren't created, create them.

After creating these files we can now Git add-commit-push using the following code in the terminal

```shell
git add . 
git commit -m "YOUR MESSAGE HERE"
git push -u origin main
```

Once pushed, we now create our virtual environment by running the command:

```shell
py -m venv .venv
```

Now we will activate the virtual environment using this command:

```shell
.venv\Scripts\activate
```

Once the virtual environment has been activated, we can install our dependencies from requirements.txt.

Before installing, it's best to update key packages first.

```shell
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```

Lastly, we will select our VS Code Interpreter

1. Press Ctrl+Shift+P
2. Search for "Python: Select Interpreter"
3. Choose the Interpreter for the local .venv 

Now your project is ready and the real fun can begin

Don't forget to regularly Git add-commit-push to keep everything up to date

## Workflow for this Notebook

### Part 1 - Chart a Straight Line

This short section focuses solely on learning how to graph using axes with a slope and intercept.  The graph made compares Fahrenheit and Celsius values.

### Part 2 - Prediction

Part 2 focuses on creating a linear regression line to fit the Average High in NYC January 1895-2018 dataset.  

The data is first cleaned, then the model is built using stats from scipy.

At the end, the linear regression line is graphed with the data for a nice visual.

### Part 3 - Prediction

Following a similar pattern to Part 2, another linear regression line is made to fit the same dataset.

This time, however, the model is built using LinearRegression() from sklearn.

This linear regression line is also graphed with the data for another nice visual.