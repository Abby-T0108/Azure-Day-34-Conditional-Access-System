# Day 34: Smart Access - Conditional Access Policies

## Project Overview
Designed comprehensive Conditional Access policies for SecureCloud Corp to implement intelligent, risk-based access controls.

## Policies Created

### 1. Admin MFA Required
- **Target:** Global Administrators and User Administrators
- **Condition:** All applications, all locations
- **Action:** Require multi-factor authentication
- **Purpose:** Protect privileged accounts

### 2. Block Risky Countries
- **Target:** All users
- **Condition:** Access from high-risk countries
- **Action:** Block access completely
- **Purpose:** Prevent attacks from known threat regions

### 3. Company Devices Required
- **Target:** All users accessing Office 365/SharePoint
- **Condition:** Non-company devices
- **Action:** Require compliant or domain-joined device
- **Purpose:** Protect sensitive corporate data

## Risk-Based Rules Implemented
- Suspicious login pattern detection
- Impossible travel scenarios
- Off-hours access monitoring
- Adaptive authentication based on risk level

## Files Delivered
- Policy1-AdminMFA.json
- Policy2-RiskyLocations.json  
- Policy3-CompanyDevices.json
- ConditionalAccess-TestScenarios.md
- Day34-Documentation.md

## Skills Learned
- Conditional Access policy design
- Risk-based authentication
- Azure AD Premium features
- Security policy documentation
- Enterprise access controls

## Day 34/100 - COMPLETED ✅
