# SEMLab_HFUT-Building-Electricpowerloaddata

Given the increasing electricity demand in industrial parks, understanding their electric power load patterns is of utmost importance for improving energy efficiency and ensuring the rational utilization of energy resources. We introduce three years (1 January 2017 till 31 December 2019) of the electric power load data for different types of buildings in an industrial park in Suzhou, China. The data is obtained from smart meters and has three different time resolutions.


| Aspect       |   Fact about data        |
| ------------- |:-------------:|
| Number of buildings      | 4 |
| Duration     | 3 years      |  
| Resolution| 5 min, 30 min, and 1 hour    |
| Is data public? | Yes    |


## Usage Notes

The code used for data visualization is based on Matlab R2018a. 
For graphing purposes, our Matlab code reads data in the form of a 365*24 matrix. Therefore, we need to read the xlsx file in the folder in advance and convert it into the form of a matrix. The detailed process is shown in the matrix.txt, which is done in R (4.1.0).


## History

* June 2023: Data goes public!

