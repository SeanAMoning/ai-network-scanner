# Agentic Network Analysis Tool (AI Network Scanner)

This project is an AI-driven autonomous cybersecurity agent designed to explore, analyze, and visualize enterprise-like networks. It simulates the decision-making process of a real cybersecurity analyst using AI, machine learning, and automated scanning workflows.

---

## Project Overview

The Agentic Network Analysis Tool uses an AI agent to autonomously perform reconnaissance, vulnerability scanning, classification, and risk visualization.  
It uses MITRE ATT&CK–aligned workflows, machine-learning-based vulnerability prioritization, and a modern dashboard for real-time visibility.

The system is designed to reduce manual workload by:
- Automating host and service scanning  
- Identifying high-risk vulnerabilities  
- Mapping network topology  
- Prioritizing risk using machine learning and GNN models  
- Presenting results in a real-time, interactive dashboard  

---

## Features

### Autonomous Network Scanning
- Host discovery  
- OS fingerprinting  
- Service enumeration  
- Integrations: Nmap, OpenVAS, Nikto, Metasploit  

### AI and Machine Learning Classification
- PyTorch-based supervised vulnerability classifier  
- Enhanced scoring using CVSS + EPSS  
- Adaptive contextual risk prioritization  

### Network Topology Modeling
- Graph Neural Network (GNN) for mapping node relationships  
- Risk propagation modeling  
- Dynamic risk overlays  

### Real-Time Dashboard
- Built with Next.js and D3.js/Cytoscape.js  
- Live network topology visualization  
- Vulnerability ranking lists  
- AI agent activity and decision logging  

---

## Technology Stack

- AI Agent: GPT-OSS-120B (locally hosted)  
- Agent Framework: LangChain / LangGraph  
- Scanning Tools: Nmap, OpenVAS, Nikto, Metasploit  
- Machine Learning: PyTorch (Classifier + GNN)  
- Backend: Python microservices, PostgreSQL  
- Frontend: Next.js with D3.js or Cytoscape.js  
- Infrastructure: Containerized testbed on HCU servers  

---

## System Architecture

A detailed architecture diagram will be added soon.  
(Place in `/docs/architecture.png` once ready.)

---

## How The System Works

### Inputs
- Network scan results  
- CVE/NVD and EPSS threat intelligence  
- IDS/IPS logs  
- Network topology updates  

### Process
1. AI agent selects actions based on MITRE ATT&CK workflows  
2. Performs scans and collects network data  
3. Machine-learning model classifies vulnerabilities  
4. GNN analyzes network structure and risk flow  
5. Dashboard displays real-time insights  

### Outputs
- Ranked vulnerability list  
- Topology map with risk overlays  
- Agent action and decision log  
- Mitigation recommendations  

---

## Project Status

Current status: **In Progress**

Planned milestones:
- [ ] Implement baseline scanner  
- [ ] Develop agent workflows  
- [ ] Train ML classifier  
- [ ] Implement GNN topology model  
- [ ] Build dashboard interface  
- [ ] Conduct live testbed demonstration  

---

## Team Roles

### Sean Moning — Network Analyst / Engineer
- Creates vulnerable configurations and test environments  
- Maps vulnerabilities to MITRE ATT&CK  
- Validates IDS/IPS alerts  
- Helps build and maintain sandbox network infrastructure  

Other team contributions include AI/ML development, dashboard engineering, and server infrastructure setup.

---

## License

To be added.


