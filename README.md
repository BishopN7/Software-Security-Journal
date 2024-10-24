# Software-Security-Journal
This repository gives a glimpse on what I have learned in regards to software security. 

**Question 1: Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**
Artemis Financial is a consulting company that deals in financial plans that are customized for each of their cuustomers. When it comes to their software requirements,
security is one of the main issues that they need to have addressed. Their financial plans include savings, retirements, investments, and insurance. It seeks Global Rain's
expertise in designing an effective security system, since Artemis has a public web interface. Specifically, speaking they want to add a verification step authentication, 
so that communications are secure. 

**Question 2: What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**
When it came to reviewing the software files, one approach that I took was running a vulunerability check. This revealed a bunch of susceptible errors in the code, so that it would be patched later. Typcially, in software security, developers are responsible for ensuring that there are no open-ended pathways that hackers can use to install malware within their code. Sometimes, even zero day attacks can occur. By definition, it is a cyberattack that hackers use to exploit an unknown code vulnerability, and where it is not discovered by developers. Therefore, it has no patch nor fix. It's crucial to secure code, so that it is not exploited or manipulated by those who seek to cause cyber-harm. Software security adds assurance and protection to those who seek to keep their sensitive information private and secure. It can range from bank accounts to even business records; all depends really.

**Question 3: Which part of the vulnerability assessment was challenging or helpful to you?**
From my experience, it was trying to understand what each vulnerabiity did in terms of their risk probability. When I ran dependency-check reports via Eclipse, it got frustrating for me,
because I was trying to get used to how it operates. It was an entirely new concept for me to learn, and it took time for me understand. 

**Question 4: How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**
When it came to working towards the main goal of adding authentication for Artemis's public web interface, we had to figure out what would be the best solution. 
Most developers that work in this field, tend to utilize what is known as multi-factor authentication, and even biometrics. So, our chosen path was to increase
the layer of security by implementing stronger authentication mechanisms, so that verification checks were met by the user trying to log in. In the future, when 
it comes to assessing vulnerability and deciding mitgation techniques, what I would use are automated scanning tools, threat intelligence platforms, security frameworks,
etc. All of these resources will help to contribute to even other companies, that may need their products to be secure within their designed code and structure.

**Question 5: How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**
Simply, through a combination of testing, security validation, and continuous monitoring. Functional testing involved analyzing each individual component, followed by integration and regression testing
to ensure that the refactored code was working as expected. That included software penetration testing to simulate real-world scenarios, so that the system would get used to what is occurring. In addition, we
also used OWASP to identify run-time security vulnerabilities within the files, through the third-party librarries. 

**Question 6: What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**
So, through the use of automated testing tools, security scanning, code quality and review practices, continuous integration, and team collaboration, it can better help me
to incorporate those practices into what I may innovate in future projects. It takes me to put more effort in to make it happen. 

**Question 7: Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**
From this assignment, I may show them what I have done so far, in terms of my effort in practicing software security techniques. As mentioned earlier, this still takes time for me to even comprehend on a 
developer level. But, if I were to develop other applications along with security practices that I learned over the course of these past few months, then I would also include it in GitHub. In fact, I even designed
my own currency converter program in C++ just for fun, because I wanted to experiment and mess around with what I can do, as far as code goes. 
