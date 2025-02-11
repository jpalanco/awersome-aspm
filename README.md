# Awesome ASPM

This document is a curated, community‐driven list of resources from the ASPM universe—a comprehensive collection covering application security (AppSec), Application Security Posture Management (ASPM), and Software Supply Chain Security. Whether you're a developer, security engineer, or decision‐maker, use this list to navigate essential tools, techniques, URLs, and leading providers in the appsec space while gaining insight into supply chain risk management and transparency.

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
   - [Vulnerable Projects for Testing](#Vulnerable-Projects-for-Testing)
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

In today's evolving cybersecurity landscape, effective Application Security Posture Management (ASPM) is critical to ensure that your applications remain secure throughout their lifecycle. This document not only highlights the best tools, techniques, and providers for ASPM but also dives into the vital realm of Software Supply Chain Security—covering initiatives, standards, regulations, and research that help manage risk from code to dependencies.

---

## Tools

### SAST Tools

#### Checkmarx SAST
- **Description:** Comprehensive scanning with support for 35+ languages and robust AI‐assisted remediation.

#### SonarQube
- **Website:** [https://www.sonarqube.org](https://www.sonarqube.org)
- **Description:** An open‐source solution focused on code quality and vulnerability detection.

#### Veracode
- **Website:** [https://www.veracode.com](https://www.veracode.com)
- **Description:** A cloud‐based platform offering low false positives and detailed remediation guidance.

#### Semgrep
- **Website:** [https://semgrep.dev](https://semgrep.dev)
- **Description:** Highly configurable SAST that integrates into CI/CD pipelines for multiple languages.

#### Opengrep
- **Website:** [https://opengrep.dev](https://opengrep.dev)
- **Description:** A Semgrep fork for additional customization.

#### Synopsys Coverity
- **Website:** [https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html)
- **Description:** Enterprise‐grade analysis for large codebases with extensive language support.

---

### DAST Tools

#### Burp Suite
- **Website:** [https://portswigger.net/burp](https://portswigger.net/burp)
- **Description:** Industry‐standard web security testing tool available in Community and Professional editions.

#### OWASP ZAP
- **Website:** [https://www.zaproxy.org](https://www.zaproxy.org)
- **Description:** Open‐source DAST tool for automated vulnerability scanning and manual testing.

#### Nuclei
- **Website:** [https://nuclei.projectdiscovery.io](https://nuclei.projectdiscovery.io)
- **Description:** A fast and flexible vulnerability scanner based on templates for automated scanning across web services and networks.

---

### IAST & RASP Tools

#### Contrast Security
- **Website:** [https://www.contrastsecurity.com](https://www.contrastsecurity.com)
- **Description:** Offers both IAST and RASP capabilities for continuous in‐context vulnerability detection.

#### HCL AppScan CodeSweep
- **Website:** [https://www.hcltech.com/software/appscan](https://www.hcltech.com/software/appscan)
- **Description:** Delivers on‐the‐fly static and dynamic analysis integrated into your development workflow.

---

### ASPM Platforms

#### Plexicus
- **Website:** [https://www.plexicus.com](https://www.plexicus.com)
- **Description:** Offers a limited but free ASPM for small projects.

#### Cycode ASPM
- **Website:** [https://www.cycode.com](https://www.cycode.com)
- **Description:** Secures the entire software supply chain with continuous scanning and secrets management.

#### GitLab
- **Website:** [https://about.gitlab.com](https://about.gitlab.com)
- **Description:** A DevSecOps platform that integrates SAST, DAST, container scanning, and more into one unified workflow.

#### Snyk
- **Website:** [https://snyk.io](https://snyk.io)
- **Description:** Developer‐centric platform focusing on vulnerability detection and remediation in open‐source dependencies.

---

### SCM Tools & Git Repositories

#### GitHub
- **Website:** [https://github.com](https://github.com)
- **Description:** The largest code hosting platform with robust collaboration and security features.

#### GitLab
- **Website:** [https://gitlab.com](https://gitlab.com)
- **Description:** Offers integrated CI/CD, SAST, and container scanning alongside repository hosting.

#### Bitbucket
- **Website:** [https://bitbucket.org](https://bitbucket.org)
- **Description:** Atlassian’s code hosting service that integrates seamlessly with other Atlassian tools like Jira.

#### Gitea
- **Website:** [https://gitea.io](https://gitea.io)
- **Description:** A lightweight, self‐hosted Git service designed for simplicity and speed.

---

### CNAPP Tools

#### Prowler
- **Website:** [https://github.com/prowler-cloud/prowler](https://github.com/prowler-cloud/prowler)
- **Description:** An open‐source AWS security tool that performs extensive checks for cloud configuration best practices.

#### CloudSploit
- **Website:** [https://github.com/cloudsploit/CloudSploit](https://github.com/cloudsploit/CloudSploit)
- **Description:** Scans cloud environments for misconfigurations and vulnerabilities to secure cloud resources.

---

### IaC & Container Security Tools

#### Trivy
- **Website:** [https://github.com/aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **Description:** A versatile scanner covering container images and IaC, including vulnerability scanning, SCA, license compliance, SBOM generation, and container security.

#### Kics
- **Website:** [https://kics.io](https://kics.io)
- **Description:** Developed by Checkmarx, Kics scans IaC for misconfigurations and vulnerabilities across multiple formats.

#### Hadolint
- **Website:** [https://github.com/hadolint/hadolint](https://github.com/hadolint/hadolint)
- **Description:** A Dockerfile linter that enforces best practices and security standards in container builds.

#### Checkov
- **Website:** [https://www.checkov.io](https://www.checkov.io)
- **Description:** Performs comprehensive security and compliance scans on IaC templates across cloud infrastructures and containers.

---

### SCM Security & Software Supply Chain Tools

#### Chainbench
- **Website:** [https://chainbench.io](https://chainbench.io)
- **Description:** Evaluates and secures SCM environments to ensure software supply chain integrity.

#### Syft
- **Website:** [https://github.com/anchore/syft](https://github.com/anchore/syft)
- **Description:** Generates a Software Bill of Materials (SBOM) from container images and filesystems for effective vulnerability management.

#### FOSSA
- **Website:** [https://fossa.com](https://fossa.com)
- **Description:** Provides robust Software Composition Analysis (SCA) to manage open‐source dependencies and license compliance.

#### SLSA Resources
- **Website:** [https://slsa.dev](https://slsa.dev)
- **Description:** Offers frameworks and guidelines for Supply‐chain Levels for Software Artifacts (SLSA) to ensure secure build integrity.

---

### Secrets Management Tools

#### TruffleHog
- **Website:** [https://github.com/trufflesecurity/trufflehog](https://github.com/trufflesecurity/trufflehog)
- **Description:** Searches git repositories for high‐entropy strings and potential secrets leaks.

#### GitGuardian
- **Website:** [https://www.gitguardian.com](https://www.gitguardian.com)
- **Description:** Monitors repositories for exposed secrets and credentials in real time.

#### Detect Secrets
- **Website:** [https://github.com/Yelp/detect-secrets](https://github.com/Yelp/detect-secrets)
- **Description:** An open‐source tool by Yelp that identifies potential secrets before code commits.

#### CredScan
- **Website:** [https://github.com/microsoft/CredScan](https://github.com/microsoft/CredScan)
- **Description:** Microsoft’s tool for scanning codebases for credentials and secrets to ensure secure deployments.

---

### Vulnerable Projects for Testing

#### SAST Vulnerable Projects
- [AltoroJ](https://github.com/HCL-TECH-SOFTWARE/AltoroJ)
- [pygoat](https://github.com/adeyosemanputra/pygoat)
- [WebGoat.NET](https://github.com/tobyash86/WebGoat.NET)
- [Juice Shop](https://github.com/juice-shop/juice-shop)
- [Intentionally Vulnerable Golang Project](https://github.com/sonatype-nexus-community/intentionally-vulnerable-golang-project)

#### SCA Vulnerable Projects
- [sca-small-goat](https://github.com/cxsca/sca-small-goat)

#### IaC Vulnerable Projects
- [IacGOAT](https://github.com/reinerHaneburgerSnyk/IacGOAT)
- [VulnerableDockerfile](https://github.com/SamP10/VulnerableDockerfile)

#### Secrets Vulnerable Projects
- [wrongsecrets](https://github.com/OWASP/wrongsecrets)

---

## Techniques

### Secure Coding & Threat Modeling

#### OWASP Top Ten
- **Website:** [https://owasp.org/www-project-top-ten/](https://owasp.org/www-project-top-ten/)
- **Description:** Understand and mitigate common vulnerabilities such as Injection, Broken Access Control, and more.

#### Threat Modeling
- **Description:** Incorporate design reviews and risk analysis early in the SDLC to identify potential security issues.

### Fuzz Testing & Penetration Testing

#### Fuzz Testing
- **Description:** Use fuzzers to generate random inputs and detect unexpected behavior or security flaws.

#### Penetration Testing
- **Website:** [https://www.metasploit.com](https://www.metasploit.com)
- **Description:** Combine automated scans with manual testing (using tools like Metasploit) to comprehensively evaluate security.

---

## URLs & Resources

#### OWASP Official Website
- **Website:** [https://owasp.org](https://owasp.org)

#### Awesome AppSec (GitHub)
- **Website:** [https://github.com/paragonie/awesome-appsec](https://github.com/paragonie/awesome-appsec)

#### Awesome Security (GitHub)
- **Website:** [https://github.com/sbilly/awesome-security](https://github.com/sbilly/awesome-security)

#### eSecurity Planet
- **Website:** [https://www.esecurityplanet.com](https://www.esecurityplanet.com)

#### Burp Suite Documentation
- **Website:** [https://portswigger.net/burp/documentation](https://portswigger.net/burp/documentation)

---

## Providers & Services

#### Plexicus
- **Website:** [https://www.plexicus.com](https://www.plexicus.com)
- **Description:** Offers a limited but free ASPM for small projects.

#### Veracode
- **Website:** [https://www.veracode.com](https://www.veracode.com)
- **Description:** Offers comprehensive security testing services tailored for large enterprises.

#### Snyk
- **Website:** [https://snyk.io](https://snyk.io)
- **Description:** Provides developer‐friendly vulnerability scanning and remediation with seamless CI/CD integration.

#### Checkmarx
- **Website:** [https://www.checkmarx.com](https://www.checkmarx.com)
- **Description:** Enterprise‐grade SAST solutions with deep language support and AI‐assisted vulnerability prioritization.

#### Cycode
- **Website:** [https://www.cycode.com](https://www.cycode.com)
- **Description:** Secures the software supply chain with real‐time ASPM capabilities.

---

## Software Supply Chain Security

Software Supply Chain Security is a critical complement to ASPM. This section gathers initiatives, standards, organizations, and tooling that help ensure the integrity and transparency of every software component—from development to deployment.

### Organizations & Foundations

#### NTIA
- **Website:** [https://www.ntia.gov/page/software-bill-materials](https://www.ntia.gov/page/software-bill-materials)
- **Description:** Provides SBOM resources, FAQs, and guides to help organizations generate and manage Software Bills of Materials (SBOMs).

#### CISA
- **Website:** [https://www.cisa.gov/sbom](https://www.cisa.gov/sbom)
- **Description:** Offers SBOM resources, security guidance, and recommendations on defending against software supply chain attacks.

#### The White House – ONCD and NIST
- **Description:** Develop national cybersecurity strategies and secure software development frameworks (e.g., NIST SP 800-218, SP 800-161).

#### OWASP, OpenSSF, and CNCF
- **Description:** Drive community initiatives such as the OWASP Software Component Verification Standard, OpenSSF Scorecard, and CNCF best practices for supply chain security.

### Regulations

#### EO-14028
- **Description:** An executive order on improving the nation’s cybersecurity that emphasizes supply chain risk management.

#### European Cyber Resilience Act (CRA)
- **Description:** A regulatory framework aimed at enhancing cybersecurity in the software supply chain across Europe.

### Standards, Frameworks, & Best Practices

#### SLSA (Supply-chain Levels for Software Artifacts)
- **Website:** [https://slsa.dev](https://slsa.dev)
- **Description:** A framework to ensure that software builds are secure and verifiable.

#### OWASP SCVS and CSAF
- **Description:** Standards for verifying third‐party components and exchanging security advisory information.

#### NIST SP 800-218 & SP 800-204D
- **Description:** Guidelines and drafts for secure software development and integrating supply chain security into CI/CD pipelines.

### Threats, Attacks & Vulnerability Management

#### Threat Catalogs and Attack Vectors
- **Description:** Resources like MITRE ATT&CK, CAPEC, and CNCF’s catalog provide insights into supply chain compromise techniques.

#### Vulnerability Databases
- **Description:** Integrate data from CVE, NVD, VulnDB, OSV, and Snyk Vulnerability DB for continuous monitoring of risks.

#### Exploitability Information (VEX, EPSS)
- **Description:** Standards and tools to assess vulnerability exploitability and prioritize remediation.

### Software Identification & Bill of Materials

#### Software Identification
- **Description:** Standards like CPE, SWID, and purl help uniquely identify software components.

#### SBOM & Related BOMs
- **Description:** Tools and formats (CycloneDX, SPDX) support the creation and management of SBOMs, which are essential for understanding component dependencies and vulnerabilities.

### Tooling & Cloud Supply Chain Security

#### SBOM Generation & Analysis Tools
- **Description:** Tools such as Syft, Tern, Trivy, and Dependency-Track enable automated SBOM generation and vulnerability scanning.

#### Cloud Supply Chain Security
- **Description:** Guidance from AWS, Azure, and GCP on using SBOMs and securing container image build pipelines.
- **AWS:** [Exporting SBOMs with Amazon Inspector](https://docs.aws.amazon.com/inspector/latest/user/sbom-export.html)
- **Azure:** [SBOM in Azure Engineering](https://devblogs.microsoft.com/engineering-at-microsoft/tag/sbom/)
- **Google Cloud:** [Software Supply Chain Security Documentation](https://cloud.google.com/software-supply-chain-security/docs)

### Further Reading & Resources

#### Books & Industry Reports
- **Description:** Titles such as *Securing the Software Supply Chain* and annual reports from Sonatype, Snyk, and OpenSSF provide deeper insights.

#### Guides & Documentation
- **Description:** Resources like the OWASP CycloneDX SBOM Guide and GitHub’s documentation on Software Supply Chain Security offer practical steps.

#### GitHub Repos & Projects
- **Description:** Community‐driven repositories such as awesome‐software‐supply‐chain‐security and various SBOM toolkits.

For a more exhaustive list of resources—including detailed organization pages, attack research reports, and technical guides—please refer to the extended Software Supply Chain Security knowledge base available on GitHub and through linked publications.

---

## Additional Resources

#### Books & Courses
- *The Web Application Hacker's Handbook*
- OWASP training materials and official guides.

#### Community Forums & Conferences
- **Reddit:** [r/devsecops](https://www.reddit.com/r/devsecops/)
- Conferences such as Black Hat, DefCon, and OWASP AppSec.

#### Research & Blogs
- **Description:** Wired, Lifewire, and eSecurity Planet offer articles on emerging trends in appsec, ASPM, and supply chain security.
