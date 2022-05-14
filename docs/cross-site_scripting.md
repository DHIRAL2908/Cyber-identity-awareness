# Cross site scripting/XSS attacks.
If an attacker can execute or manipulate any javascript code leading to compromise of a victim's browser, it will be a cross site scripting or XSS attack.

## Indications:
- Sudden logout or suspicious account activity.
- Weird or strange pop ups and alerts.
- Webpage not functioning or displaying properly.
- Unintended connections and traffic when visiting a webpage.
- Errors in browsers, especially related to networking.
- Strange message/s from unknown or known person.

## Steps to prevent:
- Extensions for web browsers like `NoScript`, `HTTPS Everywhere`, `UblockOrigin`, etc. should be used.
- Regularly logout and login to reset old cookies in sensitive websites.
- Web administrators should use security proxies such as `cloudflare` and proper handling of user input to not allow XSS.
- Browser cache and temporary files should be cleared often.
- Sensitive permissions such as location or file access should not be given to unknown webpages.

## Mitigation:
- The website administrator should be notified regarding the issue.
- Passwords should be reset to trigger an automatic logout from all devices.
- If possible, reset or reinstall the browser.
- Any suspicious webpage should be closed as soon as possible.

## Useful links:
#### [`NoScript extension`](https://noscript.net/)
#### [`HTTPS Everywhere extension`](https://www.eff.org/https-everywhere)
#### [`UblockOrigin extension`](https://ublockorigin.com/)
#### [`Cloudflare web proxy`](https://www.cloudflare.com/)
#### [`OWASP article on XSS`](https://owasp.org/www-community/attacks/xss/)

### [← Back](index.md)
