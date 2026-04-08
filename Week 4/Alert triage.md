**Alert Triage**

**1\. Introduction**

This task focuses on analyzing and prioritizing security alerts to determine their severity, validate their authenticity, and decide appropriate response actions.

**2\. Objective**

To evaluate alerts based on severity, validate indicators using

threat intelligence, and classify them as true positive or false positive.

**3\. Tools Used**

Wazuh

VirusTotal

TheHive

**4\. Practical Triage**

1\. Receive alert from Wazuh

2\. Identify alert details IP 10.0.2.15

3\. Assign severity (High/Medium/Low)

4\. Validate indicator using VirusTotal

5\. Analyze context frequency, user behavior, time

6\. Classify alert True Positive / False Positive

7\. Take action escalate.

**5\. Practical Implementation**

Step 1: Create a Sample Alert

Example:

Alert: Suspicious File Download

Source IP: 10.0.2.15

User: test user

Step 2: Validate Indicator

Go to: VirusTotal

Check IP 10.0.2.15

Step 3: Add Context

Is IP malicious?

Is it internal or external?

Is activity repeated?

Is timing suspicious?

Step 5: Final Classification

Result: True Positive

Reason: IP flagged as malicious and repeated activity observed

Step 6: Action Taken

Block IP

Escalate to incident response

Create case in TheHive

**6\. Conclusion:**

The alert was identified as a true positive after validating the

source IP against threat intelligence. The repeated suspicious activity

from the same IP indicates potential malicious behavior, requiring

immediate response.