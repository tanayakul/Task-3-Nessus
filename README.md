# Vulnerability Scan Report

## Task 3: Perform a Basic Vulnerability Scan on Your PC

### Objective

The objective of this task was to identify common vulnerabilities and security issues present on my computer using Nessus Essentials.

### Tool Used

* Nessus Essentials

### Target Information

* Target IP Address: 192.168.1.7
* Scan Type: Host Discovery Scan

### Procedure

1. Installed and configured Nessus Essentials.
2. Identified the local machine IP address.
3. Created a new scan in Nessus.
4. Entered the target IP address.
5. Executed the scan and waited for completion.
6. Analyzed the scan results.

### Scan Results
The scan was completed successfully on the target system.

#### Open Ports Detected

1. 135 (Microsoft RPC)
2. 139 (NetBIOS Session Service)
3. 445 (SMB)
4. 49664
5. 49665
6. 49666
7. 49669
8. 49674
9. 49684

#### Vulnerability Summary

1. Critical: 0
2. High: 0
3. Medium: 0
4. Low: 0
5. Informational: 2

### Findings:
The scan identified two informational findings. No critical, high, medium, or low severity vulnerabilities were detected. The detected findings were related to network services and open ports available on the system.

### Recommendations
1. Keep the operating system updated.
2. Enable Windows Firewall.
3. Close unnecessary ports and services if not required.
4. Perform regular vulnerability scans.
5. Use updated antivirus and security software.

### Conclusion
The vulnerability assessment was successfully performed using Nessus Essentials. The scan did not identify any serious vulnerabilities on the system. 
