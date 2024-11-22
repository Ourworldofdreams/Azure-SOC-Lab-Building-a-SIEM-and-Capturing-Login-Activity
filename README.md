# Azure SOC Lab RDP Honey Pot: Building a SIEM for Real-Time Threat Detection

## Project Overview
This project demonstrates the implementation of a Security Operations Center (SOC) in Azure, featuring a SIEM solution to monitor and analyze potential security threats. The lab simulates real-world scenarios by intentionally exposing RDP services to capture and analyze unauthorized access attempts.

<img width="755" alt="Screenshot 2024-11-22 at 12 36 57 AM" src="https://github.com/user-attachments/assets/4f0445ef-a6f7-46f8-8385-d82e9ad106ff">

---

## 🎯 Project Objectives
- Deploy and configure a Windows 10 Pro VM in Azure
- Implement a SIEM solution for log aggregation and analysis
- Monitor and analyze RDP login attempts
- Create and refine threat detection rules
- Develop incident response procedures

---

## 🛠️ Technologies Used
- Microsoft Azure
- Windows 10 Pro VM
- Remote Desktop Protocol (RDP)
- SIEM Solution
- PowerShell for automation
- Azure Log Analytics
- Azure Security Center

---

## 📋 Project Architecture

### 1. Virtual Machine Configuration
- Deployed Windows 10 Pro VM in Azure
- Configured Network Security Groups (NSGs)
- Enabled RDP access for simulation purposes
- Implemented basic authentication for testing
---
![image](https://github.com/user-attachments/assets/e5a59085-82e1-45a5-9ad9-2d145863ba5f)
![image](https://github.com/user-attachments/assets/96b28321-ebf5-4014-8080-d4df652f9df1)

---

### 2. SIEM Implementation
- Deployed SIEM solution in Azure environment
- Configured log collection and aggregation
- Set up real-time monitoring dashboards
- Established alert rules for suspicious activities
---
![image](https://github.com/user-attachments/assets/62ee057b-ec7c-4acc-acd2-0d389dadaadf)
![image](https://github.com/user-attachments/assets/0905db20-c49e-4ecf-b8df-b6632ed221c4)
![image](https://github.com/user-attachments/assets/3a959065-b053-4846-abc0-a5606433d22f)
![image](https://github.com/user-attachments/assets/ffdf291a-a855-4b9b-9b8a-54ed59d35748)

---
### 3. Security Monitoring Setup
- Created custom log queries
- Implemented alert thresholds
- Configured email notifications
- Developed incident response playbooks
---
![image](https://github.com/user-attachments/assets/6bc1cecd-4651-439f-9d38-5e3848ea4ed0)
![image](https://github.com/user-attachments/assets/e2ac8072-215b-436d-8690-6b7059991e8f)
<img width="897" alt="Screenshot 2024-11-22 at 1 03 08 AM" src="https://github.com/user-attachments/assets/83c334d2-710e-4326-aeb5-4de6bb3c4b33">
![image](https://github.com/user-attachments/assets/77514e20-6dec-4c41-812b-7de51e5e3c53)
![image](https://github.com/user-attachments/assets/55849087-67cb-4692-9a20-34c4bc4ca847)
<img width="1095" alt="image" src="https://github.com/user-attachments/assets/aabb5f1a-f375-43db-941a-3dc9bb050b47">
<img width="1635" alt="image" src="https://github.com/user-attachments/assets/2a93c8ac-827f-4e68-ba02-6d5a39351810">

---

## 🔍 Threat Detection Features
1. **Login Activity Monitoring**
   - Track failed login attempts
   - Monitor successful authentications
   - Identify brute force attack patterns
   - Geographic location analysis of login attempts

2. **Alert Configuration**
   - Multiple failed login attempts
   - Off-hours access attempts
   - Unusual IP address ranges
   - Concurrent session detection

3. **Threat Intelligence Integration**
   - Known malicious IP tracking
   - Automated threat feed updates
   - Custom IOC implementation
   - Real-time threat correlation

---

## 🔐 Security Considerations
- RDP exposure risks and mitigations
- Password policy implementation
- Network segmentation strategies
- Defense-in-depth approach

---

## 📈 Future Enhancements
1. Implementation of Machine Learning for anomaly detection
2. Integration with additional threat intelligence feeds
3. Automated incident response workflows
4. Enhanced visualization and reporting capabilities

---

## 🎓 Learning Outcomes
- Practical experience in SOC operations
- SIEM deployment and configuration
- Real-time threat monitoring
- Incident response procedures
- Log analysis and threat detection
---

## **Key Insights:**

### **Real-time Threat Detection:** 
- The lab showed the power of SIEM systems in monitoring real-time login activity, which is critical for detecting threats early.
### **Understanding Exposed RDP Vulnerabilities:** 
- Exposing RDP services can provide valuable log data for security monitoring, but it also highlights the risk of brute-force attacks on weak passwords.
### **Threat Intelligence Feeds:** 
- Integrating threat intelligence with SIEM enhances the ability to monitor and respond to security threats effectively.

---

## **Conclusion:**

This lab provided hands-on experience in building a SOC and deploying a SIEM system in Azure. I gained valuable insights into cloud-based security monitoring, log analysis, and threat detection techniques. This setup will serve as a foundation for more advanced security operations in the future.

---

## 📝 Documentation and Resources
- [Azure Security Documentation](https://docs.microsoft.com/azure/security/)
- [SIEM Best Practices](https://docs.microsoft.com/security/operations)
- [Azure VM Security](https://docs.microsoft.com/azure/virtual-machines/security-overview)

---

  
