# security-data-engineering-portfolio
# Security Data Engineering & Threat Analytics Portfolio

Hi, I'm **Karen**, a **Security Data Engineer** based in Canada. 🇨🇦  
I bridge the gap between Big Data architecture and Cyber Defense by designing scalable data pipelines, optimizing log ingestion schemas, and engineering automated threat-detection models.

---

## 🛠️ Technical Ecosystem
* **Languages & Scripting:** Python, Bash, SQL, KQL (Kusto Query Language)
* **SIEM & Logging Infrastructures:** Microsoft Sentinel, Azure Log Analytics Workspaces, Splunk Enterprise
* **Data & Cloud Platforms:** Microsoft Azure, AWS, GitHub Actions (CI/CD)
* **Security & Testing Frameworks:** NIST SP 800-30, TruffleHog OSS, MITRE ATT&CK Mapping

---

## 🚀 Hands-On Security Engineering Projects

### 📊 1. Threat Intelligence Data Pipeline & Ingestion Engine (Azure SIEM)
* **The Problem:** Raw infrastructure security logs and external threat feeds arrive in massive, non-standardized formats, making rapid threat hunting impossible.
* **The Solution:** Architected a cloud ingestion pipeline using an **Azure Log Analytics Workspace** and **Microsoft Sentinel**. Normalized raw Windows Event timelines and atomic threat lists (derived from open-source intelligence repositories) into high-fidelity custom data tables (`_CL`).
* **The Impact:** Engineered custom **KQL queries** to filter out structural network behaviors, tracking multi-stage attack loops (Brute Force `4625` -> Mimikatz execution -> Ransomware deployment).
* **Keywords:** `Microsoft Sentinel` `KQL` `Log Normalization` `Azure Monitor`

### 🤖 2. Machine Learning Phishing Classifier (Security Data Science)
* **The Problem:** High volumes of social engineering strings evade traditional signature-based firewall inspection rules.
* **The Solution:** Built an automated text classification engine in Python using **Natural Language Processing (NLP)**. Implemented Scikit-Learn's `CountVectorizer` to convert unstructured email text blocks into numerical feature matrices.
* **The Impact:** Trained a **Multinomial Naive Bayes Classifier** capable of analyzing incoming notification blocks and routing real-time predictions (`Phishing` vs. `Safe`) to defensive ops queues.
* **Keywords:** `Python` `Machine Learning` `NLP` `Threat Classification`

### 🔒 3. Automated Incident Response Trigger (Security Scripting)
* **The Problem:** Active brute-force bots hammer infrastructure public network cards for hours before manual analyst intervention occurs.
* **The Solution:** Developed a proactive infrastructure monitoring script in Python that aggregates network stream JSON data blocks in real time.
* **The Impact:** Programmed a threshold-monitoring loop that automatically flags malicious IPs exceeding 5 failed login attempts and systematically triggers simulated endpoint firewall blocks.
* **Keywords:** `Python` `Incident Response Automation` `JSON Parsing` `Network Hardening`

### ⚙️ 4. Automated Secure CI/CD Code Pipeline (AppSec/DevSecOps)
* **The Problem:** Developers accidentally commit cloud secret keys and database access credentials directly into GitHub, causing production exposure.
* **The Solution:** Engineered a programmatic compliance gate using **GitHub Actions CI/CD workflows** to run automatically upon every code branch modification.
* **The Impact:** Native integration of **TruffleHog OSS** filesystem scanning routines to parse application configuration matrices, blocking builds via explicit non-zero exit code failures if unverified credentials are identified.
* **Keywords:** `DevSecOps` `GitHub Actions` `TruffleHog` `Secrets Management`

### ⚖️ 5. Third-Party Cloud Software Risk Architecture (GRC)
* **The Problem:** Enterprise procurement teams often adopt SaaS applications without assessing data privacy vulnerabilities or national residency regulatory exposures.
* **The Solution:** Developed an end-to-end third-party risk management framework utilizing **NIST SP 800-30** standards to analyze systemic remote application usage.
* **The Impact:** Modeled matrix calculations mapping threat probability against business impact vectors, delivering technical remediation steps including explicit multi-factor authentication (MFA) enforcement policies and geo-fenced data residency controls.
* **Keywords:** `GRC` `NIST Framework` `Risk Modeling` `Compliance Auditing`

---

## 📬 Let's Connect!
* **LinkedIn:** [Insert Your LinkedIn Link]
* **Email:** [Insert Your Email]
