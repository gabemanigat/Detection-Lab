# Detection Lab: Simulating and Detecting Cyber Attacks

## Objective

The **Detection Lab** project created a controlled environment to simulate and detect cyber attacks. The main goal was to ingest and analyze logs within a **Security Information and Event Management (SIEM)** system, generating realistic telemetry to mimic real-world attack scenarios. This hands-on lab deepened understanding of network security, attack patterns, and effective defensive strategies.

---

### Skills Learned

- Advanced understanding of **SIEM concepts** and their practical applications. 
- Proficiency in analyzing and interpreting **network and system logs**.
- Ability to generate and identify **attack signatures** and patterns.
- Enhanced knowledge of **network protocols** and associated vulnerabilities.
- Strengthened **critical thinking** and problem-solving skills in cybersecurity.

---

### Tools Used

- **SIEM System:** For log ingestion, analysis, and threat detection.
- **Network Analysis Tools (e.g., Wireshark):** For capturing and analyzing network traffic.
- **Telemetry Generation Tools:** To simulate realistic network traffic and attack scenarios.
- **Windows/Linux Systems:** Configured as endpoints and servers for testing.

---

## Steps

### **Step 1: Design the Network Diagram**
   - A virtual network was set up to simulate a real-world environment:
     - **Windows Client:** Represents the user endpoint and target for attacks.
     - **Windows Server:** Configured as the Active Directory domain controller.
     - **Linux Server:** Hosting a vulnerable web application.
     - **SIEM Server:** Aggregates logs from all endpoints for monitoring and analysis.

   *Ref 1: Network Diagram*  
   <img src="https://i.imgur.com/sample-network-diagram.png" alt="Network Diagram" width="70%"/>

---

### **Step 2: Configure the SIEM System**
   - Ingested logs from multiple sources:
     - **Windows Event Logs:** Captured user authentication, privilege escalations, and system activities.
     - **Sysmon Logs:** Provided detailed telemetry on process execution and network connections.
     - **Linux Syslogs:** Monitored server activity and network events.
   - Set up correlation rules to detect suspicious patterns like brute force attacks and lateral movement.

   *Ref 2: SIEM Configuration Screenshot*  
   <img src="https://i.imgur.com/sample-siem-setup.png" alt="SIEM Configuration" width="70%"/>

---

### **Step 3: Simulate Attack Scenarios**
   - Generated telemetry using attack simulation tools to replicate real-world threats:
     - **Brute Force Attacks:** On RDP and SSH services.
     - **Phishing Simulations:** Tested email payloads targeting user credentials.
     - **Lateral Movement:** Using SMB and other protocols to move between systems.
   - Captured logs and telemetry from these attacks for analysis in the SIEM.

   *Ref 3: Attack Simulation Screenshot*  
   <img src="https://i.imgur.com/sample-attack-simulation.png" alt="Attack Simulation" width="70%"/>

---

### **Step 4: Analyze Logs and Detect Threats**
   - Correlated logs to identify indicators of compromise (IOCs):
     - **Example 1:** Multiple failed login attempts followed by a successful login (brute force detection).
     - **Example 2:** High volume of DNS requests to an unknown domain (potential exfiltration).
   - Created dashboards to visualize attack patterns and monitor events in real-time.

   *Ref 4: Detection Dashboard Screenshot*  
   <img src="https://i.imgur.com/sample-detection.png" alt="Detection Dashboard" width="70%"/>

---

### **Step 5: Document Findings**
   - Recorded findings, including:
     - Rules and alerts created for attack detection.
     - Recommendations for improving log ingestion and correlation.
   - Compiled reports highlighting vulnerabilities and suggested mitigation strategies.

   *Ref 5: Documentation Screenshot*  
   <img src="https://i.imgur.com/sample-documentation.png" alt="Documentation Screenshot" width="70%"/>


   

---

---
