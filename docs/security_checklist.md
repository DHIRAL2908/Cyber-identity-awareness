# Security Checklist.
These are some suspicious activities which can point to a cyber attack or starting of one.

## Accounts:
### For individuals.
- Notification regarding login lockouts, login attempts or login success from an unknown location.
- OTP messages without any interactions from user.
- Messages from unknown sources especially for `email confirmtaion`.
- Unrecognized activities in social media accounts.
- Spam notifications from an unknown origin with URLs.

## Operating systems:
### For computers with simple usage.
- More than usual time for boot/startup.
- Unusual internet consumption or connections in traffic.
- TCP ports and connections which are not intended to be open.
- Creation of hidden folders or files without any new installations or activity.
- Opening, closing or rapidly doing both for any applications.
- `Blue Screen Of Death` due to large memory or storage consumption.

## Webservers:
### For devices hosting webapps.
- Sudden modifications in contents of any configurations or files hosted.
- Unusual or sudden errors in routine operations.
- Logins or suspicious activity from the webserver handler user without prior arrangement of the same.
- Malicious `child/forked` processes from simple webserver softwares.
- Admin or superuser logins without prior notice.
- Requests with similar contents from the same origin.
- Unrecognizable, special or unprintable characters in user-input oriented places.
- Rate-limiting and restrictions on upload features.

## Intranet devices:
### Devices located in independent subnets. (Databases, backups, storage, etc.)
- Unusual traffic from device connected to the internet and the local subnet both.
- Malicious applications like `chisel.exe, port-tunnel.exe, nc.exe, msfvenom payloads, etc.` which can be detected with hash-checking or antivirus softwares.
- Larger data read/write than routine.
- Weird connection issues. Especially originating from unknown subnets.
- Sudden errors in workflow or automation builds with usual queries/targets.


### [← Back](index.md)
