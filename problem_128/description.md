## Problem: Open Port Scanner

### Description
Write a program that reads network port scan data and prints all open ports sorted in ascending order by port number. Each port entry includes the port number, state, and service name. Only ports with state "open" should be included in the output. You may assume there is at least one open port in the input.

### Input Format
First line: an integer n indicating the number of port entries
Next n lines: tab-separated values in the format `PORT\tSTATE\tSERVICE`

### Output Format
Print each open port number (without the protocol suffix like "/tcp") on a separate line, sorted in ascending numerical order

### Examples

---
Input:
```
5
22/tcp   open     ssh
80/tcp   open     http
443/tcp  open     https
3306/tcp closed   mysql
8080/tcp open     http-alt
```
Output:
```
22
80
443
8080
```

---
Input:
```
4
21/tcp   open     ftp
25/tcp   closed   smtp
110/tcp  open     pop3
143/tcp  open     imap
```
Output:
```
21
110
143
```

---
Input:
```
1
443/tcp  open     https
```
Output:
```
443
```

---
Input:
```
6
5000/tcp open     upnp
80/tcp   open     http
8443/tcp open     https-alt
22/tcp   open     ssh
3000/tcp closed   ppp
443/tcp  open     https
```
Output:
```
22
80
443
5000
8443
```

---
Input:
```
7
3389/tcp closed   ms-wbt-server
8080/tcp open     http-proxy
445/tcp  closed   microsoft-ds
80/tcp   open     http
22/tcp   closed   ssh
443/tcp  open     https
1433/tcp closed   ms-sql-s
```
Output:
```
80
443
8080
```