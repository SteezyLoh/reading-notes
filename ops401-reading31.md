# Ops 401 Reading 31
## Malware Detection with YARA rules

**1. What is the main goal of Threat Hunting and how is it different from traditional threat monitoring?**
- I would say that threat hunting is like the YARA rules. From my understanding a YARA rule is a rule you create to threat actors from trying to scam with phishing links. You create a YARA rule so that before the phishing comes to play YARA rules already rules it out which i believe that is threat hunting. For Threat monitoring i would say that the threat is already there or even potentially there but your just keeping a close eye on it.

**2. What are the four types of YARA rules and what does each one of them use to identify and classify malicious software?**
- String-based rules - Uses sting of text to identify malware
- File metadata-based rules - These rules use metadata about the files being analyzed to identify malware
- Hash-based rules - Uses cryptographic hashes to identify malware
- Network-based rules - Using network traffic data (IP/Ports) to identify the malware 

**3. How are YARA rules similar to how Anti-Virus programs detect malicious software?**
- I would say that the Yara rules and anti-virus programs are simuular to detect malicious software because they can prevent threat actors from infatuating the system. Even tho a threat actor can always find another way around they both help keeping the data safe. 

## Things i want to know more about
I want to know more about how i can set up a YARA rule on my personal computer

### Resources: https://www.geeksforgeeks.org/threat-hunting-using-yara/