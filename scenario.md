# Scenario Questions #
*These questions have no right and wrong answer. They should allow the candidate to provide full responses. The interviewers here are not just looking for complete answers but also keeping track of HOW a candidate responds (rambles, gets distracted, doesn't answer the question, etc.).*

## Tech Questions ##
### General Pentest ###
1. "I am your customer. I have a /24 subnet of hosts on the Internet that I'd like you to pentest. Take me through, in detail, all the steps that you will go through in this assessment." *@webbreacher* 
    1. *This question is good to not only see if the candidate thinks about pre-assessment things like Rules of Engagement and Scoping meetings, but the interviewer can (and should!) say "Tell me more about that..." each step of the way to ensure that the candidate gives sufficiently deep answers.*
    2. *The interviewer should have an idea of where they want the assessment to go, "You ran your scan and found two servers. One has TCP ports 23, 53, 80 open and the other has 80, 443 and 3306. What do you do next?" Provide direction but don't lead.*
3. For in-person interviews I like asking the candidate to "go to a white board (or paper taped to the wall). You have an unlimited budget and resources. Please draw the most secure corporate network for my organization. It must have certain components including but not limited to: the Internet, one user subnet, at least one Active Directory server, one web server (with backend database) on the Internet, one Human Resources server, Wifi for your users, a VPN, etc."  *@webbreacher* 
    1. *The interviewer is looking for completeness.*
        1. *Do they put all the required components in?*
        2. *Are they in secure places?*
        3. *Did they add in other security devices/conventions (IDS/IPS, FW, DMZ, SIEM...)?*
        4. *Does their architecture make sense? If not, call them on it and ask them to fix it.*
    5. *Once the candidate has completed their drawing, the interviewer goes to the board and draws a stick figure person attached to the Internet.* "This is you. You are an attacker on the Internet. I want you to tell me how you are going to compromise the AD server here (*circle it in the drawing*) and exfiltrate the AD user hashes."
        1. *At this point the candidate can use any number of techniques to compromise the network and systems. The interviewer is looking for plausible attacks. Ask for more details at each step of their attack. Provide them challenges ("Our firm uses egress filter for servers so they cannot talk right to the Internet.") and see how they roll with them.*
2. On an assessment, you have just compromised a Mac OS X laptop inside a corporate user subnet. Your goal is to exfiltrate Active Directory hashes from the AD servers. How do you accomplish this? *@webbreacher*