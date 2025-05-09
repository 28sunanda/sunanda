# 👋 Hi there, I'm Sunanda!

🌐 Cybersecurity Professional | 🛡️ ISO 27001 Lead Auditor | ☁️ Cloud Security & Compliance  
🎓 MEng Cybersecurity, UMD | 🔍 Ex-Cybersecurity Consultant at Vodafone

---

## 🚀 Projects

### 🩺 Secure Cloud Architecture Redesign for Healthcare Infrastructure
Redesigned a healthcare provider’s cloud infrastructure with a focus on security, compliance, and scalability. The project aligned with HIPAA requirements and AWS best practices to ensure the confidentiality, integrity, and availability of Protected Health Information (PHI).

Key Responsibilities & Solutions
1. Network Segmentation:
Architected a segmented Amazon VPC with public/private subnets, NAT gateways, and security groups to isolate workloads and minimize the attack surface.

2. Identity & Access Management:
Implemented IAM role-based access control and enforced Multi-Factor Authentication (MFA) to restrict and monitor privileged access.

3. Data Protection:
Enabled TLS encryption for data-in-transit and deployed secure API gateways to safeguard sensitive healthcare data, meeting HIPAA technical safeguard requirements.

4. Compliance Alignment:
Delivered detailed dataflow diagrams for patient, provider, and IT admin use cases, ensuring infrastructure and processes aligned with HIPAA and NIST frameworks.
🔗 [GitHub Repo]((https://github.com/28sunanda/Securing-a-Cloud-based-Healthcare-Application))

### 🛒 Scalable & Secure E-commerce Platform on AWS
Designed and deployed a secure, scalable e-commerce platform leveraging core AWS services to ensure high availability, robust security, and strong performance.

Key Responsibilities & Solutions
1. Cloud Infrastructure Design:
Architected the solution using AWS EC2 for compute, RDS for managed relational databases, CloudFront as a CDN, and Auto Scaling to handle variable traffic demands.

2. High Availability & Data Security:
Configured Amazon RDS with Multi-AZ deployment for redundancy and disaster recovery. Secured all sensitive data at rest using Amazon KMS encryption.

3. Web Application Security:
Implemented AWS WAF to protect against common web exploits such as SQL injection and cross-site scripting (XSS). Enforced SSL/TLS for all communications to ensure data-in-transit security.

4. Performance Optimization:
Conducted rigorous stress testing using Apache JMeter, identifying and resolving bottlenecks to optimize system performance during periods of high traffic.

### 🔒 Security Assessment for AWS-based Microservices Architecture
Conducted a comprehensive security review of an AWS EKS-based microservices deployment, ensuring alignment with industry security best practices and AWS Well-Architected Framework.

Key Responsibilities & Solutions
1. Security Review:
Assessed the AWS EKS microservices architecture for vulnerabilities, configuration issues, and compliance gaps, focusing on secure deployment and operations.

2. Web Application Protection:
Implemented AWS WAF to defend against common web exploits such as SQL injection and cross-site scripting (XSS).

3. Data-in-Transit Security:
Enabled SSL/TLS encryption across all services to ensure secure data transmission between microservices and external clients.

4. Automated CI/CD Pipeline:
Developed and integrated a CI/CD pipeline using GitHub Actions, incorporating automated security scanning and vulnerability assessments to detect and remediate risks early in the development lifecycle.

### 🛡️ Security Assessment & Incident Response Analysis for a Fictional Company
Executed a comprehensive security assessment and incident response analysis for a simulated enterprise environment, integrating both offensive and defensive security methodologies.

Key Responsibilities & Solutions
1. Offensive Security (Penetration Testing):
Conducted a Capture The Flag-style assessment simulating a real-world penetration test against a vulnerable company environment with multiple exploitable services.

Utilized Nmap, Metasploit, and Burp Suite to identify and exploit vulnerabilities, achieving unauthorized access across systems.

2. Defensive Security (Incident Response):
Performed incident response analysis to reconstruct the attacker’s timeline, tracing the path from initial access and privilege escalation to lateral movement, actions on objectives, and persistence mechanisms.

Leveraged Wireshark and Splunk to analyze logs and network traffic, effectively tracing and documenting attacker activity.

### 🧪 Forensic Analysis of a Suspected Malware Disk Image
Performed a forensic investigation on a malware-infected disk image, utilizing the Autopsy Forensics Suite to extract critical artifacts and uncover the presence and behavior of a malicious executable.

Key Responsibilities & Solutions
1. Disk Image Processing:
Loaded and processed the disk image in Autopsy, leveraging its GUI to browse the file system, recover deleted files, and analyze metadata such as access, modification, and creation dates.

2. Artifact Extraction:
Used Autopsy’s File Analysis and Keyword Search features to systematically identify suspicious files, registry changes, and potential indicators of compromise, focusing on common malware locations and user activity traces.

3. Malware Identification:
Traced the infection chain by correlating file artifacts, log entries, and system changes, ultimately pinpointing the malicious executable responsible for the compromise.

4. Behavioral Analysis:
Once the malware was isolated, conducted a detailed review of its characteristics and behavior, including persistence mechanisms and network activity.

5. Supporting Tools:
Supplemented the analysis with VeraCrypt for encrypted volume examination, Wireshark for network traffic analysis, and CyberChef for artifact decoding and data transformation.

### ⚡ Enhancing the Security Posture of a Fictitious Power Plant Company – Information Assurance
Led a cybersecurity enhancement initiative for a simulated power plant company, focusing on protecting critical industrial systems-Distributed Control Systems (DCS), SCADA, and ERP/MES-from ransomware and advanced cyber threats.

Key Responsibilities & Solutions
1. Infrastructure Assessment & Threat Modeling:
Conducted a detailed assessment of the power plant’s OT and IT infrastructure. Utilized STRIDE and DREAD frameworks to systematically identify vulnerabilities, including risks such as Denial of Service (DoS), privilege escalation, and data tampering.

2. Risk Prioritization:
Mapped threat scenarios to critical assets and prioritized risks based on potential operational, safety, and business impacts.

3. Three-Phase Mitigation Plan:
Developed a phased security improvement roadmap:

Phase 1:
(i) Implemented WAN redundancy and network segmentation to limit lateral movement and enhance system resilience.
(ii) Enforced multi-factor authentication (MFA) across all critical systems to reduce the risk of unauthorized access and privilege escalation.

Phase 2:
(i) Deployed intrusion detection systems (IDS) for real-time monitoring and rapid threat detection.
(ii) Applied strong encryption to secure sensitive data in transit and at rest.

Phase 3:
(i) Established disaster recovery protocols and regular patch management for ICS/OT environments.
(ii) Conducted ongoing security awareness training for staff to mitigate social engineering and insider threats.

### CMMC 2.0 Level 1 Self-Assessment for Michael Scott Paper Company
A CMMC 2.0 Level 1 self-assessment was conducted for the Michael Scott Paper Company-a small business providing paper products and on-demand printing via a custom web application. The assessment was requested by a US Federal agency as a prerequisite for a major contract, requiring a thorough review of the company’s web application and supporting system to identify compliance gaps and recommend improvements.

Key Responsibilities & Solutions
1. System & Application Review:
Conducted a comprehensive technical assessment of the Michael Scott Paper Company’s web application and supporting Linux-based system using a cloned production VM, reviewing system configurations, logs, and application features for compliance with CMMC 2.0 Level 1 requirements.

2. Policy & Documentation Analysis:
Evaluated company policies on media destruction, physical access, and data center management to ensure alignment with federal standards and best practices.

3. Evidence Collection:
Gathered evidence through command-line log analysis, system file inspection, and direct testing of web application functionality (e.g., file upload and user management).

4. Gap Identification:
Mapped existing technical and procedural controls against each CMMC 2.0 Level 1 requirement, identifying compliance gaps and vulnerabilities in areas such as access control, authentication, network segmentation, and system integrity.

5. Recommendations:
Provided actionable, requirement-specific recommendations for technical and policy improvements, including:
(i) Implementing robust input validation, authentication, and authorization for all web application interactions.

(ii) Restricting file upload types, enforcing server-side validation, and integrating malware scanning for uploaded files.

(iii) Adding user registration, secure login, strong password policies, and multi-factor authentication.

(iv) Deploying firewalls, IDS/IPS, network segmentation (e.g., DMZs), and encrypted tunnels.

(v) Establishing a vulnerability management program with regular scanning and patching.

(vi) Enabling scheduled and real-time malware scanning using ClamAV.

(vii) Enhancing logging and monitoring for both system and web application activities.

(viii) Improving asset management and employee access logging.

---

## 🛠️ Skills & Tools

- Cloud Platforms & Security: Amazon Web Services (AWS): EC2, RDS, EKS, VPC, IAM, CloudFront, WAF, KMS, NAT Gateway, API Gateway, CloudWatch, Auto Scaling, Cloud Security Architecture & Assessment, Cloud Risk Management

- Security & Compliance Frameworks: ISO 27001, NIST CSF, NIST SP 800-53, HIPAA, GDPR, CMMC 2.0 Level 1, Risk Management & Threat Modeling (STRIDE, DREAD), GRC (Governance, Risk, and Compliance), TPRM (Third-Party Risk Management)

- Penetration Testing & Vulnerability Assessment: Nmap, Metasploit, Burp Suite, Network Segmentation & Firewalls (IDS/IPS, DMZ, VLANs, WAF)

- Digital Forensics & Incident Response: Autopsy Forensic Suite, Wireshark, Splunk (SIEM), VeraCrypt, CyberChef, Malware Analysis, Incident Response

- Identity & Access Management: Role-Based Access Control (RBAC), Multi-Factor Authentication (MFA), Secure Authentication & Authorization, User Account Management

- Programming & Scripting: Python, Bash, PowerShell

- DevOps & Automation: GitHub Actions, Jenkins, Docker, Kubernetes (EKS), CI/CD Pipeline Development

- Data & Reporting: Power BI

- Operating Systems & Platforms: Linux (Ubuntu, Kali), Windows Server

---

## 📜 Certifications

- ✅ ISO 27001 Lead Auditor  
- 🎯 AWS Solutions Architect (in progress)  
- 🎯 CRISC (in progress)

---

## 📫 Let’s Connect

- 💼 [LinkedIn](https://linkedin.com/in/sunanda-mandal)
- 📧 Email: sunandamandal28@gmail,com
