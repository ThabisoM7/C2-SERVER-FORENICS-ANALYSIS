 C2 (COMMAND AND CONTROL) FRAMEWORK FORENSIC ANALYSIS

This repository documents a security lab simulation involving red team operations using a C2 (Command and Control) framework and blue team digital forensics using Velociraptor.



 Overview
- Onboarded an agent using a C2 framework on a simulated Windows VM
- Executed post-exploitation tasks (SHELLCODE EXECUTION, PROCESS LISTING AND PERSISTANCE MECHANISM)
- Collected forensic artifacts via Velociraptor for investigation
- Analyzed registry keys, event logs, and execution timelines

 Key Skills Demonstrated
- Command & Control operations
- Endpoint forensics with Velociraptor
- Windows internals (processes, registry)
- Blue team threat detection and response

Files Included
- `/report/` – Full written lab report (DOCX)
- `/LAB-SNAPSHOTS/` – Images of tasks, callbacks, Velociraptor queries
- `/logs/` – Output logs from agent and Velociraptor
- `/artifacts/` – Extracted forensic artifacts

## Tools Used
AdaptixC2 (COMMAND AND CONTROL)
Velociraptor
VirtualBox
Windows 10 VM + Kali Linux
DHCP config
STIX ATTACK SEQUENCE MODEL


The agent successfully beaconed to the C2 server and established persistence via registry keys. Velociraptor hunts revealed malicious artifacts, execution timestamps, and supported timeline analysis

(DISCLAIMER: ALL THE WORK AND CONFIGURATIONS THAT HAVE TAKEN PLACE WITHIN THIS REPO ARE STRICTLY FOR EDUCATIONAL PURPOSES.THE TOOLS AND METHODOLOGIES SHOULD NOT BE USED FOR ANY MALICIOUS ACTIVITY)
