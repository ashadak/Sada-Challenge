# sada-challenge

This repository consists of the solution to the Highest Profit problem from the collection of SADA challenges. The goal of this assessment is to read a CSV file containing corporate profits data, reproduce the data in JSON format, and look for the highest profit values in the data.

The input needed for this assessment is the data.csv file consisting of the corpoate data and there should be 4 outputs produced: The number of rows in the original data, the      number of rows in the data after dropping all rows with invalid non-numeric values in the profits column, the top twenty rows with the highest profit values, and a JSON file should be generated consisting of the updated data

This problem is solved using various data manipulation techniques with mainly the use of functions provided in the Python Pandas library.

Note: This file requires Pandas, NumPy dependecies and was tested using a Bash terminal. 

In order to run this solution:
 - Dowload the zip file and extract its content.
 - Open up your terminal and navigate to the folder where the files are located. 
 - Run the command "run.sh" or "sh run.sh". This will result in the three outputs required for this challenge. The JSON file should be generated in the current directory              you are located in. 

Explanation of the code is provided in the comments of the code file: highest_profit.py 
