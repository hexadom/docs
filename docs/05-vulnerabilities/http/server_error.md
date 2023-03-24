---
sidebar_position: 1
title: Server Error
---

# Server Error

## Description

A server error occurred.

## Remediation

To fix this issue, you should check the logs and fix the handler that caused the error.
Make sure you also refer to the query we sent to the server to reproduce the issue.


## Configuration

> CheckId: `http/server_error`


### Examples


#### Ignoring this check

```json
{
    "checks": {
        "http/server_error": {
            "skip": true
        }
    }
}
```




## Score

- Escape Severity: **<span className="high-severity">HIGH</span>**
- OWASP: **[A05:2023](https://github.com/OWASP/API-Security/blob/master/2023/en/src/0xa5-broken-function-level-authorization.md)**
- PCI DSS: **6.5.8**
- CWE
  - **284**




### CVSS

- CVSS_VECTOR: **CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:N/E:H/RL:O/RC:C**
- CVSS_SCORE: **8.7**

## References

