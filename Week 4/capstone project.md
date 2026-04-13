**Capstone Project**

**1\. Summary**

A simulated cyberattack was conducted to evaluate SOC capabilities.

The attack was detected, analyzed, and mitigated successfully.

However, delays in detection and gaps in alerting mechanisms were identified.

Improvements in automation and monitoring are recommended.

**2\. Attack Simulation**

A simulated attack was performed using a brute force login attempt

followed by successful system access using valid credentials.

**3\. Timeline**

Time Activity

10:00 AM Attack initiated

10:10 AM Multiple failed logins

10:15 AM Successful login detected

10:30 AM Investigation started

11:00 AM Response action taken

**4\. Detection**

The attack was identified through Windows Security logs,

specifically Event ID 4625 (failed login) and 4624 (successful login).

However, no automated alert was triggered.

**5\. Triage**

The alert was analyzed and classified as a true positive based

on repeated login failures followed by successful access.

**6\. Response**

The suspicious IP was blocked and the affected account was reviewed.

Further access attempts were prevented.

**7\. Root Cause Analysis (RCA)**

The incident occurred due to weak password policies and lack of

account lockout mechanisms, allowing multiple login attempts.

**8\. Metrics**

MTTD = 15 minutes

MTTR = 45 minutes

Dwell Time = 30 minutes

**9\. Recommendations**

Enforce strong password policies

Enable account lockout after multiple failures

Implement multi-factor authentication

Configure alerting for abnormal login activity

**10.Conclusion:**

potential brute-force attack was detected through multiple failed login attempts. The activity was analyzed and monitored. No immediate critical impact was observed