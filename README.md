# 🛡️ Automated Vulnerability Scanner 

A modern, web-based vulnerability scanning platform that integrates multiple security assessment tools into a beautiful, easy-to-use dashboard. Built for cybersecurity professionals, penetration testers, and security enthusiasts.

### Dashboard Overview
Beautiful, modern interface with real-time statistics and vulnerability tracking.

### Scan Results
Detailed vulnerability reports with severity classification and remediation guidance.

## ✨ Features

### 🔍 Multi-Tool Integration
- **Port Scanning**: Integrated Nmap for comprehensive port and service detection
- **Web Vulnerability Scanning**: Nikto integration for web server security assessment
- **SSL/TLS Analysis**: Automated SSL certificate and configuration checking
- **Modular Design**: Easy to add more security tools

### 📊 Beautiful Visualizations
- **Real-time Dashboard**: Live statistics and vulnerability counts
- **Interactive Charts**: Severity distribution using Chart.js
- **Color-coded Results**: Easy-to-understand severity indicators
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile

### 📈 Comprehensive Reporting
- **PDF Export**: Professional PDF reports for each scan
- **Detailed Findings**: Complete vulnerability descriptions and remediation steps
- **Historical Tracking**: Keep track of all your scans over time
- **Severity Classification**: Critical, High, Medium, Low, and Info categories

### 🎯 User-Friendly Interface
- **Bootstrap 5**: Modern, responsive UI components
- **Font Awesome Icons**: Beautiful, professional iconography
- **Gradient Backgrounds**: Eye-catching design elements
- **Intuitive Navigation**: Easy to use, even for beginners

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Git


## 📋 Project Structure

```
vuln-scanner-dashboard/
│
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
├── README.md              # Project documentation
├── LICENSE                # MIT License
├── .gitignore            # Git ignore rules
│
├── templates/
│   └── index.html        # Main dashboard template
│
├── static/               # (Auto-created)
│   ├── css/
│   ├── js/
│   └── images/
│
└── instance/             # (Auto-created)
    └── vulnerabilities.db  # SQLite database
```










