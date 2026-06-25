# OWASP Dependency Check Analysis

## Objective

Identify vulnerable third-party libraries in a web application using OWASP Dependency-Check.

## Tools Used

* OWASP Dependency-Check 12.2.2
* Java 26
* Git
* WebGoat

## Procedure

1. Installed OWASP Dependency-Check.
2. Downloaded the vulnerable WebGoat project.
3. Performed dependency scanning.
4. Generated an HTML vulnerability report.
5. Analyzed vulnerable third-party components.

## Results

* Dependencies Scanned: 93
* Unique Dependencies: 90
* Vulnerable Dependencies: 9
* Vulnerabilities Found: 43

### Vulnerable Libraries

* Bootstrap 3.1.1
* jQuery 1.10.2
* jQuery 2.1.4
* jQuery UI

## Key Learning

Learned how Software Composition Analysis (SCA) tools identify vulnerable dependencies and help mitigate software supply-chain risks.
