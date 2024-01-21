# Project Portfolio: Enhancing Network Security with Suricata, OPNsense, and Wazuh

## Project Overview
In this project, the goal was to strengthen the network security of my simulated enterprise in my homelab by implementing a comprehensive solution involving Suricata for custom rule creation in OPNsense and integrating Wazuh for advanced threat detection and active response.

### 1. Suricata Custom Rules in OPNsense
- **Objective:** Strengthen network visibility and threat detection by customizing Suricata rules on the OPNsense firewall.
- **Implementation:**
  - Configured Suricata, an open-source intrusion detection and prevention system, on the OPNsense firewall.
  - Developed and deployed custom rules in Suricata to generate alerts for every interaction with IP addresses within the network.

### 2. Wazuh Active Response for Brute Force Protection
- **Objective:** Enhance security measures by implementing active response mechanisms using Wazuh.
- **Implementation:**
  - Integrated Wazuh, an open-source security information and event management (SIEM) tool, into the network infrastructure.
  - Utilized custom active responses in Wazuh to implement dynamic firewall blocking in response to brute force attacks.
  - Configured Wazuh to initiate firewall blocks for IP addresses involved in multiple failed login attempts within a specified time frame.

### 3. Key Achievements and Outcomes
- **Improved Threat Detection:**
  - Suricata's custom rules provided granular visibility into network interactions, enabling swift detection of potential threats.
  - OPNsense, empowered by Suricata, became a robust first line of defense against various network-based attacks.

- **Proactive Brute Force Protection:**
  - Wazuh's active response mechanisms, combined with custom rules, allowed for the immediate identification and mitigation of brute force attacks.
  - Automatic firewall blocking for repeat offenders added an additional layer of security against persistent threats.

- **Efficient Incident Response:**
  - By integrating Suricata and Wazuh, the project facilitated a streamlined incident response process, minimizing the time between threat detection and mitigation.

### 4. Lessons Learned
- **Configuration Accuracy:**
  - Precision in creating custom rules is crucial for effective threat detection. Ensuring accurate configurations in Suricata is essential for minimizing false positives and negatives.

- **Active Response Fine-Tuning:**
  - Continuous refinement of active response mechanisms in Wazuh is necessary to strike a balance between security and user convenience.

### 5. Future Enhancements
- **Incident Investigation Capabilities:**
  - Consider expanding Wazuh's integration with additional security tools to enhance incident investigation capabilities.

- **User Awareness Training:**
  - Implement user awareness programs to educate users about the importance of strong passwords and cybersecurity best practices.

### 6. Conclusion
This project successfully leveraged Suricata, OPNsense, and Wazuh to create a robust network security infrastructure. The combination of custom rules for threat detection and active response mechanisms for immediate mitigation ensures a proactive and efficient defense against various cyber threats. Continuous monitoring, periodic rule adjustments, and user education will contribute to the project's long-term success in maintaining a secure network environment.
