## The CIA Triad
- Confidentiality: Only authorized people can access information
- Integrity: Information is accurate and untampered
- Availability: Systems are accessible when needed

## Threat Types
- External: Outside the organization, intentional
- Internal: Inside the organization, often accidental

## Security Analyst Core Responsibilities
- Monitor and protect networks
- Penetration testing (ethical hacking)
- Security audits

## Complete Security Analyst Skills Map

### Transferable Skills
- Communication: explain technical issues to non-technical people
- Problem-solving: structured approach - attempt, research, resolve
- Time management: prioritize under pressure (highest risk first)
- Growth mindset: technology evolves, learning never stops
- Diverse perspectives: different backgrounds = better solutions
- Collaboration: work with engineers, forensic investigators, managers

### Technical Skills
- Programming (Python, SQL): automate tasks, analyze data
- SIEM: collects all logs network-wide, analyses in real time,
  alerts analyst → like reviewing all security camera footage
- IDS: monitors live network traffic, triggers immediate alerts
  → like a motion sensor alarm
- Threat landscape knowledge: stay current on new attack methods
- Incident response: follow procedures when attack occurs

### Key difference: SIEM vs IDS
- SIEM = what happened (historical + real time analysis)
- IDS  = something is happening RIGHT NOW (immediate detection)

## PII and SPII

### PII (Personally Identifiable Information)
- Any information that identifies a person
- Examples: name, DOB, address, phone, email, IP address

### SPII (Sensitive PII)
- Stricter subset of PII — more damaging if stolen
- Examples: SSN, medical records, financial info, biometrics

### Key difference:
- PII stolen = bad
- SPII stolen = potentially life-ruining

### Identity Theft
- Primary concern when PII/SPII is compromised
- Goal: financial gain through impersonation
- Can take years for victims to recover

### Connection to CIA Triad:
- PII/SPII protection = primarily Confidentiality

## Why Data Breaches Hurt Organizations

1. Human impact
   → PII/SPII stolen → identity theft risk for real people

2. Reputation damage
   → Users lose trust → brand damaged → less business

3. Financial damage
   → Ransom payments + lost customers + regulatory fines

## Real Fine Examples:
- Equifax 2017 → $575M fine (147M SSNs exposed)
- British Airways 2019 → $230M fine (PII breach)
- Meta 2023 → $1.3B fine (GDPR violation)

## Key Compliance Laws (learn more in Course 2):
- GDPR → European data protection
- HIPAA → US healthcare data
- PCI DSS → Payment card data

  ## IDS vs IPS — Critical Difference
IDS (Intrusion Detection System)
→ Monitors network traffic
→ ALERTS analyst when suspicious activity found
→ Does NOT block anything

IPS (Intrusion Prevention System)  
→ Monitors network traffic
→ Automatically BLOCKS suspicious activity
→ AND alerts analyst

Memory trick:
Detection = tells you
Prevention = stops it

## Identity Theft
Primary concern when PII/SPII is stolen
→ Criminal impersonates victim for financial gain
→ Can take years to recover from

## Key Compliance Laws
GDPR → protects European citizens' data
HIPAA → protects US medical/health data
PCI DSS → protects payment card data
Violation = massive fines

## The Security Response Chain

IDS (detects) → IPS (blocks automatically)
→ Security Analyst (investigates using SIEM)
→ Two paths:
   Active attack → contain and stop it
   Past attack → Digital Forensics investigates

Key insight: Tools detect. Humans decide.

## Why History Matters in Cybersecurity

Pattern recognition — the most valuable analyst skill
Built by studying past attacks, not reading manuals

History → recognize attack patterns → faster response
No history → starting from zero → slower response
                                 → more damage

Real example:
WannaCry 2017 → taught analysts ransomware patterns
Change Healthcare 2024 → analysts recognized patterns
                         from 2017 and responded faster
                         
