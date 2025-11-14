## Problem: HTTP Status Code Classifier

### Description
Write a program that reads a list of HTTP status codes and classifies each code into its category. HTTP status codes are categorized as follows: 2xx codes (200-299) are "Success", 3xx codes (300-399) are "Redirection", 4xx codes (400-499) are "Client Error", and 5xx codes (500-599) are "Server Error". Print each status code followed by its category.

### Input Format
First line: an integer n indicating the number of status codes
Next n lines: each contains a single integer representing an HTTP status code

### Output Format
Print each status code followed by a space and its category (Success, Redirection, Client Error, or Server Error), one per line

### Examples

---
Input:
```
4
200
404
301
500
```
Output:
```
200 Success
404 Client Error
301 Redirection
500 Server Error
```

---
Input:
```
6
201
302
403
503
204
307
```
Output:
```
201 Success
302 Redirection
403 Client Error
503 Server Error
204 Success
307 Redirection
```

---
Input:
```
1
418
```
Output:
```
418 Client Error
```

---
Input:
```
5
299
300
399
400
499
```
Output:
```
299 Success
300 Redirection
399 Redirection
400 Client Error
499 Client Error
```

---
Input:
```
7
502
200
404
301
500
201
403
```
Output:
```
502 Server Error
200 Success
404 Client Error
301 Redirection
500 Server Error
201 Success
403 Client Error
```