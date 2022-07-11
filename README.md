February 1, 2022

# Differentially Private Vaccination Statuses

This project operates on a CSV file of vaccine statistics of US counties obtained for November 18th, 2021. It then applies concepts of Differential Privacy 
to allow us to operate on the data while treating the raw statistics of each individual county as sensitive information that needs to be protected. In operating on this data, we can 
make inferences about the progress of vaccine administration throughout the US, but with scoring functions, sample-and-aggregate, and DP-queries. We can even then determine
the overall progress by state and even by regional quadrants throughout the country.

Citations:
This project relied significantly on concepts taught by Joe Near, a Computer Science Lecturer at the University of Vermont. The code is frequently referenced
from his online publication, Programming Differential Privacy (which you can find here: https://programming-dp.com/index.html). The operation on the data and formulation
of code is all my own. 
