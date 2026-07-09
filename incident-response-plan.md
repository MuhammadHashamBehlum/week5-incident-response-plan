
Summer Training Program 2026

Incident Response Plan — From Detection to Recovery

Prepared By:
Mohammad Hesham Wazir Ali Behlum
Bachelor of Science in Cybersecurity
Rochester Institute of Technology (RIT) Dubai
Final-Year Student

Submission Date: 09 July 2026

Introduction
EduTrack Learning Solutions is a mid-sized educational technology company that is able to provide cloud-based learning platforms for schools, universities, and even training providers. The organization is able to store sensitive information such as student records and employee data, along with payment information, and internal business documents. Because of this, cybersecurity is able to play an important role in protecting the company's daily operations, as well as maintaining customer trust.

Throughout the previous internship tasks, the organization strengthened its overall cybersecurity posture by performing an ISO/IEC 27001 gap assessment, which was able to develop the security policies, along with collecting compliance evidence, and preparing for an audit, as well as improving employee security awareness, and assessing third-party vendor risks. While these governance activities do significantly reduce the cyber risks, there is no organization that can completely eliminate the possibility of a security incident.

For that reason, EduTrack Learning Solutions requires a structured Incident Response (IR) Plan that is able to clearly explain how security incidents should be detected, analyzed, contained, eradicated, recovered, and reviewed. A well-planned response helps reduce business disruption, limits financial and reputational damage, protects sensitive information, and ensures that everyone involved understands their responsibilities during an incident.

This Incident Response Plan follows the NIST Special Publication 800-61 Incident Response Lifecycle and uses a realistic phishing attack that is able to lead to an employee account compromise as the primary incident scenario. Since phishing remains one of the most common attack methods used against organizations today, it is able to provide an appropriate example for demonstrating how the incident response process works from the beginning to the end.

Incident Severity Levels
Severity
Description
Example Incidents
Escalation
Low
Minor security event with little or no business impact.
Antivirus blocks malware, isolated failed login attempts.
Security Analyst
Medium
Incident affecting one employee or a limited number of systems.
Compromised employee account, suspicious login activity.
Security Analyst and Incident Commander
High
Multiple systems affected or sensitive data may be exposed.
Ransomware affecting several devices, privilege escalation.
Incident Response Team, IT Manager, Executive Management
Critical
Major business disruption or confirmed data breach affecting essential services.
Large-scale ransomware, customer data theft, complete service outage.
Executive Management, Legal Team, Communications Team, Regulatory Authorities (if required)



Incident Classification Criteria
Criteria
Low
Medium
High
Critical
Systems Affected
One device
Several devices
Multiple business systems
Organization-wide
Data Exposure
None
Possible
Confirmed limited exposure
Large-scale exposure
Business Impact
Minimal
Moderate
Significant
Critical
Expected Recovery Time
Less than 2 hours
Same business day
1–2 days
Several days


Incident Response Team Roles
Role
Responsibility
Incident Commander
Leads the incident response process, coordinates activities, assigns responsibilities, and approves major decisions.
Security Analyst
Reviews security alerts, investigates incidents, collects evidence, and monitors suspicious activity.
IT Infrastructure Team
Isolates affected systems, restores services, performs system recovery, and verifies system integrity.
Communications Representative
Provides approved updates to employees, customers, vendors, and other stakeholders when necessary.
Legal and Compliance Officer
Reviews legal obligations, privacy regulations, contractual requirements, and reporting responsibilities.
Executive Management
Makes business decisions, approves critical actions, and oversees organizational recovery.


Incident Scenario
An employee receives an email that appears to come from the Human Resources department and they are requesting for an urgent password reset. The message basically contains a fake Microsoft 365 login page that is able to closely resemble the legitimate website. Believing that the request is genuine, the employee then enters their username and password.

Within some time, the attacker is able to successfully sign into the employee's Microsoft 365 account from an overseas location. The attacker is able to begin accessing the internal documents, as well as attempts to move laterally through the cloud services.

The organization's SIEM platform is able to detect several suspicious activities, which includes:
Login from an unusual geographic location.
Travel detection is impossible.
Multiple failed authentication attempts being made.
Unusual file access activity.
New sign-in from an unrecognized device.

These alerts are able to trigger the formal Incident Response process.

NIST Incident Response Lifecycle
Phase
Actions Taken by EduTrack Learning Solutions
1. Preparation
Maintain security awareness training, multi-factor authentication (MFA), endpoint protection, SIEM monitoring, documented incident response procedures, regular backups, updated contact lists, and periodic response exercises.
2. Detection & Analysis
The SIEM platform generates alerts for unusual login behaviour. The Security Analyst reviews authentication logs, confirms the account compromise, determines the incident severity, documents the findings, and informs the Incident Commander.
3. Containment
Disable the compromised account, terminate all active sessions, isolate any affected devices if necessary, block suspicious IP addresses where possible, and require an immediate password reset.
4. Eradication
Remove phishing emails from employee inboxes, scan systems for malware, verify that no persistence mechanisms remain, update detection rules, and close any identified security gaps.
5. Recovery
Restore secure user access, confirm systems are operating normally, continue enhanced monitoring for several days, validate backups if restoration was required, and verify that no additional suspicious activity exists.
6. Lessons Learned
Conduct a post-incident review meeting, document lessons learned, update security awareness training, improve SIEM detection rules, revise the Incident Response Plan if necessary, and recommend long-term security improvements.


Evidence


Evidence
Purpose
SIEM Alerts
Identify suspicious activity and confirm detection.
Authentication Logs
Verify unauthorized login attempts and account usage.
Firewall Logs
Identify attacker IP addresses and network activity.
Email Headers
Investigate the phishing email source and delivery path.
Endpoint Security Scan Results
Confirm whether malware was installed.
User Interview
Understand how the phishing email was received and whether credentials were disclosed.
Cloud Access Logs
Review file access and account activity after compromise.


Communication Plan
Stage
Person Notified
Purpose
Incident Confirmed
Incident Commander
Begin incident coordination and assign responsibilities.
Medium or High Severity
IT Manager
Approve containment and recovery activities.
High or Critical Severity
Executive Management
Provide business impact updates and approve major decisions.
Data Exposure Confirmed
Legal and Compliance Officer
Review regulatory notification requirements.
Customer Impact Identified
Communications Representative
Prepare customer and stakeholder communications.
Incident Closed
All Relevant Stakeholders
Share the final report, lessons learned, and improvement actions.

Incident Escalation Process
The SIEM platform detects suspicious activity and generates an alert.
The Security Analyst reviews available logs and confirms whether the event is a genuine security incident.
The incident is assigned a severity level based on its business impact.
The Incident Commander activates the Incident Response Team when required.
Immediate containment actions are performed to prevent further damage.
After the threat has been removed, system recovery activities begin.
The response team performs a post-incident review and documents recommendations for future improvements.

Recovery Success Criteria
The recovery phase is considered complete when:
All affected accounts have been secured, as well as protected using new credentials and multi-factor authentication.
Systems have been verified to be free from malware or even unauthorized changes.
Business services have returned to normal operation.
Continuous observation and monitoring is able to confirm that no additional suspicious activity is occurring.
Any restored data has been validated for accuracy, as well as integrity.
The Incident Commander is able to approve the final incident report, as well as formally closes the incident.


Conclusion
An effective incident response process is just as important as preventing cyberattacks. Although EduTrack Learning Solutions has strengthened its cybersecurity through ISO/IEC 27001 governance, along with the security policies and audit readiness activities, as well as third-party risk management and employee security awareness training, the organization must also be prepared to be able to respond quickly and effectively when any form of incident occurs.

This Incident Response Plan is able to complete the organization's cybersecurity lifecycle by being able to connect detection, governance, risk management, and even the operational recovery into a single structured process. By following the six phases of the NIST SP 800-61 Incident Response Lifecycle and defining clear severity levels, along with assigning responsibilities and maintaining effective communication, as well as continuously learning from every incident, EduTrack Learning Solutions can tend to minimize business disruption and even protect sensitive information, as well as strengthen customer trust and continuously improve its overall cybersecurity posture.
