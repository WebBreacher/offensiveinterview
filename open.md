# Open-ended Questions #
*These questions have no right and wrong answer. They should allow the candidate to provide full responses. The interviewers here are not just looking for complete answers but also keeping track of HOW a candidate responds (rambles, gets distracted, doesn't answer the question, etc.).*

## People Questions ##
1. Do you have a blog and, if so, what is the URL? *@digininja*
2. Do you contribute to open source projects and, if so, which and at what level? *@digininja*
3. What conferences do you attend? *@digininja*
4. What conferences have you spoken at? *@digininja*
5. Name a couple of people in the industry that you'd look to for advice/trust their advice. *Asking this to make sure they are active and know who does what, if they are claiming to be wifi experts and don't name people like Josh Wright then they are lying.* *@digininja*

## Tech Questions ##
### General Pentest ###
1. You are performing a blackbox penetration test for a client. The only allowable attack vectors are network and application level attacks. Where do you start?  *@jstnkndy*
    1. Describe how you would find all domains associated with the client *(if they didn’t answer)* 
    2. Describe how you would find all network ranges associated with the client. *(if they didn’t answer)*
3. During the penetration test you find an instance of Outlook Web Access belonging to the client. Describe how you would attack this. *@jstnkndy*
    1. Describe how you would find potential usernames to use. *(if they didn’t answer)*
    2. Describe how you would pick which passwords to use. *(if they didn’t answer)*
    3. Describe how you would avoid account lockouts. *(if they didn’t answer)*
4. If you run the following scan without root privileges, describe what would happen: ```nmap www.google.com``` *@jstnkndy*
    1. What kind of scan was performed? *(if they didn’t answer)*
    2. How many ports were scanned? *(if they didn’t answer)*
    3. If you ran the same command as root, describe the differences. *(if they didn’t answer)*
4. You are launching a Metasploit reverse https meterpreter payload against a host that you know is vulnerable to your attack, but once you type “exploit” nothing happens after it launches the attack, how would you debug this (or what would you change to get your meterpreter session?) *@jstnkndy*
5. You have successfully initiated a meterpreter session against a Windows host. What type of post exploitation do you perform? *@jstnkndy*
    1. How would you extract the local password hashes?
    2. How would you gather cleartext credentials from the machine?
    3. You attempt to run mimikatz but error occurs, how do you debug this? (or what would you do to try and fix the error?)
4. Using the same meterpreter session as previous, you are able to dump the local machine hashes, describe what you would do with these. *@jstnkndy*