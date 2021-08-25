# Malicious documents and everyday-used files.
The most common target for social engineering and easy command execution for attackers is to make the victim open or execute an innocent and regular looking file. This can be word/excel documents, `.hta` or `.msi` related alternatives for executables and webpages with malicious JavaScript code.

## Indications:
- Any unknown file from untrusted source can be malicious to open.
- Symptoms for malware/virus infections apply here too.
- Spontaneous opening of browser or command prompt window.
- Suspicous activity on opening a document.
- Document or file asking to enable a special permission such as turning of anti-virus or enabling macro service.
- Known or popular login pages opening with `localhost` or `127.0.0.1` in the URL.

## Steps to prevent:
- Any document or file should be scanned for malicious content with a good anti-virus depending upon the enviornment.
- Sensitive services which can be harmful like Macro, JavaScript from unknown sites, etc. should be turned off by defaut and turned on only with special examination of the file in subject.
- E-mail attachments should be checked and opened only from known sources.
- Even with known extensions, foreign files should not be "double-clicked" or executed.
- URL for any spontaneously-opened pages requiring credentials or sensitive information should be checked to match with the expected hostname.
- VBA and Macro should be disabled in all of the Microsoft Office products in case they were enabled.

## Mitigation:
- A full system security scan should be done in case a malicious document is opened.
- The file in case or URL should be reported to antivirus providers in order to protect others.
- Reseting or reinstalling the infected application such as Microsoft office or internet browser can help.
- The whole operating system might require a full reset to remove any persistance tools.
- In case of a malicious email from anyone, it should be reported to the email provider.

## Useful links:
#### [`VirusTotal`](https://www.virustotal.com/gui/)
#### [`Any.Run sandbox tool`](https://any.run/)
#### [`Gmail reporting support`](https://support.google.com/mail/answer/8253?hl=en)
#### [`Sophos article on Macro attacks`](https://home.sophos.com/en-us/security-news/2019/macro-viruses.aspx)

### [← Back](index.md)
