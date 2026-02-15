# 06 – Account Lockout

## Objective
Configure and test Active Directory account lockout policy to protect against brute-force login attempts.

---

## Steps Performed

### 1️⃣ Reviewed Default Lockout Policy
- Opened Group Policy Management Console (GPMC)
- Checked Default Domain Policy settings
- Verified default account lockout threshold

### 2️⃣ Configured Lockout Policy
- Set Account lockout threshold: 3 invalid attempts
- Set Account lockout duration: 10 minutes
- Set Reset account lockout counter after: 10 minutes
- Applied policy to the domain

### 3️⃣ Tested Account Lockout
- Attempted multiple invalid logins
- Triggered account lockout
- Verified lockout message on client machine
- Confirmed locked status in Active Directory Users and Computers (ADUC)

---

## Skills Practiced
- Group Policy configuration
- Security hardening
- Account protection mechanisms
- Troubleshooting authentication issues
