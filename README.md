# Programming Assignment 1





## Method:

  * >`input1.csv and input2.csv` :- This csv file contains matrix to check factorization funcation
  * >`matrix_factorization_gradient` :- Funcation to do matrix_factorization
  * > There are many matrix factorization method available to use in recomondation systems.
  * > Here I have used gradient descent.
  * > 'Method' 
  * > 1.Define two matrix.(A and B)
  * > 2.Define X matrix size of |A| and |B|.
  * > 3.Transpose Of matrix B,B will be the same dimension as A to multiply both the matrix.(Number of columns of matrix A and Rows of matrix B should be same to do matrix multiplication.)
  * > 4.Multiply A by B to achieve an estimate for Y.
  * > 5.Define i as the row number and j as column number. i and j used to access any cell in a matrix.
  * > 6.By using each value of Y the corresponding values of A and B are updated according to a (simplified) gradient descent formula.
  * > 7.Calculated the mean squared error for each value and saves it to an error variable e.
  * > 8.Return matrix A and traspose of B.
  * > 9.Called the function on input files
  * > 10.Saved the output in output1.csv and output2.csv respectivly for both input files.

# How to use:-

* > change the input files as location input_file1 and input_file2 respectivly and run the code.
* > Output will also be stored in output1.csv and output2.csv.

	

 
Reference Used [here]( https://towardsdatascience.com/recommendation-system-matrix-factorization-d61978660b4b )

For git code click [here]( https://github.com/vishwanaik15/Matrix_Factorization )