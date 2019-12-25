# abao - matrix operations package

Summary of Package
    This package and containing class was created for Udacity ML Nanodegree 1st Portfolio Exercise : Upload a Package 
    to Pypi by Bilgehan Kılınç.
    Basic Matrix Operations calls for adding, subtracting, unequal addition, matrix multiplication,
    matrix transpose calculation and scalar multiplication.

Attributes:
    Class assumes operations will be applied on two distinct matrices. Therefore 2 attributes are created.
    matrix_one: numpy(array) representing first matrix inputed by user.
    matrix_two: numpy(array) representing second matrix inputed by user.
    
Methods:
    adding_matrices(self):
        Function to add two matrices.
        Args: None
        Returns: a list or error massage.
        Note: Controls also matrix shapes for math accuracy.    
    subtracting_matrices(self):
        Function to subtract two matrices.
        Args: None
        Returns: a list or error massage.
        Note: Controls also matrix shapes for math accuracy.    
    unequal_dimensions_matrix_addition(self):
        Function to add two different-shaped matrices with special method of unequal matrix addition.
        Args: None
        Returns: a numpy(array) or error massage.
        Note: Controls also matrix shapes for math accuracy.  
    multiplying_two_matrices(self):
        Function to multiply/dot product two matrices.
        Args: None
        Returns: a numpy(array) or error massage.
        Note: Controls also matrix shapes for math accuracy.    
    transpose_of_matrix(given_matrix):
        Method to transpose a matrix.
        Args: given_matrix: numpy(array) or a list
        Returns: a list   
    scalar_multiplication(given_matrix, multiplier):
        Method to multiply a matrix with a numeric value.
        Args: given_matrix: numpy(array) or a list
              multiplier: an int or a float
        Returns: a list

# Files
This package contains:
    README.md
    __init__.py
    license.txt
    matrix_operations.py
    setup.cfg

#I Installization
This package can be installed with pip from pypi.