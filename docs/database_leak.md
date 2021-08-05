# Database leaks, breaches and theft.
If sensitive information such as the data stored in a database (especially passwords) is accessed via any method without permission, it is a database leak. This types of leaks are sold in forums and are usually hard to track once gone.
There can be many reasons behind it including improper/unsafe SQL query structure, weak or default password for the DBMS software/server, open database tools such as phpmyadmin or adminier, etc.

## Indications:
- Web traffic shows massive amount of data transport, more than any webpages hosted.
- Large read/write calls in the DBMS server which can never occur for only one query.
- If present, admin access from unknown origins.
- Malware infection in the DBMS server or somehow access to command execution.
- Change in sensitive information on the database.
- Account takeover complains from clients reusing their passwords.

## Steps to prevent:
- Safe coding must be used for SQL queries and implementation of the database.
- Proper hashing algorithms with random and changing salt must be used for password storage.
- Source code leaks should be prevented or made harder by techniques such as obfucation, useless distracting code, etc.
- The DBMS server/port should not be open for public connections and should have very strong login credentials.
- Tools/software used for database management should not be available for public access.
- Regular checks for database leaks in sites like HaveIBeenPwned or cyber security forums should be done.
- Proper resource and network inspection tools (i.e. IDS/IPS) helps detecting abnormal accesses.

## Mitigation:
- The database should be locked from the network until a proper fix is applied to the entry point.
- All the clients who have their information exposed should be addressed in a public statement.
- Main credentials used for accessing the database should be changed immediately.
- In case of a password reuse, immediate change of the password should be done throughout every accounts on the internet.
- Proper forensics and checking of unsafe code should be done before hosting the system again.
- Backing up the database before reseting/changing the system can be helpful.

## Useful links:
#### [`HaveIBeenPwned`](https://haveibeenpwned.com/)
#### [`Data Theft by CyberCell Delhi`](http://www.cybercelldelhi.in/datatheft.html)
#### [`Data Breach by FTC`](https://www.ftc.gov/data-breach-resources)
#### [`Datbase breach checklist`](https://www.itgovernance.co.uk/blog/your-checklist-for-responding-to-and-reporting-data-breaches)

### [← Back](index.md)
