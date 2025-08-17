# Incident Response Report - Task 2

## Overview
This task involved using Splunk SIEM for monitoring logs and detecting security incidents. Sample log files were ingested, and suspicious activities were identified.

## Steps Performed
- Installed Splunk Enterprise and logged into web interface
- Uploaded CSV log files: network_traffic.csv, firewall_logs.csv, malware_alerts.csv, failed_logins.csv
- Executed SPL queries to detect anomalies
- Identified suspicious SSH traffic, blocked firewall events, malware infection, and failed login attempts
- Compiled findings into a detailed Incident Response Report

## Findings Summary
| Category | Description |
|----------|-------------|
| Network Traffic | SSH attempt from IP 10.0.0.4 to port 22 |
| Firewall Logs | Blocked connections: 203.0.113.10 (3389), 198.51.100.5 (22) |
| Malware Alert | PC1 infected with Trojan.Generic (High severity) |
| Failed Logins | User john had 2 failed logins |

## Files Included
- incident_response_report_task2.pdf (final report with screenshots)
- /screenshots/ folder (raw analysis images)
- Sample logs/ folder (Since no sample logs were provided by the internship mentors, simulated log files were used for Splunk ingestion and analysis.)
- Alert_classification_log

## Conclusion
This task demonstrates basic SOC analyst activities: log ingestion, monitoring, threat identification, and reporting through Splunk.

## Author
**Mayur Sandipan Jadhav**

