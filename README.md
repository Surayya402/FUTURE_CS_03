# API Security Risk Analysis

## Overview

This project presents an API security assessment conducted to identify common security risks through API testing and analysis.

## Tools Used

- Postman
- Chrome DevTools
- Canva
- GitHub

## Testing Approach

The API endpoints were tested using different requests and response observations to identify authentication weaknesses, exposed information, technology details, and missing security controls.

## Security Areas Tested

- Authentication & Authorization
- Data Exposure
- Information Disclosure
- Security Headers
- Error Handling

## Key Findings

- No Authentication Mechanism — High
- Excessive Data Exposure — Medium
- Technology Information Disclosure — Low
- Missing/Incomplete Security Headers — Low to Medium

## Remediation

- Implement strong authentication for protected API resources.
- Limit the amount of data returned by API responses.
- Remove unnecessary technology-related information from responses.
- Configure appropriate security headers.
- Apply proper input validation and controlled error handling.

## Conclusion

The API security assessment identified several security weaknesses related to authentication, data exposure, technology information disclosure, and security headers. These findings show the importance of implementing proper authentication, limiting exposed information, and strengthening security controls to improve the overall security of APIs.
