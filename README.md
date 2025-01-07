# Advanced-Active-Directory-Lab-with-Splunk-and-Atomic-Red-Team


---

## **Introduction**
This project sets up an advanced **Active Directory Lab** environment integrated with **Splunk** for monitoring and **Atomic Red Team** for simulating adversary behaviors. It provides a hands-on approach to learning Active Directory administration, security monitoring, and attack detection in a controlled environment. This lab is designed for cybersecurity enthusiasts and professionals looking to enhance their skills in Active Directory security and threat hunting.

---

## **Objectives**
- Build and configure an Active Directory environment with domain controllers, member servers, and clients.
- Integrate Splunk for log collection, monitoring, and analysis.
- Utilize Atomic Red Team to simulate real-world attack scenarios.
- Analyze and detect simulated attacks using Splunk dashboards and alerts.

---

## **Scope**
This project focuses on:
- **Active Directory Setup**: Create a realistic domain environment with standard configurations.
- **Threat Simulation**: Execute Atomic Red Team techniques to mimic adversarial activities.
- **Log Analysis**: Use Splunk for monitoring, threat hunting, and event correlation.
- **Incident Detection**: Develop custom Splunk dashboards and alerts to identify and respond to threats.

---

## **Tools**
- **VMWare/VirtualBox**: For hosting the virtual lab environment.
- **Windows Server ISO**: For creating domain controllers and member servers.
- **Windows 10 ISO**: For configuring client machines.
- **Splunk Free Edition**: For log collection and monitoring.
- **Atomic Red Team**: For executing simulated attack techniques.
- **Kali Linux**: As the attacking machine for penetration testing and reconnaissance.

---

## **Methodology**
1. **Environment Setup**:
   - Configure domain controllers, member servers, and clients in a virtualized environment.
   - Install and configure Splunk for centralized logging.
   - Set up necessary services such as DNS, DHCP, and Group Policy.

2. **Splunk Integration**:
   - Forward logs from domain controllers and member servers to Splunk.
   - Set up data inputs and create indexes for log categorization.
   - Develop dashboards for monitoring Active Directory activity.

3. **Attack Simulation**:
   - Use Atomic Red Team to execute techniques such as lateral movement, privilege escalation, and persistence.
   - Simulate real-world scenarios to test the effectiveness of detection mechanisms.

4. **Log Analysis and Detection**:
   - Analyze logs in Splunk to identify patterns of malicious activity.
   - Configure alerts for critical events, such as unauthorized logins or privilege changes.

5. **Validation and Reporting**:
   - Document findings, detections, and remediations.
   - Assess the effectiveness of security measures and propose improvements.

---

## **Results**
- **Enhanced Detection Capabilities**: Successfully identified and detected various attack techniques using Splunk dashboards.
- **Practical Experience**: Improved understanding of Active Directory security, log analysis, and threat hunting.

---

## **Challenges**
- Configuring seamless log forwarding from all systems to Splunk.
- Managing resource usage while running multiple virtual machines.
- Fine-tuning Splunk queries for optimal detection accuracy.

---

## **Key Takeaways**
- Comprehensive log collection and analysis are critical for effective threat detection.
- Simulating real-world attacks provides invaluable insights into system vulnerabilities and detection gaps.

---

## **Acknowledgments**
- **Atomic Red Team**: For providing an open-source library of adversary simulation techniques. [Learn more here](https://github.com/redcanaryco/atomic-red-team).
- **Splunk Team**: For their robust platform and community resources on log analysis and monitoring. [Learn more here](https://www.splunk.com/).
- **Tech Tutorials**: For their guidance on Active Directory and security monitoring setups.
