# Xibalba Threat Modeling Assessment

## Project Overview

This project documents a threat modeling security assessment for Xibalba Interactive.

The assessment focused on identifying important assets, reviewing the organization’s attack surface, identifying potential threat actors, mapping attacker behavior to MITRE ATT&CK, and recommending defensive controls to reduce risk.

The goal was to evaluate the environment from an adversarial perspective and identify areas where security weaknesses could affect confidentiality, integrity, or availability.

## Assets and Attack Surface

The assessment reviewed areas including:

- Administrative credentials
- API endpoints
- API logs
- Development servers
- End users
- IT administrators
- Payment gateway software
- Payment processing servers
- Public-facing IP addresses
- Public website servers
- Source code
- Source code repositories
- Transaction data
- User credentials
- Web application code

Each area was evaluated based on associated assets, relevant ATT&CK techniques, likelihood, and potential impact.

## Threat Actors

### Cybercriminals

Cybercriminals were evaluated as a threat because of the potential financial value of user credentials, billing information, and exposed application vulnerabilities.

Potential scenarios included:

- Exploitation of web application vulnerabilities
- Phishing campaigns targeting user or employee credentials

### Nation-State Actors

Nation-state actors were considered because of the potential for espionage or disruption.

Potential scenarios included:

- Using exposed network information to target development systems
- Attempting to access proprietary information
- Targeting private communications

### Insider Threats

Employees or contractors with legitimate access were also evaluated as a potential threat.

Potential scenarios included:

- Theft of proprietary source code
- Misuse of shared credentials
- Unauthorized access to systems beyond an individual’s assigned scope

## MITRE ATT&CK Mapping

Potential attacker behavior was mapped to techniques including:

- T1190 – Exploit Public-Facing Application
- T1566.001 – Spearphishing Link
- T1552 – Unsecured Credentials
- T1590 – Gather Victim Network Information
- T1098 – Account Manipulation
- T1133 – External Remote Services
- T1530 – Data from Cloud Storage
- T1195.002 – Compromise Software Supply Chain
- T1189 – Drive-by Compromise

## Defensive Recommendations

The assessment included several categories of defensive improvements.

### Deception and Detection

Proposed deception controls included:

- Honeyfiles
- Honey credentials
- Honeyports
- Honeynets
- Honeymail
- Honeynet logging and monitoring

These controls were intended to improve visibility into unauthorized activity and provide earlier warning of suspicious behavior.

### Monitoring and Data Sources

Recommended monitoring improvements included:

- File access monitoring
- Network traffic analysis
- Application log monitoring
- Cloud file access monitoring
- Reconnaissance detection

### Preventive Controls

Preventive recommendations included:

- User phishing-awareness training
- Phishing simulations
- Data filtering rules
- Network blocking policies
- Ongoing network activity review

## Skills Demonstrated

- Threat modeling
- Attack surface analysis
- Threat actor identification
- Asset identification
- Risk analysis
- Likelihood and impact assessment
- MITRE ATT&CK mapping
- Defensive control planning
- Deception technology concepts
- Monitoring strategy
- Preventive security controls
- Security reporting

## Takeaway

This project demonstrated how threat modeling can be used to identify potential attack paths before an incident occurs.

By evaluating assets, threat actors, attack surfaces, and defensive controls together, the assessment provided a structured way to identify security gaps and prioritize improvements.
