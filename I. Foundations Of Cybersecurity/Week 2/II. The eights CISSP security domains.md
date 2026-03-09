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
