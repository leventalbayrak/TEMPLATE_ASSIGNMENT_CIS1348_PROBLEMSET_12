## Problem: Reverse DNS Lookup

### Description
Write a program that reads DNS mappings and answers reverse DNS lookup queries. For each IP address query, find and print the corresponding domain name. If an IP address is not in the DNS table, print "Not found".

### Input Format
First line: an integer n indicating the number of DNS entries
Following n lines: each containing a domain name and IP address separated by a tab
Next line: an integer m indicating the number of queries
Following m lines: each containing an IP address to lookup

### Output Format
Print the domain name for each queried IP address, or "Not found" if the IP is not in the DNS table. Print one result per line in the order queries were received.

### Examples

---
Input:
```
3
example.com	192.168.1.1
google.com	8.8.8.8
github.com	140.82.114.4
2
8.8.8.8
192.168.1.100
```
Output:
```
google.com
Not found
```

---
Input:
```
4
api.example.com	10.0.0.1
web.example.com	10.0.0.2
db.example.com	10.0.0.3
cache.example.com	10.0.0.4
3
10.0.0.2
10.0.0.4
10.0.0.1
```
Output:
```
web.example.com
cache.example.com
api.example.com
```

---
Input:
```
2
site1.com	1.2.3.4
site2.com	5.6.7.8
2
9.9.9.9
10.10.10.10
```
Output:
```
Not found
Not found
```

---
Input:
```
1
localhost	127.0.0.1
1
127.0.0.1
```
Output:
```
localhost
```

---
Input:
```
1
example.org	93.184.216.34
3
93.184.216.34
1.1.1.1
93.184.216.34
```
Output:
```
example.org
Not found
example.org
```
