# Ops 401 Reading 36
## XSS with w3af, DVWA

**1. Explain how a cross-site scripting attack works in non-technical terms.**
- Okay so cross-site scripting attacks is a vulnerability on the web that an attacker can use to get access to another persons personal account. If that person has important stuff on there, the attack can get into it by fooling the server.

**2. What are the three types of XSS attacks?**
- Reflected XSS - where the malicious script comes from the current HTTP request.
- Stored XSS - where the malicious script comes from the website's database.
- DOM-based XSS, where the vulnerability exists in client-side code rather than server-side code.

**3. If an attacker successfully exploits a XSS vulnerability, what malicious actions would they be able to perform?**
- If an attacker successfully exploits a XSS vulnerbility then the attacker/attackers has a lot of things they can get their hands on. One example is if the attacker gets to any read any data then they can read all the things that are in the read only data. Pretty much take over the target.

**4.What are some security controls that can be implemented to prevent XSS attacks?**
-  It can be very difficult to prevent XSS if it was attacked. There are a few steps in order to do so though. Can filer input on arrival, Encode data on output. Use appropriate response headers and use content security policies.

## I wish I knew more about
- I wish I knew more about who came up with the XSS idea. And how it is used.

## Resources:
- https://portswigger.net/web-security/cross-site-scripting