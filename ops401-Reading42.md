# Ops Reading 42
## Pass the Hash with Mimikatz

**1. Name the six credential-gathering techniques which Mimikatz is able to perform and explain how two of them work.**
- Pass-the-hash - Attackers use Mimikatz to pass an exact hash string to log in to the target computer
- Pass-the-ticket - Mimikatz provides functionality for a user to pass a Kerberos ticket to another computer an log in with that user's ticket. 
- Overpass-the-hash(pass-the-key)
- kerberoast golden tickets
- Kerberoast silver tickets
- Pass-the-cache


**2. What are four ways we can defend against Mimikatz attacks. Explain how two of the mitigations can stop Mimikatz.**
- Change admin privileges - This can be done by imiting admin privileges to only user who need them
- Change caching policy - Windows caches password hashes that were recently used through their system registry. Mimikatz can then gain access to these cached passwords, which is why it’s important to change your default settings to cache zero recent passwords. This can be accessed through Windows Settings > Local Policy > Security Options > Interactive Logon.  
- Turn off deugging privileges
- Increase local security authority

## Things i wish i knew more of
I wish i knew if the end users can spot an attacker who uses Mimikatz

## Resources: https://www.varonis.com/blog/what-is-mimikatz