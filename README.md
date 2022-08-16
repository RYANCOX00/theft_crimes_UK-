# Theft Crimes in the UK 


<br>

## Summary of the notebook

<br>

The aim of this program is to: 
1. Analyse the most prevalent theft crime type in the UK in 2015. 
2. Identify the regions that have the highest crime rate of this particular offence and that lie outside the standard deviation. 
3. Identify the crime rate per population for those that lie outside the standard deviation as idetified at objective 2. 

<br>

A static version of the notebook on nbviewer by clicking the below icon or by selecting the [**UK_crimes.ipynb**](https://github.com/RYANCOX00/theft_crimes_UK-/blob/main/UK_crimes.ipynb) file. 

<br> [![nbviewer](https://user-images.githubusercontent.com/2791223/29387450-e5654c72-8294-11e7-95e4-090419520edb.png)](https://nbviewer.org/github/RYANCOX00/theft_crimes_UK-/blob/main/UK_crimes.ipynb)


<br>


<br>

***

<br>


## Steps for running the code

<br>

1. To run this code on your own machine a user will require Python 3 and the below listed packages to be installed.  It is recommended that a user downloads Anaconda as these particular packages are already pre-installed.  You can download Anaconda [here](https://www.anaconda.com/products/individual).  Alternatively, Python 3 can be downloaded [here](https://www.python.org/downloads/). 

<br>

2. Should the user decide not to use Anaconda. You can install the below the packages by calling the below on their command line:  

- pip install pandas
- pip install numpy 
- pip install matplotlib
- pip install seaborn


<br>

3. Installing cmder is recommended for users on Windows machines. cmder can be downloaded [here](https://cmder.net/). The command line on Linux and Mac is suitable.   The repository is public and therefore can be pulled from GitHub by anyone. 

<br>

4. A user can interact with the code by running _jupyter lab_ in the command line from the local directory that this repository is pulled to. Jupyter will launch in their default browser. 

<br>


***

<br>

## Run

1. To pull the code to a local directory a user will first need to clone this repository using the SSH. Go to the desired directory in the command line and type 

```
gitclone git@github.com:RYANCOX00/theft_crimes_UK-.git
```

<br>

2. To open the directory in Jupyter type jupyter lab in the current directory on the command line. 

```
jupyter lab
```

<br>

3. The browser should open automatically, however if it does not open go to Google Chrome or Firefox and type the below in the url bar.

```
http://localhost:8888/lab/workspaces/auto-d
```

<br>

4. To run either cao.ipynb or pyplot.ipynb notebooks 
- Open the desired file in Jupyter.
- Go to *Kernel*. 
- Click *Restart Kernel and Run All Cells*. 

<br>

***

<br>

## Explore

<br>

This dataset contains all crimes across the UK from 2000 - 2015.  The reported crimes are broken down per police region. Theft offences for 2014 and 2015 are only in scope for this program.  

<br>

Should a person wish to analyse other crime types, they can change the 'cols' variable at input 3, under importing dataset. 

<br>

Also, only 2014 and 2015 crimes are used in this workbook, all others are dropped as per input 6.  If you wish to analyse other year, go to input 6 and amend the dropped years. 

<br>

Should a person wish to analyse another theft offence which may not be the "top crime", the value of the topcrime variable at input 13 should be changed to the name of the name of the crime i.e. 'Robbery of personal property'. The hardcoded populations at input 27 should also be updated.

<br>

***


## Contact

<br>

Should any person wish to contact me in relation to the content of this workbook, they can contact me by email: 

[ryancox212@gmail.com](mailto:ryancox212@gmail.com)

<br>

***