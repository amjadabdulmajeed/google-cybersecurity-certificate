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

## Important Cybersecurity Terms
- Following Rules (Compliance): You must follow internal and external rules to avoid fines.
- The Plan vs. The Tools (Frameworks & Controls): A framework is the security plan; controls are the tools used to execute the plan (like locks and alarms).
- Overall Health (Security Posture): How strong the organization's security is.
- The Enemy (Threat Actor): Any person or group trying to cause harm.
- Inside Danger (Internal Threat): A risk from people inside the organization, which can be accidental or intentional.
- Protecting Connections (Network Security): Securing the internal network.
- Protecting the Internet Space (Cloud Security): Securing data stored online.
- Making Things Automatic (Programming): Using code to do repetitive security tasks.

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
SIEM = what happened (historical + real time analysis)
IDS  = something is happening RIGHT NOW (immediate detection)

### SIEM vs IDS — My Own Analogies

SIEM = like a company's complete activity records system
       stores + analyses everything across all devices
       alerts on suspicious patterns found in the data

IDS  = like a security guard watching live cameras 24/7
       monitors network traffic in real time
       immediately alerts when something suspicious 
       is happening RIGHT NOW

Key difference:
SIEM = analyses what happened (broad, historical + real time)
IDS  = detects what is happening right now (immediate, focused)

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
