---
icon: triangle-right
order: "60"
---
This section can be thought of as the **joiner–mover–leaver** control lesson. It includes identity management, authentication, access control, account management, authorized users, role membership, privileges, account managers, and removal/disablement of accounts. 

<br>
<br>

![[Checklist-guy.jpg]]

<br>
<br>

### Learning Objective

By the end of this section, we will understand that accounts must be managed from creation to removal. Employees, managers, HR, IT, and executives all have a role in making sure access is created properly, changed when roles change, reviewed regularly, and removed when no longer needed.

**Employees should learn this core behavior:** - Your access should match your current role, and unnecessary access should be reported.

**Managers and executives should learn this assurance principle:** - Every account should have an owner, a purpose, an approval trail, and a removal process.

### Why This Matters

An account is a doorway into the company.

When accounts are created, changed, forgotten, or left active after someone leaves, attackers gain opportunities. A company may have strong passwords and MFA, but still be exposed if it does not know who has accounts, what those accounts can access, and whether those accounts are still needed.

**Poor account lifecycle management can lead to:**

- Former employees retaining access
    
- Contractors keeping access after a project ends
    
- Employees keeping permissions from old roles
    
- Dormant accounts being hijacked
    
- Shared accounts being used without accountability
    
- Administrator accounts being left active unnecessarily
    
- Temporary accounts becoming permanent
    
- External users remaining inside cloud folders or systems
    
- Accounts existing without a clear owner
    
- Delayed removal after resignation or termination
    

**The risk is simple:**

If the company does not manage accounts throughout their lifecycle, access quietly accumulates.

That accumulated access becomes a security weakness.

### Core Rule

**Every account should be managed through four stages:**

1. **Create access carefully**
    
2. **Change access when roles change**
    
3. **Review access regularly**
    
4. **Remove access when it is no longer needed**
    

This is often called the **joiner, mover, and leaver process**.

- **Joiner:** someone joins the company or needs new access.
    
- **Mover:** someone changes role, department, project, location, or responsibility.
    
- **Leaver:** someone leaves the company, ends a contract, or no longer needs access.
    

The process must cover employees, executives, temporary staff, contractors, vendors, interns, service providers, and administrators.

### Stage 1: Create Accounts Carefully

When a new person joins the company, they need access to systems, files, applications, devices, and communication tools.

**A strong account creation process should answer:**

- Who is the person?
    
- What is their role?
    
- Who approved the access?
    
- Which systems do they need?
    
- What permission level is required?
    
- Is MFA required?
    
- Is the access temporary or permanent?
    
- Who owns the account?
    
- Who will review the access later?
    

Access should not be copied blindly from another employee unless the access is reviewed first.

**Example of weak account creation:**

“Give the new employee the same access as Sarah.”

**Risk:** - Sarah may have accumulated old permissions over several years. Copying her access may give the new employee far more access than needed.

**Better approach:** - Create access based on the new employee’s actual role and approved responsibilities.

### Stage 2: Change Access When Roles Change

Access must change when a person’s role changes.

This is one of the most commonly missed steps.

**Examples:**

- An employee moves from finance to sales.
    
- A manager transfers to another department.
    
- A contractor moves to a new project.
    
- An executive changes responsibilities.
    
- A staff member receives temporary project access.
    
- A user receives temporary administrator rights.
    
- A team member stops supporting a client account.
    
- A person changes location or business unit.
    

The mistake companies often make is adding new access without removing old access.

This creates access creep.

### What Is Access Creep?

Access creep happens when people accumulate permissions over time.

**For example:**

An employee starts in customer support, moves to operations, later joins finance, and then becomes a manager. If old access is never removed, that person may still have access to customer support tools, operations folders, finance data, and management files.

The employee may not have bad intentions. The problem is that their account now has more access than their current role requires.

If that account is compromised, the attacker inherits all of that unnecessary access.

**The correct rule is:**

**When new access is added, old access should be reviewed and removed if it is no longer needed.**

### Stage 3: Review Access Regularly

Access should not be approved once and forgotten.

**Regular access reviews help the company find:**

- Former employees with active accounts
    
- Contractors who still have access
    
- Users with outdated permissions
    
- Dormant accounts
    
- Shared accounts
    
- Unnecessary administrator rights
    
- External users in cloud folders
    
- Third-party app access
    
- Users with access to sensitive data they no longer need
    
- Temporary access that was never removed
    

Managers and system owners should participate in access reviews because they understand who actually needs access.

IT can produce the access list, but business owners must confirm whether the access still makes sense.

### Stage 4: Remove Access Promptly

Access should be removed when a person leaves the company, ends a contract, changes role, or no longer needs a system.

Leaver access removal should cover:

- Email
    
- Cloud storage
    
- Business applications
    
- Remote access
    
- VPN
    
- Password manager access
    
- Shared mailboxes
    
- Collaboration tools
    
- CRM systems
    
- Finance systems
    
- HR systems
    
- Admin accounts
    
- Mobile devices
    
- Third-party apps
    
- Vendor portals
    
- Physical access where relevant
    

For higher-risk departures, access removal may need to happen before or at the exact time the person is notified.

For normal departures, the company should still have a defined schedule for disabling access.

**The dangerous assumption is:**

“IT probably handled it.”

Account removal should be documented and verified.

### Types of Accounts That Need Lifecycle Management

Account lifecycle management should cover more than standard employee accounts.

#### 1. Employee Accounts

These are normal staff accounts for email, systems, devices, and applications.

**Risk:** - Employees may accumulate old permissions or keep access after leaving.

**Required control:** - Create, review, update, and remove access based on current role.

#### 2. Executive Accounts

Executive accounts are high-value targets because they may contain sensitive communications, authority, and business data.

**Risk:** - Attackers can impersonate executives or access strategic information.

**Required control:** - Use stronger authentication, careful delegation, monitoring, and rapid access removal when needed.

#### 3. Contractor and Temporary Staff Accounts

Contractors often need access for a specific project or time period.

**Risk:** - Their access may remain active long after the project ends.

**Required control:** - Use expiration dates, named accounts, approved access levels, and project-end access removal.

#### 4. Vendor and Third-Party Accounts

External providers may need access to systems, portals, cloud environments, or data.

**Risk:** - External accounts may be unmanaged, overprivileged, or forgotten.

**Required control:** - Assign an internal owner, limit access, require MFA where possible, and review access periodically.

#### 5. Administrator and Privileged Accounts

Admin accounts can change systems, create users, modify security settings, and access sensitive data.

**Risk:** - A compromised admin account can cause major damage.

**Required control:** - Limit admin accounts, use separate named admin accounts, require strong MFA, monitor activity, and review privileges frequently.

#### 6. Shared or Generic Accounts

Shared accounts are accounts used by more than one person.

**Risk:** - The company cannot reliably know who performed an action.

**Required control:** - Eliminate wherever possible. If unavoidable, document the reason, protect the credentials, limit access, monitor usage, and review regularly.

#### 7. Service Accounts

Service accounts are used by systems, applications, or automated processes rather than people.

**Risk:** - They may have powerful access and may be forgotten because no person logs in interactively.

**Required control:** - Assign an owner, document the purpose, limit privileges, rotate credentials where appropriate, and review periodically.

#### 8. Emergency or Break-Glass Accounts

These are used for rare emergency access.

**Risk:** - They can become hidden backdoors if not controlled.

**Required control:** - Protect strongly, monitor usage, restrict access, document every use, and review regularly.

### What Employees Should Do

**Employees should:**

1. Use only their own approved accounts.
    
2. Complete account setup using official company instructions.
    
3. Report if they cannot access a system they genuinely need.
    
4. Report if they have access they no longer need.
    
5. Avoid using old access from a previous role.
    
6. Avoid requesting access “just in case.”
    
7. Avoid using someone else’s account to get around access delays.
    
8. Report unexpected access to sensitive folders or systems.
    
9. Report unexpected password reset emails or login alerts.
    
10. Follow company instructions when changing phones, devices, or authentication methods.
    
11. Return devices and access tools when leaving a role or project.
    
12. Use approved channels for access requests and changes.
    

### Manager Responsibilities

Managers are central to account lifecycle management because they know what their team members actually need.

**Managers should:**

- Request access for new staff based on role requirements
    
- Avoid copying access from another employee without review
    
- Approve access only when there is a clear business need
    
- Notify IT or the account owner when someone changes roles
    
- Confirm old access is removed when new access is granted
    
- Ensure contractors and temporary staff have access end dates
    
- Review team access periodically
    
- Confirm access is removed when staff leave
    
- Make sure shared folders and project spaces are cleaned up after projects
    
- Escalate urgent leaver access removal when needed
    
- Ensure high-risk access is approved by the correct owner
    
- Support employees who report unnecessary access
    

Managers should not treat account access as an administrative detail. Access is a business risk decision.

### HR Responsibilities

HR often owns the employment status information that drives account lifecycle events.

**HR should ensure that IT, security, and relevant managers are informed when:**

- A person is hired
    
- A person changes role
    
- A person changes department
    
- A person goes on extended leave
    
- A person is terminated
    
- A contractor engagement ends
    
- A temporary worker’s assignment ends
    
- A person’s departure date changes
    

The timing matters.

If IT learns about a departure late, access may remain active longer than it should.

### IT and Security Responsibilities

IT and security teams usually implement account lifecycle controls.

**They should:**

- Create accounts through approved processes
    
- Apply role-based access where possible
    
- Enforce MFA
    
- Disable accounts promptly when required
    
- Remove or modify access when roles change
    
- Maintain account inventories
    
- Identify dormant accounts
    
- Review privileged accounts
    
- Monitor suspicious login activity
    
- Support access reviews
    
- Document exceptions
    
- Manage service, emergency, and admin accounts carefully
    

IT should not be forced to guess who needs access. Business owners and managers must provide approval and context.

### Executive and Key Staff Assurance Points

Executives and key staff should verify that account lifecycle management is working across the company.

**Leadership should ensure the company has:**

- A documented joiner, mover, and leaver process
    
- Clear ownership between HR, managers, IT, and security
    
- Defined timelines for account creation, change, and removal
    
- Access request and approval records
    
- Periodic access reviews
    
- Contractor and vendor access controls
    
- Privileged-account controls
    
- Dormant-account reviews
    
- Shared-account reduction plans
    
- MFA coverage for critical accounts
    
- A process for emergency access
    
- A process for service account ownership and review
    
- Evidence that access removals actually happen
    

The leadership question is:

**Can we prove that access changes when people’s business need changes?**

#### Example: The Former Employee Account

An employee leaves the company. Their email is disabled, but their account in a cloud project management tool remains active. The account still has access to client files and internal discussions.

**Risk:** - If the former employee logs in, or if an attacker compromises the account later, company information may be exposed.

**Correct process:** - Offboarding should include all business applications, not only email. The company should maintain a list of systems and confirm access removal from each relevant platform.

#### Example: The Role Change

An employee moves from finance to operations. They receive access to operations systems but keep access to finance folders and payment records.

**Risk:** - The employee now has more access than their current role requires. If their account is compromised, the attacker may access both finance and operations information.

**Correct process:** - Role changes should trigger a review of old access. New access should be added, and unnecessary old access should be removed.

#### Example: Contractor Access

A marketing contractor is given access to a cloud folder for a three-month project. Six months later, the contractor still has access.

**Risk:** - External access remains open after the business need ended.

**Correct process:** - Contractor access should have an owner, a business purpose, and an end date. Access should be removed when the project ends.

#### Example: Dormant Account

A system contains several accounts that have not logged in for more than a year.

**Risk:** - Dormant accounts may go unnoticed if compromised. They may not be protected as carefully as active accounts.

**Correct process:** - Dormant accounts should be reviewed, disabled, or removed unless there is a documented business reason to keep them.

### Key Takeaway

Account security is not finished when an account is created.

Accounts must be managed throughout their full lifecycle: when people join, when their roles change, when access is reviewed, and when they leave. Employees should report unnecessary access. Managers should approve and review access based on current business need. Executives should verify that account lifecycle controls are documented, measured, and working.

**Access that is no longer needed is not harmless. It is an open door.**
