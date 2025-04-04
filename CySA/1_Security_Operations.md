# SECURITY OPERATIONS
*Security Operations is a critical component in the Cybersecurity Analyst (CySA+) certification, as it directly ties into the day-to-day activities of a cybersecurity analyst. It refers to the practices, processes, and tools used to detect, analyze, and respond to security threats in an organization. Security Operations ensures that cybersecurity teams can effectively monitor, detect, and respond to incidents, minimizing damage and preventing future risks.*

## [1.1] Explain the importance of system and network architecture concepts in security operations.
### Log ingestion 
  - Time synchronization: the process of collecting and processing logs from various sources such as systems, network devices, applications, and security appliances. 
  - Logging levels: Different logging levels (e.g., info, warning, error, debug) define the severity of the logged event.
    - Fatal:	One or more key business functionalities are not working and the whole system doesn’t fulfill the business functionalities.
    - Error:	One or more functionalities are not working, preventing some functionalities from working correctly.
    - Warn:	Unexpected behavior happened inside the application, but it is continuing its work and the key business features are operating as expected.
    - Info:	An event happened, the event is purely informative and can be ignored during normal operations.
    - Debug:	A log level used for events considered to be useful during software debugging when more granular information is needed.
    - Trace:	A log level describing events showing step by step execution of your code that can be ignored during the standard operation, but may be useful during extended debugging sessions.


### Operating system (OS) concepts
  - Windows Registry: Hierarchical database used by the Windows operating system to store configuration settings and options for both the OS and installed applications.
  - System hardening: Process of securing an OS by reducing its surface of vulnerability. This includes patching vulnerabilities, disabling unnecessary services, configuring security settings, and applying security best practices.
  - File structure: 
    - Configuration file locations
  - System processes: Programs that the operating system manages and executes, ranging from critical system functions to user applications.
  - Hardware architecture: Physical components of a system and how they interact with the software. This includes CPU, memory, storage devices, and network interfaces.

### Infrastructure concepts
  - Serverless: 
  - Virtualization
  - Containerization

### Network architecture
  - On-premises
  - Cloud
  - Hybrid
  - Network segmentation
  - Zero trust
  - Secure access secure edge (SASE)
  - Software-defined networking (SDN)

 ### Identity and access management
  - Multifactor authentication (MFA)
  - Single sign-on (SSO)
  - Federation
  - Privileged access management (PAM)
  - Passwordless
  - Cloud access security broker (CASB)

 ### Encryption
  - Public key infrastructure (PKI)
  - Secure sockets layer (SSL) inspection

### Sensitive data protection
  - Data loss prevention (DLP)
  - Personally identifiable information (PII)
  - Cardholder data (CHD)

## [1.2] Given a scenario, analyze indicators of potentially malicious activity.
### Network-related
  - Bandwidth consumption
  - Beaconing
  - Irregular peer-to-peer communication
  - Rogue devices on the network
  - Scans/sweeps
  - Unusual traffic spikes
  - Activity on unexpected ports

### Host-related
  - Processor consumption
  - Memory consumption
  - Drive capacity consumption
  - Unauthorized software
  - Malicious processes
  - Unauthorized changes
  - Unauthorized privileges
  - Data exfiltration
  - Abnormal OS process behavior
  - File system changes or anomalies
  - Registry changes or anomalies
  - Unauthorized scheduled tasks

### Application-related
  - Anomalous activity
  - Introduction of new accounts
  - Unexpected output
  - Unexpected outbound communication
  - Service interruption
  - Application logs

### Other
  - Social engineering attacks
  - Obfuscated Links 

## [1.3] Given a scenario, use appropriate tools or techniques to determine malicious activity.

## [1.4] Compare and contrast threat-intelligence and threat-hunting concepts.

## [1.5] Explain the importance of efficiency and process improvement in security operations.

