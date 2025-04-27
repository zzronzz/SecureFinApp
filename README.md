# SecureFinApp
This CS 305 final project implements multi-layered security for financial web applications, featuring vulnerability remediation, SHA-256 cryptographic verification, and HTTPS protocols. By applying defense-in-depth principles, I reduced security vulnerabilities from 144 to zero, demonstrating effective protection of sensitive financial data.
# Artemis Financial Secure Software Implementation

## Project Overview

This repository contains my secure software implementation work for Artemis Financial, completed as part of CS-305 Secure Coding. The project demonstrates my skills in implementing security measures, secure coding practices, and vulnerability remediation in a financial application.

## Client Information & Requirements

Artemis Financial is a financial consulting company that develops personalized financial plans including savings, retirement, investments, and insurance for clients. As part of their modernization efforts, they needed to enhance their web application's security to protect sensitive financial data. Specifically, they required a file verification mechanism (checksum) to ensure data integrity during transfers and secure communications protocols to protect client information.

## Security Implementation Strengths

I successfully implemented a comprehensive security solution that included:
- SHA-256 cryptographic algorithm for checksum verification
- Self-signed certificates using Java Keytool with 2048-bit RSA encryption
- HTTPS/TLS implementation for secure communications
- Vulnerability remediation through dependency updates

Secure coding is vital because it protects sensitive financial information from unauthorized access and tampering. For Artemis Financial, this security implementation adds tremendous value by safeguarding client data, ensuring regulatory compliance, building client trust, and protecting the company's reputation and financial well-being against potential breaches.

## Challenges & Learning Opportunities

The most challenging aspect of the vulnerability assessment was systematically reducing the initial 144 vulnerabilities to zero through multiple iterations of dependency updates. This process required careful analysis of security reports and strategic decisions about which dependencies to update first. This methodical approach taught me valuable skills in prioritizing security risks and implementing solutions efficiently.

## Security Enhancement Approach

I increased security through a defense-in-depth strategy with multiple layers:
- Dependency Security: Updated all vulnerable dependencies
- Transport Security: Implemented HTTPS using TLS
- Data Verification: Added SHA-256 checksum functionality
- Security Verification: Implemented comprehensive security testing

In future projects, I would use tools like OWASP Dependency-Check, static code analysis, and dynamic application security testing (DAST) to assess vulnerabilities. For mitigation, I would follow the OWASP Top 10 guidelines and implement appropriate countermeasures based on risk assessment.

## Verification Methodology

To ensure the application remained functional and secure after implementation, I:
1. Ran the application to verify core functionality
2. Verified HTTPS communications were working correctly
3. Confirmed the checksum verification was working with test data
4. Conducted dependency checks to verify no new vulnerabilities were introduced
5. Implemented proper suppression for remaining low-risk vulnerabilities with documentation

## Resources & Tools

The most valuable resources and tools I used were:
- Java Keytool for certificate generation
- Spring Security for implementing HTTPS
- OWASP Dependency-Check for vulnerability scanning
- Maven for dependency management
- SHA-256 cryptographic hashing libraries

These tools will be invaluable for future security-focused assignments and professional work.

## Professional Application

From this project, I would showcase to potential employers:
1. My systematic approach to vulnerability remediation (reducing 144 vulnerabilities to 0)
2. My implementation of industry-standard security protocols (SHA-256, HTTPS/TLS)
3. My ability to document security implementations thoroughly
4. My understanding of defense-in-depth security principles
5. My skills in testing and verifying security measures

These demonstrations highlight my capabilities in secure software development, especially for industries handling sensitive data like finance, healthcare, and government applications.
