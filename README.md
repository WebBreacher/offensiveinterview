# Purpose
Collect a large sampling of interview questions to screen offensive (red team/pentest) candidates

If you are a candidate and looking to find some good questions to ask employers, visits @doctorj's page here: [https://gitlab.com/doctorj/interview-questions/blob/master/interview-questions.yml](https://gitlab.com/doctorj/interview-questions/blob/master/interview-questions.yml)

# Contributing
1. Use the standard method of forking this repository, making your changes and doing a "pull" request to have your content added
   - Format your questions as a numbered list, the question, your name (*@name*) if you'd like attribution, then any directions for the interviewer *in italics*. These are directions on what to look for or how to ask the question not answers to the questions.
   - Examples:
      1. "What is CSRF and how is it different from XSS?" *@webbreacher*
      1. "I have a /24 subnet on the Internet. You are a pentester. Tell me, start to finish, how you would execute this assessment." *@webbreacher* *Look for everything from scoping meeting and rules of engagement to the depth/detail of their responses.*
2. Alternatively, if you just want to copy/paste your content, we'll take that too! [Create an "Issue"](https://github.com/WebBreacher/offensiveinterview/issues) with your content and we will add for you. Please tell us if you'd like attribution ("this question came from @johndoe") or not.

# Organization
Questions should be organized (right now at least) in a couple different formats:

1. [Open-ended Questions](https://github.com/WebBreacher/offensiveinterview/blob/master/open.md)
   - These questions have multiple methods of achieving a "correct" response. 
   - Examples:
      - "Describe how you would compromise a victim's laptop using a phishing attack."
      - "What would you do once you successfully got a shell on a database server?"
2. [Knowledge-based Questions](https://github.com/WebBreacher/offensiveinterview/blob/master/knowledge.md)
   - There is a specific right and wrong answer for these questions.
   - Examples:
      - "What is CSRF and how is it different from XSS?"
      - "What are the primary differences between ```netcat``` and ```ncat```?"
3. [Scenario-based Questions](https://github.com/WebBreacher/offensiveinterview/blob/master/scenario.md)
   - These questions are ones in which the interviewer sets up a situation and allows the candidate to respond. During their responses, the interviewer adds (more information | emulates a client | tells the candidate what happens when they take an action) in order to more fully understand the breadth and depth of a candidate's knowledge.
   - Examples:
      - "I have a /24 subnet on the Internet. You are a pentester. Tell me, start to finish, how you would execute this assessment."
      - "You have just compromised a Mac OS X laptop inside a corporate user subnet. Your goal is to exfiltrate Active Directory hashes. How do you accomplish this?"
4. [Other Questions](https://github.com/WebBreacher/offensiveinterview/blob/master/other.md)
   - These questions do not fit in the other categories. 
   - Examples:
      - *Right now I have no examples of this but you may!*

# License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
