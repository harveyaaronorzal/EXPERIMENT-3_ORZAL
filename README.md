`ECE2112: Advanced Computer Programming and Algorithms`
## EXPERIMENT 3: PHYTON DATA ANALYSIS

### I. Intended Learning Outcomes:

1. To identify the codes and functions incorporated in the Pandas library.  
2. To be able to apply and use the different codes and functions in creating a Python program using a
Pandas library.

### II. Instructions:

Write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter Notebook in the dedicated submission bin.  
  
For this programming assignment, download the following file and save to your default user folder: 
[cars.csv](https://github.com/user-attachments/files/22256285/cars.csv)

### III. Problems:
PROBLEM 1: Save your file as Surname_Pandas-P1.py    
Using knowledge obtained from the experiment and demonstrations:  

a. Load the corresponding .csv file into a data frame named cars using pandas.  
b. Display the first five and last five rows of the resulting cars.


<img width="749" height="775" alt="image" src="https://github.com/user-attachments/assets/08925c84-8970-4e08-9e94-fd873e92a5ed" />  
  
```
Pseudocode:
1. Import pandas.
2. Load the CSV file into a DataFrame named cars using read_csv().
3. Display the first five rows using head().
4. Display the last five rows using tail().
5. Print
```

PROBLEM 2: Save your file as Surname_Pandas-P2.py  
Using the dataframe cars in problem 1, extract the following information using subsetting, slicing and
indexing operations.  

a. Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7...) of cars.  
b. Display the row that contains the ‘Model’ of ‘Mazda RX4’.  
c. How many cylinders (‘cyl’) does the car model ‘Camaro Z28’ have?  
d. Determine how many cylinders (‘cyl’) and what gear type (‘gear’) do the car models ‘Mazda RX4
Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have.  


<img width="599" height="803" alt="image" src="https://github.com/user-attachments/assets/fb627d6c-30b2-4382-8869-1beeb0dedc86" />  
  
```
Pseudocode:
1. Use the cars DataFrame from Problem 1.
2. Part a: Select odd-numbered columns using slicing cars.iloc[:, ::2] and display the first five rows.
3. Part b: Find the row where Model is 'Mazda RX4' using boolean indexing and display it.
4. Part c: Find the number of cylinders (cyl) for 'Camaro Z28' using boolean indexing and .loc.
5. Part d: For models 'Mazda RX4 Wag', 'Ford Pantera L', and 'Honda Civic', extract cyl and gear columns using .loc and display the result.
6. Print
```

### IV. Conclusion

- Through this activity, I was able to identify the different codes and functions incorporated in the Pandas library, such as loading a dataset, subsetting, slicing, and indexing operations. These functions provided a clear understanding of how data can be efficiently managed and analyzed within Python. Furthermore, I was able to apply and use these functions in creating a Python program that loads, displays, and extracts specific information from a dataset. This demonstrates the practical application of Pandas in handling real-world data and highlights its importance as a fundamental tool in data analysis.

Harvey Aaron E. Orzal  
2ECE - B





