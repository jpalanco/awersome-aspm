# Awesome ASPM

This document is a curated, community‐driven list of resources from my ASPM universe—a comprehensive collection covering application security (AppSec), Application Security Posture Management (ASPM), and the broader software supply chain security. Whether you're a developer, security engineer, or decision‐maker, use this list to navigate essential tools, techniques, URLs, and leading providers in the appsec space.

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
6. [Additional Resources](#additional-resources)

---

## Introduction

In today's evolving cybersecurity landscape, effective Application Security Posture Management (ASPM) is critical. This awesome list brings together the best tools, techniques, and resources for enhancing your application security—from automated code scanning and dynamic testing to securing your development pipelines, cloud environments, and software supply chain. Explore the sections below to discover what you need to secure your applications throughout the entire software lifecycle.

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
  *Semgrep fork.*  
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
  *A fast and flexible vulnerability scanner based on templates for automated vulnerability scanning across web services and networks.*  
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
Source Code Management (SCM) tools host and manage your code repositories—an essential component for secure development workflows.

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
  *Scans cloud environments for misconfigurations and vulnerabilities, ensuring cloud resource security.*  
  [Learn More](https://github.com/cloudsploit/CloudSploit)

### IaC & Container Security Tools
Tools in this category focus on securing Infrastructure as Code (IaC) and container environments. Many of these tools offer multiple features:
  
- **Trivy**  
  *A versatile scanner that covers container images and IaC files. It provides vulnerability scanning, Software Composition Analysis (SCA), license compliance checks, SBOM generation, and container security—all in one tool.*  
  [Learn More](https://github.com/aquasecurity/trivy)

- **Kics**  
  *Developed by Checkmarx, Kics scans IaC for misconfigurations and vulnerabilities across multiple formats.*  
  [Learn More](https://kics.io)

- **Hadolint**  
  *A Dockerfile linter that helps enforce best practices and security standards in container builds.*  
  [Learn More](https://github.com/hadolint/hadolint)

- **Checkov**  
  *Performs comprehensive security and compliance scans on IaC templates, supporting a wide range of checks for cloud infrastructures and container configurations.*  
  [Learn More](https://www.checkov.io)

### SCM Security & Software Supply Chain Tools
These resources focus on securing your development pipeline and software supply chain—from SCM integrity to dependency analysis and SBOM management.

- **Chainbench**  
  *A tool designed to evaluate and secure SCM environments, helping ensure the integrity of your software supply chain.*  
  [Learn More](https://chainbench.io)

- **Syft**  
  *Generates a Software Bill of Materials (SBOM) from container images and filesystems, aiding in vulnerability management and compliance.*  
  [Learn More](https://github.com/anchore/syft)

- **FOSSA**  
  *Provides robust Software Composition Analysis (SCA) to manage open-source dependencies and ensure license compliance.*  
  [Learn More](https://fossa.com)

- **SLSA Resources**  
  *Explore frameworks and guidelines for Software Supply Chain Levels for Software Artifacts (SLSA) to improve build integrity and security.*  
  [Learn More](https://slsa.dev)

### Secrets Management Tools
These tools are dedicated to detecting, managing, and preventing the leakage of sensitive information from your code and repositories.

- **TruffleHog**  
  *Searches through git repositories for high-entropy strings and potential secrets leaks.*  
  [Learn More](https://github.com/trufflesecurity/trufflehog)

- **GitGuardian**  
  *Monitors public and private repositories for exposed secrets and credentials in real time.*  
  [Learn More](https://www.gitguardian.com)

- **Detect Secrets**  
  *An open-source tool by Yelp that identifies potential secrets in codebases before they are committed.*  
  [Learn More](https://github.com/Yelp/detect-secrets)

- **CredScan**  
  *Microsoft’s tool for scanning codebases for credentials and secrets, helping ensure secure code before deployment.*  
  [Learn More](https://github.com/microsoft/CredScan)

### Other Useful Tools
- **Wireshark**  
  *A powerful network sniffer for capturing and analyzing network traffic—useful for diagnosing security issues.*  
  [Learn More](https://www.wireshark.org)

- **Burp Suite Extensions (BApps)**  
  *Enhance Burp Suite’s functionality with community and custom plugins (e.g., Param Miner, HTTP Request Smuggler).*  
  [Explore BApps](https://portswigger.net/bappstore)

---

## Techniques

### Secure Coding & Threat Modeling
- **OWASP Top Ten**  
  *Understand and mitigate common vulnerabilities such as Injection, Broken Access Control, and more.*  
  [OWASP Top Ten](https://owasp.org/www-project-top-ten/)

- **Threat Modeling**  
  *Incorporate design reviews and risk analysis early in the SDLC to identify potential security issues.*

### Fuzz Testing & Penetration Testing
- **Fuzz Testing**  
  *Use fuzzers to generate random inputs and detect unexpected behavior or security flaws.*

- **Penetration Testing**  
  *Combine automated scans with manual testing (using tools like Metasploit) to evaluate security comprehensively.*  
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

## Additional Resources

- **Books & Courses**  
  - *The Web Application Hacker's Handbook*  
  - OWASP training materials and official guides.

- **Community Forums & Conferences**  
  - [r/devsecops on Reddit](https://www.reddit.com/r/devsecops/)  
  - Attend conferences like Black Hat, DefCon, and OWASP AppSec.

- **Research & Blogs**  
  - Wired, Lifewire, and eSecurity Planet offer articles on emerging trends in appsec, ASPM, and software supply chain security.

