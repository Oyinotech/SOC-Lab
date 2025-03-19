# SOC LAB

## Description

This SOC lab project focused on implementing a Security Information and Event Management (SIEM) system using Splunk to monitor, detect, and analyze security threats within an IT infrastructure. The project involved installing Splunk on a virtualized Windows environment, ingesting event logs, and performing security queries to enhance real-time monitoring and threat detection.


### Objectives

- To understand the role of SIEM in security operations.
- To install and configure Splunk as a SIEM tool.
- To collect, index, and analyze security event logs.
- To enhance threat detection, incident response, and compliance monitoring in an IT environment.

### Skills Learned

- SIEM fundamentals and its importance in Security Operations Centers (SOC).
- Installation and configuration of Splunk on a virtual machine.
- Log ingestion and data indexing using Splunk.
- Search Processing Language (SPL) for querying security logs.
- Event correlation and threat detection techniques.
- Troubleshooting and overcoming compatibility challenges.

### Tools Used

- Splunk (for log collection, indexing, and security analysis).
- Oracle VirtualBox (for creating a virtual machine).
- Windows 10 ISO (to provide a compatible OS for Splunk).
- Microsoft Event Logs (for data ingestion: Application, Security, and System logs).

## Steps

1. Environment Setup:
- Installed Oracle VirtualBox
- Created a Windows 10 Virtual Machine (due to Splunk’s incompatibility with Windows 11)
2. Splunk Installation:
- Downloaded and installed Splunk Enterprise on Windows
- Configured network settings to access Splunk Web Interface

*Fig 1 & 2: Installation Process*
![image](https://github.com/user-attachments/assets/0cb8087a-2f82-4f4c-b38b-b0393c91d9f7)

![image](https://github.com/user-attachments/assets/2faec924-4c21-4ad0-9ec5-f1735fb01805)

3. Data Ingestion:
- Collected Windows Event Logs (Application, Security, and System logs)
- Configured Splunk inputs for log indexing

*Fig 3: Data Inputs*

![image](https://github.com/user-attachments/assets/5e02a7b2-af58-402d-9369-789942341420)

  
4. Navigating & Querying Splunk:
- Used Search Processing Language (SPL) for querying logs
- Explored event codes


*Fig 4: SPL Queries*
![image](https://github.com/user-attachments/assets/7eb45d36-279c-42a1-84d6-16fe32900d22)

*Fig 5: Search Query*
![image](https://github.com/user-attachments/assets/56e73e73-e056-4f01-9aab-ecf1b11f65fc)

*Fig 6: Event Log*
![image](https://github.com/user-attachments/assets/b34ceeef-eabe-4486-83ce-d4a2ff519bf5)

  
5. SIEM & SOC Integration:
- Understood how SIEM assists SOC teams with threat detection, incident response, compliance, and automation
- Explored real-time alerts and automated threat response


### Challenges Faced

- Initial attempts to install Splunk on Ubuntu failed due to compatibility issues.
- Had to use Windows 10 instead of Windows 11, as Splunk was not supported on Windows 11.

### Conclusion
This project demonstrated the power of SIEM tools like Splunk in security monitoring and threat detection. By centralizing log collection and applying advanced analytics, organizations can detect threats, improve incident response, and maintain regulatory compliance. The hands-on experience reinforced key cybersecurity, data analysis, and SIEM administration skills essential for security professionals.

