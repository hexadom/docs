---
sidebar_position: 30
title: SSL certificate expiration
---

# SSL certificate expiration

## Description

The SSL certificate found on the website is no longer valid. This is most probably due to the fact that the SSL certificate is expired.

## Remediation

Purchase a new SSL certificate.


## Configuration

> CheckId: `http/ssl_certificate_expiration`


### Examples


#### Ignoring this check

```json
{
    "checks": {
        "http/ssl_certificate_expiration": {
            "skip": true
        }
    }
}
```




## Score

- Escape Severity: **<span className="high-severity">HIGH</span>**
- OWASP: **[A02:2023](https://github.com/OWASP/API-Security/blob/master/2023/en/src/0xa2-broken-authentication.md)**
- PCI DSS: **6.5.4**
- CWE
  - **295**
  - **319**
- WASC: **4**



### CVSS

- CVSS_VECTOR: **CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H/E:H/RL:O/RC:C**
- CVSS_SCORE: **7.2**

## References

https://www.thesslstore.com/blog/what-happens-when-your-ssl-certificate-expires/