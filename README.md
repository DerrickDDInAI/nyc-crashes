# nyc-crashes
This is a work in progress.


## Table of Contents

- [Introduction](#introduction)

- [Installation](#installation)

- [Instructions](#instructions)

- [Architecture](#architecture)

- [Next steps](#next-steps)

---

## Introduction
### Description
This is a python project for the mayor of New York City (NYC), *Bill de Blasio*.
His *New York City Police Department* (NYPD), collected information about all the traffic accidents happened in NYC.
This dataset as well as explanation is available in the following link: [NYC Motor Vehicle Crashes](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95).
The program allows to **clean** and **prepare the dataset** for a machine learning model.

### Objective
*Bill de Blasio* wants to predict which streets are the most dangerous in NYC.

### When?
It is a 2 days project.
The deadline to complete it is scheduled to `10/03/2021 at 4 p.m.`.

### Visuals
![Output cleaned dataset](core/assets/output_csv_good_enough.png)


## Installation
To run the program, you need:
- To install the libraries below.
- To download the example dataset `data_100000.csv` 
- Or to download a different sized dataset using the script `download.py` (written by BeCode).

### Install the libraries
| Library       | Used to                                        |
| ------------- | :----------------------------------------------|
| Sodapy        | To download the dataset                        |
| Numpy         | To handle Numpy arrays                         |
| Pandas        | To store and access info in a DataFrame        |

Follow these instructions to install the required libraries: on terminal
1. Open your terminal;
2. cd to the directory where the `requirements.txt` file is located;
3. Create and activate your virtual environment.
4. Run the command: 
```pip3 install -r requirements.txt```

### Download `data_100000.csv` or a different sized dataset using the script
- [data_100000.csv]()
- [download.py]()

Follow these instructions to see how to use the `download.py` script: on terminal
1. Open your terminal;
2. Activate your virtual environment if not activated yet;
2. cd to the directory where the `download.py` file is located;
3. Run the command:
```python download.py -h```

Save the data into the following directory:
```
core/assets
```

## Instructions
### How to run the program
Open `exploration.ipynb` jupyter notebook
to see the data exploration and preprocessing.

### Usage example
#### Example of input the user can give:
_ToDo_

#### Output of the example:
_ToDo_


## Architecture
The project is structured as follows:

```
nyc-crashes
│   README.md               :explains the project
│   main.py                 :script to run in order to start the program
│   requirements.txt        :packages to install to run the program
│   LICENSE.txt             :license information
│   .gitignore              :specifies which files to ignore when pushing to the GitHub repository
│
└───core                    :directory contains all the core scripts of the program
│   │   __init__.py
│   │   download.py         :script to download the dataset in different size (written by BeCode)
│   │   exploration.ipynb   :jupyter notebook where to follow the data exploration and preprocessing
│   │
│   └───assets              :contains the datasets and images
```

### Roadmap
- [x] Download the dataset
- [X] Explore the dataset
- [X] Clean dataset: no missing values (remove or fill in missing values)
- [ ] Clean dataset: Consolidate values
- [ ] Clean dataset: Make sure data format is correct
- [ ] Clean dataset: Trim blank spaces
- [ ] Prepare dataset for machine learning model: If necessary, add new useful features based on existing features in the dataset
- [ ] Prepare dataset for machine learning model: feature selection
- [ ] Prepare dataset for machine learning model: feature engineering
- [ ] Prepare dataset for machine learning model: feature normalization
- [ ] Prepare dataset for machine learning model: feature resampling

Depending on progress in roadmap above:
- [X] Export data into `data_clean_GOOD_ENOUGH.csv`
- [ ] Export data into `data_clean_GOOD.csv`
- [ ] Export data into `data_clean_PRECISE.csv`

Finally:
- [ ] Optimizing and automate the preprocessing steps


### Contributing
Open to contributions.
Requirements to be defined.
Instructions on how to contribute will be described in this section.


### Author(s) and acknowledgment
This project is carried out by **Van Frausum Derrick** from Theano 2.27 promotion at BeCode.
I would like to thank my colleagues and coaches at BeCode for their help and guidance.
`download.py` script is written and owned by BeCode.



## Next steps
- Determine requirements for contributions
- Add instructions on how to contribute
- Progress in roadmap: continue cleaning and preparing data
- Export data into `data_clean_GOOD.csv`
- Export data into `data_clean_PRECISE.csv`
- Optimizing and automate the preprocessing steps (in main file)
