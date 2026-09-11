# Windows Security Log Investigation

## 1. Objective

The objective of this investigation is to analyze Windows security logs and identify suspicious failed login attempts.

## 2. Event Investigated

- Event ID: 4625
- Event Type: Failed Logon
- Log Source: Windows Security Event Log

## 3. Investigation

The Windows Security Event Log was reviewed to identify repeated failed login attempts.

## 4. Findings

Suspicious login activity will be analyzed based on:
- Number of failed attempts
- Account targeted
- Source/network address
- Time of activity
- Logon type

## 5. Conclusion

The collected security events will be analyzed to determine whether the activity could indicate a brute-force or unauthorized login attempt.

## 6. Recommended Actions

- Use strong passwords
- Enable multi-factor authentication
- Monitor repeated failed logins
- Restrict unnecessary remote access
- Review suspicious IP addresses
