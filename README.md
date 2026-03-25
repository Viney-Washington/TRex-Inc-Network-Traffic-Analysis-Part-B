# TRex-Inc-Network-Traffic-Analysis-Part-B

[View Project File](https://github.com/Viney-Washington/TRex-Inc-Network-Traffic-Analysis-Part-B/blob/main/Viney%20Washington%20_%20Part%20B%20Analyzing%20Network%20Traffic%20.pdf)

## Overview
This project analyzes network and system activity to detect cyber attack behavior using Windows Event Viewer and traffic analysis concepts. The focus is on identifying attack phases, correlating system events, and validating detection using a phased incident response decision matrix.

## Objectives
- Analyze network and system activity to identify suspicious behavior  
- Map system events to cyber attack phases using the Cyber Kill Chain  
- Correlate Event IDs to attacker techniques such as privilege escalation and persistence  
- Validate detection methods using a phased attack decision matrix  
- Strengthen incident response strategies based on real system evidence  

## Tools & Technologies
- Wireshark (network traffic analysis concepts)  
- Windows Event Viewer  
- Cyber Kill Chain Framework  
- Incident Response Methodology  

## Key Analysis & Findings
- Event ID 4624 identified successful logon activity, indicating potential initial access using valid credentials  
- Event ID 4672 revealed privileged logon activity, indicating possible privilege escalation  
- Event ID 7045 showed new service installation, supporting persistence mechanisms used by attackers  
- Event ID 1102 indicated audit log clearing, suggesting defense evasion techniques  
- Event ID 5156 highlighted outbound network connections, supporting detection of command-and-control activity  

## Attack Phase Mapping
The detected activity was mapped to cyber attack phases:
- Initial Access → Valid credential logins (Event ID 4624)  
- Privilege Escalation → Elevated access (Event ID 4672)  
- Persistence → Service installation (Event ID 7045)  
- Defense Evasion → Log clearing (Event ID 1102)  
- Command & Control → Outbound connections (Event ID 5156)  

## Incident Response Application
A phased attack decision matrix was used to:
- Identify indicators of compromise (IOCs)  
- Validate suspicious activity using system logs  
- Trigger response actions such as isolation, credential reset, and containment  
- Improve response speed and decision-making consistency  

## Key Takeaways
- System event logs provide critical visibility into attacker behavior  
- Correlating multiple event IDs improves detection accuracy  
- Attack phases can be identified through log analysis  
- Early detection reduces the impact of cyber incidents  
- Structured response models improve incident handling and containment  

## Conclusion
This project demonstrates how network and system log analysis can be used to detect, analyze, and respond to cyber threats. By mapping real system events to attack phases and validating detection through an incident response framework, organizations can improve their overall security posture and reduce risk.
