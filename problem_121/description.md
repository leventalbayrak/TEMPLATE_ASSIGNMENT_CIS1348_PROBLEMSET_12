## Problem: Log Transpose

### Description
Write a program that reads a log table where each row contains two strings followed by an integer, and prints its transpose. The transpose converts rows into columns and columns into rows, preserving the mixed data types.

### Input Format
First line: an integer n (number of rows)
Next n lines: each line contains two space-separated strings and one integer

### Output Format
Print the transposed table with 3 rows. The first two rows contain strings, and the third row contains integers. Each row should have space-separated values.

### Examples

---
Input:
```
3
user1 login 5
user2 logout 10
user3 login 15
```
Output:
```
user1 user2 user3
login logout login
5 10 15
```

---
Input:
```
2
Alice write 100
Bob read 200
```
Output:
```
Alice Bob
write read
100 200
```

---
Input:
```
4
server1 start 1000
server2 stop 2000
server3 restart 3000
server4 start 4000
```
Output:
```
server1 server2 server3 server4
start stop restart start
1000 2000 3000 4000
```

---
Input:
```
1
test action 42
```
Output:
```
test
action
42
```

---
Input:
```
5
A X 1
B Y 2
C Z 3
D W 4
E V 5
```
Output:
```
A B C D E
X Y Z W V
1 2 3 4 5
```
