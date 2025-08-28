

# Matrix Operations in C

This C program performs basic matrix operations including:

* Matrix addition
* Matrix subtraction
* Matrix multiplication
* Matrix transpose

The program supports user input for matrix dimensions and elements, validates the operations based on matrix dimensions, and displays the results.

---

## Features

* Dynamically sized matrices based on user input
* Error handling for dimension mismatches in addition, subtraction, and multiplication
* Displays the transpose of the first matrix
* Clean and modular code with separate functions for each operation

---

## How to Use

1. Clone the repository or download the `matrix_operations.c` file.

2. Compile the program using a C compiler, e.g.:

   ```bash
   gcc matrix_operations.c -o matrix_operations
   ```

3. Run the executable:

   ```bash
   ./matrix_operations
   ```

4. Follow the prompts to:

   * Enter dimensions and elements for two matrices
   * View the sum, difference, and product (if dimensionally valid)
   * View the transpose of the first matrix

---

## Example

```
Enter dimensions of matrix 1 (rows columns): 2 3
Enter elements of matrix 1:
1 2 3
4 5 6
Enter dimensions of matrix 2 (rows columns): 2 3
Enter elements of matrix 2:
6 5 4
3 2 1

Sum of matrices:
7	7	7	
7	7	7	

Difference of matrices (Matrix1 - Matrix2):
-5	-3	-1	
1	3	5	

Matrix multiplication not possible due to dimension mismatch.

Transpose of Matrix 1:
1	4	
2	5	
3	6	
```

---

## Requirements

* C compiler supporting C99 or later (due to variable-length arrays)
* Standard C library

---

## Code Structure

* `printMatrix`: Prints the matrix in a tabular format
* `addMatrices`: Adds two matrices if dimensions match
* `subtractMatrices`: Subtracts two matrices if dimensions match
* `multiplyMatrices`: Multiplies two matrices if compatible
* `transposeMatrix`: Calculates transpose of a given matrix
* `main`: Handles input/output and calls the above functions

---


