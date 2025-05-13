
# 🔍 IT Audit Using Excel BI – Access Log Risk Analysis

This project demonstrates how Business Intelligence (BI) tools like **Excel Power Query** and **Pivot Tables** can be used in an **IT Audit** to identify and analyze potential security risks from access log data.

## 📁 Project Overview

This exercise simulates how IT auditors can analyze access logs to detect:
- Logins outside business hours
- Failed login attempts
- Access from unusual geographic locations
- Role-based system misuse

The dataset was manually created to mimic real-world log entries from an ERP system.

## 📊 Tools & Skills Demonstrated

- **Microsoft Excel**
  - Power Query for data cleaning and transformation
  - Pivot Tables for dynamic risk analysis
  - Conditional formatting for visual emphasis
- **Data Analytics for IT Auditing**
  - Time-based access analysis
  - Behavioral anomaly detection
  - Role-to-system alignment checks

## 🧪 Audit Process

### 1. Data Preparation
- Sample access log data was loaded into Excel from a `.csv` file.
- Power Query was used to:
  - Convert timestamps to `Date/Time`
  - Extract login hour
  - Flag logins outside business hours (`Access Window` column)

### 2. Risk Analysis via Pivot Tables
- Frequency of user actions
- Login times outside 8 AM – 6 PM
- Users with failed login attempts
- Role vs system access alignment

### 3. Key Risk Indicators Identified
| Risk Indicator                | Example (From Dataset)                      |
|------------------------------|---------------------------------------------|
| Late-night admin logins      | `amoyo` logged in at 2:40 AM                |
| Failed login attempts        | `kmakoni` had a failed login                |
| Suspicious access time & location | `jdoe` logged in at 10:15 PM from Zimbabwe |

## 📈 Results

This analysis demonstrates how Excel BI capabilities can be applied effectively in IT auditing for:
- Insider threat detection
- Policy enforcement verification
- Access control weaknesses

## 🚀 How to Reproduce

1. Download the `sample_access_log.csv` from this repo.
2. Open in Excel.
3. Use **Data > From Table/Range** to load into Power Query.
4. Apply transformations (extract hour, add Access Window).
5. Load back to Excel and build Pivot Tables for analysis.

## 🤝 Connect

If you're an IT Auditor, Cybersecurity Analyst, or Excel enthusiast — feel free to connect!

🔗 [LinkedIn Profile](https://www.linkedin.com/in/tariro-chagwiza)

