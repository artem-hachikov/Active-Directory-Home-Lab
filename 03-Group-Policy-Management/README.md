# 03 – Group Policy Management

## Objective
Configure and test Group Policy Objects (GPOs) to enforce security settings across the domain.

---

## Steps Performed

### Account Lockout Policy Configuration
- Configured Account lockout threshold: 3 invalid attempts
- Set lockout duration: 10 minutes
- Enabled administrator account lockout
- Set reset lockout counter: 10 minutes

### Password Policy Configuration
- Enforced password complexity requirements
- Set minimum password length
- Configured maximum password age

### Testing & Verification
- Triggered account lockout using invalid login attempts
- Verified lockout message on client machine
- Unlocked account via Active Directory Users and Computers

---

## Skills Practiced
- Group Policy Management Console (GPMC)
- Security policy configuration
- Domain-level enforcement
- Troubleshooting account lockout
