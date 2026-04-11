
## Module 2 — Evolution of Cybersecurity

### Key Terms
Virus: malicious code that attaches to programs
       and spreads through infected files/disks
Worm: self-replicating program that spreads
      through networks automatically
Malware: umbrella term for all malicious software
         (viruses, worms, ransomware etc.)

### Brain Virus (1986)
- Created by: Alvi brothers
- Intent: track pirated medical software
- Spread: infected disks passed between computers
- Impact: slowed productivity globally
- CIA triad: Availability attacked
- Lesson: unintended consequences are just
          as damaging as intentional attacks

### Morris Worm (1988)
- Created by: Robert Morris
- Intent: measure size of internet
- Spread: network vulnerabilities, self-replicating
- Impact: 6,000 computers crashed (10% of internet)
- CIA triad: Availability attacked
- Lesson: one programming error = catastrophic damage

### CERTs (born from Morris Worm)
Computer Emergency Response Teams
→ First organized cybersecurity response structure
→ Modern equivalents: CISA, US-CERT, NCSC

### Pattern Noticed:
Early attacks → primarily targeted Availability
Spread because → no detection controls existed yet

## Digital Age Attacks

### LoveLetter Attack (2000)
- Creator: Onel De Guzman
- Method: email attachment "I Love You"
- Spread: automatically emailed itself to
  all contacts on victim's address book
- Impact: 45 million computers, $10 billion damages
- CIA triad: Confidentiality (credentials stolen)
- First example of: Social Engineering
- Prevention: email filtering + security awareness training

### Social Engineering
Manipulating humans instead of hacking systems
→ Exploits human error and trust
→ Responsible for 91% of cyberattacks today
→ Bypasses ALL technical security controls

Types:
- Phishing: fake emails
- Spear Phishing: targeted phishing
- Vishing: phone-based phishing
- Smishing: SMS-based phishing
- Pretexting: fake scenario manipulation
- Baiting: infected physical media left as bait

### Equifax Breach (2017)
- Target: credit reporting agency
- Stolen: 143 million records (40% of Americans)
- Data stolen: SSN, DOB, addresses (PII + SPII)
- Cause: multiple unpatched known vulnerabilities
- Fine: $575 million settlement
- CIA triad: Confidentiality
- Lesson: knowing about risk ≠ managing risk

### Attack Evolution Pattern:
1986-1988 → Availability attacks (nothing to steal)
2000-present → Confidentiality attacks (valuable data online)
Reason: internet growth = more valuable digital data

## Key Corrections and Additions

### Social Engineering Defense
Only defense = security awareness training
Technical tools CANNOT stop social engineering
because it bypasses humans, not systems

### Exponential Spread (LoveLetter)
Person A → emails 100 contacts
100 contacts → each emails 100 more
= millions infected in hours
LoveLetter spread FASTER than Morris Worm
despite Morris Worm needing no human action
Reason: exponential growth via contact lists

### Vulnerability Management (Equifax lesson)
4 steps:
1. Find vulnerabilities
2. Prioritize by risk level
3. Patch before attackers exploit them
4. Verify patches worked
Knowing risk ≠ managing risk
Unpatched known vulnerability = worst kind

### CIA Attack Shift — Corrected
Brain Virus 1986 → Availability
Morris Worm 1988 → Availability
LoveLetter 2000 → Confidentiality ← NOT Availability
Equifax 2017 → Confidentiality
Reason: valuable data moved online between 1988-2000

## Why Organizations Fail at Basic Security

Root cause: Misaligned incentives

Security team → wants to fix vulnerabilities
Business team → wants to ship products on time
Management → wants quarterly profits

Result: security gets deprioritized repeatedly
until a breach makes it impossible to ignore

### The Solution: CISO Role
Chief Information Security Officer
→ Sits at executive level
→ Translates security risk into business language
→ Aligns security with business incentives

### How Analysts Should Communicate Risk:
❌ Technical: "CVE-2024-1234, CVSS score 9.8"
✅ Business: "This vulnerability could expose
   customer data and cost $575M in fines — 
   we can fix it in 48 hours"

Key insight:
Technical problems → technical solutions
Organizational problems → communication + alignment

## The 8 CISSP Security Domains

Key insight: Gaps in one domain affect ALL domains
All domains are interconnected

### Domain 1 — Security and Risk Management
Focus: goals, risk mitigation, compliance, law
Examples: updating HIPAA policies, risk assessments
Key terms: compliance, business continuity, risk mitigation

### Domain 2 — Asset Security  
Focus: securing + disposing of digital/physical assets
Examples: proper server wiping before disposal
Key connection: Sean's eBay server = Domain 2 failure

### Domain 3 — Security Architecture & Engineering
Focus: building security into systems
Examples: configuring firewalls, implementing IDS
Firewall = monitors + filters network traffic
(like a bouncer checking everyone at the door)

### Domain 4 — Communication & Network Security
Focus: securing networks and communications
Examples: preventing unsecured WiFi use
Risk: Man-in-the-Middle attacks on public WiFi
