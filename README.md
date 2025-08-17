# FUTURE_CS_02

**Incident Response Report – Task 2**

**Overview**

This task involved using Splunk SIEM for monitoring logs and detecting potential security incidents. Sample log files were uploaded in Splunk, suspicious activities were analyzed, and a final incident response report was generated.

**Steps Performed**

• Installed and logged into Splunk Enterprise

• Uploaded CSV log files: network_traffic.csv, firewall_logs.csv, malware_alerts.csv, and failed_logins.csv

• Ran SPL queries to identify anomalies in network traffic, firewall events, malware alerts, and login attempts

• Noted all suspicious findings and documented them in a report

• Exported the report in PDF and DOCX formats and attached evidence screenshots

**Findings Summary**

• Network Traffic: SSH attempt from IP 10.0.0.4 to port 22

• Firewall Logs: Blocked connections from 203.0.113.10 on port 3389 and 198.51.100.5 on port 22

• Malware Alert: PC1 infected with Trojan.Generic (High severity)

• Failed Logins: User 'john' had 2 failed login attempts (minor suspicious activity)

**Files Included**

• incident_response_report_task2.pdf (final report with screenshots)

• A folder named "screenshots" containing raw screenshot images

**Conclusion**

This task successfully simulated SOC analyst work by identifying multiple security alerts using Splunk SIEM and creating a professional incident response report based on the findings.

**Author**

Mayur Sandipan Jadhav
