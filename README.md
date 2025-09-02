# SSH-Login-Attempt-Analysis

## Overview
This project focuses on analysing illegal SSH login attempts using a dataset of authentication logs. The goal was to detect attack patterns, identify targeted accounts 
and build a Splunk dashboard for monitoring.

## Dataset
Format: CSV log data  
Fields extracted using Splunk regex:  
Timestamp  
Username  
Source IP  
Target server  
Port  

## Attack Patterns Observed  
Brute Force – One IP attempted over 20 logins against one account within 15 minutes.  
Privileged Account Targeting – The root account was the primary focus across multiple attempts.  
Distributed Brute Force - Multiple IP addresses tried logging into the same account within the same time interval.  

## Dashboard Insights
- Total Failed Login Attempts
- Top Attacked Usernames
- Location of Source IPs
- Top Attacker IPs (masked for privacy)

## Skills gained from project
Log normalisation  
Regex field extraction  
Splunk dashboard creation  
Threat pattern identification  

<img width="1405" height="582" alt="Image" src="https://github.com/user-attachments/assets/8ca4b9c4-a3e9-4513-b83f-865ab93b7c6a" />
<img width="1394" height="394" alt="Image" src="https://github.com/user-attachments/assets/4b8f0295-0c3f-4014-b005-b596ae262c8e" />
