# AAA-framework
Improving authentication, authorization, and accounting for a small business

# Cybersecurity Incident Report

## Overview
As the first cybersecurity professional hired by a growing business, it is my responsibility to investigate a recent incident involving a suspicious deposit.

## Incident Description
Recently, a deposit was made from the business to an unknown bank account. The finance manager confirmed that they did not make a mistake. Fortunately, the payment was stopped before it was processed.

## Objective
The business owner has tasked me with investigating the incident to determine what happened and to implement measures to prevent future occurrences.

## Steps

### 1. Review Access Log
We will begin by reviewing the access log for the time period surrounding the incident. This will help us identify who accessed the financial systems and any anomalies in user activity.

### 2. Identify Possible Threat Actors
Next, we will take detailed notes to help us identify a potential threat actor. This includes:
- Analyzing the access log for unusual patterns or unauthorized access.
- Identifying any users with elevated privileges or recent changes to their access rights.
- Reviewing any external access attempts or suspicious IP addresses.

### 3. Spot Issues with Access Controls
We will then examine the identified issues with the access controls that were exploited during the incident. This involves:
- Checking for gaps in the current access control policies.
- Evaluating the effectiveness of existing authentication methods.
- Identifying any instances of shared or weak passwords.

### 4. Recommend Mitigations
Finally, we will recommend mitigations to improve the business' access controls and reduce the likelihood of a similar incident occurring in the future.

# Event Log

**Event Type:** Information  
**Event Source:** AdsmEmployeeService  
**Event Category:** None  
**Event ID:** 1227  

**Date:** 10/03/2023  
**Time:** 8:29:57 AM  

**User:** Legal\Administrator  
**Computer:** Up2-NoGud  
**IP:** 152.207.255.255  

**Description:**  
Payroll event added. FAUX_BANK


# Event Directory

| Name              | Role            | Email                  | IP address      | Status    | Authorization | Last access                    | Start date | End date   |
|-------------------|-----------------|------------------------|-----------------|-----------|---------------|--------------------------------|------------|------------|
| Lisa Lawrence     | Office manager  | l.lawrence@erems.net   | 118.119.20.150  | Full-time | Admin         | 12:27:19 pm (0 minutes ago)    | 10/1/2019  | N/A        |
| Jesse Pena        | Graphic designer| j.pena@erems.net       | 186.125.232.66  | Part-time | Admin         | 4:55:05 pm (1 day ago)         | 11/16/2020 | N/A        |
| Catherine Martin  | Sales associate | catherine_M@erems.net  | 247.168.184.57  | Full-time | Admin         | 12:17:34 am (10 minutes ago)   | 10/1/2019  | N/A        |
| Jyoti Patil       | Account manager | j.patil@erems.net      | 159.250.146.63  | Full-time | Admin         | 10:03:08 am (2 hours ago)      | 10/1/2019  | N/A        |
| Joanne Phelps     | Sales associate | j_phelps123@erems.net  | 249.57.94.27    | Seasonal  | Admin         | 1:24:57 pm (2 years ago)       | 11/16/2020 | 1/31/2020  |
| Ariel Olson       | Owner           | a.olson@erems.net      | 19.7.235.151    | Full-time | Admin         | 12:24:41 pm (4 minutes ago)    | 8/1/2019   | N/A        |
| Robert Taylor Jr. | Legal attorney  | rt.jr@erems.net        | 152.207.255.255 | Contractor| Admin         | 8:29:57 am (5 days ago)        | 9/4/2019   | 12/27/2019 |
| Amanda Pearson    | Manufacturer    | amandap987@erems.net   | 101.225.113.171 | Contractor| Admin         | 6:24:19 pm (3 months ago)      | 8/5/2019   | N/A        |
| George Harris     | Security analyst| georgeharris@erems.net | 70.188.129.105  | Full-time | Admin         | 05:05:22 pm (1 day ago)        | 1/24/2022  | N/A        |
| Lei Chu           | Marketing       | lei.chu@erems.net      | 53.49.27.117    | Part-time | Admin         | 3:05:00 pm (2 days ago)        | 11/16/2020 | 1/31/2020  |

# Mitigation Recommendations

| **Identification of the Threat** | **Authorization Issues Identified** | **Recommendation to Prevent Incident** |
|----------------------------------|------------------------------------|---------------------------------------|
| - User: Robert Taylor Jr         | - Robert Taylor Jr accessed payroll systems in 2023 despite contract ending in 2019. | - Enable Multi-Factor Authentication (MFA) to add an extra layer of security. |
| - Event Date: 10/03/23           |                                    |                                       |
| - Device Used: 'Up2-NoGud'       |                                    |                                       |
| - IP Address: 152.207.255.255    |                                    |                                       |
