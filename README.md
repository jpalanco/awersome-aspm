# Awesome ASPM

A community‐driven, curated list of top resources from the ASPM universe. This guide covers application security (AppSec), Application Security Posture Management (ASPM), and Software Supply Chain Security. Whether you’re a developer, security engineer, or decision‐maker, use this list to quickly identify the tools, techniques, and providers that matter.

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
   - [Vulnerable Projects for Testing](#vulnerable-projects-for-testing)
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

ASPM isn’t just another buzzword—it’s a necessity in today’s evolving cybersecurity landscape. This guide highlights the tools, techniques, and providers that help you secure your applications and manage the risks in your software supply chain. Simple, clear, and straight to the point.

---

## Tools

### SAST Tools

| Tool | Description |
|:-----|:------------|
| [Checkmarx SAST](https://checkmarx.com/cxsast-source-code-scanning/) | Comprehensive scanning with support for 35+ languages and robust AI‐assisted remediation. |
| [SonarQube](https://www.sonarqube.org) | Open-source solution focused on code quality and vulnerability detection. |
| [Veracode](https://www.veracode.com) | Cloud-based platform offering low false positives and detailed remediation guidance. |
| [Semgrep](https://semgrep.dev) | Highly configurable static analysis that easily integrates into CI/CD pipelines across multiple languages. |
| [Opengrep](https://opengrep.dev) | A Semgrep fork with extra customization options. |
| [Synopsys Coverity](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) | Enterprise-grade analysis for large codebases with support for a wide range of languages. |

### DAST Tools

| Tool | Description |
|:-----|:------------|
| [Burp Suite](https://portswigger.net/burp) | The industry-standard web security testing tool available in both Community and Professional editions. |
| [OWASP ZAP](https://www.zaproxy.org) | Open-source DAST tool for automated vulnerability scanning and manual testing. |
| [Nuclei](https://nuclei.projectdiscovery.io) | Fast, flexible vulnerability scanner that uses templates for automated scans across web services and networks. |

### IAST & RASP Tools

| Tool | Description |
|:-----|:------------|
| [Contrast Security](https://www.contrastsecurity.com) | Provides both IAST and RASP for continuous, in-context vulnerability detection. |
| [HCL AppScan CodeSweep](https://www.hcltech.com/software/appscan) | Offers on-the-fly static and dynamic analysis integrated into your development workflow. |

### ASPM Platforms

| Platform | Description |
|:---------|:------------|
| [Plexicus](https://www.plexicus.com) | A no-frills, free ASPM perfect for small projects. |
| [Cycode ASPM](https://www.cycode.com) | Secures the entire software supply chain with continuous scanning and secrets management. |
| [GitLab](https://about.gitlab.com) | A full DevSecOps platform that bundles SAST, DAST, container scanning, and more in a unified workflow. |
| [Snyk](https://snyk.io) | Developer-centric platform for detecting and remediating vulnerabilities in open-source dependencies. |

### SCM Tools & Git Repositories

| Service | Description |
|:--------|:------------|
| [GitHub](https://github.com) | The largest code hosting platform with robust collaboration and security features. |
| [GitLab](https://gitlab.com) | Combines repository hosting with integrated CI/CD, SAST, and container scanning. |
| [Bitbucket](https://bitbucket.org) | Atlassian’s hosting service that meshes seamlessly with tools like Jira. |
| [Gitea](https://gitea.io) | Lightweight, self-hosted Git service designed for simplicity and speed. |

### CNAPP Tools

| Tool | Description |
|:-----|:------------|
| [Prowler](https://github.com/prowler-cloud/prowler) | Open-source AWS security tool performing extensive checks on cloud configuration best practices. |
| [CloudSploit](https://github.com/cloudsploit/CloudSploit) | Scans cloud environments for misconfigurations and vulnerabilities to secure your cloud assets. |

### IaC & Container Security Tools

| Tool | Description |
|:-----|:------------|
| [Trivy](https://github.com/aquasecurity/trivy) | A versatile scanner covering container images and IaC, including vulnerability scanning, SCA, license compliance, SBOM generation, and container security. |
| [Kics](https://kics.io) | Developed by Checkmarx, Kics scans IaC for misconfigurations and vulnerabilities across multiple formats. |
| [Hadolint](https://github.com/hadolint/hadolint) | A Dockerfile linter enforcing best practices and security standards in container builds. |
| [Checkov](https://www.checkov.io) | Conducts comprehensive security and compliance scans on IaC templates across cloud infrastructures and containers. |

### SCM Security & Software Supply Chain Tools

| Tool | Description |
|:-----|:------------|
| [Chainbench](https://chainbench.io) | Evaluates and secures SCM environments to help maintain software supply chain integrity. |
| [Syft](https://github.com/anchore/syft) | Generates a Software Bill of Materials (SBOM) from container images and filesystems for effective vulnerability management. |
| [FOSSA](https://fossa.com) | Offers robust Software Composition Analysis (SCA) for managing open-source dependencies and license compliance. |
| [SLSA Resources](https://slsa.dev) | Provides frameworks and guidelines to ensure that software builds are secure and verifiable. |

### Secrets Management Tools

| Tool | Description |
|:-----|:------------|
| [TruffleHog](https://github.com/trufflesecurity/trufflehog) | Scans Git repositories for high-entropy strings and potential secret leaks. |
| [GitGuardian](https://www.gitguardian.com) | Monitors repositories in real time for exposed secrets and credentials. |
| [Detect Secrets](https://github.com/Yelp/detect-secrets) | An open-source tool from Yelp that identifies potential secrets before code commits. |
| [CredScan](https://github.com/microsoft/CredScan) | Microsoft’s solution for scanning codebases for credentials and secrets to ensure secure deployments. |

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

- **[OWASP Top Ten](https://owasp.org/www-project-top-ten/):** The essential guide to common vulnerabilities—Injection, Broken Access Control, and more.
- **Threat Modeling:** Integrate design reviews and risk analysis early in the SDLC to identify potential security issues.

### Fuzz Testing & Penetration Testing

- **Fuzz Testing:** Use fuzzers to generate random inputs that can reveal unexpected behaviors and security flaws.
- **[Penetration Testing](https://www.metasploit.com):** Combine automated scans with manual testing to get a comprehensive security evaluation.

---

## URLs & Resources

- [OWASP Official Website](https://owasp.org)
- [Awesome AppSec (GitHub)](https://github.com/paragonie/awesome-appsec)
- [Awesome Security (GitHub)](https://github.com/sbilly/awesome-security)
- [eSecurity Planet](https://www.esecurityplanet.com)
- [Burp Suite Documentation](https://portswigger.net/burp/documentation)

---

## Providers & Services

| Provider | Description |
|:---------|:------------|
| [Plexicus](https://www.plexicus.com) | A straightforward, free ASPM suited for small projects. |
| [Veracode](https://www.veracode.com) | Comprehensive security testing services aimed at large enterprises. |
| [Snyk](https://snyk.io) | Developer-friendly vulnerability scanning and remediation integrated with CI/CD pipelines. |
| [Checkmarx](https://www.checkmarx.com) | Enterprise-grade SAST with extensive language support and AI-assisted vulnerability prioritization. |
| [Cycode](https://www.cycode.com) | Provides real-time ASPM capabilities to secure the software supply chain. |

---

## Software Supply Chain Security

Software Supply Chain Security is the essential counterpart to ASPM. This section gathers initiatives, standards, organizations, and tooling to ensure that every component—from code to dependencies—is secure and transparent.

### Organizations & Foundations

- **[NTIA](https://www.ntia.gov/page/software-bill-materials):** Offers SBOM resources, FAQs, and guides to help organizations generate and manage Software Bills of Materials.
- **[CISA](https://www.cisa.gov/sbom):** Provides security guidance and recommendations to defend against software supply chain attacks.
- **The White House – ONCD and NIST:** Develop national cybersecurity strategies and secure software development frameworks (e.g., NIST SP 800-218, SP 800-161).
- **OWASP, OpenSSF, and CNCF:** Lead community initiatives like the OWASP Software Component Verification Standard and OpenSSF Scorecard.

### Regulations

- **EO-14028:** An executive order focused on improving national cybersecurity and supply chain risk management.
- **European Cyber Resilience Act (CRA):** A framework designed to enhance cybersecurity across Europe’s software supply chain.

### Standards, Frameworks, & Best Practices

- **[SLSA (Supply-chain Levels for Software Artifacts)](https://slsa.dev):** A framework ensuring that software builds are secure and verifiable.
- **OWASP SCVS and CSAF:** Standards for verifying third-party components and exchanging security advisories.
- **NIST SP 800-218 & SP 800-204D:** Guidelines for secure software development and integrating supply chain security into CI/CD pipelines.

### Threats, Attacks & Vulnerability Management

- **Threat Catalogs and Attack Vectors:** Resources like MITRE ATT&CK, CAPEC, and CNCF’s catalog offer insight into supply chain compromise techniques.
- **Vulnerability Databases:** Use data from CVE, NVD, VulnDB, OSV, and Snyk Vulnerability DB for continuous risk monitoring.
- **Exploitability Information (VEX, EPSS):** Tools and standards to assess and prioritize vulnerability remediation.

### Software Identification & Bill of Materials

- **Software Identification:** Standards such as CPE, SWID, and purl uniquely identify software components.
- **SBOM & Related BOMs:** Formats like CycloneDX and SPDX support the creation and management of SBOMs to track component dependencies.

### Tooling & Cloud Supply Chain Security

- **SBOM Generation & Analysis Tools:** Solutions like Syft, Tern, Trivy, and Dependency-Track automate SBOM creation and vulnerability scanning.
- **Cloud Supply Chain Security:** Guidance from AWS, Azure, and GCP on using SBOMs and securing container image build pipelines:
  - **AWS:** [Exporting SBOMs with Amazon Inspector](https://docs.aws.amazon.com/inspector/latest/user/sbom-export.html)
  - **Azure:** [SBOM in Azure Engineering](https://devblogs.microsoft.com/engineering-at-microsoft/tag/sbom/)
  - **Google Cloud:** [Software Supply Chain Security Documentation](https://cloud.google.com/software-supply-chain-security/docs)

### Further Reading & Resources

- **Books & Industry Reports:** Titles like *Securing the Software Supply Chain* and annual reports from Sonatype, Snyk, and OpenSSF offer deeper insights.
- **Guides & Documentation:** Check out the OWASP CycloneDX SBOM Guide and GitHub’s Software Supply Chain Security documentation.
- **GitHub Repos & Projects:** Explore community-driven repositories (e.g., awesome‑software‑supply‑chain‑security) for additional tools and best practices.

---

## Additional Resources

- **Books & Courses:**  
  *The Web Application Hacker's Handbook* and various OWASP training materials provide practical, hands-on knowledge.
- **Community Forums & Conferences:**  
  - Join discussions on [r/devsecops](https://www.reddit.com/r/devsecops/)  
  - Attend conferences like Black Hat, DefCon, and OWASP AppSec.
- **Research & Blogs:**  
  Stay updated with industry articles from Wired, Lifewire, and eSecurity Planet on trends in AppSec, ASPM, and supply chain security.
