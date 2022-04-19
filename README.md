# ShepRD

Readme RTG2416 Data Transfer Tool

1. Introduction
2. How to use
3. Readout
4. Changelog
5. Upcoming changes
6. Credits

# 1. Introduction

The RTG 2416 Data Transfer Tool provides the possibility to keep track of recorded data within 
a group of researchers without increasing the effort and time of regular data handling. 

# 2. How to use

2.1 SQL Database

Connect the tool to a SQL-database. Inside of the code, several positions are marked with "xxxxxxx". 
The variables are named "host", "user"and "password". Insert here the information you got from your IT admin.

2.2 Compiling 

There are only standard packages used from a recent Anaconda distribution. Test the ShepRD.py in your Python installation and compile it to an exe-file for unexperienced users. Follow the documentation here: https://pypi.org/project/py2exe/

2.3 Installation

Put the compiled exe-file on your setup computers, where it can be easily found. The amount of space is capped by the size of the file. 

# 3. Readout

The sql database is filled with different information. According to the used system, the database can be viewed with the 
known SQL-statements as "SELECT * FROM databasename". Further tools to visualize the readout of the database is in progress.

# 4. Changelog

v0.1 Release Testversion 16.06.20

# 5. Upcoming changes

- Integration with the API of elabftw (https://www.elabftw.net/) to generate automatized entries into a labbook. 

# 6. Credits

The programm was developed and written by Christopher Wiesbrock within the Reasearch Training Group 2416 "Multisenses - Multiscales" and 
was funded by the DFG. 
