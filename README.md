# The Code Pub: Machine Learning Time
The Code Pub goes AI!

## Preparation
Note: You can skip the preparation part if you already have python3 installed with the following packages: 
``` 
pandas
scikit-learn
jupyter
matplotlib
```
I recommend using a virtual environment as described in the preparation steps. 

DISCLAIMER: I use a Macbook, so the preparation steps might differ for other operating systems. The most important is that you have the required packages installed. 

### 1. Install python3 
Make sure you have python3 installed on your computer along with its' package manager pip(in python 3.4 or later pip is included in the binaries). Please google how to do this based on your operating system. 
You can verify your installation in your terminal by running the commands `python3` and `pip3`. 

### 2. Install virtualenv 
Virtualenv is used to create virtual python environments. We will use virtualenv to create an environment for this workshop. 
Use pip to install virtualenv: 

``` 
pip3 install virtualenv 
```

Verify the installation by running `virtualenv` in your terminal. 

### 3. Create a virtual environment
Create a folder called "pythonenvs" anywhere on your computer. We will install the virtual environment in that folder. 
run the following command in your terminal inside the pythonenvs folder: 

```
virtualenv code-pub-10-19 
```

You should now have a new folder called `code-pub-10-19`. Inside that folder you will see the following folders: ` bin,	include,lib `

### 4. Activate virtual environment
Run the following command to activate your virtual environment from the pythonenvs folder: 

```
source code-pub-10-19/bin/activate
``` 

NOTE: The path might differ on a windows machine. 

You can verify that you are using your virtual environment by running the following command: 

```
which python
```

The output should contain the path where your virtualenvironment is located. 

To deactivate your virtualenvironment simply type `deactivate` in your terminal (But don't do that now!).

### 5. Install necessary packages 
Now that you have activated your virtual environment, run the following commands to install the necessary packages. 

``` 
pip install scikit-learn pandas jupyter matplotlib
``` 

### 6. Verify jupyter notebook is working
Run the following command in the terminal: 

```
jupyter notebook
``` 

This should open a new tab in your browser if everything has worked. 


### 7. You're done! 
On the day of the workshop I will upload a jupyter notebook with a prepared code skeleton and a dataset. To access the notebook and the data you will be asked to clone this repo as a first step during the workshop. 
