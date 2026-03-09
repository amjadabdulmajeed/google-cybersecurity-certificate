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
