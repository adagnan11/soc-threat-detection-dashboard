# soc-threat-detection-dashboard
SIEM-inspired cybersecurity dashboard for threat detection, severity analysis, MITRE ATT&amp;CK mapping, and threat visualization using Flask, Pandas, and Plotly.
# SOC Threat Detection Dashboard

## Overview

The SOC Threat Detection Dashboard is a SIEM-inspired cybersecurity analytics platform built using Python, Flask, Pandas, Plotly, HTML, CSS, and the MITRE ATT&CK Framework.

The system analyzes network traffic datasets, detects malicious activity, classifies attack severity, maps threats to MITRE ATT&CK techniques, and visualizes cybersecurity threats through an interactive dashboard.

---

## Features

- Threat Detection and Classification
- Severity Scoring (Low, Medium, High, Critical)
- MITRE ATT&CK Mapping
- Interactive Plotly Visualizations
- Threat Search and Filtering
- SOC-Style Dashboard Interface
- Cybersecurity Dataset Analysis

---

## Technologies Used

- Python
- Flask
- Pandas
- Plotly
- HTML
- CSS
- JavaScript
- MITRE ATT&CK Framework

---

## Dataset

This project uses the CICIDS2017 cybersecurity dataset to simulate real-world network attacks.

Detected attack categories include:

- DoS Hulk
- DDoS
- PortScan
- FTP-Patator
- SSH-Patator
- Heartbleed
- Web Attack SQL Injection
- Web Attack XSS

---

## Dashboard Components

### Threat Analytics

Displays detected attacks and attack counts.

### Severity Classification

Threats are classified into:

- Critical
- High
- Medium
- Low

### MITRE ATT&CK Mapping

| Threat | Technique |
|---------|-----------|
| PortScan | T1046 |
| DDoS | T1498 |
| FTP-Patator | T1110 |
| SSH-Patator | T1110 |
| Heartbleed | T1190 |

### Visualization

Interactive Plotly charts display attack distributions and threat analytics.

---

## Future Enhancements

- Real-time packet monitoring
- Suricata integration
- Threat intelligence feeds
- User authentication
- Database logging
- Geolocation tracking

---

## Author

Arthur Christian Dagnan

M.S. Cybersecurity Graduate
Northern Illinois University
