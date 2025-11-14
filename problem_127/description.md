## Problem: IP Address Type

### Description
Write a program that reads an IP address and determines whether it is IPv4 or IPv6. IPv4 addresses contain dots, while IPv6 addresses contain colons. All inputs will be valid IP addresses.

### Input Format
Single line containing a valid IP address

### Output Format
Print "IPv4" or "IPv6"

### Examples

---
Input:
```
192.168.1.1
```
Output:
```
IPv4
```

---
Input:
```
2001:0db8:85a3:0000:0000:8a2e:0370:7334
```
Output:
```
IPv6
```

---
Input:
```
10.0.0.1
```
Output:
```
IPv4
```

---
Input:
```
fe80::1
```
Output:
```
IPv6
```

---
Input:
```
127.0.0.1
```
Output:
```
IPv4
```
