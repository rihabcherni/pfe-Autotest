# pfe-AutoTest
Automated Testing Platform  

<p align="center">
    <img src="screenshots/logo.png" alt="logo" width="10%"/>
</p>

## Overview
**AutoTest** is an all-in-one automated testing platform that unifies **functional testing**, **SEO audits**, and **security penetration testing** into a single workflow.  
It enables teams to streamline test execution, track results in real-time, and centralize reporting for better decision-making.

## Architecture
- **Frontend (Angular)** → User-friendly interface to configure and launch tests  
- **Backend (FastAPI)** → API for test orchestration, vulnerability detection, SEO analysis, and reporting  
- **Database (PostgreSQL)** → Stores test scenarios, results, and reports  
- **Message/Notification Layer** → Slack, Email, Jira integrations  

<p align="center">
    <img src="screenshots/architecture.png" alt="Architecture" width="70%"/>
</p>

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

## Screenshots & Demos

### Home
<p align="center">
    <img src="screenshots/acc1.png" alt="Home Screenshot" width="49%"/>
    <img src="screenshots/acc2.png" alt="Home Screenshot" width="49%"/>
</p>

### Authentication
<p align="center">
    <img src="screenshots/auth1.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth2.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth3.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth4.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth5.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth6.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth7.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth8.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth9.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth10.png" alt="Auth Screenshot" width="49%"/>
    <img src="screenshots/auth11.png" alt="Auth Screenshot" width="49%"/>
</p>

### Dashboard View
<p align="center">
    <img src="screenshots/dash1.png" alt="Dashboard Screenshot" width="49%"/>
    <img src="screenshots/dash2.png" alt="Dashboard Screenshot" width="49%"/>
</p>

### Functional Testing Workflow
<p align="center">
    <img src="screenshots/workflow.png" alt="Workflow Screenshot" width="70%"/>
    <img src="screenshots/fn1.png" alt="Functional Test Screenshot" width="60%"/>
    <img src="screenshots/fn2.png" alt="Functional Test Screenshot" width="39%"/>
</p>

### SEO Audit Report
<p align="center">
    <img src="screenshots/seo.png" alt="SEO Report Screenshot" width="70%"/>
</p>

### Pentest Scan Results
<p align="center">
    <img src="screenshots/sec0.png" alt="Pentest Screenshot" width="49%"/>
    <img src="screenshots/sec1.png" alt="Pentest Screenshot" width="49%"/>
    <img src="screenshots/sec00.png" alt="Pentest Screenshot" width="49%"/>
    <img src="screenshots/sec01.png" alt="Pentest Screenshot" width="49%"/>
    <img src="screenshots/sec2.png" alt="Pentest Screenshot" width="49%"/>
    <img src="screenshots/sec3.png" alt="Pentest Screenshot" width="49%"/>
    <img src="screenshots/sec4.png" alt="Pentest Screenshot" width="70%"/>
    <img src="screenshots/sec5.png" alt="Pentest Screenshot" width="49%"/>
    <img src="screenshots/sec6.png" alt="Pentest Screenshot" width="49%"/>
</p>

### Report Configuration (Jira, Gmail, Slack)
<p align="center">
    <img src="screenshots/config.png" alt="Config Screenshot" width="49%"/>
    <img src="screenshots/config5.png" alt="Config Screenshot" width="49%"/>   
    <img src="screenshots/config2.PNG" alt="Config Screenshot" width="49%"/>    
    <img src="screenshots/config3.PNG" alt="Config Screenshot" width="49%"/>    
    <img src="screenshots/config4.png" alt="Config Screenshot" width="49%"/>
    <img src="screenshots/config6.png" alt="Config Screenshot" width="49%"/>
</p>

### Notifications
<p align="center">
    <img src="screenshots/notif.PNG" alt="Notification Screenshot" width="30%"/><br>
    <img src="screenshots/notif1.PNG" alt="Notification Screenshot" width="49%"/>
    <img src="screenshots/notif2.png" alt="Notification Screenshot" width="49%"/>    
</p>

### Reports
<p align="center">
    <img src="screenshots/report1.PNG" alt="Report Screenshot" width="49%"/>
    <img src="screenshots/report2.PNG" alt="Report Screenshot" width="49%"/>
    <img src="screenshots/report3.png" alt="Report Screenshot" width="49%"/>
</p>

### Scheduling
<p align="center">
    <img src="screenshots/planfication.png" alt="Scheduling Screenshot" width="49%"/>
</p>

### User List
<p align="center">
    <img src="screenshots/user-liste.PNG" alt="User List Screenshot" width="49%"/>
</p>
