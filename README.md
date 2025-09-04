# Azure-Day-34-Conditional-Access-System

Smart Access- Conditional Access Policies
Project Overview
I designed and implemented Conditional Access policies for “SecureCloud Corp” to enforce risk-based access controls aligned with Zero Trust.

What I Built
Conditional Access Policies
* Policy1-AdminMFA.json — require multi-factor authentication for administrators
* Policy2-RiskyLocations.json — block sign-ins from high-risk countries/locations
* Policy3-CompanyDevices.json — require compliant, company-managed devices

Documentation and Testing
* ConditionalAccess-TestScenarios.md — test cases and expected risk-based responses
* Day34-Documentation.md — implementation notes and admin runbook

Technologies Used
* Microsoft Entra ID (Azure AD)
* Conditional Access
* Microsoft Graph / JSON export
* Risk-based authentication
* Zero Trust model

Key Learnings
* Designing enterprise access policies that balance security and usability
* Applying risk signals to drive adaptive access decisions
* Entra ID Premium capabilities for Conditional Access
* Structuring policy documentation and test evidence

Skills Developed
* Security policy architecture
* Conditional Access design and tuning
* Risk assessment and mitigation
* Enterprise access control governance
* Security documentation

Project Status
* Completed
* Day 34/100 - #100DaysOfCloud
