# Securing web browsers.
The purpose of security in a web browser is to avoid client-side attacks like XSS, tab-nabbing, phishing, web-sandbox escape, etc. The protection is required to be designed and implemented from both, server and client sides.

## Indications:
- Change of the webpage contents or the website itself without any user request or activity.
- Session hijacking involving modification of preferences and abnormal usage of features.
- Errors in displaying some of the contents like images, headers, posts, etc. in a webpage.
- Unsual alerts and pop-ups usually asking for sensitive information or visiting other URLs.
- Annoying advertisments or redirects due to poor server controlled web browser security.
- Warnings or errors regarding `CSP (Content Security Policy)`, `XSS protection (Cross-Site Scripting)`, `CORS (Cross-Origin Resource Sharing)`, `CSRF (Cross-Site Request Forgery)`, etc. by the browser.

## Steps to prevent:
- Using extensions like `HTTPS Everywhere`, `NoScript`, `uBlock Origin`, etc. can compensate against poor server-side security configurations and headers regarding web browser security.
- The URL displayed in the very bottom of the browser window should be checked before clicking on any links or buttons.
- The web browser software should be kept up-to-date to disallow exploits which can bypass the web sandbox and execute code on the client's system.
- Server-side has the responsibility for designing the website to not allow attacks such as `XSS`, `tab-nabbing`, `CSRF`, etc. by implementing the required `security headers`, `CORS configuration` and `CSRF tokens`.
- Secure tags such as div containers, content sanitization, etc. should be used by the website.

## Mitigation:
- The session can be reset by clearing the cookies, changing the password, relogging in, using any website features to `log out of all devices`, etc. for dealing with session hijacking.
- If suspicious of a login form, fake information or credentials can be supplied to verify it. Although it is recommended not to interact with such websites and use passive methods such as `whois` or `DNS lookup` to verify the website authenticity.
- Any kind of unusual activity mentioned above should be reported to the website administrator as soon as possible for the safety of others.

## Useful links:
#### [`NoScript extension`](https://noscript.net/)
#### [`HTTPS Everywhere extension`](https://www.eff.org/https-everywhere)
#### [`UblockOrigin extension`](https://ublockorigin.com/)
#### [`Whois tool`](https://who.is/)
#### [`DNS lookup tool`](https://mxtoolbox.com/DNSLookup.aspx)
#### [`Security HTTP response headers by Spring`](https://docs.spring.io/spring-security/site/docs/5.0.x/reference/html/headers.html)
#### [`CORS, XSS and CSRF explained by dev.to`](https://dev.to/maleta/cors-xss-and-csrf-with-examples-in-10-minutes-35k3)

### [← Back](index.md)
