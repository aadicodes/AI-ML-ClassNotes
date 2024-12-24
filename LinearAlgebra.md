# Linear Algebra Summary
## Agenda :
Scalars and Vectors
Linear Independence in Vectors
Matrix operations, transpose a matrix, calculate rank of a Matrix

## NOTES: 
linear algebra is very important to deeply understand Machine Learning domain 
While building ML Models, there is a need to reduce dimensions of data for which right hyper parameters need to be seelcted. 
Knowledge of Linear Algebra is a building block for ML and is very critical for Machine Learning model implementation

### Imp. Concepts of Linear Algebra for ML are 
Notations
Operations
Matrix factorization

### Scalars and Vectors
In linear algebra, a "scalar" is simply a single real number, used to represent a quantity with only magnitude and no direction; essentially, it's just a number that can be used to "scale" vectors through an operation called scalar multiplication, where you multiply a vector by a scalar to produce another vector.

In linear algebra, a vector is a mathematical object that possesses both magnitude (size) and direction, representing quantities like force, velocity, or displacement in physics; essentially, it's a directed line segment with an arrow indicating its direction and length representing its magnitude.

Dot Product of Two Vectors
***
If X and Y are vectors, Dot Product of Vectors = X.Y 
Vector is represented by one Dimensional Matrix.

Eg. 
X = [ a1,a2,a3]
Y = [b1,b2, b3]
X.Y = a1*b1  + a2*b2 + a3*b3

DotProduct result is a Scalar.

LINEAR INDEPENDENCE of Vectors
Learn more, video does not have enough info

NORM of a Vector: 
Norm of a Vector is length of the Vector
||V|| = SQRT(V.V)

Eg. V = [1,2,5]
Norm of the vector ie ||V|| = Sqrt(1*1 + 2*2 + 5*5 )=5.47722557505166 

Matrix and Matrix Operations

Matrix is a rectangular array or muti dimensional array.

Matrix addition:
***
Addition of Matrix carried out by adding the positional elements in a matrix and resulting Matrix will be of same dimension. Also two matrices being added shall have same dimension or Order e.g 2X2 or 3X3 etc. 

Scalar Multiplication of a Matrix 
***
Multiply a n X m matrix with single numeric value C and result will be a Matrix of nXm order and each element multiplied by Scalar C.

Subtraction of Matrices
***
Similar to addition of Matrices, subtraction also needs two nXm matrices of same order.
Subject each element of second matrix from first and results will be a Matrix of same order.

Matrix multiplication:
***
Matrix multiplication involves, multiplying elements of a row from first matrix with elements from columns of second matrix. Hence to successfully do matrix multiplication, number of Columns from first matrix , shall match number of rows in second matrix. 
Eg. 4 X 3 and 3 X 2 Matrices can be multiplied. 3 X 3 and 3 X 3 matrices can be mutliplied. 

A = 2 X 3 Matrix
B = 3 X 2 Matrix  
A * B = 2 X 2 Matrix

Other Operations and Concepts include Transpose, Rank of a Matrix, Determinant of a Matrix, Inverse and Eigen values
Calculus in Linear Algebra : 
Differential Calculus
Integral Calculus
Calculus is necessary to learn Machine Learning algorithms. Concepts differential calculus are applied in gradient descent. 
TODO : What is Back propagation of Neural Networks. This measures how the output of a function changes by changing small amounts of input of a function.
