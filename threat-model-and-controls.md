# Threat Model and Security Controls

## Threat Modeling Approach

The assessment evaluated Xibalba Interactive by reviewing:

- Important assets
- Potential threat actors
- Attack surfaces
- Relevant MITRE ATT&CK techniques
- Likelihood
- Potential impact
- Defensive controls

The goal was to connect possible attacker behavior to specific areas of the environment and identify where additional protections would provide the most value.

## Threat Actors

The assessment considered three primary threat actor groups:

### Cybercriminals

Potential motivations included financial gain through:

- Credential theft
- Billing information theft
- Exploitation of public-facing applications
- Phishing

### Nation-State Actors

Potential motivations included espionage and disruption.

Areas of concern included:

- Development infrastructure
- Proprietary source code
- Exposed network information
- Private communications

### Insider Threats

Employees or contractors with legitimate access could potentially misuse that access.

Scenarios included:

- Source code theft
- Misuse of shared credentials
- Unauthorized access to systems outside assigned responsibilities

## Attack Surface Evaluation

Attack surface areas were reviewed using both likelihood and impact.

Examples included:

- Administrative credentials
- API endpoints
- Development servers
- Payment processing systems
- Public-facing infrastructure
- Source code repositories
- Transaction data
- User credentials

Higher-risk areas were identified where both the likelihood of attack and potential business impact were significant.

## ATT&CK Mapping

Potential attacker behavior was mapped to MITRE ATT&CK techniques such as:

- T1190 – Exploit Public-Facing Application
- T1566.001 – Spearphishing Link
- T1552 – Unsecured Credentials
- T1590 – Gather Victim Network Information
- T1098 – Account Manipulation
- T1133 – External Remote Services
- T1530 – Data from Cloud Storage
- T1195.002 – Compromise Software Supply Chain
- T1189 – Drive-by Compromise

## Deception Controls

The solution roadmap included deception-based controls designed to provide earlier detection of suspicious activity.

Proposed controls included:

- Honeyfiles
- Honey credentials
- SSH honeyports
- Honeynets
- Honeymail
- Honeynet logging

## Monitoring Controls

Recommended monitoring improvements included:

- File access monitoring
- Network traffic analysis
- Application log monitoring
- Cloud file access monitoring
- Reconnaissance detection
- Activity baselining
- Regular log review

## Preventive Controls

Preventive controls included:

- User phishing-awareness training
- Phishing simulations
- Data filtering policies
- Network blocking policies
- Ongoing review of reconnaissance and scanning activity

## Risk Prioritization

The assessment used likelihood and impact together to help prioritize security improvements.

This made it possible to focus defensive controls on areas where compromise could have the greatest effect on Xibalba’s systems, users, and business operations.
