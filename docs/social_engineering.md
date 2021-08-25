# Social engineering attacks.
The impersonation or manipulation of any person, web application or software with the intent of misleading the victim into giving their sensitive information is called a social engineering attack. This types of attacks target the weakest factor of technology, humans.

## Indications:
- The best way to identify a social engineering attack is to check the URL of the website that is asking for sensitive information.
- In case if the webpage is not getting displayed properly, the browser is warning for security issues or the device is connected to an open WiFi network, that is a high probability of a social engineering attack.
- If a pop window asking for information is opened, even with the correct URL, can be dangerous. To verify, the window should stay present if the webpage/tab behind it is closed.
- SSL, CORS, CSRF-cookie issues are the best indications of impersonated websites.
- Change in DNS settings or the `hosts` configuration file can lead to this kind of attacks.

## Steps to prevent:
- Proper configuration for DNS servers and hostname management should be implemented.
- Usage of VPNs and SSL enabled websites are very useful for surfing the web via unknown networks.
- In order to verify a login page, any rouge/fake information should be provided first to see how it reacts. However, not interacting with suspicious webpage is highly recommended.
- Extensions for web browsers like `NoScript`, `HTTPS Everywhere`, `UblockOrigin`, etc. should be used.
- Password managers are very useful to verify certain login pages.
- Any errors or warnings from the browser due to invalid SSL certificate, CORS restrictions or CSRF errors from servers should be taken seriously and fixed accordingly.
- If unsure regarding the legibility of the website, `whois` or alternative tools can be useful.

## Mitigation:
- Trusted DNS servers such as `1.1.1.1` (CloudFlare) or `8.8.8.8`(Google) should be used.
- Passwords should be reset in the most sensitive websites in case a social engineering attack is suspected.
- Organizations should use properly configured VPNs and DNS servers with regular configuration checkups.
- The URL, file or E-Mail should be reported to Anti-Virus, Domain name and email providers.

## Useful links:
#### [`NoScript extension`](https://noscript.net/)
#### [`HTTPS Everywhere extension`](https://www.eff.org/https-everywhere)
#### [`UblockOrigin extension`](https://ublockorigin.com/)
#### [`Google domain name abuse report`](https://support.google.com/domains/answer/10093434?hl=en )
#### [`Google phishing email report`](https://support.google.com/mail/answer/8253?hl=en)
#### [`Whois tool`](https://who.is/)

### [← Back](index.md)
