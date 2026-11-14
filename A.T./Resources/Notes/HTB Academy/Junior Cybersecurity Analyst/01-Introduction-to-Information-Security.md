
# Introduction to Information Security

## Metadata
- Platform: Hack The Box Academy
- Path: Junior Cybersecurity Analyst
- Status: In Progress
- Started: 2026-11-14

## 1. Learning Objectives

- ==🟡01LO-Structure of InfoSec==
- ==🟡02LO-Areas of Information Security==
- ==🟡03LO-Principles of Information Security==
- ==🟡04LO-Processes in Information Security==
- ==🟡05LO-Purpose of Information Security==
- ==🟡06LO-Network Seurity==
- ==🟡07LO-Application Security==

## 2. Key Concepts

![[Pasted image 20261114150201.png]]

## 3. Detailed Notes

**<01LO-Structure of InfoSec>**
- **`Client`:** This is a PC/Laptop through which you access resources and services "on the Internet".
- **`Internet`:** This is a vast, interconnected network of servers that offer different services and applications, such as Hack The Box.
- **`Servers`:** Servers provide various services and applications designed to perform specific tasks. For example, one type of server might be a "web server", allowing you and others to view the content of a website (such as this section you're reading currently) on your computer or smartphone.
- **`Network`:** When multiple servers or computers are connected and can communicate with each other, it's called a network.
- **`Cloud`:** Cloud refers to data centers that offer interconnected servers for companies and individuals to use.
- **`Blue Team`:** This team is responsible for the internal security of the company and defends against cyber attacks.
- **`Red Team`:** This team simulates an actual adversary/attack on the company.
- **`Purple Team`:** This team consists of both Blue Team and Red Team members working together to enhance the company's security.

- **`The Treasure`:** Your valuable data and information.
- **`The Castle Walls`:** Firewalls, defensive mechanisms, and encryption that keep outsiders from getting in.
- **`The Guards`:** Security protocols and access controls that monitor who enters and leaves.
- **`Penetration Testers`:** Knights who test the castle's defenses by simulating attacks to find weak spots.
- **`Digital Transformation`:** Expanding the castle to store more treasure, which attracts more thieves.
- **`Cyber Threats`:** Thieves who are constantly looking for ways to breach the castle's defenses.

**<02LO-Areas of Information Security>**
IMPORTANT TERMS: **==🔴'Confidentiality', 'Integrity', 'Availability'==**

*Cyber Threats:*

1. **Network Security**
2. **Application Security**
3. **Operational Security**
4. **Disaster Recovery and Business Continuity**
5. **Cloud Security**
6. **Physical Security**
7. **Mobile Security**
8. **Internet of Things (IoT) Security**

*Roles In Information Security:*

| **Role**                                      | **Description**                                         | **Relevance to Penetration Testing**                                                                                                              |
| --------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Chief Information Security Officer` (`CISO`) | Oversees the entire information security program        | Sets overall security strategy that pen testers will evaluate                                                                                     |
| `Security Architect`                          | Designs secure systems and networks                     | Creates the systems that pen testers will attempt to breach                                                                                       |
| `Penetration Tester`                          | Identifies vulnerabilities through simulated attacks    | Actively looks for and exploits vulnerabilities within a system, legally and ethically. This is likely your target role.                          |
| `Incident Response Specialist`                | Manages and responds to security incidents              | Often works in tandem with pen testers by responding to their attacks, and sharing/collaborating with them afterwards to discuss lessons learned. |
| `Security Analyst`                            | Monitors systems for threats and analyzes security data | May use pen test results to improve monitoring                                                                                                    |
| `Compliance Specialist`                       | Ensures adherence to security standards and regulations | Pen test reports often support compliance efforts                                                                                                 |

**<03LO-Principles of Information Security>**
1. `Confidentiality`
    - Ensures that information is accessible only to those authorized to have access
    - Protects against unauthorized disclosure of information
    - Implemented through measures like encryption and access controls
2. `Integrity`
    - Maintains and assures the accuracy and completeness of data over its entire lifecycle
    - Protects against unauthorized modification of information
    - Implemented through measures like hashing and digital signatures
3. `Availability`
    - Ensures that information is accessible to authorized users when needed
    - Protects against disruption of access to information
    - Implemented through measures like redundancy and disaster recovery planning
4. `Non-repudiation`
    - Ensures that a party cannot deny the authenticity of their signature on a document or the sending of a message that they originated
    - Important in e-commerce and legal contexts
    - Implemented through measures like digital signatures and audit logs
5. `Authentication`
    - Verifies the identity of a user, process, or device
    - Crucial for ensuring that only authorized entities can access resources
    - Implemented through measures like passwords, biometrics, and multi-factor authentication
6. `Privacy`
    - Focuses on the proper handling of sensitive personal information
    - Ensures compliance with data protection regulations
    - Implemented through measures like data minimization and consent management

**<04LO-Processes in Information Security>**
1. `Risk Assessment`
    - Identifies and evaluates potential threats and vulnerabilities
    - Determines the potential impact of security breaches
    - Helps prioritize security efforts
2. `Security Planning`
    - Develops strategies to address identified risks
    - Creates policies and procedures to guide security efforts
    - Allocates resources for security initiatives
3. `Implementation of Security Controls`
    - Puts security plans into action
    - Involves deploying technical solutions and enforcing policies
    - Includes both preventive and detective controls
4. `Monitoring and Detection`
    - Continuously watches for security events and anomalies
    - Uses tools like SIEM systems and intrusion detection systems
    - Aims to identify security incidents as quickly as possible
5. `Incident Response`
    - Reacts to detected security incidents
    - Follows established procedures to contain and mitigate threats
    - Includes steps like isolation, eradication, and recovery
6. `Disaster Recovery`
    - Focuses on restoring systems and data after a major incident
    - Involves implementing backup and redundancy measures
    - Aims to minimize downtime and data loss
7. `Continuous Improvement`
    - Reviews and learns from security incidents and near-misses
    - Updates security measures based on new threats and technologies
    - Involves regular security assessments and audits

**<05LO-Purpose of Information Security>**
- `Protecting sensitive data from unauthorized access`
    - Safeguards confidential information like personal data, financial records, and trade secrets
    - Prevents data breaches that could lead to financial loss or reputational damage
- `Ensuring business continuity`
    - Maintains the availability of critical systems and data
    - Enables organizations to continue operations even in the face of security incidents or disasters
- `Maintaining regulatory compliance`
    - Ensures adherence to laws and industry standards related to data protection
    - Helps avoid legal penalties and maintains customer trust
- `Preserving brand reputation`
    - Protects against reputational damage caused by security breaches
    - Demonstrates commitment to protecting stakeholder interests
- `Safeguarding intellectual property`
    - Protects valuable ideas, inventions, and creative works from theft or unauthorized use
    - Maintains competitive advantage in the market
- `Enabling secure digital transformation`
    - Allows organizations to adopt new technologies safely
    - Supports innovation while managing associated security risks

**Tools in Information Security:**

- `Firewalls`: Control incoming and outgoing network traffic
- `Intrusion Detection/Prevention Systems (IDS/IPS)`: Monitor for and block suspicious activities
- `Security Information and Event Management (SIEM) systems`: Collect and analyze security event data
- `Vulnerability scanners`: Identify potential weaknesses in systems and applications
- `Penetration testing tools`: Simulate attacks to find vulnerabilities (e.g., Metasploit, Burp Suite)
- `Encryption tools`: Protect data confidentiality and integrity
- `Access control systems`: Manage user permissions and authentication
- `Security awareness training platforms`: Educate users about security best practices

- Linux, Windows, MacOS
- Nmap: Network scanning and discovery
- Wireshark: Network protocol analysis
- Metasploit: Exploitation framework
- Burp Suite: Web application security testing
- John the Ripper: Password cracking

**<06LO-Network Security>**

|**Element**|**Description**|
|---|---|
|`Firewalls`|Act as barriers between trusted internal networks and untrusted external networks, filtering traffic based on predetermined security rules.|
|`Intrusion Detection and Prevention Systems` (`IDS`/`IPS`)|Monitor network traffic for suspicious activities and take automated actions to detect or block potential threats.|
|`Virtual Private Networks` (`VPNs`)|Provide secure, encrypted connections over public networks, ensuring data privacy and integrity during transmission. For example, used by employees to connect to internal network resources.|
|`Access control mechanisms`|Include authentication and authorization protocols to ensure only legitimate users can access network resources.|
|`Encryption technologies`|Protect sensitive data both in transit and at rest, rendering it unreadable to unauthorized parties.|

IMPORTANT TERMS: ==🔴'Chief Information Security Officer (CISO)'==



## 4. Tools and Commands

## 5. Practical Exercises

## 6. Real-World Applications

## 7. Questions and Knowledge Gaps

## 8. Key Takeaways

## 9. References

## 10. Review Checklist
- [ ] Understand theory
- [ ] Complete exercises
- [ ] Explain concepts without notes
- [ ] Review after seven days
  