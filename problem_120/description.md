## Problem: Matrix Transpose

### Description
Write a program that reads a matrix of integers and prints its transpose. The transpose of a matrix is formed by flipping the matrix over its diagonal, turning rows into columns and columns into rows.

### Input Format
First line: two space-separated integers m (number of rows) and n (number of columns)
Next m lines: each line contains n space-separated integers representing a row of the matrix

### Output Format
Print the transposed matrix with n rows and m columns. Each row should contain space-separated integers.

### Examples

---
Input:
```
2 3
1 2 3
4 5 6
```
Output:
```
1 4
2 5
3 6
```

---
Input:
```
3 2
1 2
3 4
5 6
```
Output:
```
1 3 5
2 4 6
```

---
Input:
```
1 4
10 20 30 40
```
Output:
```
10
20
30
40
```

---
Input:
```
4 1
5
10
15
20
```
Output:
```
5 10 15 20
```

---
Input:
```
3 3
1 2 3
4 5 6
7 8 9
```
Output:
```
1 4 7
2 5 8
3 6 9
```
