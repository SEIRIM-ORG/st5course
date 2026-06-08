---
icon: triangle-right
order: "80"
---
In addition to root security, shared accounts and logins also negatively affect business accountability as they prohibits traceability, access control, and incident response. Not to mention drastically increasing data loss when a shared account is compromised.

What we refer to here are shared passwords, shared accounts, lending active sessions, sending credentials through chat, sharing MFA codes, and allowing another person to use one's account.

<br><br>
![[Quizzical-folks.jpg]]
*Don't do it!*
<br>
<br>


### Learning Objective

By the end of this module, learners will understand why account sharing is dangerous, what counts as an authentication method, and how to respond when someone asks them to share access.

Employees should learn this core behavior:

**Never let another person use your account, password, MFA code, device approval, passkey, security key, or recovery method.**

Managers and executives should learn this assurance principle:

**Every person should have their own account, and high-risk access should be traceable to a specific individual.**

### Why This Matters

A company account is not just a login. It is a digital identity.

When an employee uses a company account, that account may allow access to email, files, customer data, finance systems, HR records, business applications, administrative tools, or confidential information.

If accounts are shared, the company loses control over who did what.

That creates serious problems:

- Nobody can reliably identify who performed an action.
    
- Former employees may still know the password.
    
- Sensitive data may be accessed by people who no longer need it.
    
- MFA may be weakened or bypassed.
    
- Suspicious activity becomes harder to investigate.
    
- Access cannot be removed cleanly when someone leaves.
    
- A single compromised shared account can expose more people, systems, and data.
    
- Employees may be blamed for actions they did not perform.
    
- Attackers can hide behind “normal” shared-account behavior.
    

The issue is not only secrecy. It is accountability, access control, and incident response.

A company cannot protect what it cannot trace.

### Core Rule

Every employee should use their own approved account and authentication method.

Do not share:

- Passwords
    
- MFA codes
    
- MFA push approvals
    
- Passkeys
    
- Security keys
    
- Recovery codes
    
- Device unlock PINs
    
- Password manager access
    
- Browser profiles
    
- Active sessions
    
- Remote access credentials
    
- Admin credentials
    
- One-time login links
    

The simple rule is:

**Your login proves you are you. Do not let anyone else use it.**

### What Counts as an Authentication Method?

Authentication means proving your identity to access a system. It is not limited to passwords.

Authentication methods include:

#### 1. Passwords

A password proves that you know a secret.

Never share it with a coworker, manager, IT support person, vendor, contractor, or executive.

#### 2. MFA Codes

An MFA code is a temporary security code from an authenticator app, text message, email, or hardware device.

Never read it out, forward it, screenshot it, or type it into a system for someone else.

#### 3. MFA Push Approvals

A push approval confirms that you are allowing a login.

Never approve a login prompt unless you personally started the login.

#### 4. Passkeys

A passkey is tied to a device or account and is designed to confirm your identity.

Do not allow another person to use your passkey or device to access a system as you.

#### 5. Security Keys

A physical security key is a strong authentication method.

Do not lend it to another person.

#### 6. Recovery Codes

Recovery codes are backup access methods. They are powerful because they may bypass the normal login flow.

Store them only as approved by company policy. Never share them.

#### 7. Active Sessions

If you leave a system open and let someone else use it, that is account sharing.

Lock your device when stepping away.

#### 8. Password Manager Access

Your password manager may contain access to many systems.

Never share your master password, unlock method, or full vault access.

### Why Account Sharing Is Dangerous

#### 1. It Destroys Accountability

If three people use the same account, the company cannot reliably know which person performed a specific action.

**This matters for:**

- Financial approvals
    
- File changes
    
- Data exports
    
- Customer communications
    
- HR records
    
- System administration
    
- Legal or compliance investigations
    
- Incident response
    

If an account is shared, the audit trail becomes weak.

#### 2. It Makes Offboarding Unsafe

When someone leaves the company, their access should be removed.

If they used their own account, the company can disable that account.

If they knew a shared password, the company may need to change the password everywhere it was used. If that does not happen quickly, the former employee may retain access.

Shared passwords make offboarding messy and risky.

#### 3. It Increases the Damage of Compromise

A shared account often has broader access than one person actually needs.

If an attacker compromises that account, they may gain access to more data, more systems, and more business functions than they would through a normal individual account.

#### 4. It Encourages Unsafe Storage

Shared credentials are often stored in unsafe places, such as:

- Spreadsheets
    
- Notes apps
    
- Shared documents
    
- Chat messages
    
- Email threads
    
- Screenshots
    
- Whiteboards
    
- Sticky notes
    

Once stored this way, the credential can be copied, forwarded, leaked, or forgotten.

#### 5. It Normalizes Security Shortcuts

When a team gets used to shared access, employees may become more willing to share other authentication methods too.

That can lead to dangerous behavior such as:

- Sharing MFA codes
    
- Approving prompts for others
    
- Sending passwords through chat
    
- Using one admin account for multiple people
    
- Leaving systems unlocked for coworkers
    

A shortcut becomes a habit. A habit becomes a vulnerability.

### Common Examples of Unsafe Sharing

#### Example 1: Shared Team Login

A department uses one login for a vendor portal because it is easier than creating separate accounts.

**Risk:** - Everyone uses the same credentials. Nobody can identify who made a change. If someone leaves, the password may not be changed. If the account is compromised, the attacker may gain broad access.

**Better approach:** - Each user should have their own account with the correct access level. If a shared business function is needed, use role-based access or a shared mailbox with individual user access, not a shared password.

#### Example 2: Coworker Asks for a Password

**A coworker says:** - “I just need to check something quickly. Can you send me your login?”

**Risk:** - Even if the coworker is trustworthy, this breaks accountability and may violate company policy.

**Better approach:** - The coworker should request access through the approved process.

#### Example 3: Manager Asks for MFA Code

**A manager says:** - “I am trying to get into the system for the meeting. Send me the code that came to your phone.”

**Risk:** - The MFA code proves the identity of the account holder. Sharing it defeats the purpose of MFA.

**Better approach:** - The manager should use their own account or contact IT through the official support process.

#### Example 4: Executive Assistant Uses Executive Account

An executive assistant logs into the executive’s email account directly to manage messages.

**Risk:** - Actions performed by the assistant appear as if they were performed by the executive. If something goes wrong, the company cannot separate the two users’ activities.

**Better approach:** - Use delegated access or approved mailbox delegation, where the assistant has their own account and permissions are assigned properly.

#### Example 5: Shared Admin Account

Several IT or operations staff use one administrator account.

**Risk:** - This is especially dangerous because admin accounts can change systems, access sensitive data, disable controls, or create new users.

**Better approach:** - Each administrator should use their own named admin account. Privileged access should be limited, logged, and reviewed.

### Acceptable Alternatives to Account Sharing

Employees often share accounts because they are trying to solve a real business problem.

**Instead of sharing accounts, use:**

- Individual user accounts
    
- Role-based access
    
- Delegated mailbox access
    
- Shared mailboxes with named-user permissions
    
- Group-based permissions
    
- Approved password manager sharing features
    
- Temporary access requests
    
- Vendor-provided multi-user access
    
- Privileged access management for admin tasks
    
- Break-glass emergency accounts with strict controls
    
- Ticket-based approval for special access
    

The key principle:

**Share access through approved systems, not by sharing credentials.**

### Special Case: Shared Mailboxes

A shared mailbox is different from a shared password if it is configured properly.

**Bad approach:** - Everyone logs in using the same mailbox password.

**Better approach:** - Each employee logs in with their own account and is granted permission to access the shared mailbox.

This allows the company to remove access when someone changes roles or leaves, while still keeping individual accountability.

### Special Case: Emergency or Break-Glass Accounts

Some companies maintain emergency accounts for rare situations, such as loss of normal administrator access.

**These should not be used casually.**

**Emergency accounts should have:**

- Strong protection
    
- Limited access
    
- Strict approval requirements
    
- Secure storage of credentials
    
- Logging and monitoring
    
- Periodic review
    
- Immediate password rotation after use
    
- Management awareness
    

Emergency access is a controlled exception, not a normal workaround.

### What Employees Should Do

**Employees should:**

1. Use only their own approved account.
    
2. Keep passwords private.
    
3. Never share MFA codes or approve prompts for others.
    
4. Lock devices when stepping away.
    
5. Use delegated access instead of sharing accounts.
    
6. Request access through the official process when needed.
    
7. Report shared passwords or unsafe workarounds.
    
8. Refuse requests to share authentication methods, even from senior staff.
    
9. Report unexpected MFA prompts immediately.
    
10. Ask IT or the manager for a proper access solution when the current process creates pressure to share credentials.
    

### What Employees Should Never Do

Employees should never:

- Send passwords through email or chat
    
- Let a coworker use their account
    
- Let someone else use their unlocked device
    
- Share MFA codes
    
- Approve MFA prompts for another person
    
- Lend a security key
    
- Share passkeys or device unlock methods
    
- Store shared passwords in spreadsheets
    
- Use another person’s account to complete work
    
- Ask someone else for their login
    
- Use a shared admin account unless explicitly authorized under a controlled process
    
- Keep using access after their role no longer requires it
    

### What to Say When Someone Asks for Access

Employees need practical language. Many people share credentials because they do not want to sound unhelpful.

**Safe responses include:**

“I cannot share my login, but I can help you request proper access.”

“For security reasons, I cannot send passwords or MFA codes.”

“You will need your own account for that system.”

“I cannot approve an MFA prompt for someone else.”

“Let’s contact IT or the system owner to set up the correct permissions.”

“I can share the file through the approved method instead of giving account access.”

“I cannot use my account for your task because the action would be recorded under my name.”

These responses are professional, not obstructive.

## Manager Responsibilities

Managers set the tone. If managers ask for shared access, employees will assume sharing is acceptable.

Managers should:

- Never ask employees to share passwords or MFA codes
    
- Never pressure staff to use another person’s account
    
- Ensure team members have the access needed for their roles
    
- Escalate access gaps instead of creating workarounds
    
- Review whether team processes depend on shared credentials
    
- Remove access when staff change roles
    
- Make sure temporary staff and contractors receive proper individual access
    
- Report shared-account practices to IT or security
    
- Support employees who refuse to share authentication methods
    
- Make sure shared mailboxes, vendor portals, and team tools are configured properly
    

Managers should treat password sharing as a process failure, not an employee convenience issue.


### Questions Leaders Should Ask

Executives and key staff should ask:

1. Do all employees have their own accounts for major systems?
    
2. Do contractors have individual accounts, or are they using shared access?
    
3. Which systems still use shared logins?
    
4. Why do those shared logins exist?
    
5. Who owns the plan to remove or control them?
    
6. Are shared passwords stored in spreadsheets, documents, or chat tools?
    
7. Do administrators use named accounts?
    
8. Are executive assistants using delegated access rather than executive passwords?
    
9. Are former employees removed from shared access immediately?
    
10. Are access rights reviewed periodically?
    
11. Are emergency accounts monitored and reviewed?
    
12. Can we trace high-risk actions to a named individual?
    


### Common Misconceptions

#### Misconception 1: “It is safe if I trust the person.”

Trust is not the only issue. The company still loses accountability and control.

#### Misconception 2: “It is only temporary.”

Temporary credential sharing often becomes permanent. If access is needed, use the proper access request process.

#### Misconception 3: “It is fine because everyone on the team uses it.”

That is exactly the problem. If everyone uses the same account, no one can prove who did what.

#### Misconception 4: “Sharing MFA is harmless if the person already knows the password.”

No. MFA is meant to prevent access even when the password is known or stolen.

#### Misconception 5: “Senior staff are exempt.”

Senior staff are often higher-value targets. Their accounts need stronger controls, not weaker ones.

### Key Takeaway

Accounts and authentication methods are not personal conveniences. They are the company’s way of controlling access and proving accountability.

Employees should never share passwords, MFA codes, login sessions, passkeys, security keys, or recovery methods. Managers should fix access problems instead of creating shortcuts. Executives should verify that shared accounts are identified, controlled, and eliminated wherever possible.

**If everyone uses the same account, the company cannot know who did what.**