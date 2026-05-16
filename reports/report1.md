# Vulnerability Report 1

## Target
Example Web Application

## Tool Used
Burp Suite Community Edition

## Findings
- Reflected XSS vulnerability detected in search parameter
- Input not properly sanitized
- Payload injected successfully via proxy

## Risk Level
Medium

## Recommendation
- Implement input validation
- Use output encoding
- Apply Content Security Policy (CSP)

## Status
Tested (Learning Project)
