# Azure-Entra-ID-Identity-Enterprise-Application-Security-Implementation

📖 Project Overview

In this project, I implemented enterprise-level identity and access security controls using Microsoft Entra ID (Azure AD) and Microsoft 365.

The objective was to simulate a real organizational environment where:

Users are provisioned

Security groups are created

Licenses are assigned

Enterprise applications are integrated

Conditional Access policies are enforced

Application registrations are configured securely

This project demonstrates hands-on experience in Identity & Access Management (IAM), Zero Trust, and Cloud Application Security.

🎯 Business Problem

Organizations face major risks from:

Over-privileged users

Uncontrolled SaaS app access

Weak authentication policies

Poor license governance

Lack of identity monitoring

This lab simulates securing a small enterprise tenant using best practices.

🏗 Architecture Components Implemented
1️⃣ User Provisioning (Microsoft 365 Admin Center)

Created multiple users

Assigned Microsoft 365 Business Basic licenses

Validated login and access behavior

📸 Screenshot: Users and license assignment

2️⃣ Security Groups Implementation

Created security groups:

DepartmentGroup

mastermind

Designed for role-based access assignment

Prepared groups for license and application access control

📸 Screenshot: Security groups dashboard

3️⃣ Enterprise Application Integration

Added external SaaS application (Dropbox Business)

Enabled user sign-in

Configured properties

Validated activation status

This simulates real-world SaaS integration with Entra ID as Identity Provider.

📸 Screenshot: Dropbox Enterprise Application Properties

4️⃣ Application Registration

Created custom application registration (nakcm)

Generated client ID

Configured certificates & secrets

Prepared for secure API authentication

This demonstrates understanding of:

OAuth 2.0 concepts

Service principals

Token-based authentication

📸 Screenshot: App Registration dashboard

5️⃣ Conditional Access Policy Implementation

Created 2 Conditional Access policies

Enforced identity-based access control

Prepared tenant for MFA and risk-based authentication

📸 Screenshot: Conditional Access Policies dashboard

🔐 Security Controls Demonstrated

✔ Role-Based Access Control (RBAC)
✔ Conditional Access
✔ SaaS Application Governance
✔ Identity Lifecycle Management
✔ Application Registration Security
✔ Microsoft 365 License Governance
✔ Zero Trust Principles

🚨 Simulated Threat Scenario

Scenario:
An attacker attempts to log into a SaaS application (Dropbox Business) using compromised credentials.

Mitigation implemented:

Conditional Access enforcement

Identity-based sign-in controls

Group-based access management

Restricted enterprise app access

Result:
Reduced risk of unauthorized SaaS access and credential misuse.

🛠 Technical Skills Demonstrated

Microsoft Entra ID
Microsoft 365 Administration
Conditional Access
Enterprise Applications
Application Registration
Identity Governance
RBAC
OAuth Concepts
SaaS Integration
Zero Trust Architecture

📊 Why This Project Matters

This project demonstrates the ability to:

Design secure cloud identity architecture

Integrate third-party SaaS applications securely

Implement access control policies

Reduce identity attack surface

Configure application-based authentication

Apply security best practices in Azure environments

🚀 Career Focus

I am currently preparing for AZ-500 and building hands-on experience in:

Cloud Identity Security

Conditional Access Engineering

Privileged Access Management

SaaS Governance

Zero Trust Architecture

