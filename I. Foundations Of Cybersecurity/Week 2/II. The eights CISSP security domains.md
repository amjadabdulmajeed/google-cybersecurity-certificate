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

## Domain Details — Additional Notes

### Domain 1 triggers:
→ Laws change (HIPAA, GDPR, PCI DSS)
→ New business operations begin
→ Security goals need redefining
Domain 1 = the "WHY" behind everything

### Domain 2 — Data Remanence
Residual data remaining after deletion
Simple delete = NOT enough
Solutions:
→ Professional wiping tools (DoD standard)
→ Physical destruction (shredding)
→ Degaussing (magnetic erasure)

### Domain 4 — Unauthorized Device Response
1. Detect → SIEM alerts on unknown devices
2. Investigate → identify devices and access
3. Respond → block unauthorized devices
4. Prevent → implement NAC + employee training

Key insight: One incident spans multiple domains


## CISSP Domains 5-8

### Domain 5 — Identity and Access Management (IAM)
Focus: controlling WHO accesses WHAT
Key principle: Least Privilege
→ access only what's needed for the job
Examples: keycards, login permissions,
network access levels
Defense against: internal threats

### Domain 6 — Security Assessment and Testing
Focus: verifying security controls work
Key tool: Security Audit
→ reviews access, controls, compliance gaps
Examples: auditing user permissions regularly
Think: quality control of cybersecurity
Connection: Equifax needed better Domain 6

### Domain 7 — Security Operations
Focus: responding when security fails
Key principle: contain first, investigate second
Examples: responding to unknown device alerts
Connection: Sean's advice = Domain 7 thinking

### Domain 8 — Software Development Security
Focus: building security INTO software
Key principle: Secure by Design
→ security built in from day one
→ cheaper + safer than adding it later
Examples: advising on password policies,
secure coding practices in SDLC

## Complete Domain Framework:
Domain 1 → WHY we protect (risk + goals)
Domain 2 → WHAT we protect (assets)
Domain 3 → HOW we build protection (architecture)
Domain 4 → WHERE we protect (networks)
Domain 5 → WHO accesses what (IAM)
Domain 6 → IS it working (testing + audits)
Domain 7 → WHAT when it fails (operations)
Domain 8 → HOW we build secure software (SDLC)


## Domain 5 — Additional Details

### Offboarding Process (critical Domain 5 task)
When employee leaves → immediately:
→ Disable login credentials
→ Revoke keycard access
→ Remove from all systems
→ Retrieve company devices

Real example: Cisco 2020
→ Former employee used active credentials
   months after leaving
→ Deleted 456 VMs, $2.4M damage
→ Pure Domain 5 offboarding failure

## Domain 8 — Shift Left Security
Move security EARLIER in development timeline
Design → Build → Test → Launch → Maintain
  ↑
Start security HERE

Cost of fixing security bugs:
→ Design phase: $1
→ Development: $10
→ After launch: $100
→ After breach: $1,000+

## Domain 7 — Correct Incident Response Order
❌ Wrong: block immediately without understanding
✅ Correct:
1. Observe → gather information first
2. Assess → understand the threat level
3. Contain → block based on findings
4. Investigate → understand full scope

Never contain before you understand
what you're containing

## Domain 6 — Access Rights Audit Process
1. Pull list of all users with access
2. Compare against approved access list
3. Identify unauthorized users
4. Revoke access immediately
5. Document why wrong access existed
6. Fix the PROCESS that caused it ← most important
7. Schedule regular audits going forward

## Change Healthcare — Complete Domain Analysis

Failed Domains (6 total):

Domain 1 (Risk Management)
→ Known ransomware risk not properly assessed
→ No adequate business continuity plan

Domain 3 (Architecture) ← root cause
→ MFA not enabled on critical system
→ One missing control = entire breach

Domain 4 (Network Security)
→ No network segmentation
→ Attackers moved freely for days
→ Lateral movement undetected

Domain 5 (IAM)
→ Stolen credentials gave full system access
→ No second verification factor required

Domain 6 (Assessment)
→ Regular testing would have found MFA gap
→ Penetration testing never flagged it

Domain 7 (Security Operations)
→ No 24/7 monitoring detected intrusion
→ Days passed before breach discovered

Key lesson:
Real breaches = multiple domain failures together
Security = team effort across all 8 domains
One missing control (MFA) triggered 6 domain failures
## Defense in Depth

Never rely on single security control
Build multiple overlapping layers

Example — what Change Healthcare needed:
Layer 1: Strong passwords
Layer 2: MFA ← was missing, caused everything
Layer 3: Network segmentation
Layer 4: 24/7 SOC monitoring
Layer 5: Regular penetration testing
Layer 6: Business continuity plan

If Layer 2 existed:
→ stolen password = useless
→ chain reaction never starts
→ 6 domain failures never happen

Key principle:
"Security is only as strong as
its weakest single point"
