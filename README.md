Below is an enriched version of the Awesome ASPM document that not only covers the core application security and ASPM tools, techniques, and providers but also integrates a comprehensive Software Supply Chain Security section. This combined resource brings together best practices from both worlds to help you secure your applications and their entire supply chain.

---

# Awesome ASPM

This document is a curated, community‐driven list of resources from my ASPM universe—a comprehensive collection covering application security (AppSec), Application Security Posture Management (ASPM), and Software Supply Chain Security. Whether you're a developer, security engineer, or decision‐maker, use this list to navigate essential tools, techniques, URLs, and leading providers in the appsec space, while also gaining insight into supply chain risk management and transparency.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Tools](#tools)
   - [SAST Tools](#sast-tools)
   - [DAST Tools](#dast-tools)
   - [IAST & RASP Tools](#iast--rasp-tools)
   - [ASPM Platforms](#aspm-platforms)
   - [SCM Tools & Git Repositories](#scm-tools--git-repositories)
   - [CNAPP Tools](#cnapp-tools)
   - [IaC & Container Security Tools](#iac--container-security-tools)
   - [SCM Security & Software Supply Chain Tools](#scm-security--software-supply-chain-tools)
   - [Secrets Management Tools](#secrets-management-tools)
   - [Other Useful Tools](#other-useful-tools)
3. [Techniques](#techniques)
4. [URLs & Resources](#urls--resources)
5. [Providers & Services](#providers--services)
6. [Software Supply Chain Security](#software-supply-chain-security)
   - [Organizations & Foundations](#organizations--foundations)
   - [Regulations](#regulations)
   - [Standards, Frameworks, & Best Practices](#standards-frameworks--best-practices)
   - [Threats, Attacks & Vulnerability Management](#threats-attacks--vulnerability-management)
   - [Software Identification & Bill of Materials](#software-identification--bill-of-materials)
   - [Tooling & Cloud Supply Chain Security](#tooling--cloud-supply-chain-security)
   - [Further Reading & Resources](#further-reading--resources)
7. [Additional Resources](#additional-resources)

---

## Introduction

In today's evolving cybersecurity landscape, effective Application Security Posture Management (ASPM) is critical to ensure that your applications remain secure throughout their lifecycle. This document not only highlights the best tools, techniques, and providers for ASPM but also dives into the vital realm of Software Supply Chain Security—covering initiatives, standards, regulations, and research that help manage risk from code to dependencies. Explore the sections below to discover how you can secure your applications and the software components that make them up.

---

## Tools

### SAST Tools
Static Application Security Testing (SAST) tools analyze source code to detect vulnerabilities early in the development process.

- **Checkmarx SAST**  
  *Comprehensive scanning with support for 35+ languages and robust AI‐assisted remediation.*

- **SonarQube**  
  *An open-source solution focused on code quality and vulnerability detection.*  
  [Learn More](https://www.sonarqube.org)

- **Veracode**  
  *A cloud-based platform offering low false positives and detailed remediation guidance.*  
  [Learn More](https://www.veracode.com)

- **Semgrep**  
  *Highly configurable SAST that integrates into CI/CD pipelines for multiple languages.*  
  [Learn More](https://semgrep.dev)

- **Opengrep**  
  *A Semgrep fork for additional customization.*  
  [Learn More](https://opengrep.dev)

- **Synopsys Coverity**  
  *Enterprise-grade analysis for large codebases with extensive language support.*  
  [Learn More](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html)

### DAST Tools
Dynamic Application Security Testing (DAST) tools assess running applications by simulating real-world attacks.

- **Burp Suite**  
  *Industry-standard web security testing tool available in Community and Professional editions.*  
  [Learn More](https://portswigger.net/burp)

- **OWASP ZAP**  
  *Open-source DAST tool for automated vulnerability scanning and manual testing.*  
  [Learn More](https://www.zaproxy.org)

- **Nuclei**  
  *A fast and flexible vulnerability scanner based on templates for automated scanning across web services and networks.*  
  [Learn More](https://nuclei.projectdiscovery.io)

### IAST & RASP Tools
Interactive Application Security Testing (IAST) combines the strengths of SAST and DAST, while Runtime Application Self-Protection (RASP) provides in-process defense.

- **Contrast Security**  
  *Offers both IAST and RASP capabilities for continuous in-context vulnerability detection.*  
  [Learn More](https://www.contrastsecurity.com)

- **HCL AppScan CodeSweep**  
  *Delivers on-the-fly static and dynamic analysis integrated into your development workflow.*  
  [Learn More](https://www.hcltech.com/software/appscan)

### ASPM Platforms
ASPM platforms consolidate multiple testing and monitoring tools to provide a unified view of your application security posture.

- **Plexicus**  
  *Offers a limited but free ASPM for small projects.*  
  [Learn More](https://www.plexicus.com)

- **Cycode ASPM**  
  *Secures the entire software supply chain with continuous scanning and secrets management.*  
  [Learn More](https://www.cycode.com)

- **GitLab**  
  *A DevSecOps platform that integrates SAST, DAST, container scanning, and more into one unified workflow.*  
  [Learn More](https://about.gitlab.com)

- **Snyk**  
  *Developer-centric platform focusing on vulnerability detection and remediation in open-source dependencies.*  
  [Learn More](https://snyk.io)

### SCM Tools & Git Repositories
Source Code Management (SCM) tools host and manage your code repositories—essential for secure development workflows.

- **GitHub**  
  *The largest code hosting platform with robust collaboration and security features.*  
  [Learn More](https://github.com)

- **GitLab**  
  *Offers integrated CI/CD, SAST, and container scanning alongside repository hosting.*  
  [Learn More](https://gitlab.com)

- **Bitbucket**  
  *Atlassian’s code hosting service that integrates seamlessly with other Atlassian tools like Jira.*  
  [Learn More](https://bitbucket.org)

- **Gitea**  
  *A lightweight, self-hosted Git service designed for simplicity and speed.*  
  [Learn More](https://gitea.io)

### CNAPP Tools
Cloud-Native Application Protection Platforms (CNAPP) provide comprehensive security across cloud environments.

- **Prowler**  
  *An open-source AWS security tool that performs extensive checks for cloud configuration best practices.*  
  [Learn More](https://github.com/prowler-cloud/prowler)

- **CloudSploit**  
  *Scans cloud environments for misconfigurations and vulnerabilities to secure cloud resources.*  
  [Learn More](https://github.com/cloudsploit/CloudSploit)

### IaC & Container Security Tools
Tools in this category secure Infrastructure as Code (IaC) and container environments. Many offer multi-feature scanning such as vulnerability assessment, SCA, SBOM generation, and license checks.

- **Trivy**  
  *A versatile scanner covering container images and IaC, including vulnerability scanning, SCA, license compliance, SBOM generation, and container security.*  
  [Learn More](https://github.com/aquasecurity/trivy)

- **Kics**  
  *Developed by Checkmarx, Kics scans IaC for misconfigurations and vulnerabilities across multiple formats.*  
  [Learn More](https://kics.io)

- **Hadolint**  
  *A Dockerfile linter that enforces best practices and security standards in container builds.*  
  [Learn More](https://github.com/hadolint/hadolint)

- **Checkov**  
  *Performs comprehensive security and compliance scans on IaC templates across cloud infrastructures and containers.*  
  [Learn More](https://www.checkov.io)

### SCM Security & Software Supply Chain Tools
These tools secure your development pipeline and software supply chain by ensuring SCM integrity, dependency analysis, and SBOM management.

- **Chainbench**  
  *Evaluates and secures SCM environments to ensure software supply chain integrity.*  
  [Learn More](https://chainbench.io)

- **Syft**  
  *Generates a Software Bill of Materials (SBOM) from container images and filesystems for effective vulnerability management.*  
  [Learn More](https://github.com/anchore/syft)

- **FOSSA**  
  *Provides robust Software Composition Analysis (SCA) to manage open-source dependencies and license compliance.*  
  [Learn More](https://fossa.com)

- **SLSA Resources**  
  *Offers frameworks and guidelines for Supply-chain Levels for Software Artifacts (SLSA) to ensure secure build integrity.*  
  [Learn More](https://slsa.dev)

### Secrets Management Tools
These tools detect, manage, and prevent the leakage of sensitive information from your code and repositories.

- **TruffleHog**  
  *Searches git repositories for high-entropy strings and potential secrets leaks.*  
  [Learn More](https://github.com/trufflesecurity/trufflehog)

- **GitGuardian**  
  *Monitors repositories for exposed secrets and credentials in real time.*  
  [Learn More](https://www.gitguardian.com)

- **Detect Secrets**  
  *An open-source tool by Yelp that identifies potential secrets before code commits.*  
  [Learn More](https://github.com/Yelp/detect-secrets)

- **CredScan**  
  *Microsoft’s tool for scanning codebases for credentials and secrets to ensure secure deployments.*  
  [Learn More](https://github.com/microsoft/CredScan)

### Other Useful Tools
- **Wireshark**  
  *A powerful network sniffer for capturing and analyzing network traffic for diagnostic purposes.*  
  [Learn More](https://www.wireshark.org)

- **Burp Suite Extensions (BApps)**  
  *Enhance Burp Suite’s capabilities with community and custom plugins (e.g., Param Miner, HTTP Request Smuggler).*  
  [Explore BApps](https://portswigger.net/bappstore)

---

## Techniques

### Secure Coding & Threat Modeling
- **OWASP Top Ten**  
  *Understand and mitigate common vulnerabilities such as Injection, Broken Access Control, and more.*  
  [Learn More](https://owasp.org/www-project-top-ten/)

- **Threat Modeling**  
  *Incorporate design reviews and risk analysis early in the SDLC to identify potential security issues.*

### Fuzz Testing & Penetration Testing
- **Fuzz Testing**  
  *Use fuzzers to generate random inputs and detect unexpected behavior or security flaws.*

- **Penetration Testing**  
  *Combine automated scans with manual testing (using tools like Metasploit) to comprehensively evaluate security.*  
  [Learn More About Pen Testing](https://www.metasploit.com)

---

## URLs & Resources

- **OWASP Official Website**  
  [https://owasp.org](https://owasp.org)

- **Awesome AppSec (GitHub)**  
  [https://github.com/paragonie/awesome-appsec](https://github.com/paragonie/awesome-appsec)

- **Awesome Security (GitHub)**  
  [https://github.com/sbilly/awesome-security](https://github.com/sbilly/awesome-security)

- **eSecurity Planet**  
  [https://www.esecurityplanet.com](https://www.esecurityplanet.com)

- **Burp Suite Documentation**  
  [https://portswigger.net/burp/documentation](https://portswigger.net/burp/documentation)

---

## Providers & Services

- **Plexicus**  
  *Offers a limited but free ASPM for small projects.*  
  [Learn More](https://www.plexicus.com)

- **Veracode**  
  *Offers comprehensive security testing services tailored for large enterprises.*  
  [Learn More](https://www.veracode.com)

- **Snyk**  
  *Provides developer-friendly vulnerability scanning and remediation with seamless CI/CD integration.*  
  [Learn More](https://snyk.io)

- **Checkmarx**  
  *Enterprise-grade SAST solutions with deep language support and AI-assisted vulnerability prioritization.*  
  [Learn More](https://www.checkmarx.com)

- **Cycode**  
  *Secures the software supply chain with real-time ASPM capabilities.*  
  [Learn More](https://www.cycode.com)

---

## Software Supply Chain Security

Software Supply Chain Security is a critical complement to ASPM. This section gathers initiatives, standards, organizations, and tooling that help ensure the integrity and transparency of every software component—from development to deployment.

### Organizations & Foundations
- **NTIA**  
  *Provides SBOM resources, FAQs, and guides to help organizations generate and manage Software Bills of Materials (SBOMs).*  
  [NTIA SBOM Resources](https://www.ntia.gov/page/software-bill-materials)

- **CISA**  
  *Offers SBOM resources, security guidance, and recommendations on defending against software supply chain attacks.*  
  [CISA SBOM Resources](https://www.cisa.gov/sbom)

- **The White House – ONCD** and **NIST**  
  *Develop national cybersecurity strategies and secure software development frameworks (e.g., NIST SP 800-218, SP 800-161).*

- **OWASP, OpenSSF, and CNCF**  
  *Drive community initiatives such as the OWASP Software Component Verification Standard, OpenSSF Scorecard, and CNCF best practices for supply chain security.*

### Regulations
- **EO-14028**  
  *An executive order on improving the nation’s cybersecurity that emphasizes supply chain risk management.*
  
- **European Cyber Resilience Act (CRA)**  
  *A regulatory framework aimed at enhancing cybersecurity in the software supply chain across Europe.*

### Standards, Frameworks, & Best Practices
- **SLSA (Supply-chain Levels for Software Artifacts)**  
  *A framework to ensure that software builds are secure and verifiable.*  
  [Learn More](https://slsa.dev)

- **OWASP SCVS and CSAF**  
  *Standards for verifying third-party components and exchanging security advisory information.*

- **NIST SP 800-218 & SP 800-204D**  
  *Guidelines and drafts for secure software development and integrating supply chain security into CI/CD pipelines.*

### Threats, Attacks & Vulnerability Management
- **Threat Catalogs and Attack Vectors**  
  *Resources like MITRE ATT&CK, CAPEC, and CNCF’s catalog provide insights into supply chain compromise techniques.*

- **Vulnerability Databases**  
  *Integrate data from CVE, NVD, VulnDB, OSV, and Snyk Vulnerability DB for continuous monitoring of risks.*

- **Exploitability Information (VEX, EPSS)**  
  *Standards and tools to assess vulnerability exploitability and prioritize remediation.*

### Software Identification & Bill of Materials
- **Software Identification**  
  *Standards like CPE, SWID, and purl help uniquely identify software components.*

- **SBOM & Related BOMs**  
  *Tools and formats (CycloneDX, SPDX) support the creation and management of SBOMs, which are essential for understanding component dependencies and vulnerabilities.*

### Tooling & Cloud Supply Chain Security
- **SBOM Generation & Analysis Tools**  
  *Tools such as Syft, Tern, Trivy, and Dependency-Track enable automated SBOM generation and vulnerability scanning.*

- **Cloud Supply Chain Security**  
  *Guidance from AWS, Azure, and GCP on using SBOMs and securing container image build pipelines.*  
  - [Exporting SBOMs with Amazon Inspector](https://docs.aws.amazon.com/inspector/latest/user/sbom-export.html)  
  - [SBOM in Azure Engineering](https://devblogs.microsoft.com/engineering-at-microsoft/tag/sbom/)  
  - [Google’s Software Supply Chain Security Documentation](https://cloud.google.com/software-supply-chain-security/docs)

### Further Reading & Resources
- **Books & Industry Reports**  
  *Titles such as "Securing the Software Supply Chain" and annual reports from Sonatype, Snyk, and OpenSSF provide deeper insights.*

- **Guides & Documentation**  
  *Resources like the OWASP CycloneDX SBOM Guide and GitHub’s documentation on Software Supply Chain Security offer practical steps.*

- **GitHub Repos & Projects**  
  *Community-driven repositories such as awesome-software-supply-chain-security and various SBOM toolkits.*

For a more exhaustive list of resources—including detailed organization pages, attack research reports, and technical guides—please refer to the extended Software Supply Chain Security knowledge base available on GitHub and through linked publications.

---

## Additional Resources

- **Books & Courses**  
  - *The Web Application Hacker's Handbook*  
  - OWASP training materials and official guides.

- **Community Forums & Conferences**  
  - [r/devsecops on Reddit](https://www.reddit.com/r/devsecops/)  
  - Attend conferences like Black Hat, DefCon, and OWASP AppSec.

- **Research & Blogs**  
  - Wired, Lifewire, and eSecurity Planet offer articles on emerging trends in appsec, ASPM, and supply chain security.

---

This enriched document aims to bridge traditional application security with the broader challenges of securing the software supply chain. By integrating ASPM tools with supply chain transparency and vulnerability management, organizations can build a holistic, resilient security posture from development to deployment.

Enjoy exploring and leveraging these resources to enhance your security strategy!
