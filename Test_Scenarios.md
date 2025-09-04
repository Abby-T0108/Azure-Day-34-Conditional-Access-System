# Conditional Access Test Scenarios - Day 34

## Test Scenario 1: Admin Login from Office
**User:** Global Administrator
**Location:** Office network (trusted location)
**Device:** Company laptop
**Expected Result:** ✅ Access granted after MFA

## Test Scenario 2: Admin Login from Home
**User:** Global Administrator  
**Location:** Home network
**Device:** Personal device
**Expected Result:** ❌ Blocked - requires company device + MFA

## Test Scenario 3: Regular User from Risky Country
**User:** Standard user
**Location:** China/Russia/North Korea
**Device:** Any device
**Expected Result:** ❌ Completely blocked

## Test Scenario 4: Emergency Access Account
**User:** Emergency breakglass account
**Location:** Any location
**Device:** Any device
**Expected Result:** ✅ Access granted (excluded from all policies)

## Risk-Based Responses

### Suspicious Login Patterns
- Multiple failed attempts: Automatic temporary block
- Login from new device: Require additional verification
- Impossible travel: Block and require admin approval
- Off-hours access: Additional MFA challenge

### Adaptive Authentication
- Low risk: Standard authentication
- Medium risk: MFA required
- High risk: Block + security review
