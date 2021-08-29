# Escalation of privileges and lateral movement.
Gaining the privileges of another user(usually the administrator/root user) in an operating system by exploiting trusts/permissions given to a low-level user is privilege escalation. However, gaining access to a user on a host of private subnet from another publically exposed host in a similar way is called lateral movement. Most of the information followed can be applied to lateral movement as well.

## Indications:
- If any processes running as a low-level user has child processes running as a superuser, it might be an indication if the privileged process is a sensitive executable.
- Any backdoor found in a privileged executable/service.
- Modification of permissions related to sensitive executables such as SETUID permission in bash/sh shell binary.
- Logins from the superuser from unknown sources and times.
- Unknown user with superuser permissions created without knowledge of the system owner.
- New vulnerabilities detected by scanners or AntiVirus softwares without any known changes to the system.

## Steps to prevent:
- Regular checks regarding privilege escalation vulnerabilities using scanners like linpeas/winpeas, seatbelt, winenum, etc.
- Up-to-date operating system version and applications with superuser permissions.
- Very strict permissions to low-level users. Especially the web-server manager or any services exposed to the internet.
- Users should be added to a group only if required.
- The default username for superusers should be changed to prevent bot attacks.
- Process monitoring and permission checking of sensitive executables should be done at regular intervals.
- Remote access logins for superusers should be secured with key-based authentication and MFA features.

## Mitigation:
- The infected user/service should be stopped or deleted for proper forensics analysis and removal.
- Full system security check-ups should be done to remidiate backdoors or resources for persistance.
- A full system reset and update might be required for resetting permissions.
- Reassignment of permissions, groups and trust should be done for the affected user/service.
- Change in authentication for remote access login and local login should be helpful.

## Useful links:
#### [`Linpeas/Winpeas scanner`](https://github.com/carlospolop/PEASS-ng)
#### [`Exploit-db`](https://www.exploit-db.com/)
#### [`StealthBits blog on PE and LM`](https://stealthbits.com/blog/understanding-lateral-movement-and-privilege-escalation/)

### [← Back](index.md)
