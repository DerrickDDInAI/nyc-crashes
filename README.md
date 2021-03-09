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
The program allows to **clean** and **prepare the dataset** for a machine learning model

### Objective
*Bill de Blasio* wants to predict which streets are the most dangerous in NYC.

### When?
It is a 2 days project.
The deadline to complete it is scheduled to `10/03/2021 at 4 p.m.`.

### Visuals
_ToDO_


## Installation
To run the program, you need:
- To install the libraries below.
- To download the example dataset `data_100000.csv` or a different sized dataset using the script `download.py`.

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

You can even install the libraries and run the program directly after the installation as such:

4. Run the command:
```pip3 install -r requirements.txt && python3 main.py```

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
- Run `main.py` to start the program.
Or
- On your terminal:
```python3 main.py```

### Usage example
#### Example of input the user can give:
![Example input](core/assets/Example_input.png)

#### Output of the example:
![Example output](core/assets/Example_output.png)


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
│   │   download.py         :script to download the dataset in different size
│   │
│   └───assets              :contains the datasets and images
```

### Roadmap
- [x] Download the dataset
- [x] Explore the dataset
- [X] Clean the dataset
- [X] Prepare the dataset for a machine learning model


### Contributing
Open to contributions.
Requirements to be defined.
Instructions on how to contribute will be described in this section.


### Author(s) and acknowledgment
This project is carried out by **Van Frausum Derrick** from Theano 2.27 promotion at BeCode.
I would like to thank my colleagues and coaches at beCode for their help and guidance.


## Next steps
- Determine requirements for contributions
- Add instructions on how to contribute