Medicare Plus Hospital – PCI DSS and HIPAA Compliance Case Study
This project examines two information security and regulatory compliance incidents at Medicare Plus Hospital, focusing on PCI DSS requirements for protecting payment cardholder data and HIPAA safeguards for protecting patient health information. It identifies compliance gaps, recommends appropriate security controls, and proposes an integrated Governance, Risk and Compliance (GRC) strategy to strengthen data protection, accountability, and regulatory compliance.
Table of Contents
- Project Overview
- Network Topology
- Tools and Technologies
- Configuration Steps
- Results and Findings
- Author
Project Overview
Medicare Plus Hospital is a healthcare facility that uses an Electronic Health Record (EHR) system, accepts card payments through an online patient portal and at the front desk, maintains patient medical and treatment records, and works with third-party suppliers providing cloud, payment, and medical services.

The purpose of this case study is to assess two incidents involving information security and compliance, identify the applicable regulatory requirements, evaluate the gaps, and recommend practical controls to address the identified weaknesses.

The assessment covers two key compliance areas:

1. PCI DSS – Payment Cardholder Data Protection

Medicare Plus accepts card payments through its online patient portal and front desk. Since the hospital handles cardholder data and transmits payment information to a payment processor, PCI DSS requirements apply to its payment environment.

The assessment focuses on protecting cardholder data during storage, transmission, and payment system activities.

2. HIPAA – Patient Health Information Protection

The second incident involves a nurse discovering that multiple staff members have access to patient records even when the information is not required for their duties.

Patient records contain Protected Health Information (PHI), including diagnoses, treatment records, test results, billing records, and insurance information.

The assessment focuses on strengthening access controls and applying appropriate HIPAA safeguards to protect patient information.

Project objectives:
- Identify the PCI DSS requirements applicable to Medicare Plus's payment environment.
- Evaluate the security controls needed to protect cardholder data.
- Identify HIPAA safeguards applicable to the hospital's patient records and EHR system.
- Assess the compliance gaps associated with excessive staff access to patient information.
- Recommend practical administrative, technical, and physical safeguards.
- Develop an integrated GRC approach to improve compliance, accountability, and information security.
Network Topology
Not applicable. This project is a compliance case study focused on PCI DSS and HIPAA requirements rather than network design, simulation, or infrastructure configuration.

However, the assessment identifies the following technology environments and information systems:
- Online Patient Portal: Used by patients to make card payments.
- Front Desk Payment Environment: Used to accept card payments at the hospital.
- Payment Processor: Receives cardholder information from the hospital's payment environment.
- Electronic Health Record (EHR) System: Stores and manages patient medical and treatment records.
- Cloud Services: Provided by external suppliers supporting hospital operations.
- Medical Services: Supported through third-party service providers.
- Workstations and Devices: Used by hospital staff to access patient records and other organizational information.
The case study does not provide specific network diagrams, device models, IP addresses, subnet configurations, or detailed system architecture.
Tools and Technologies
The project focuses on regulatory compliance frameworks, information security safeguards, access management, and GRC practices.
- PCI DSS (Payment Card Industry Data Security Standard): Framework for protecting payment cardholder data.
- HIPAA (Health Insurance Portability and Accountability Act): Framework establishing safeguards for protecting patient health information.
- Electronic Health Record (EHR) System: Technology used to maintain patient medical and treatment records.
- Role-Based Access Control (RBAC): Access management approach that assigns permissions according to employee roles and responsibilities.
- Minimum-Necessary Principle: Approach to limiting access to patient information to what is required for assigned duties.
- Authentication Controls: Mechanisms for verifying user identities before granting access to systems and information.
- Encryption: Protection of cardholder information during transmission and, where applicable, storage.
- Audit Logs and Monitoring: Processes for recording and monitoring access to sensitive information.
- GRC Framework: Integrated approach to managing governance, risk, and compliance requirements.
- Administrative, Technical, and Physical Safeguards: Categories of controls used to protect patient information under the HIPAA assessment.
Configuration Steps
The following steps outline the assessment process and recommended control implementation for the two incidents.

1. Assess the PCI DSS Payment Environment
- Identify the payment channels used by Medicare Plus, including the online patient portal and front desk.
- Establish that PCI DSS applies because the hospital handles and transmits cardholder data.
- Identify the systems and processes involved in the cardholder data environment.
- Review the security measures required to protect cardholder information.
2. Identify Applicable PCI DSS Requirements
- Network Security Controls: Protect online payment connections and the payment environment from untrusted networks.
- Secure Configurations: Avoid default vendor passwords and insecure system settings.
- Protect Stored Data: Minimize cardholder data retention and use appropriate encryption, hashing, masking, or truncation where applicable.
- Protect Data in Transit: Encrypt cardholder information before transmission to the payment processor over open or public networks.
- Protect Against Malware: Maintain anti-malware protection for payment processing systems.
- Secure Systems and Software: Apply secure coding practices and regular system and software updates.
- Restrict Access: Grant access to cardholder information only to employees with a valid business need.
- Identify and Authenticate: Use unique user identification, strong credentials, and appropriate authentication controls.
- Restrict Physical Access: Prevent unauthorized physical access to payment devices and media containing cardholder data.
- Log and Monitor Access: Record and monitor access to payment systems and cardholder information.
- Test Security Regularly: Conduct regular security testing, including appropriate vulnerability scanning and penetration testing.
- Support with Policy: Maintain information security policies, staff awareness training, and incident response procedures.
3. Implement Recommended PCI DSS Controls
- Minimize the amount of cardholder data retained.
- Protect stored cardholder information using appropriate security measures.
- Encrypt cardholder data transmitted between the hospital's payment environment and payment processor.
- Use individual accounts and suitable authentication controls.
- Restrict access according to business need.
- Maintain network security rules, secure configurations, malware protection, and timely software updates.
- Log and monitor access to payment systems.
- Establish incident response procedures and regularly test security controls.
- Provide staff with information security awareness training.
4. Identify the PCI DSS Compliance Gap
- Recognize that the case study does not confirm whether the hospital has implemented the necessary payment security controls.
- Identify the potential exposure of cardholder data during storage, transmission, access, and payment processing.
- Recommend a documented PCI DSS control program for the payment environment.
- Identify the cardholder data environment and apply relevant PCI DSS requirements.
- Establish access restrictions, encryption, monitoring, testing, and supporting policies.
5. Assess the HIPAA Patient Records Incident
- Identify patient medical and treatment records as Protected Health Information (PHI).
- Recognize that multiple employees have access to patient records even when access is not required for their duties.
- Evaluate the hospital's access control practices and the potential for inappropriate access to sensitive patient information.
6. Identify Applicable HIPAA Safeguards
- Administrative Safeguards: Establish staff responsibilities, security management procedures, training, and access control requirements.
- Technical Safeguards: Implement authentication and access controls within the EHR system to restrict access according to staff duties.
- Physical Safeguards: Restrict physical access to workstations and devices used to view patient records.
- Organizational Requirements: Establish appropriate contractual and accountability arrangements for third parties handling sensitive health information.
7. Implement Recommended HIPAA Access Controls
- Apply the minimum-necessary principle so staff can only access patient information required for their responsibilities.
- Implement role-based access control within the EHR system.
- Assign individual user accounts and appropriate authentication controls.
- Conduct regular access reviews.
- Remove unnecessary access when employees change roles or leave the organization.
- Maintain audit logs and monitor patient record access.
- Establish clear administrative access guidelines and provide staff training.
8. Identify the HIPAA Compliance Gap
- Identify excessive employee access to patient records as the primary compliance gap.
- Recognize that current access controls may not adequately restrict patient information according to job responsibilities.
- Recommend minimum-necessary access and role-based access control within the EHR system.
- Support technical controls with administrative procedures, employee training, individual accountability, and access monitoring.
9. Develop an Integrated GRC Strategy
- Document the compliance requirements applicable to payment processing and patient information.
- Assign ownership and accountability for relevant security controls.
- Assess compliance gaps and prioritize corrective actions.
- Implement appropriate PCI DSS and HIPAA safeguards.
- Conduct routine compliance assessments to evaluate control effectiveness.
- Maintain ongoing oversight of patient and cardholder data protection.
Results and Findings
The case study identified two significant information security and compliance concerns at Medicare Plus Hospital: the potential exposure of payment cardholder data and excessive employee access to patient health information.

Incident 1: PCI DSS Payment System

Identified gap:

The case study does not establish whether Medicare Plus has implemented the necessary security controls for its card-payment environment. This creates uncertainty about how cardholder information is protected during storage, transmission, access, and payment processing.

Recommended controls:
- Establish a documented PCI DSS control program.
- Identify the systems within the cardholder data environment.
- Minimize stored cardholder data and apply appropriate protection measures.
- Encrypt cardholder information during transmission.
- Restrict access according to valid business requirements.
- Maintain secure configurations, network security controls, and malware protection.
- Monitor access and regularly test security controls.
- Maintain information security policies, staff awareness, and incident response procedures.
Incident 2: HIPAA Patient Records

Identified gap:

Multiple employees have access to patient records even when the information is not necessary for their assigned duties. This indicates that access controls may not adequately restrict access to PHI based on job responsibilities.

Recommended controls:
- Apply the minimum-necessary principle.
- Implement role-based access control within the EHR system.
- Assign unique user accounts and appropriate authentication controls.
- Conduct periodic user access reviews.
- Remove unnecessary access when employees change roles or leave the organization.
- Maintain audit logs and monitor access to patient records.
- Strengthen administrative procedures and employee security awareness.
Overall GRC Findings and Recommendations

The assessment demonstrates the importance of integrating governance, risk management, and compliance when protecting sensitive healthcare and payment information.

An integrated GRC strategy should:
- Document applicable PCI DSS and HIPAA compliance requirements.
- Assign clear ownership of information security controls.
- Identify and assess compliance gaps.
- Implement appropriate administrative, technical, and physical safeguards.
- Monitor access to sensitive information.
- Conduct regular compliance assessments.
- Strengthen accountability through policies, procedures, and staff training.
The project concludes that Medicare Plus should establish a coordinated compliance approach to protect both cardholder data and patient health information. Addressing the identified gaps through documented controls, restricted access, encryption, monitoring, and regular assessments will strengthen information security and improve organizational compliance.

Author
Name: Moyinoluwa

Role: GRC Analyst in Training

Field: Governance, Risk and Compliance (GRC)
