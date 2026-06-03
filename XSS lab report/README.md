# Cross-Site Scripting (XSS) Lab

## Overview

This lab focused on identifying and exploiting Cross-Site Scripting (XSS) vulnerabilities in a vulnerable web application. The objective was to understand how malicious JavaScript can be injected into web pages and executed within a victim's browser.

## Environment

* Ubuntu Linux
* Docker
* Web Browser
* Vulnerable Web Application

## Skills Demonstrated

* Cross-Site Scripting (XSS)
* Client-Side Security
* Web Application Testing
* Input Validation Analysis

## Tasks Completed

### Reflected XSS

Injected malicious scripts through user-supplied input and observed execution in the browser.

### Stored XSS

Submitted persistent payloads that executed whenever users viewed affected content.

### Payload Development

Crafted JavaScript payloads to demonstrate the impact of XSS vulnerabilities.

### Security Mitigation

Evaluated input sanitization, output encoding, and Content Security Policy (CSP) protections.

## Key Takeaways

* Improper input validation can expose users to script execution attacks.
* XSS can lead to session theft and account compromise.
* Secure coding practices significantly reduce XSS risk.

## Tools Used

* Linux
* Firefox
* Docker
* JavaScript
