SCENARIO-01 – Account Locked After Failed Login Attempts
Business Context

Horizon Freight Logistics is a 25-employee hybrid logistics company with remote and on-site employees. User authentication is managed through Active Directory with account lockout policies enforced.
Reliable access to corporate systems is critical for daily operations.

Ticket Summary
Ticket ID: HD-0001
Category: Login Issue
Impact: Single User
Urgency: High
Priority: P1
User: Olivia Grant (Admin)
Device: Lenovo ThinkPad X1 Carbon (Windows 11)

User Reported Issue
“I can’t log into Windows. It says my account has been locked.”

System message displayed:
Your account has been locked. Please contact your system administrator.
CompTIA A+ Troubleshooting Methodology

1️⃣ Identify the Problem
User recently returned from 2-week leave.
Attempted password reset.
Account now shows locked status in Active Directory.
No reports of similar issue from other users.

2️⃣ Establish Theory
Possible causes considered:
Incorrect password entered multiple times
Account lockout policy triggered
VPN authentication mismatch
Suspicious login attempts (brute force

Most likely cause:
User entered incorrect password multiple times following recent password reset.

3️⃣ Test the Theory
Reviewed Active Directory logs.
Account showed 6 failed login attempts within 5 minutes.
Verified no suspicious external IP addresses.
Confirmed account lockout threshold policy set to 5 attempts.

Theory confirmed:
Lockout triggered due to incorrect password attempts.

4️⃣ Plan of Action
Unlock user account in Active Directory.
Reset password.
Require password change at next login.
Confirm VPN authentication alignment.

5️⃣ Verify Functionality
Account successfully unlocked.
User logged in using temporary password.
Password changed successfully.
VPN connection confirmed operational.
User verified access to shared drive and email.

6️⃣ Document Findings
Root Cause:
User error — incorrect password attempts triggered Active Directory lockout policy.

Resolution:
Unlocked account and reset password. Verified successful authentication and access to required resources.

Preventative Action:
Reviewed account lockout threshold policy and educated user on password best practices and password manager usage.

Time to Resolve: 18 minutes

Business Impact
Minimal operational disruption. Issue resolved quickly with no security compromise.

Skills Demonstrated:
Active Directory account management
Account lockout policy awareness
Log review and validation
User verification and communication
Structured CompTIA troubleshooting methodology
Preventative user education
