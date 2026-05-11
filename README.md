# Wazuh SOC Homelab

## Objective

The objective of this project was to build a basic SOC-style homelab using Wazuh, Ubuntu Server, Docker, a Windows endpoint, Sysmon, and Windows Event Viewer.

This project demonstrates hands-on experience with endpoint monitoring, SIEM visibility, failed login detection, event review, and cybersecurity documentation.

## Tools Used

- Wazuh
- Ubuntu Server
- Docker
- Docker Compose
- Windows 11 endpoint
- Wazuh Agent
- Sysmon
- Windows Event Viewer
- VirtualBox

## Lab Environment

The lab was built using a single-node Wazuh deployment on Ubuntu Server with Docker. A Windows endpoint was connected to the Wazuh manager using the Wazuh agent. Sysmon was installed on the Windows endpoint to provide additional endpoint visibility.

## What I Configured

- Installed and ran Wazuh using Docker on Ubuntu Server
- Accessed the Wazuh dashboard through a web browser
- Connected a Windows endpoint to the Wazuh manager
- Installed and enabled Sysmon on the Windows endpoint
- Verified Sysmon Operational logs in Windows Event Viewer
- Generated and captured failed login activity
- Documented security events as evidence

## Security Relevance

This lab helped me practice skills that are important for SOC Analyst and cybersecurity support roles, including:

- SIEM monitoring
- Endpoint visibility
- Log review
- Windows event analysis
- Failed login detection
- Security documentation
- Basic incident response thinking

## Key Takeaways

Through this project, I learned how endpoint activity can be collected, reviewed, and documented in a SIEM environment. I also practiced connecting technical events to security concepts, such as authentication activity, failed logins, endpoint monitoring, and event-based investigation.

## Screenshots

Screenshots will be added to show:

- Wazuh dashboard access
- Windows agent connection
- Sysmon Operational log
- Failed login event capture
- Windows Event Viewer evidence
- Docker/Wazuh containers running

## Future Improvements

- Add more detection examples
- Create sample incident reports
- Add PowerShell event monitoring
- Add Linux endpoint monitoring
- Practice alert triage workflows
