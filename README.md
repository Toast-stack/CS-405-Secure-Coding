# CS-405 Secure Coding

## Overview

This repository contains coursework, assignments, and projects completed for the CS-405 Secure Coding course at [Your University]. The course focuses on identifying and mitigating security vulnerabilities in software development, emphasizing secure coding practices and principles.

## Course Description

CS-405 delves into common security vulnerabilities found in software, teaching techniques and strategies to develop robust and secure code. Students gain hands-on experience in identifying security issues and applying secure programming principles to safeguard software and data.

## Green Pace Secure Development Policy

### Overview & Purpose:

The **Green Pace Secure Development Policy** outlines the company’s commitment to secure software development practices. It incorporates core security principles, C/C++ coding standards, and standards for authorization, authentication, and encryption. This policy ensures uniformity and compliance throughout all phases of development, from design to deployment.

### Scope:

This policy applies to all Green Pace staff involved in the creation, deployment, or support of custom software.

### Key Components:

1. **Ten Core Security Principles**:  
   These principles include practices such as validating input data, adhering to the principle of least privilege, defense in depth, and secure coding standards. Each principle is explained with its importance and impact on security.

2. **C/C++ Coding Standards**:  
   Ten specific standards address vulnerabilities such as buffer overflows, uninitialized memory, and SQL injection risks. For each standard:

   - Compliant and non-compliant code examples are provided.
   - Risk assessments (severity, likelihood, remediation cost) and tools for automated detection are included.

3. **Encryption Policies**:
   Encryption is mandated for data:

   - **At Rest**: Stored on devices.
   - **In Flight**: Actively transmitted.
   - **In Use**: During processing.
     The policy specifies how encryption protects data against unauthorized access.

4. **Triple-A Framework**:
   The policy focuses on the **Triple-A Framework**:

   - **Authentication**: Ensures users are identified.
   - **Authorization**: Restricts user access based on roles.
   - **Accounting**: Logs activities for transparency and auditing.

5. **Risk Assessment Summary**:  
   A consolidated table summarizes the risks for all coding standards, ranked by severity, likelihood, cost, and priority.

6. **Automation in Security**:  
   The policy advocates for the use of static analysis tools and unit testing in DevSecOps pipelines to continuously enforce security policies.

7. **Audit Controls & Management**:  
   Requires documentation of compliance, including system logs, access-control evidence, and data-control standards.

### Policy Management:

- **Enforcement**: Compliance is monitored by the OCISO (Office of the Chief Information Security Officer) and reported to the Risk Management Committee.
- **Exceptions Process**: Requires justification, impact analysis, and a plan to achieve compliance. Approval is needed from senior officers.
- **Review Schedule**: The policy is reviewed annually or upon significant regulatory changes.

## Module Eight Journal: Adoption of Secure Coding Standards and Security Practices

### Overview & Purpose:

This journal reflects on the importance of integrating secure coding standards early in the software development lifecycle. It emphasizes practices such as risk evaluation, adopting zero-trust principles, and implementing security policies to reduce vulnerabilities and meet regulatory requirements.

### Key Topics:

1. **Adopting Secure Coding Standards**:  
   Early adoption of secure coding standards minimizes the costs associated with retrofitting security measures later. Planning ahead ensures applications are secure throughout their entire lifecycle, from development to deployment.

2. **Risk Evaluation and Mitigation**:  
   Examining past breaches, such as the Yahoo data breach, highlights the importance of encryption and the need to protect against vulnerabilities like SQL injection. Understanding these risks enables informed decisions on cost-benefit analysis for mitigating potential threats.

3. **Zero-Trust Model**:  
   The zero-trust model stresses the importance of verifying all connections before granting access, especially in cloud-based and remote work environments. This principle is crucial in preventing unauthorized access as remote work becomes more prevalent.

4. **Implementation of Security Policies**:  
   Security policies provide developers with a framework for creating secure applications. Key considerations include:
   - Identifying risks associated with neglecting security measures.
   - Ensuring compliance with regulatory frameworks like HIPAA and Sarbanes-Oxley.
   - Emphasizing frequent training and adherence checks to maintain security best practices.

### References:

The journal cites various articles and sources discussing secure coding practices, notable breaches, and the role of security policies in modern software development.
