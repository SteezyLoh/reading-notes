# Ops 401 reading 37
## Automated AppSec with ZAP

**1. What are the three common stages of the Penetration Testing process and what tasks are performed at each one?**
- Explore - The tester try to learn more about the system being tested. That includes finding out what software is being used, How many people are the endusers. Also looking for all the weakness and vulnerablilities.
- Attack - They plan to exploit the system by determining the vulnerabilitys that excist 
- Report - They report the results of their testing. How they did the attack and all the weakness, etc.

**2. Explain a “main-in-the-middle proxy” in non-technical terms.**
- A Man in the middle proxy is what stands between the tester and the browser and the web application. It intercepts and inspects messages sent between the browswer and web application. 

**3. What are the 2 spiders available for use in ZAP?**
- The 2 spiders that are used in ZAP are for web application crawling. They are fast and they explore web aplication by invoking browswers which then follow the link that have been generated. The AJAX spider is slower the then traditional spider and requires additional configuration dor us ein a "headless" enviornment.

**4. What situations are they best suited for?**
- As ZAP spiders your web application, it constructs a map of your web applications’ pages and the resources used to render those pages. Then it records the requests and responses sent to each page and creates alerts if there is something potentially wrong with a request or response.

## Things i wish i knew more about.
I wish I knew more about how to use ZAP and the spiders that come with it. I want a taste of being a pentester. 

## RESOURCES 
https://www.zaproxy.org/getting-started/