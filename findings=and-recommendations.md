# Findings and Recommendations

## Key Findings

### 1. Administrative Credentials Present High Risk

Administrative credentials were identified as a high-risk area because compromise could provide attackers with access to development systems and other sensitive resources.

The assessment associated this area with unsecured credentials and account manipulation techniques.

### 2. Public-Facing Systems Increase Exposure

Public website servers, public-facing IP addresses, API endpoints, and payment systems create opportunities for reconnaissance and exploitation.

These systems were evaluated as likely targets for attackers attempting to exploit exposed services or gather network information.

### 3. Development Systems and Source Code Require Strong Protection

Development servers, source code, and source code repositories were identified as important assets because compromise could expose proprietary information or enable further attacks.

Potential risks included reconnaissance, unauthorized access, and software supply-chain related activity.

### 4. User and Administrative Credentials Are Attractive Targets

User credentials and administrative credentials were identified as valuable targets for both external attackers and insider threats.

Potential attack paths included phishing, credential misuse, and unauthorized remote access.

### 5. Payment and Transaction Systems Have High Business Impact

Payment processing systems and transaction data were identified as sensitive areas because compromise could affect financial information and business operations.

The assessment assigned high potential impact to several payment-related assets.

### 6. Multiple Threat Actor Types Must Be Considered

The threat model evaluated:

- Cybercriminals
- Nation-state actors
- Insider threats

Each threat actor was associated with different motivations, attack methods, and potential targets.

## Recommendations

### Improve Deception and Early Detection

Recommended deception controls included:

- Deploy honeyfiles on shared drives
- Use honey credentials for unauthorized login detection
- Deploy honeyports for SSH probing
- Establish honeynets to monitor attacker behavior
- Use honeymail accounts to identify phishing activity
- Integrate honeynet activity with centralized logging

### Improve Monitoring

Recommended monitoring improvements included:

- Monitor file access activity
- Analyze network traffic
- Monitor application logs
- Monitor cloud file access
- Detect reconnaissance activity
- Establish normal activity baselines
- Regularly review security logs

### Strengthen Preventive Controls

Preventive recommendations included:

- Provide phishing-awareness training
- Conduct phishing simulations
- Implement data filtering rules
- Apply network allow/block policies
- Review network activity for reconnaissance and scanning

### Support Incident Response

Deception and monitoring alerts should be incorporated into incident response workflows so suspicious activity can be reviewed and escalated consistently.

## Key Lesson

The assessment showed that threat modeling can help identify where attackers are most likely to focus before an actual compromise occurs.

Evaluating assets, threat actors, attack surfaces, likelihood, and impact together helps prioritize security controls around the areas that present the greatest risk.
