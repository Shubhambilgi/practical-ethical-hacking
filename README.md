
# Practical Ethical Hacking 🛡️

A structured, hands-on journey from cybersecurity fundamentals to ethical hacking and penetration testing.

This repository contains my daily notes, practical exercises, lab evidence, scripts, and security reports.

## Learning Approach

Every day includes:

1. One main topic to study.
2. Concepts to understand and explain in my own words.
3. Practical exercises in an authorised lab.
4. Notes, commands, observations, and screenshots.
5. A Git commit documenting my progress.

## Phase 1: Computer, Networking and Security Fundamentals

| Day | Topic | What to Learn and Practise |
|---|---|---|
| 01 | Ethical Hacking Fundamentals | Ethical hacking, penetration testing, authorisation, scope, rules of engagement, and responsible disclosure. |
| 02 | Computer Architecture | CPU, RAM, storage, processes, applications, and how an operating system runs programs. |
| 03 | Operating System Fundamentals | Kernel, user space, filesystems, processes, memory, and system calls. |
| 04 | Networking Fundamentals | Networks, hosts, clients, servers, LAN, WAN, and internet communication. |
| 05 | IP Addressing | IPv4, IPv6, public and private addresses, loopback, and subnet masks. |
| 06 | Subnetting | CIDR, network addresses, broadcast addresses, host ranges, and subnet calculations. |
| 07 | MAC and ARP | MAC addresses, ARP requests, ARP tables, and local network communication. |
| 08 | TCP and UDP | Connections, handshakes, ports, reliability, and datagrams. |
| 09 | Ports and Protocols | Common ports and the purpose of HTTP, HTTPS, SSH, DNS, SMTP, FTP, and SMB. |
| 10 | OSI and TCP/IP Models | Network layers, encapsulation, packet flow, and troubleshooting. |
| 11 | DNS | Domain resolution, records, recursive resolvers, authoritative servers, and caching. |
| 12 | DHCP and NAT | Address assignment, leases, gateways, and network address translation. |
| 13 | Routing and Switching | Switches, routers, gateways, routing tables, and packet forwarding. |
| 14 | Firewalls and Network Segmentation | Rules, allowlists, denylists, inbound/outbound traffic, and segmentation. |
| 15 | Wireshark Fundamentals | Capture traffic in your lab, apply filters, and identify basic protocols. |
| 16 | Linux Fundamentals | Filesystem navigation, files, directories, users, and permissions. |
| 17 | Linux Administration | Processes, services, package management, logs, and system information. |
| 18 | Linux Networking | Interfaces, routes, DNS configuration, sockets, and network troubleshooting. |
| 19 | Bash Fundamentals | Variables, conditions, loops, functions, and shell scripts. |
| 20 | Windows Fundamentals | Windows architecture, filesystems, users, groups, and system tools. |
| 21 | Windows Administration | Services, processes, permissions, Event Viewer, and PowerShell basics. |
| 22 | Virtualisation and Lab Setup | Virtual machines, snapshots, isolated networks, and safe lab configuration. |
| 23 | Git and GitHub | Repositories, commits, branches, Markdown, and documenting technical work. |
| 24 | Python Fundamentals | Variables, data types, conditions, loops, functions, and modules. |
| 25 | Python for Security | File handling, parsing logs, validating input, sockets, and exception handling. |
| 26 | Regular Expressions and Text Processing | Patterns, extraction, filtering, and processing security logs. |
| 27 | Cryptography Fundamentals | Encryption, hashing, encoding, digital signatures, and key management. |
| 28 | Authentication and Authorisation | Identity, permissions, MFA, least privilege, and access control. |
| 29 | Security Principles | Confidentiality, integrity, availability, threat, vulnerability, risk, and impact. |
| 30 | Fundamentals Assessment | Explain network traffic, inspect a lab capture, use Linux and Windows tools, and document findings. |

## Phase 2: Reconnaissance and Network Penetration Testing

| Day | Topic | What to Learn and Practise |
|---|---|---|
| 31 | Penetration Testing Methodology | Planning, scoping, discovery, enumeration, validation, reporting, and retesting. |
| 32 | Rules of Engagement | Written permission, target scope, exclusions, testing windows, and stop conditions. |
| 33 | Passive Reconnaissance | Publicly available domain, DNS, certificate, and organisation information. |
| 34 | Active Reconnaissance | Controlled discovery against explicitly authorised lab targets. |
| 35 | DNS Enumeration | Understand DNS records and inspect a lab domain or permitted test domain. |
| 36 | Service Discovery | Discover hosts and services inside an isolated lab. |
| 37 | Nmap Fundamentals | Target selection, basic scan types, output formats, and safe scan scope. |
| 38 | Nmap Service Detection | Identify services and versions on lab machines and validate results. |
| 39 | Nmap Output Analysis | Read scan results, save evidence, and explain limitations. |
| 40 | Network Service Enumeration | Understand what exposed services reveal and which defensive controls apply. |
| 41 | SMB Fundamentals | Shares, permissions, authentication, and safe enumeration in a lab. |
| 42 | SSH and Remote Administration | Keys, authentication, secure configuration, and access logs. |
| 43 | FTP and File Transfer Security | Plaintext risks, secure alternatives, permissions, and configuration review. |
| 44 | HTTP Service Discovery | Identify web services, virtual hosts, headers, and application entry points. |
| 45 | Vulnerability Assessment | Match evidence to potential weaknesses without assuming every finding is exploitable. |
| 46 | CVEs and CVSS | Vulnerability identifiers, severity scoring, exploitability, and environmental context. |
| 47 | False Positives and Validation | Confirm findings safely and document uncertainty. |
| 48 | Network Defence | Firewall rules, patching, segmentation, secure configurations, and monitoring. |
| 49 | Network Pentest Lab | Assess a deliberately vulnerable lab network within its defined scope. |
| 50 | Network Assessment Report | Write findings, evidence, severity, impact, and remediation recommendations. |

## Phase 3: Web Application Security

| Day | Topic | What to Learn and Practise |
|---|---|---|
| 51 | How the Web Works | Browsers, servers, requests, responses, and application architecture. |
| 52 | HTTP Methods and Status Codes | GET, POST, PUT, DELETE, common response codes, and method handling. |
| 53 | HTTP Headers | Host, Origin, Referer, content types, caching, and security headers. |
| 54 | Cookies and Sessions | Session identifiers, cookie attributes, expiration, and session security. |
| 55 | HTML Fundamentals | Forms, inputs, DOM structure, and user-controlled data. |
| 56 | JavaScript Fundamentals | Variables, functions, events, browser execution, and DOM manipulation. |
| 57 | Web Architecture | Frontend, backend, APIs, databases, authentication, and trust boundaries. |
| 58 | Burp Suite Fundamentals | Proxy setup, HTTP history, Repeater, and lab traffic inspection. |
| 59 | Web Reconnaissance | Identify application routes, technologies, entry points, and exposed information. |
| 60 | Content and Directory Discovery | Understand route discovery and practise only against designated lab applications. |
| 61 | Authentication Testing | Login logic, password policy, MFA, and account recovery weaknesses. |
| 62 | Session Management | Session fixation, invalidation, expiration, and cookie protection. |
| 63 | Access Control | Horizontal and vertical privilege boundaries and server-side authorisation. |
| 64 | IDOR and Broken Object-Level Authorisation | Test access to lab-owned objects using separate authorised test accounts. |
| 65 | SQL Fundamentals for Security | Queries, tables, conditions, joins, and database permissions. |
| 66 | SQL Injection | Understand root causes, controlled lab validation, parameterised queries, and remediation. |
| 67 | Cross-Site Scripting | Reflected, stored, and DOM-based XSS in training applications. |
| 68 | Cross-Site Request Forgery | Request forgery, CSRF tokens, SameSite cookies, and origin checks. |
| 69 | File Upload Vulnerabilities | File validation, storage controls, content handling, and safe lab testing. |
| 70 | Path Traversal | File path handling, normalisation, access boundaries, and remediation. |
| 71 | Command Injection | Unsafe operating-system command construction and safer APIs. |
| 72 | Server-Side Request Forgery | Server-side URL fetching, trust boundaries, and egress restrictions. |
| 73 | XML External Entity Vulnerabilities | XML parser risks, external entities, and secure parser settings. |
| 74 | Server-Side Template Injection | Template evaluation risks and safe lab demonstrations. |
| 75 | Business Logic Vulnerabilities | Abuse of application workflows, limits, and assumptions. |
| 76 | API Security Fundamentals | REST, JSON, endpoints, methods, status codes, and API authentication. |
| 77 | API Authorisation Testing | Object-level and function-level access controls in test APIs. |
| 78 | JWT Security | Token structure, signature validation, expiry, and claim verification. |
| 79 | CORS and Browser Security | Origins, credentialed requests, CORS configuration, and browser trust boundaries. |
| 80 | Security Headers and TLS | HTTPS, certificates, HSTS, CSP, and secure transport configuration. |
| 81 | Password Reset and Account Recovery | Token strength, expiry, reuse, and recovery workflow security. |
| 82 | File Inclusion and Resource Handling | Understand inclusion risks, safe file access, and secure design. |
| 83 | Web Vulnerability Chaining | Understand how individually small weaknesses can combine into greater impact in a lab. |
| 84 | OWASP Top 10 Review | Map findings to common web application risk categories and mitigations. |
| 85 | Web Security Assessment | Assess a training application and prepare reproducible evidence and remediation advice. |

## Phase 4: Exploitation Fundamentals and System Security

| Day | Topic | What to Learn and Practise |
|---|---|---|
| 86 | Exploitation Fundamentals | Vulnerability conditions, proof of concept, impact, and safe validation. |
| 87 | Public Exploit Research | Read advisories, affected versions, prerequisites, and exploit limitations. |
| 88 | Metasploit Fundamentals | Understand modules, payload concepts, sessions, and isolated lab use. |
| 89 | Shell and Process Concepts | Understand shells, processes, permissions, and how applications execute commands. |
| 90 | Linux Privilege and Permissions | Users, groups, sudo rules, SUID, capabilities, and secure configuration. |
| 91 | Linux Privilege Escalation Assessment | Review a deliberately vulnerable VM for unsafe permissions and misconfigurations. |
| 92 | Linux Persistence Risks and Defence | Understand persistence mechanisms, audit trails, and defensive detection. |
| 93 | Linux Logs and Monitoring | Authentication logs, system logs, audit evidence, and incident investigation. |
| 94 | Windows Security Architecture | Security principals, access tokens, UAC, and Windows permissions. |
| 95 | Windows Command Line and PowerShell | Inspect processes, services, users, and event logs. |
| 96 | Windows Privilege Boundaries | Service permissions, privileged groups, and secure configuration review. |
| 97 | Windows Privilege Escalation Assessment | Identify misconfigurations in a dedicated lab and recommend fixes. |
| 98 | Credential Security | Password storage, hashes, salts, secrets management, and defensive controls. |
| 99 | Password Auditing | Understand password policy and authorised offline auditing with test data. |
| 100 | Security Assessment Project | Assess a lab host, validate findings, and write a concise report. |

## Phase 5: Active Directory Security

| Day | Topic | What to Learn and Practise |
|---|---|---|
| 101 | Active Directory Fundamentals | Domains, forests, domain controllers, and directory services. |
| 102 | Active Directory Objects | Users, groups, computers, organisational units, and group policy. |
| 103 | LDAP Fundamentals | Directory queries, attributes, authentication, and secure configuration. |
| 104 | Kerberos Fundamentals | Tickets, principals, authentication flow, and common security considerations. |
| 105 | NTLM Fundamentals | Challenge-response authentication, legacy risks, and hardening. |
| 106 | Group Policy | Policy application, security baselines, and configuration management. |
| 107 | Domain Trusts | Trust relationships, authentication boundaries, and defensive review. |
| 108 | Active Directory Enumeration | Collect permitted lab information and understand directory relationships. |
| 109 | Active Directory Permissions | Delegation, group memberships, ACLs, and excessive privileges. |
| 110 | Service Accounts | Managed service accounts, SPNs, and least-privilege configuration. |
| 111 | Credential Exposure Risks | Understand exposed secrets, credential protection, and safe evidence handling. |
| 112 | Kerberos Attack Concepts | Study common attack prerequisites, lab-only demonstrations, and mitigations. |
| 113 | NTLM Security Risks | Understand relay conditions and protections such as signing and channel binding. |
| 114 | Lateral Movement Risks | Understand trust boundaries and defensive detection without accessing unauthorised systems. |
| 115 | Active Directory Hardening | Review privileged groups, delegation, authentication settings, and audit policy. |
| 116 | Active Directory Monitoring | Review authentication events and suspicious behaviour indicators. |
| 117 | Active Directory Lab Assessment | Evaluate a purpose-built training domain within its scope. |
| 118 | Active Directory Remediation | Prioritise and explain fixes for discovered weaknesses. |
| 119 | Active Directory Reporting | Document evidence, attack paths, business impact, and recommendations. |
| 120 | Active Directory Assessment Review | Recheck findings and present a clear technical summary. |

## Phase 6: Defensive Security, Detection and Incident Response

| Day | Topic | What to Learn and Practise |
|---|---|---|
| 121 | Security Operations Fundamentals | SOC workflows, alerts, triage, escalation, and incident lifecycle. |
| 122 | Log Analysis | Read system, authentication, web server, and application logs. |
| 123 | Windows Event Logs | Understand key security events and investigation context. |
| 124 | Linux Log Analysis | Review authentication, service, and system activity. |
| 125 | SIEM Fundamentals | Understand log ingestion, parsing, correlation, dashboards, and alerts. |
| 126 | Detection Engineering Basics | Turn observable suspicious behaviour into testable detection rules. |
| 127 | Network Detection | Recognise scanning, unusual connections, and suspicious traffic patterns. |
| 128 | Endpoint Detection | Understand process activity, file changes, and endpoint telemetry. |
| 129 | Incident Response | Preparation, identification, containment, eradication, recovery, and lessons learned. |
| 130 | Malware Fundamentals | Static versus dynamic analysis, safe handling, and isolated analysis environments. |
| 131 | Indicators of Compromise | Understand hashes, domains, IPs, filenames, and indicator limitations. |
| 132 | Threat Intelligence | Research threat reports, assess reliability, and map relevant indicators. |
| 133 | Phishing Analysis | Inspect suspicious messages, URLs, headers, and attachments safely. |
| 134 | Email Security | SPF, DKIM, DMARC, spoofing risks, and email authentication. |
| 135 | Vulnerability Management | Asset inventory, prioritisation, remediation deadlines, and retesting. |
| 136 | Patch Management | Evaluate patch risk, deployment, validation, and rollback planning. |
| 137 | Security Baselines | Apply least privilege, disable unnecessary services, and harden configurations. |
| 138 | Backup and Recovery Security | Backup isolation, restoration tests, and ransomware resilience. |
| 139 | Incident Investigation Exercise | Investigate a provided or lab-generated set of security logs. |
| 140 | Defensive Assessment Report | Document timeline, evidence, root cause, and prevention measures. |

## Phase 7: Cloud, Containers and Modern Infrastructure

| Day | Topic | What to Learn and Practise |
|---|---|---|
| 141 | Cloud Computing Fundamentals | IaaS, PaaS, SaaS, shared responsibility, and cloud identity. |
| 142 | Cloud Identity and Access | IAM users, roles, policies, least privilege, and MFA. |
| 143 | Cloud Storage Security | Public exposure, access policies, encryption, and logging. |
| 144 | Cloud Networking | Virtual networks, subnets, routes, security groups, and network ACLs. |
| 145 | Cloud Logging and Monitoring | Audit logs, access events, alerting, and retention. |
| 146 | Cloud Security Misconfigurations | Identify common configuration risks in a sandbox or sample configuration. |
| 147 | Cloud Secrets Management | Secure storage, rotation, access control, and secret scanning. |
| 148 | Docker Fundamentals | Images, containers, registries, networks, and volumes. |
| 149 | Container Security | Image vulnerabilities, root execution, capabilities, and isolation. |
| 150 | Container Networking | Ports, network boundaries, exposed services, and secure defaults. |
| 151 | Kubernetes Fundamentals | Clusters, nodes, pods, deployments, and services. |
| 152 | Kubernetes Security | RBAC, secrets, pod security, network policies, and workload identity. |
| 153 | Infrastructure as Code Security | Review configuration for excessive permissions and exposed secrets. |
| 154 | CI/CD Security | Pipeline permissions, dependency risks, protected secrets, and artifact integrity. |
| 155 | Dependency Security | Software composition analysis, known vulnerabilities, and remediation. |
| 156 | Software Supply Chain | Package provenance, trusted sources, signing, and build integrity. |
| 157 | Web Application Deployment Security | Secure environment variables, reverse proxies, TLS, and production configuration. |
| 158 | Cloud Threat Modelling | Identify assets, trust boundaries, threats, and mitigations. |
| 159 | Cloud and Container Lab | Review a controlled environment and document configuration findings. |
| 160 | Cloud Security Report | Prioritise findings and provide clear remediation steps. |

## Phase 8: Advanced Assessment Skills and Specialisations

| Day | Topic | What to Learn and Practise |
|---|---|---|
| 161 | Threat Modelling | Identify assets, entry points, trust boundaries, threats, and mitigations. |
| 162 | Secure Code Review | Review authentication, authorisation, input validation, and secrets handling. |
| 163 | Static Application Security Testing | Understand source-code scanning, findings, and false positives. |
| 164 | Dynamic Application Security Testing | Understand runtime testing and validation of application behaviour. |
| 165 | Software Fuzzing Fundamentals | Learn input mutation, crash detection, and safe local testing. |
| 166 | Race Conditions | Understand concurrent requests, state changes, and safe remediation. |
| 167 | Advanced API Assessment | Review authorisation, rate limiting, schema validation, and sensitive data exposure. |
| 168 | Web Cache Security | Understand caching behaviour, cache keys, and potential information leaks. |
| 169 | Request Smuggling Concepts | Study HTTP parsing differences and safe training-lab demonstrations. |
| 170 | Secure Authentication Design | Review MFA, session lifecycle, recovery, and account protection. |
| 171 | Mobile Application Security | Understand app components, permissions, storage, and network traffic. |
| 172 | Android Security Fundamentals | Learn APK structure, app sandboxing, permissions, and secure storage. |
| 173 | Wireless Security Fundamentals | Understand Wi-Fi encryption, authentication, and authorised lab configuration reviews. |
| 174 | Network Device Security | Review management access, firmware, configuration backups, and segmentation. |
| 175 | IoT Security Fundamentals | Understand device interfaces, firmware risks, default credentials, and updates. |
| 176 | Secure Development Practices | Apply validation, parameterisation, dependency updates, and secrets management. |
| 177 | Risk and Severity Assessment | Evaluate likelihood, impact, exploit prerequisites, and business context. |
| 178 | Professional Report Writing | Produce an executive summary, reproducible findings, and prioritised remediation. |
| 179 | Retesting and Verification | Confirm fixes, document residual risk, and close findings accurately. |
| 180 | Final Capstone Assessment | Complete a scoped assessment of a training environment and publish a professional report. |

## Daily Folder Structure

```text
practical-ethical-hacking/
├── README.md
├── Day-001-Ethical-Hacking-Fundamentals/
│   ├── notes.md
│   ├── practical.md
│   ├── video-notes.md
│   └── screenshots/
├── Day-002-Computer-Architecture/
│   ├── notes.md
│   ├── practical.md
│   ├── video-notes.md
│   └── screenshots/
└── ...
```

## Daily Documentation

### notes.md
- Topic explanation in my own words
- Important concepts and terminology
- Commands or technical examples
- Common mistakes and lessons learned
- Short revision summary

### practical.md
- Objective
- Lab environment and authorised scope
- Prerequisites
- Steps performed and command explanations
- Results and observations
- Security impact and remediation
- Conclusion

### video-notes.md
- Resource title and source
- Concepts covered
- Important timestamps, if applicable
- Questions to investigate
- Key takeaways

### screenshots/
- Lab setup and relevant results
- Command output and evidence
- Redact credentials, tokens, personal data, and sensitive information

## Git Workflow

```bash
git add .
git commit -m "Complete Day 001 ethical hacking fundamentals"
git push
```

## Safety Rules

- Test only systems I own or have explicit permission to assess.
- Follow the defined scope and rules of engagement.
- Use isolated labs and deliberately vulnerable applications.
- Never expose secrets or sensitive data in this repository.
- Do not treat an unverified scanner result as a confirmed vulnerability.
- Include remediation guidance and retest after fixes.

## Learning Principle

Understanding matters more than completing days quickly. Spend additional time on difficult topics, repeat practical exercises, and demonstrate each skill before moving forward.
