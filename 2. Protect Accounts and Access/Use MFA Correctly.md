---
icon: triangle-right
order: "90"
---
Here we cover MFA prompts, authentication codes, push-notification fatigue, passkeys, hardware security keys, and unexpected login requests.

For this subsection, an important note is that not all MFA is not all equal: NIST now emphasizes phishing-resistant authentication for higher-assurance use cases, and CISA recommends phishing-resistant MFA like passkeys wherever possible.

<br>
<br>

![[Man-holding-mobile-phone.jpg]]

<br>
<br>


### Learning Objective

By the end of this section, learners should understand what multifactor authentication is, why it matters, how attackers try to bypass it, and how to respond correctly to MFA prompts, codes, recovery requests, and suspicious login activity.

Employees should learn one core behavior:

**Only approve an MFA request when you are personally trying to log in.**

Managers and executives should learn one core assurance question:

**Is MFA enabled, monitored, and configured correctly across the company’s critical systems?**

### Why This Matters

Multifactor authentication, or MFA, adds another powerful layer of protection when logging into an account. Instead of relying only on a password, MFA requires another proof that the user is legitimate.

**That second proof may be:**

- A code from an authenticator app
    
- A push approval on a trusted device
    
- A hardware security key
    
- A passkey
    
- A biometric check on a trusted device
    
- A one-time code sent by SMS or phone call
    

MFA is important because passwords can be stolen, guessed, reused, leaked, or captured through phishing. If an attacker gets a password, MFA can help stop them from logging in.

But MFA only works if people use it correctly.

Attackers know this. They often try to trick employees into approving access, sharing codes, or responding to fake login prompts. That means MFA is not just a technical control. It is also a behavior that employees must understand.

### Core Rule

The safest employee rule is:

**Never approve a login, share a code, or confirm an MFA request unless you personally started the login.**

If an MFA prompt appears unexpectedly, treat it as suspicious.

Do not approve it. Do not ignore repeated prompts. Report it.

### What MFA Protects Against

**MFA helps protect against:**

- Stolen passwords
    
- Password reuse
    
- Credential leaks from other websites
    
- Some phishing attempts - MFA can still be phished, watch out!
    
- Brute-force login attempts - passwords can be cracked or guessed, MFA adds an exponential layer of complexity
    
- Password spraying - this is when an attacker finds a password, and tries to use it everywhere knowing users re-use passwords on different sites.
    
- Unauthorized remote access
    
- Attempts to access email, cloud storage, finance systems, HR systems, and admin accounts
    

**MFA is especially important for:**

- Email accounts
    
- Cloud storage
    
- Remote access and VPN
    
- Finance systems
    
- HR and payroll systems
    
- Administrator accounts
    
- Password managers
    
- Customer data platforms
    
- Business-critical applications
    

If an attacker gets access to email, they may be able to reset passwords for other systems. That is why email should always be considered a high-risk account.

### MFA Is Not Magic

MFA reduces risk, but it does not remove risk.

**Attackers may still try to bypass MFA by:**

- Sending fake login pages or with fake imposter websites online
    
- Asking employees to share MFA codes
    
- Bombarding users with approval prompts
    
- Calling or messaging users while pretending to be IT support
    
- Stealing session cookies
    
- Tricking help desks into resetting MFA
    
- Using compromised devices
    
- Targeting weaker MFA methods such as SMS
    
- Convincing users to approve a login they did not start
    

The lesson is simple:

**MFA is powerful, but careless approval can still open the door.**

### Common MFA Methods

#### 1. Authenticator App Code

The employee opens an approved authenticator app and enters a temporary code.

Safe behavior:

- Enter the code only when you personally started the login.
    
- Never read or send the code to anyone.
    
- Never enter the code into a page opened from a suspicious email link.
    

**Risk:**

An attacker may call or message pretending to be IT and ask for the code.

**Correct response:**

Do not share it. Report the request.

#### 2. Push Notification

The employee receives a prompt asking them to approve or deny a login.

**Safe behavior:**

- Approve only if you personally started the login.
    
- Check the location, application, and device information if shown.
    
- Deny unexpected requests.
    
- Report repeated or suspicious prompts.
    

**Risk:**

Attackers may use “push bombing” or “MFA fatigue,” where they repeatedly trigger prompts until the user approves one by accident or frustration.

**Correct response:**

Do not approve. Deny and report.

#### 3. Number Matching

The login screen shows a number, and the employee must enter or match that number in the authenticator app.

Safe behavior:

- Only enter the number when you are actively logging in.
    
- If a number appears unexpectedly, do not interact with it.
    
- Report unexpected prompts.
    

**Benefit:**

Number matching reduces the risk of accidental approval because the user must match the login request they actually started.

#### 4. SMS or Voice Code

The employee receives a code by text message or phone call.

Safe behavior:

- Use it only when logging in yourself.
    
- Never share the code.
    
- Report unexpected codes.
    

**Risk:**

SMS and voice methods can be weaker than authenticator apps, passkeys, or hardware security keys because phone numbers can be targeted through SIM swap or social engineering attacks.

Correct response:

Use stronger MFA methods when the company provides them.

#### 5. Security Key or Passkey

A physical security key or passkey uses a stronger authentication method that is more resistant to phishing.

Safe behavior:

- Use the approved security key or passkey when available.
    
- Protect the device or key physically.
    
- Report loss immediately.
    
- Follow company setup and recovery procedures.
    

**Benefit:**

Phishing-resistant methods are stronger because they are designed to prevent users from accidentally authenticating to a fake website.



### What Employees Should Do

**Employees should:**

1. Enable MFA wherever company policy requires it.
    
2. Use the company-approved MFA method.
    
3. Approve MFA prompts only when they personally started the login.
    
4. Deny unexpected prompts.
    
5. Report repeated prompts or unusual login attempts.
    
6. Never share MFA codes with anyone.
    
7. Never approve a prompt because someone on the phone told them to.
    
8. Use number matching correctly when available.
    
9. Use passkeys or security keys when the company provides them.
    
10. Report lost phones, security keys, or authentication devices immediately.
    
11. Keep backup recovery methods secure.
    
12. Follow the company’s process when changing phones or replacing MFA devices.
    

### What Employees Should Never Do

Employees should never:

- Approve an MFA request they did not initiate
    
- Share a one-time code by phone, email, chat, or text
    
- Send a screenshot of an MFA code or prompt
    
- Approve a prompt to “make it stop”
    
- Approve a login because someone claims to be IT
    
- Enter a code into a page opened from an unexpected email
    
- Use personal recovery methods unless approved by company policy
    
- Transfer MFA to a new device without following the official process
    
- Ignore repeated MFA prompts
    
- Treat MFA fatigue as a harmless annoyance
    

**An unexpected MFA prompt usually means one of two things:**

1. Someone entered your password.
    
2. Someone is trying to trick you into granting access.
    

Both require attention.

### The MFA Prompt Decision Rule

When an MFA prompt appears, ask:

1. Am I logging in right now?
    
2. Is this the system I am trying to access?
    
3. Does the location or device information make sense?
    
4. Did I expect this prompt?
    
5. Am I being pressured by someone to approve it?
    

If the answer to any of these is concerning, deny the request and report it.

### MFA Example Warning Cases

#### Example: Unexpected MFA Prompt

You are working normally and receive an MFA approval request on your phone.

You are not trying to log in.

**Unsafe response:** - Approving the request because it might be IT.

**Safe response:** - Deny the request and report it immediately.

**Why:**

The prompt may mean an attacker has your password and is trying to complete the login.

#### Example: MFA Fatigue Attack

You receive several MFA prompts in a row. Then someone calls claiming to be from IT.

They say: - “We are testing the login system. Please approve the next prompt so we can close the ticket.”

**Unsafe response:** - Approving the prompt to stop the notifications or help IT.

**Safe response:** - Do not approve. End the call and contact IT or security through the official company channel.

**Why:**

Attackers may combine repeated prompts with a fake support call to pressure the user into approving access.

#### Example: Shared MFA Code

A coworker sends a message: - “I am locked out. Can you send me the code that just came to your phone?”

**Unsafe response:** - Sharing the code because the coworker seems to need help.

**Safe response:** - Do not share the code. Tell the coworker to contact IT through the official support process.

**Why:**

MFA codes are authentication secrets. Sharing them defeats the purpose of MFA.

#### Example: Login From a Suspicious Link

You receive an email saying your cloud account needs to be verified. You click the link and see what looks like a normal login page. After entering your password, the page asks for your MFA code.

**Unsafe response:** - Entering the code because the page looks legitimate.

**Safe response:** - Close the page, do not enter the code, and report the message.

**Why:**

An attacker may be trying to capture the password and MFA code in real time.

### MFA and Social Engineering

Attackers often use social pressure to defeat MFA.

**Common attacker claims include:**

- “This is IT support.”
    
- “We are testing the system.”
    
- “Your account will be locked if you do not approve.”
    
- “Approve the next prompt to verify your identity.”
    
- “Send me the code so I can fix your account.”
    
- “This is required for the migration.”
    
- “Your manager asked us to complete this today.”
    

The correct response is always the same:

**Do not approve or share anything unless you initiated the login through the normal trusted process.**

### MFA Recovery Is Also a Risk

MFA recovery is the process used when someone loses access to their MFA device, changes phones, loses a security key, or cannot receive codes.

This process must be secure because attackers may try to abuse it.

**Employees should:**

- Report lost or stolen authentication devices immediately.
    
- Use only official recovery procedures.
    
- Never accept MFA reset instructions from an unexpected caller.
    
- Never bypass MFA recovery steps because of urgency.
    
- Keep backup codes secure if the company uses them.
    
- Avoid storing backup codes in email, screenshots, or unsecured files.
    

Managers and executives should understand that weak recovery processes can defeat strong MFA.

If an attacker can trick the help desk into resetting MFA, the original MFA protection may be bypassed.

### Manager Responsibilities

Managers should:

- Reinforce that MFA prompts must only be approved when initiated by the user.
    
- Never pressure staff to share codes or approve prompts.
    
- Make sure new staff complete MFA setup correctly.
    
- Ensure staff know how to report unexpected prompts.
    
- Support employees who stop work to report suspicious login activity.
    
- Escalate repeated MFA prompt reports quickly.
    
- Make sure departing staff lose access promptly.
    
- Avoid normalizing shortcuts such as shared MFA devices or shared accounts.
    

Managers should treat unexpected MFA prompts as security events, not user inconvenience.

### Executive and Key Staff Assurance Points

Executives and key staff do not need to configure MFA personally, but they do need to verify that the organization’s MFA program is complete and practical.

Leadership should verify that MFA is required for:

- Email
    
- Cloud storage
    
- Remote access
    
- VPN
    
- Finance systems
    
- HR and payroll systems
    
- Password managers
    
- Administrator accounts
    
- Customer data platforms
    
- Business-critical applications
    

**Leadership should also verify that:**

- MFA is enforced, not optional
    
- MFA coverage is measured
    
- Admin and executive accounts have stronger protections
    
- Phishing-resistant MFA is used where practical
    
- Number matching is enabled for push-based MFA where possible
    
- SMS-based MFA is not the preferred method for high-risk accounts
    
- Lost-device and MFA reset procedures include identity verification
    
- MFA bypass exceptions are documented and time-limited
    
- Suspicious MFA activity is logged and reviewed
    
- Employees are trained on MFA fatigue and fake IT-support calls
    

### Common Misconceptions

#### Misconception 1: “MFA means the account is safe.”

MFA greatly reduces risk, but attackers may still try to trick users, steal sessions, or abuse recovery procedures.

#### Misconception 2: “If I receive a prompt, I should approve it.”

Only approve prompts you personally initiated.

#### Misconception 3: “IT may ask for my MFA code.”

Legitimate IT support should not ask for your MFA code.

#### Misconception 4: “SMS MFA is just as strong as every other method.”

SMS MFA is better than no MFA, but stronger options such as authenticator apps, passkeys, and hardware security keys are preferred for higher-risk accounts.

#### Misconception 5: “Repeated MFA prompts are just a system glitch.”

Repeated unexpected prompts may be a push-bombing attack and should be reported.

### Key Takeaway

MFA is one of the most important protections for company accounts, but it must be used correctly.

Employees should only approve MFA prompts they personally initiated, should never share codes, and should report unexpected prompts immediately. Managers should reinforce correct behavior and avoid shortcuts. Executives should verify that MFA is enforced across critical systems, configured strongly, and supported by secure recovery procedures.

**MFA protects the company only when people do not hand the second factor to the attacker.**