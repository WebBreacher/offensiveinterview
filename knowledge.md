# Knowledge-Based Questions #

*These questions have a right or wrong answer. They should have discrete answers.*

## Tech Questions ##

### General Pentest ###

1. What are the phases of a penetration test? *@whereistehnarwhal, reddit*
2. What is the difference between a risk assessment, a vulnerability assessment, and a penetration test? *@whereistehnarwhal, reddit*
3. When running an nmap scan, what source port can you specify to scan from to commonly bypass firewall rules? *@jstnkndy*
4. Construct an Nmap SYN scan that does not do DNS lookups, does not ping the host, and only returns open ports for tcp/139 and tcp/445. *@whereistehnarwhal, reddit*
5. What kind of attack is ARP Spoofing considered and how could you leverage it on a penetration test? *@jstnkndy*
6. Explain what NBNS poisoning is and how it can be leveraged on a penetration test. *@jstnkndy*
7. Answer true or false and explain your answer: two-factor authentication protects against session hijacking. *@jstnkndy*
8. Explain what happens when a connection from your webbrowser to a webserver is initiated on every OSI layer (as detailed as you like). *@dhauenstein*

### Crypto / Hashes / Passwords ###

1. Describe the basics of input and output of a stream cipher. *@jstnkndy*
2. List a couple block ciphers and their characteristics and security concerns. *@jstnkndy*
3. Describe when you would use a null byte during an application penetration test. *@jstnkndy*
4. What is the problem with LM hashes? *@jstnkndy* *[According to Justin, "When asking #4 you have to make sure to do it in a Jerry Seinfeld "What's the deal with airplane food?" voice"]*
5. What is the difference between netNTLM and NTLM hashes? *@jstnkndy*
6. What is pass the hash? *@jstnkndy*
7. What is token impersonation? *@jstnkndy*

### Web Application ###

1. Describe what SQL Injection is and how you would test for it? *@jstnkndy*
2. What about Blind SQL Injection and how is it different from other kinds? *@jstnkndy*
3. How can SQL Injection lead to remote code execution? *@morgoroth*
4. How can you execute OS command with mssql injection? *@enddo*
5. Describe a webshell and how you would upload/use one. *@enddo*
    1. How would you bypass uploader protections? *@enddo*
6. Describe Remote Command Execution (RCE). *@enddo*
    1. How would you prevent it in PHP? *@enddo*
7. Describe Cross Site Request Forgery. *@jstnkndy*
    1. How would you prevent it?
8. Describe the different types of Cross Site Scripting. *@jstnkndy*
    1. How would you exploit XSS?
9. What is the purpose of the same origin policy with relation to the document object model? *@jstnkndy*
10. Describe the basics of input and output of a block cipher. *@jstnkndy*
11. How does the Heartbleed vulnerability work? *@webbreacher*
12. How do you exploit the Shellshock vulnerability and what can an attacker do with it? *@webbreacher*

### Exploit Development ###

1. Describe what Buffer overflow is and how you would test for it? *@enddo*
2. Describe what SEH is and how you exploit it? *@enddo*
3. Describe how debugger modules and plugins can speed up basic exploit development? *@enddo*
4. How would you bypass DEP or ASLR in Windows 7? *@enddo*
5. How would you bypass SafeSEH? *@enddo*

### Mobile ###

1. Describe how you root an Android device or Jailbreak an iOS device. *@webbreacher*

### Active Directory ###

1. What is kerberoasting? *@leesoh*
2. What is a golden ticket? *@leesoh*
3. What is a silver ticket?  *@leesoh*
