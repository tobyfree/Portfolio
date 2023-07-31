# Scenario

Imagine yourself as a cybersecurity consultant for Sam's Scoops. Your role involves evaluating the company's current security infrastructure and identifying vulnerabilities. 

Let’s say that during your assessment of Sam's business security infrastructure, you discovered several areas where improvements are necessary:

Security policies
- The existing password policy requires employees to create passwords with a minimum length of only six characters. Additionally, periodic password changes are not enforced.

- There is no policy in place for regularly backing up data or recovering lost data in case of a disaster or system failure.

- The enforcement of access controls is inconsistent, allowing some employees to access sensitive information without proper authorization.

Infrastructure
- Sam's Scoops uses outdated operating systems that are no longer supported by the manufacturer. 

- Firewalls are not properly configured or maintained, leaving the network susceptible to cyber-attacks. 

- The current system relies solely on usernames and passwords for access, lacking strong authentication methods. 

Physical machines
- The physical machines within the company are not adequately secured.

- Remote access to physical machines lacks proper security measures.

Now, your task is to recommend initial protective measures based on your findings to secure Sam’s Scoops physical machines and user data.

# Instructions

Based on your findings from the scenario, create a comprehensive security plan that includes recommended protective measures for the following areas:

- Security policies: Provide recommendations to strengthen the password policy, establish a data backup and recovery plan, and enforce consistent access controls.

- Infrastructure: Outline measures to address the use of outdated operating systems, improve firewall configuration and maintenance, and enhance authentication methods.

- Physical machines: Recommend security measures to secure physical machines and secure remote access. 

Ensure that the recommended measures are justified and supported by the potential benefits it offers to Sam's Scoops, considering the protection of sensitive data and operations.

# Answer:

- Security policies:
  - Password policy: Current research showed the performance of long passwords is higher than the one of shorter, but more complex passwords. Therefore, I would recommend the follwing policy: min. length of 16, at least 2 character classes, no words from dictionaries of the list of most common passwords to ensure unique, safe, and memorable passwords.
  - Backup and Recovery: The 3-2-1 methods is recommendable with having 3 copies of important data, storing them at at least 2 different locations with 1 of them being off-premise like in a cloud. Backups should be performed daily.
  - Access controls: Role-based access control is recommended to ensure that all employees can only access the data needed for their work, implementing a "need-to-know"-strategy.
 
- Infrastructure:
  - Operating systems: All OS must be at least supported and provided with regular security updates. If an OS is no longer supported, it needs to be replaced by a newer version
  - Firewall configuration: The firewall configurations need to be up to date, with at least the current set of recommended rules in place.
  - Authentication methods: Access controls: MFA, with at least 2 different components like knowledge, inheritance or ownership, is necessary to protect against the simplest kinds of online attacks.
 
- Physical machines:
  - All physical machines need to be secured, being inaccessible for unauthorized people. This includes locks on private rooms, securing the cash register, locking all devices when not used and putting authentication methods like passcodes or key cards for every device or door to protect against theft or unauthorized access.
  - Remote access needs to be implemented referring to state-of-the-art access control via cloud services, remote-desktop solutions or VPN.
