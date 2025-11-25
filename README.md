# 🚀 Agentic Network Analysis Tool (AI Network Scanner)

An AI-driven autonomous cybersecurity agent designed to explore, analyze, and visualize enterprise-like networks. 
This project simulates the decision-making of a real cybersecurity analyst using AI, machine learning, and automated scanning workflows.

---

## 🎯 Project Overview

The Agentic Network Analysis Tool uses an AI agent to autonomously perform reconnaissance, vulnerability scanning, classification, and risk visualization.  
It integrates MITRE ATT&CK–aligned workflows with machine-learning-powered prioritization and a Next.js dashboard for real-time insights.

This tool reduces the manual workload of cybersecurity teams by:
- Automating scanning tasks  
- Identifying high-risk vulnerabilities  
- Mapping network topology  
- Prioritizing risk using ML and GNN models  
- Displaying findings in a real-time interactive dashboard  

---

## 🧩 Features

### 🔍 Autonomous Network Scanning
- Host discovery  
- OS fingerprinting  
- Service enumeration  
- Integrations: Nmap, OpenVAS, Nikto, Metasploit  

### 🤖 AI/ML Classification
- PyTorch-based supervised vulnerability classifier  
- CVSS + EPSS–enhanced scoring  
- Adaptive risk prioritization  

### 🌐 Network Topology Modeling
- Graph Neural Network (GNN) maps node relationships  
- Risk propagation detection  
- Dynamic risk overlays  

### 📊 Real-Time Dashboard
- Built with Next.js + D3.js/Cytoscape.js  
- Live topology mapping  
- Vulnerability ranking interface  
- AI agent activity logs  

---

## 🔧 Technology Stack

**AI Agent:** GPT-OSS-120B (locally hosted)  
**Orchestration:** LangChain / LangGraph  
**Scanning Tools:** Nmap, OpenVAS, Nikto, Metasploit  
**Machine Learning:** PyTorch (Classifier + GNN)  
**Backend:** Python microservices + PostgreSQL  
**Frontend:** Next.js + D3.js/Cytoscape.js  
**Infrastructure:** HCU-hosted server testbed (containerized)

---

## 🏗️ System Architecture  
*(Diagram coming soon)*  
`/docs/architecture.png`

---

## 🧠 How It Works (Workflow)

**Inputs:**  
- Network scan results  
- CVE/NVD + EPSS threat feeds  
- IDS/IPS log activity  
- Topology updates  

**Process:**  
1. AI agent selects ATT&CK-aligned actions  
2. Scans hosts and services  
3. Classifier evaluates vulnerabilities  
4. GNN models the full network graph  
5. Dashboard displays real-time results  

**Outputs:**  
- Ranked vulnerability list  
- Topology + risk overlay  
- Agent decision log  
- Mitigation recommendations  

---

## 📈 Project Status  
**IN PROGRESS**

Planned milestones:
- [ ] Build baseline network scanner  
- [ ] Develop agent workflows  
- [ ] Train ML classifier  
- [ ] Implement GNN topology model  
- [ ] Dashboard development  
- [ ] Live testbed demo  

---

## 👥 Team Roles

### **Sean Moning — Network Analyst / Engineer**
- Vulnerable configuration setup  
- MITRE ATT&CK technique mapping  
- IDS/IPS validation  
- Sandbox network creation and maintenance  

Other team responsibilities include ML engineering, full-stack dashboard development, and infrastructure setup.

---

## 📄 License  
To be added.
