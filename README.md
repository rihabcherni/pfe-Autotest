# 🚀 pfe-AutoTest
Automated Testing Platform  

---

## Overview
**AutoTest** is an all-in-one automated testing platform that unifies **functional testing**, **SEO audits**, and **security penetration testing** into a single workflow.  
It enables teams to streamline test execution, track results in real-time, and centralize reporting for better decision-making.

The platform is built with:
- **Backend**: FastAPI  
- **Frontend**: Angular  
- **Database**: PostgreSQL  

---

## Features

### Functional Testing
- Workflow-based execution with **Selenium integration**  
- Automated UI testing for web applications  
- Support for reusable test scenarios  

### SEO Auditing
- Technical SEO analysis (meta tags, broken links, sitemaps, structured data)  
- Performance and accessibility scoring  
- Exportable SEO reports in **PDF/HTML**  

### Security & Pentesting
- Automated vulnerability scanning using tools: **OWASP ZAP, SQLMap, Nikto, Nuclei, OpenVAS**  
- Authenticated and unauthenticated scan support  
- Centralized vulnerability database with **risk classification**  
- **Jira/Slack integration** for issue reporting and notifications  

### Reporting & Notifications
- Unified dashboard with test results and vulnerability stats  
- Export reports in **PDF, HTML, JSON** formats  
- Integration with **Slack, Gmail, Jira** for notifications  

---

## Architecture
- **Frontend (Angular)** → User-friendly interface to configure and launch tests  
- **Backend (FastAPI)** → API for test orchestration, vulnerability detection, SEO analysis, and reporting  
- **Database (PostgreSQL)** → Stores test scenarios, results, and reports  
- **Message/Notification Layer** → Slack, Email, Jira integrations  

---

## Installation

```bash
# Clone the repository
git clone https://github.com/your-repo/autotest.git
cd autotest

# Backend setup
cd backend
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:combined_app --reload

# Frontend setup
cd frontend
npm install
ng serve
````

---

## Usage

1. Log in to the **web UI**
2. Configure a test campaign (**Functional / SEO / Security**)
3. Launch automated scans or workflows
4. View results in **real-time** and export reports
5. Receive notifications via **Slack / Gmail / Jira**

---

## Screenshots & Demos

* **Dashboard View**

<p align="center">
    <img src="screenshots/dash1.png" alt="Dashboard Screenshot" width="70%"/>
    <img src="screenshots/dash2.png" alt="Dashboard Screenshot" width="70%"/>
</p>

* **Functional Testing Workflow**

<p align="center">
    <img src="screenshots/workflow.png" alt="Functional Testing Screenshot" width="70%"/>
</p>

* **SEO Audit Report**

<p align="center">
    <img src="screenshots/seo.png" alt="SEO Report Screenshot" width="70%"/>
</p>

* **Pentest Scan Results**

<p align="center">
    <img src="screenshots/sec0.png" alt="Pentest Screenshot" width="70%"/>
    <img src="screenshots/sec1.png" alt="Pentest Screenshot" width="70%"/>
    <img src="screenshots/sec2.png" alt="Pentest Screenshot" width="70%"/>
    <img src="screenshots/sec3.png" alt="Pentest Screenshot" width="70%"/>
    <img src="screenshots/sec4.png" alt="Pentest Screenshot" width="70%"/>
    <img src="screenshots/sec5.png" alt="Pentest Screenshot" width="70%"/>
    <img src="screenshots/sec6.png" alt="Pentest Screenshot" width="70%"/>
</p>

---

## Authors

* **Rihab Cherni**
* **Maïssa Ben Ghalba**