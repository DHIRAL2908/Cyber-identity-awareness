# Denial of service(DOS/DDOS) attacks.
Exhaustion of any resource in order to make it inaccessible for the intended users is denial of service attack. If the attack is carried out by spamming requests via bots, it is known as distributed denial of service attack(DDOS).

## Indications:
- If the system is lagging, froze or doesn't respond to common operations then it might be out of resources to operate on. Which might be an indication of DOS attack.
- Any unusual HTTP errors appearing constantly on usual webpages or services.
- Unusability of any application or service due to it taking most of the resources given to it without the need.
- Very high amount of requests to a specific page with a similar request structure, even from different origin, can be a sign of DOS attack.
- Rapid consumption of storage and memory can be caused due to unrestricted upload sizes and upload rate for a web-server.
- High network traffic or unusally large amount of errors given by the server software.

## Steps to prevent:
- Proper checking and restrictions of upload features regarding file sizes, quantity and types.
- Rate-limiting is a must on any web-server application.
- Using proxies/load balancers like `cloudflare`, `Akamai`, `DDOS-Guard`, etc. can help with identifing bots and anti-spamming of requests.
- Up-to-date software and services should be used to avoid public vulnerabilities present in them.
- Monitoring of web traffic and banning any suspicious requests/IPs.
- Limited resources should be given to any publically-exposed applications.
- Usage of containers like dockers, aws, azure, kerbrunets, etc. can be very helpful against DOS attacks and recovery from them.

## Mitigation:
- The rogue application or service should be stopped immediately to minimize the resource exhaustion. It should not be activated or made available again until after proper forensics investigation.
- Changing the DNS to point to another server can be helpful to temporarily disable incoming traffic from bad actors while still keeping the website up for legit users to know it is under maintenance.
- The web traffic or operation logs should be collected for cyber-crime investigators to prevent similar attacks on other systems.

## Useful links:
#### [`CloudFlare CDN`](https://www.cloudflare.com)
#### [`Akamai`](https://www.akamai.com/)
#### [`indian cybercrime portal`](https://cybercrime.gov.in/)
#### [`AWS advisory against DDOS`](https://aws.amazon.com/shield/ddos-attack-protection/)

### [← Back](index.md)