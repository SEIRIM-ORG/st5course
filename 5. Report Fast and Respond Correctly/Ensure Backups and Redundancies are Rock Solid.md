---
icon: triangle-right
order: "50"
---
### Goal

Backups and redundant systems are often the difference between a contained incident and a business crisis. 

Offline, encrypted backups of critical data and regular testing of backup availability and integrity are key capacities. Ransomware-resistant backups are paramount to set up correctly, including testing that backups are clean before restoration.

<br>
<br>

![[Lock-with-neon-block-on-blue.jpg]]

<br>
<br>



### Learning Objective

By the end of this section, we will understand why backups and redundancies are essential to incident response, what makes backups reliable, and what leadership must verify before an incident occurs.

Employees should learn this core behavior:

**Store work in approved systems, follow backup rules, and report anything that may affect recovery.**

Managers and executives should learn this assurance principle:

**The company must know what is backed up, how fast it can be restored, whether backups are protected from attack, and whether recovery has been tested.**

### Why This Matters

Backups are not just an IT detail. They are a business survival control.

During ransomware, malware, accidental deletion, insider misuse, system failure, cloud outage, hardware loss, or data corruption, the company may need to restore systems and data quickly.

**If backups fail, the company may face:**

- Extended downtime
    
- Lost customer data
    
- Lost financial records
    
- Lost operational records
    
- Interrupted payroll or billing
    
- Missed legal or contractual obligations
    
- Manual reconstruction of data
    
- Higher recovery costs
    
- Pressure to pay ransom
    
- Loss of customer trust
    

**The wrong assumption is:**

“We have backups, so we are fine.”

The better question is:

**Can we restore the right systems, with the right data, in the required time, after a real attack?**

### Core Rule

Backups and redundancies should be:

**Complete, protected, separate, tested, monitored, and aligned to business priorities.**

A backup that has never been tested is only a hope.

A backup that ransomware can delete is not reliable.

A backup that misses critical systems is not enough.

A backup that takes too long to restore may not meet business needs.

### Backup vs. Redundancy

Backups and redundancy are related, but they are not the same.

#### Backup

A backup is a recoverable copy of data or systems from a previous point in time.

**Backups help recover from:**

- Deleted files
    
- Corrupted data
    
- Ransomware
    
- Malware
    
- System failure
    
- Accidental changes
    
- Unauthorized changes
    

#### Redundancy

Redundancy means having additional systems, services, connections, or processes available so the business can continue operating if one fails.

**Redundancy may include:**

- Backup internet connection
    
- Spare laptops
    
- Alternative communication channel
    
- Secondary cloud service
    
- Manual payment process
    
- Alternate supplier or provider
    
- Failover server
    
- Emergency access process
    
- Paper-based fallback procedure
    

Backups help restore what was lost. Redundancy helps keep critical operations moving while recovery happens.

A strong incident response plan needs both.

### What Must Be Backed Up

The company should identify critical systems and data before an incident.

**Backups may need to cover:**

- File storage
    
- Email
    
- Cloud documents
    
- Customer records
    
- Financial systems
    
- Payroll records
    
- HR files
    
- Contracts
    
- Legal documents
    
- Accounting data
    
- Website content
    
- Databases
    
- Business applications
    
- Endpoint device data, where appropriate
    
- Configuration files
    
- System images
    
- Security logs
    
- Password manager recovery data
    
- Administrative documentation
    
- Critical SaaS data
    
- Key vendor records
    

Many SMEs assume that cloud systems are automatically backed up in the way the business needs. That assumption must be verified.

### Critical Recovery Questions

Leadership should know the answer to four basic questions.

#### 1. What do we need to recover first?

Not every system has the same priority.

**Critical systems may include:**

- Email and communication
    
- Customer service systems
    
- Financial systems
    
- Payroll
    
- Order processing
    
- Scheduling
    
- Manufacturing or operations systems
    
- Website or ecommerce platform
    
- Key shared folders
    
- Identity and access systems
    
- Backup administration tools
    

Recovery order should be based on business impact, not convenience.

#### 2. How much data can we afford to lose?

This is called the recovery point objective, or RPO.

Plain language:

**How far back can the restored data be before the loss becomes unacceptable?**

Example:

If backups run once per day, the company may lose up to one day of data.

For some systems, that may be acceptable. For others, it may be too much.

#### 3. How long can we afford to be down?

This is called the recovery time objective, or RTO.

Plain language:

**How quickly must the system be restored before business damage becomes serious?**

Example:

A payroll system may tolerate short downtime if payroll is not due today. An order-processing system may need faster recovery.

#### 4. Have we tested the restore?

A backup is only proven when it can be restored.

**Testing should confirm:**

- The backup exists
    
- The backup is complete
    
- The backup is readable
    
- The backup is clean
    
- The restore process works
    
- The restored system functions
    
- The right people know how to restore it
    
- The restore time meets business needs
    

### What Makes a Backup Reliable

A reliable backup program should include the following controls.

#### 1. Critical Data Is Included

The company must know which systems and data are included in backups.

If a critical system is not included, it may not be recoverable.

#### 2. Backups Run on a Defined Schedule

Backups should run often enough to match business needs.

Some systems may need daily backups. Others may need more frequent protection.

#### 3. Backups Are Protected from Ransomware

Backups should not be easy for attackers to delete, encrypt, or alter.

**Protection may include:**

- Offline backups
    
- Immutable backups
    
- Separate backup accounts
    
- Separate credentials
    
- Restricted administrator access
    
- MFA for backup administration
    
- Backup deletion protection
    
- Version history
    
- Access logging
    
- Segmented backup storage
    

If the same compromised account can delete both production data and backups, recovery is at risk.

#### 4. Backups Are Encrypted

Backup data may contain sensitive company, customer, employee, financial, or legal information.

Backups should be protected from unauthorized access.

#### 5. Backups Are Monitored

Failed backups must be detected.

The company should not discover during an incident that backups stopped running weeks ago.

**Monitoring should show:**

- Successful backups
    
- Failed backups
    
- Missed backup jobs
    
- Storage capacity issues
    
- Unusual deletion activity
    
- Backup integrity issues
    
- Restore test results
    

#### 6. Backups Are Tested

Restore testing should happen on a regular schedule.

**Testing should include:**

- Individual file restore
    
- Full folder restore
    
- Application restore
    
- Database restore
    
- SaaS data restore
    
- Server or system restore where relevant
    
- Recovery from a ransomware scenario
    
- Recovery with normal systems unavailable
    

A small file restore test is useful, but it is not enough for critical systems.

#### 7. Backups Are Documented

**The company should document:**

- What is backed up
    
- Where backups are stored
    
- How often backups run
    
- Who manages them
    
- Who can restore them
    
- How to request a restore
    
- What the recovery order is
    
- How long recovery should take
    
- What systems are not backed up
    
- What exceptions exist
    

Documentation should be accessible during an incident, even if normal systems are unavailable.

### Cloud and SaaS Backup Warning

Cloud services do not automatically remove the need for backup planning.

Cloud platforms may provide availability, version history, retention settings, or recycle bins, but those may not be enough for incident recovery.

**The company should verify backup and recovery for:**

- Email
    
- Cloud storage
    
- CRM
    
- Accounting systems
    
- HR systems
    
- Project management tools
    
- Chat systems
    
- Document platforms
    
- AI tools and workflow platforms
    
- Website platforms
    
- Ecommerce systems
    

**Key question:**

**If this cloud account were deleted, encrypted, locked, misconfigured, or compromised, how would we recover the data?**

### Redundancies the Business Should Consider

Backups restore data. Redundancies keep the business operating.

Important redundancies may include:

#### 1. Communication Redundancy

If email or chat is unavailable, the company needs another way to coordinate.

**Examples:**

- Emergency phone list
    
- SMS group
    
- Alternate messaging platform
    
- Printed contact sheet
    
- Executive call tree
    
- MSP emergency number
    

#### 2. Internet and Access Redundancy

If the office internet or remote access fails, critical staff may need alternatives.

**Examples:**

- Backup internet connection
    
- Mobile hotspot procedure
    
- Alternate office location
    
- Remote work fallback
    
- Secure emergency access process
    

#### 3. Device Redundancy

If devices are lost, encrypted, or quarantined, the company may need replacements.

**Examples:**

- Spare laptops
    
- Preconfigured emergency devices
    
- Device imaging process
    
- Rapid procurement process
    

#### 4. Vendor and Provider Redundancy

If a provider is unavailable during an incident, the company should know its options.

**Examples:**

- MSP escalation path
    
- Secondary support provider
    
- Cloud provider support contract
    
- Cyber incident response retainer
    
- Backup provider support contact
    

#### 5. Process Redundancy

If systems are down, the business may need temporary manual processes.

**Examples:**

- Manual order tracking
    
- Manual customer communication
    
- Manual payroll contingency
    
- Manual invoicing process
    
- Paper-based dispatch or operations procedure
    
- Offline access to critical instructions
    

Manual processes should be defined before the crisis, not invented during it.

### What Employees Should Do

**Employees should:**

1. Save work in approved company systems.
    
2. Avoid storing critical work only on local devices.
    
3. Avoid using personal cloud storage for company files.
    
4. Follow file naming, storage, and retention rules.
    
5. Report missing, corrupted, or accidentally deleted data quickly.
    
6. Report ransomware signs immediately.
    
7. Report if backup-related warnings appear.
    
8. Keep critical work out of unapproved tools.
    
9. Follow instructions during restore or recovery.
    
10. Use backup communication channels if normal systems are unavailable.
    

Employees are not responsible for designing the backup program, but their daily habits affect whether company data can be recovered.

### What Employees Should Not Do

**Employees should not:**

- Store important work only on a desktop or laptop
    
- Use personal drives as unofficial backup
    
- Use personal email to preserve work files
    
- Delete suspicious files before reporting
    
- Keep working in corrupted files
    
- Ignore files that are missing, renamed, or encrypted
    
- Move suspected infected files to shared folders
    
- Save sensitive data in unapproved tools
    
- Assume cloud storage means everything is recoverable
    
- Create unofficial copies of restricted data without approval
    

Unofficial backups can create security and privacy problems.

### Manager Responsibilities

**Managers should:**

- Know where their team’s critical data is stored.
    
- Ensure staff use approved storage locations.
    
- Identify critical spreadsheets, documents, databases, and tools.
    
- Avoid allowing key data to live only with one employee.
    
- Escalate business-critical systems for backup review.
    
- Support recovery testing when their team is involved.
    
- Define manual fallback procedures for critical workflows.
    
- Ensure contractors store work in approved systems.
    
- Help determine recovery priorities for their department.
    
- Report recurring data-loss or storage problems.
    

Managers should not assume IT knows every critical spreadsheet, workflow, or unofficial database used by the business.

### Executive and Key Staff Assurance Points

Executives and key staff must verify that backup and redundancy planning matches business reality.

**Leadership should ensure the company has:**

- Inventory of critical systems and data
    
- Backup coverage for critical systems
    
- Defined recovery priorities
    
- Defined RPOs and RTOs
    
- Offline or immutable backup protection where appropriate
    
- Encrypted backups
    
- Backup access controls
    
- MFA for backup administration
    
- Monitoring for backup failures
    
- Regular restore testing
    
- Documented recovery procedures
    
- SaaS and cloud backup review
    
- Backup provider or MSP responsibilities defined
    
- Redundancy for communications
    
- Redundancy for critical operations
    
- Manual fallback procedures
    
- After-incident recovery review
    

The leadership question is:

**If ransomware hit today, what could we restore, how far back would the data be, how long would it take, and who would do it?**

### Questions Leaders Should Ask

**Executives and key staff should ask:**

1. What are our most critical systems and data?
    
2. Are all critical systems backed up?
    
3. What systems are not backed up?
    
4. How often do backups run?
    
5. How much data could we lose?
    
6. How long would recovery take?
    
7. Are backups protected from ransomware?
    
8. Are backups offline, immutable, or otherwise protected from deletion?
    
9. Who has access to backup administration?
    
10. Is MFA required for backup access?
    
11. Are backup failures monitored?
    
12. When was the last restore test?
    
13. What exactly was restored during the test?
    
14. Did the restore meet business requirements?
    
15. Are cloud and SaaS systems covered?
    
16. Are backup responsibilities clear with the MSP or provider?
    
17. Do we have emergency communication methods if email is down?
    
18. Do we have manual fallback procedures for critical work?
    
19. Are backup and recovery procedures available during an outage?
    
20. Are recovery lessons tracked after tests or incidents?
    

### Backup and Incident Response Connection

During a cyber incident, backups must be handled carefully.

**Before restoring systems, the company may need to:**

- Confirm the incident is contained
    
- Identify when compromise began
    
- Avoid restoring infected or corrupted data
    
- Preserve evidence
    
- Reset compromised credentials
    
- Rebuild affected devices or servers
    
- Confirm the backup is clean
    
- Coordinate with legal, insurance, or incident response specialists
    
- Prioritize business-critical recovery
    

Restoring too quickly without understanding the incident can reintroduce the problem.

The goal is not just to restore fast. The goal is to restore safely.

### Simple Backup Standard

At a minimum, a SME should aim to have:

1. A list of critical systems and data
    
2. Approved storage locations for work files
    
3. Backups for critical systems
    
4. Backup monitoring
    
5. Protected backups that ransomware cannot easily delete
    
6. Encryption for sensitive backup data
    
7. MFA and limited access for backup administration
    
8. Regular restore testing
    
9. Recovery priorities
    
10. Emergency communication method
    
11. Manual fallback procedures for critical operations
    
12. Clear MSP or provider responsibilities
    

This does not need to be complex, but it must be real.


### Key Takeaway

Backups and redundancies are essential to recovery.

Employees should store work in approved systems and report data loss, corruption, ransomware signs, or storage problems quickly. Managers should know where critical team data lives and support recovery planning. Executives should verify backup coverage, ransomware protection, restore testing, recovery priorities, provider responsibilities, and business redundancies.

**Backups are not reliable because they exist. They are reliable because they are protected, tested, and able to restore the business when needed.**

---
