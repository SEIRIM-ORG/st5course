
Your course should not only teach employees how to avoid causing incidents. It should teach decision-makers how to determine whether the company has basic cyber controls in place before an incident occurs.

NIST CSF 2.0 places **Govern** at the center of cybersecurity risk management, and NIST’s Small Business Quick Start Guide is specifically intended to help SMEs with modest or immature cybersecurity programs establish a risk-management strategy. CISA’s small-business guidance also assigns leadership responsibilities such as reviewing the incident response plan and ensuring controls such as MFA, patching, logging, and backups are implemented. ([NIST Publications](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf?utm_source=chatgpt.com "The NIST Cybersecurity Framework (CSF) 2.0"))

The strongest design is a dual-layer course:

- **Everyone:** What each person must do.
    
- **Executives and Key Staff:** What the company must be doing, what questions to ask, and what evidence to request.
    

Do not mix technical implementation instructions into the general staff lessons. Executives do not need to know how to configure a vulnerability scanner. They need to know whether scanning occurs, what is covered, who owns remediation, how overdue risks are escalated, and whether unsupported systems remain in use.

## Recommended Structure for Every Module

Each module should follow the same six-part pattern:

1. Understand the risk
    
2. Recognize the warning signs
    
3. Take the correct personal action
    
4. Follow the correct business process
    
5. Ensure the company has the required controls
    
6. Verify that those controls are actually working
    

The last two sections should be visibly labeled **Leadership Assurance** or **For Executives and Key Staff**.

# Module 1: Spot and Stop Social Engineering

**Objective:** Staff can recognize and stop manipulation attempts, while leadership ensures that business processes cannot be bypassed by a convincing message or phone call.

### 1. How Social Engineering Manipulates People

Cover urgency, authority, fear, secrecy, curiosity, helpfulness, financial pressure, and requests to bypass normal procedures.

Employees should understand that attackers exploit human trust and business processes, not only technical weaknesses.

### 2. Recognize Attacks Across Different Channels

Include email phishing, SMS, messaging apps, phone calls, QR codes, fake login pages, video calls, deepfakes, and compromised supplier accounts.

The lesson should emphasize that a message can look professional, use correct grammar, and appear to come from a legitimate account while still being malicious.

### 3. Inspect Before Clicking, Opening, Scanning, or Replying

Teach employees to inspect sender addresses, links, attachments, shared documents, login pages, and QR codes before acting.

The repeatable behavior should be:

> Pause. Inspect. Verify. Report.

### 4. Verify High-Risk Requests Through a Separate Channel

Require independent verification for:

- Payment requests
    
- Bank-detail changes
    
- Payroll changes
    
- Password resets
    
- MFA requests
    
- Sensitive document requests
    
- Vendor-account changes
    
- Requests to bypass approval procedures
    

Verification must use a trusted phone number, known contact, or existing internal channel—not the contact details inside the suspicious request.

### 5. Leadership Assurance: Build Fraud-Resistant Business Processes

Executives and key staff should ensure the company has:

- Dual approval for significant payments
    
- Independent verification for bank-detail changes
    
- Documented procedures for vendor and payroll changes
    
- Help-desk identity verification procedures
    
- Restrictions on gift-card purchases and unusual payment methods
    
- A rule that executives cannot override security procedures through urgency or status
    
- A process for verifying sensitive requests received through email, phone, or video
    

This is especially important because a well-trained employee can still fail if the underlying process allows one person to authorize a high-risk action.

### 6. Leadership Assurance: Measure Social Engineering Readiness

Leadership should ask:

- Is security awareness training provided during onboarding and periodically afterward?
    
- Can staff report suspicious messages with one simple action?
    
- Are phishing simulations used to identify training gaps?
    
- Are reporting rates measured, not only failure rates?
    
- Are finance, HR, procurement, executives, and help-desk staff given role-specific scenarios?
    
- Are employees encouraged to report mistakes immediately without fear?
    

**Evidence to request:** training completion reports, phishing-reporting metrics, verification procedures, payment-approval records, and examples of lessons learned from reported attempts.

# Module 2: Protect Accounts and Access

**Objective:** Staff protect their accounts, while leadership ensures that access is granted, reviewed, and removed appropriately across the company.

### 1. Use Strong, Unique Credentials

Teach password managers, unique passwords, separation of personal and work credentials, and passkeys where supported.

Do not teach employees to invent complicated password formulas. The better control is a company-approved password manager.

### 2. Use MFA Correctly

Cover MFA prompts, authentication codes, push-notification fatigue, passkeys, hardware security keys, and unexpected login requests.

The core behavior is:

> Never approve a login you did not initiate.

### 3. Never Share Accounts or Authentication Methods

Include shared passwords, shared accounts, lending active sessions, sending credentials through chat, sharing MFA codes, and allowing another person to use an account.

Shared accounts weaken accountability and make incident investigation more difficult.

### 4. Grant and Use Only Necessary Access

Teach employees to avoid requesting access “just in case,” grant the minimum necessary file permissions, review external collaborators, and remove access when it is no longer required.

### 5. Leadership Assurance: Manage the Full Account Lifecycle

Executives and key staff should ensure the company has a documented process for:

- Creating accounts for new staff
    
- Changing access when roles change
    
- Removing access immediately when staff or contractors leave
    
- Reviewing dormant and inactive accounts
    
- Reviewing shared and generic accounts
    
- Separating administrator accounts from normal user accounts
    
- Reviewing access to sensitive systems and data
    
- Removing unnecessary third-party application access
    

This is commonly called the **joiner, mover, and leaver** process.

### 6. Leadership Assurance: Verify Authentication and Privileged Access Controls

Leadership should ask:

- Is MFA required for email, cloud services, remote access, administrators, and other critical systems?
    
- Is phishing-resistant MFA used for the highest-risk accounts where practical?
    
- Are privileged accounts limited to people who genuinely require them?
    
- Are access reviews performed periodically?
    
- Are former employee accounts removed promptly?
    
- Are there any systems that still rely on shared passwords?
    
- Is there a current inventory of administrator and privileged accounts?
    

CISA recommends requiring MFA broadly, with priority given to privileged, administrative, and remote-access users. ([CISA](https://www.cisa.gov/resources-tools/resources/cyber-essentials?utm_source=chatgpt.com "Cyber Essentials"))

**Evidence to request:** MFA coverage reports, privileged-account inventories, access-review records, offboarding checklists, and dormant-account reports.

# Module 3: Handle Data, Files, Cloud Tools, and AI Safely

**Objective:** Staff handle information responsibly, while leadership ensures the company knows what sensitive data it has, where it is stored, and who can access it.

### 1. Know What Information Is Sensitive

Cover customer data, employee data, financial records, contracts, credentials, intellectual property, internal strategy, security information, and regulated records.

Employees cannot protect information they do not recognize.

### 2. Use the Minimum Necessary Data

Teach staff to ask whether they need the information, whether the recipient needs all of it, and whether sensitive fields can be removed, masked, or summarized.

### 3. Share Files and Cloud Links Safely

Include recipient verification, link permissions, external collaborators, public links, view-only access, expiration dates, shared folders, and misdirected emails.

### 4. Use Approved Tools and AI Services

Cover personal email, personal cloud storage, unapproved applications, browser extensions, file-transfer tools, third-party integrations, and generative AI.

Employees should understand that placing company information into an external tool may be a form of data disclosure.

### 5. Leadership Assurance: Establish Data Governance

Executives and key staff should ensure the company has:

- A practical data-classification system
    
- Identified owners for important data
    
- Rules for collecting, using, storing, sharing, retaining, and deleting data
    
- Approved storage locations
    
- Encryption requirements where appropriate
    
- Procedures for granting and reviewing access
    
- Rules for handling regulated, personal, or confidential information
    
- A process for securely disposing of information that is no longer needed
    

The classification system must be simple enough that staff can use it. A complicated policy that nobody follows is not a control.

### 6. Leadership Assurance: Control Cloud, Third-Party, and AI Risk

Leadership should ask:

- Which cloud services and AI tools are approved?
    
- Does the company know which vendors store or process its sensitive data?
    
- Are security and privacy requirements included in vendor contracts?
    
- Are third-party applications reviewed before being connected to company accounts?
    
- Are public file-sharing links monitored or restricted?
    
- Is there a written policy for the use of generative AI?
    
- Can the company identify where its critical data is stored?
    
- Are access and sharing permissions reviewed periodically?
    

NIST CSF 2.0 includes cybersecurity supply-chain risk management within the Govern function, reflecting the need to manage risks from technology providers, service providers, and other third parties. ([NIST Publications](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf?utm_source=chatgpt.com "The NIST Cybersecurity Framework (CSF) 2.0"))

**Evidence to request:** data inventories, classification policies, approved-application lists, vendor inventories, contract templates, cloud-sharing reports, and AI-use policies.

# Module 4: Keep Devices and Software Secure

**Objective:** Staff avoid weakening their devices, while leadership ensures that the company identifies, patches, hardens, monitors, and protects its technology.

### 1. Install Updates and Restart Promptly

Teach why updates matter, why restarts may be required, why unsupported software is risky, and how to distinguish legitimate update instructions from fake update prompts.

### 2. Use Only Approved Devices and Software

Cover unapproved applications, personal devices, browser extensions, macros, scripts, unknown USB devices, and free software downloaded from untrusted websites.

### 3. Protect Devices in and Outside the Office

Include screen locking, physical security, travel, home working, public Wi-Fi, shoulder surfing, lost devices, and unauthorized family or colleague use.

### 4. Recognize and Report Unusual Device Behavior

Teach staff to report pop-ups, redirects, security warnings, unexpected slowness, missing files, disabled security tools, unusual applications, and suspected malware.

### 5. Leadership Assurance: Maintain Asset, Patch, and Vulnerability Management

Executives and key staff should ensure the company has:

- An inventory of devices, servers, applications, cloud services, and operating systems
    
- A process for identifying unsupported or end-of-life technology
    
- Automated patching where practical
    
- Defined deadlines for applying critical and high-risk updates
    
- Regular vulnerability scanning
    
- A process for prioritizing and remediating findings
    
- Named owners for remediation
    
- A process for approving, documenting, and expiring risk exceptions
    
- Secure configuration standards for important systems
    

CISA’s Cyber Essentials guidance specifically recommends automatic updates where possible, replacing unsupported technology, and deploying patches quickly. CIS Controls are also designed as a prioritized set of safeguards against prevalent attacks, with Implementation Group 1 positioned as a starting point for organizations of all sizes. ([CISA](https://www.cisa.gov/resources-tools/resources/cyber-essentials?utm_source=chatgpt.com "Cyber Essentials"))

### 6. Leadership Assurance: Ensure Protective and Detective Controls Are Operating

Leadership should ask:

- Are all company devices covered by endpoint protection or endpoint detection and response?
    
- Are mobile devices managed?
    
- Are security configurations standardized?
    
- Are email and web-filtering protections in place?
    
- Are important system logs collected and reviewed?
    
- Are alerts monitored by someone with defined responsibility?
    
- Are there known devices or systems outside the company’s management tools?
    
- Are vulnerability and patching reports reviewed by management?
    

**Evidence to request:** asset inventories, patch-compliance reports, vulnerability-scan reports, unsupported-software lists, endpoint-protection coverage reports, security-configuration standards, and exception registers.

# Module 5: Report Incidents Fast and Respond Correctly

**Objective:** Staff report incidents quickly, while leadership ensures the company can detect, respond to, and recover from serious events.

### 1. Know What Counts as an Incident

Include suspicious messages, malicious links, exposed credentials, accidental data disclosure, misdirected emails, lost devices, malware warnings, unusual account activity, suspected fraud, and unauthorized access.

### 2. Know How to Report

Provide the actual reporting channels:

- Phishing-report button
    
- Security email address
    
- Service desk
    
- Emergency phone number
    
- Manager escalation route
    
- Backup communication method
    

### 3. Take the Correct First Actions

Teach staff to stop the risky activity, avoid further interaction, report immediately, preserve evidence, and follow instructions.

Do not tell every employee to delete messages, wipe devices, power off systems, or investigate the incident themselves.

### 4. Report Mistakes Without Delay or Shame

Employees should understand that quick reporting is responsible behavior. Hiding an incident or delaying disclosure is the greater risk.

### 5. Leadership Assurance: Prepare and Exercise the Incident Response Plan

Executives and key staff should ensure the company has:

- A written incident response plan
    
- Defined roles and decision-making authority
    
- Internal and external contact lists
    
- Legal, privacy, insurance, communications, and regulatory escalation procedures
    
- Procedures for involving managed service providers and other critical vendors
    
- Alternative communication methods
    
- A process for preserving evidence
    
- Regular tabletop exercises
    
- A process for capturing and implementing lessons learned
    

CISA’s small-business guidance explicitly states that leadership should review and approve the incident response plan before an incident occurs, and NIST’s current incident-response guidance treats response as part of broader cybersecurity risk management rather than an isolated technical activity. ([CISA](https://www.cisa.gov/cyber-guidance-small-businesses?utm_source=chatgpt.com "Cyber Guidance for Small Businesses"))

### 6. Leadership Assurance: Ensure Backups and Recovery Are Proven

Executives should not ask only, “Do we have backups?” That question is too weak.

They should ask:

- What systems and data are backed up?
    
- How frequently are backups taken?
    
- Are critical backups protected from ransomware?
    
- Are offline, isolated, or otherwise protected copies maintained?
    
- Who can delete or alter backups?
    
- When was the last successful restoration test?
    
- How long would recovery take?
    
- How much data could the company afford to lose?
    
- Which business operations must be restored first?
    
- Can the company operate if email, cloud services, or core systems are unavailable?
    

CISA recommends regular automated backups, protections for backups, and backup plans aligned with the organization’s recovery objectives. ([CISA](https://www.cisa.gov/resources-tools/resources/cyber-essentials?utm_source=chatgpt.com "Cyber Essentials"))

**Evidence to request:** approved incident response plans, exercise reports, call trees, backup coverage reports, restoration-test results, recovery objectives, and post-incident improvement records.

# The Critical Design Decision

Do not require regular office staff to memorize all management controls. That would dilute the behavioral lessons and make the course feel irrelevant.

Use visible labels throughout the course:

- **Everyone Must Know**
    
- **Managers and Process Owners Must Ensure**
    
- **Executives Must Verify**
    

A finance employee may need to understand payment-verification procedures in detail. An HR manager may need to understand access removal and personal-data handling. An executive may need to understand backup restoration tests and vulnerability remediation metrics. A general office employee only needs awareness of those company controls, not operational mastery.

The final course should teach three different responsibilities:

> **Employees prevent and report.**  
> **Managers enforce secure processes.**  
> **Executives verify that the organization is prepared.**

That framing makes the course materially stronger. It stops being a basic awareness course and becomes a compact cybersecurity governance course for SMEs.