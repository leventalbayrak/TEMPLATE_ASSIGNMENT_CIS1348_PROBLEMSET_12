## Problem: API Endpoint Traffic Analyzer

### Description
Write a program that reads API endpoint usage data and ranks endpoints by number of requests, calculating each endpoint's percentage of total traffic. Endpoints should be sorted in descending order by request count. Each percentage should be formatted with exactly two decimal places.

### Input Format
First line: an integer n indicating the number of endpoints
Following n lines: each containing an endpoint path and request count separated by a space

### Output Format
Print each endpoint with its request count and traffic percentage, sorted by request count in descending order. Each line should contain three tab-separated values: endpoint path, request count, and percentage (formatted to 2 decimal places)

### Examples

---
Input:
```
4
/api/users 1500
/api/products 3000
/api/orders 500
/api/login 1000
```
Output:
```
/api/products	3000	50.00
/api/users	1500	25.00
/api/login	1000	16.67
/api/orders	500	8.33
```

---
Input:
```
3
/api/search 2400
/api/home 3600
/api/profile 1200
```
Output:
```
/api/home	3600	50.00
/api/search	2400	33.33
/api/profile	1200	16.67
```

---
Input:
```
5
/api/logout 800
/api/dashboard 1600
/api/settings 400
/api/reports 1200
/api/analytics 2000
```
Output:
```
/api/analytics	2000	33.33
/api/dashboard	1600	26.67
/api/reports	1200	20.00
/api/logout	800	13.33
/api/settings	400	6.67
```

---
Input:
```
2
/api/status 5000
/api/health 5000
```
Output:
```
/api/status	5000	50.00
/api/health	5000	50.00
```

---
Input:
```
1
/api/single 100
```
Output:
```
/api/single	100	100.00
```
