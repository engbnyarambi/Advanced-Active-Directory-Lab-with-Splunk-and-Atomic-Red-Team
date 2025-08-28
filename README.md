# Advanced AD Lab with Splunk & Atomic Red Team

---

## **Introduction**
This project involves setting up an advanced **Active Directory Lab** environment integrated with **Splunk** for monitoring and **Atomic Red Team** for simulating adversary behaviors. It provides a practical, hands-on approach to learning Active Directory administration, security monitoring, and attack detection in a controlled setting. Designed for cybersecurity professionals and enthusiasts, this lab enhances skills in Active Directory security and threat hunting.

---

## **Objectives**
- Design and configure an Active Directory environment with domain controllers, member servers, and client machines.
- Integrate Splunk for centralized log collection, monitoring, and analysis.
- Simulate real-world attack scenarios using Atomic Red Team techniques.
- Detect and analyze simulated attacks through Splunk dashboards and alerts.

---

## **Scope**
This project focuses on:
- **Active Directory Setup**: Creating a realistic domain environment with standard configurations.
- **Threat Simulation**: Executing Atomic Red Team techniques to mimic adversarial behaviors.
- **Log Analysis**: Leveraging Splunk for monitoring, threat hunting, and event correlation.
- **Incident Detection**: Developing custom Splunk dashboards and alerts to identify and respond to threats.

---

## **Tools**
- **VMWare/VirtualBox**: To host and manage the virtual lab environment.
- **Windows Server ISO**: For setting up domain controllers and member servers.
- **Windows 10 ISO**: For configuring client machines.
- **Splunk Free Edition**: For log collection, monitoring, and analysis.
- **Atomic Red Team**: To execute simulated attack techniques based on MITRE ATT&CK.
- **Kali Linux**: As the attacker machine for penetration testing and reconnaissance.

---

## **Methodology**

### **1. Environment Setup**
- Configure domain controllers, member servers, and clients in a virtualized environment.
- Install and configure Splunk for centralized logging.
- Set up core services such as DNS, DHCP, and Group Policy for the domain.

### **2. Splunk Integration**
- Forward logs from domain controllers and member servers to Splunk.
- Set up Splunk data inputs and create indexes for log categorization.
- Develop Splunk dashboards to monitor and visualize Active Directory activity.

### **3. Attack Simulation**
- Use Atomic Red Team to execute techniques such as lateral movement, privilege escalation, and persistence.
- Simulate real-world attack scenarios to evaluate detection capabilities.

### **4. Log Analysis and Detection**
- Analyze collected logs in Splunk to identify patterns of malicious activity.
- Configure alerts for critical events, such as unauthorized logins or privilege escalations.

### **5. Validation and Reporting**
- Document findings, detections, and remediation efforts.
- Assess the effectiveness of detection mechanisms and propose improvements.

---

## **Results**
- **Improved Detection Capabilities**: Successfully identified and detected various adversary techniques using Splunk.
- **Enhanced Skills**: Gained practical experience in Active Directory security, log analysis, and threat hunting.

---

## **Challenges**
- Configuring seamless log forwarding between systems and Splunk.
- Balancing system performance while running multiple virtual machines.
- Optimizing Splunk queries for accurate and efficient detection.

---

## **Key Takeaways**
- Comprehensive log collection and analysis are essential for effective threat detection.
- Simulating real-world attacks provides valuable insights into security gaps and detection capabilities.

---

## **Acknowledgments**
- **MYDFIR Tutorials**: Special thanks to Steven for his comprehensive Active Directory and security monitoring labs. [Learn more here](https://www.youtube.com/watch?v=5OessbOgyEo&t=87s).
- **Atomic Red Team**: For their open-source library of adversary simulation techniques. [Learn more here](https://github.com/redcanaryco/atomic-red-team).
