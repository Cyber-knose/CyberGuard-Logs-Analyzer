# CyberGuard-Logs-Analyzer
Repository Name: CyberGuard-Logs-Analyzer Description: 🔒 Real-time Cybersecurity Logs Analyzer with Threat Detection Tags: cybersecurity, logs, flask, security, dashboard License: MIT

CyberGuard-Logs-Analyzer/
├── README.md                 ← This description
├── app.py                    ← Main Flask app (ALL-IN-ONE)
├── requirements.txt          ← Dependencies
├── data/
│   └── sample_logs.json      ← Sample data
├── static/
│   ├── style.css            ← Optional CSS
│   └── script.js            ← Optional JS
└── .github/workflows/
    └── deploy.yml           ← Auto-deploy

    # 🔒 CyberGuard - Logs Analyzer

[![Status](https://img.shields.io/badge/Status-Live-brightgreen)](https://your-username.github.io/CyberGuard-Logs-Analyzer)
[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://python.org)
[![License](https://img.shields.io/github/license/yourusername/CyberGuard-Logs-Analyzer)](LICENSE)

**Real-time cybersecurity logs analyzer with threat detection, dashboard, and live monitoring.**

## ✨ Features
- 🔍 Real-time log analysis
- 🚨 Automatic threat detection (DDoS, brute force, port scans)
- 📊 Interactive dashboard with stats
- 🔎 Advanced search & filtering
- 🌐 Fully responsive design
- ⚡ Live updates every 30 seconds

## 🚀 Quick Start

### Option 1: GitHub Codespaces (Recommended)
1. Click **"Code" → "Codespaces" → "Create codespace"**
2. Wait for setup (2 mins)
3. Terminal: `pip install -r requirements.txt`
4. Run: `python app.py`
5. **Click "Port 5000" → Open in Browser** ✅

📈 Threat Detection Rules
DDoS: >15 requests/IP in 100 logs
Brute Force: Multiple deny actions/IP
High Threat: Threat score > 0.8
Port Scans: Multiple ports/IP
🤝 Contributing
Fork the repo
Create feature branch
Submit PR
📄 License
MIT License - Free to use/modify

🙏 Acknowledgments
Built for cybersecurity education & monitoring

### Option 2: Local Setup
```bash
git clone https://github.com/YOURUSERNAME/CyberGuard-Logs-Analyzer.git
cd CyberGuard-Logs-Analyzer
pip install -r requirements.txt
python app.py
# Open: http://localhost:5000

🛠 Tech Stack
Backend: Flask, Pandas, NumPy
Frontend: Vanilla HTML/CSS/JS
Data: JSON logs with threat scoring
Deployment: GitHub Codespaces, Replit, Render



