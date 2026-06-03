# SQL Injection Attack Lab

## Overview

This lab explored SQL injection vulnerabilities in a web application environment. The objective was to understand how improper input validation can allow attackers to manipulate SQL queries, bypass authentication, and modify database contents.

## Environment

* Ubuntu Linux
* Docker
* MySQL
* Apache
* Firefox
* curl

## Skills Demonstrated

* SQL Injection
* Authentication Bypass
* Database Security
* Secure Coding Practices
* Linux Administration

## Tasks Completed

### Authentication Bypass

Demonstrated how SQL injection can be used to bypass login mechanisms and gain unauthorized access to user accounts.

### HTTP-Level Exploitation

Used curl to submit malicious requests directly to the web application and exploit vulnerable SQL queries.

### Data Modification Attacks

Manipulated database records through vulnerable UPDATE statements to demonstrate account takeover and unauthorized data modification.

### Defensive Measures

Implemented prepared statements and parameterized queries to mitigate SQL injection vulnerabilities.

## Key Takeaways

* User input should never be trusted.
* SQL injection can compromise confidentiality, integrity, and availability.
* Parameterized queries effectively prevent injection attacks.

## Tools Used

* Docker
* MySQL
* Linux
* curl
