# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company specializing in personalized financial planning for customers, including savings, retirement, investments, and insurance. They hired Global Rain to modernize their RESTful web API while addressing security vulnerabilities to protect sensitive financial data.

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I conducted a vulnerability assessment, properly following the directions in unison. I identified weaknesses such as hardcoded credentials, a lack of input validation, and outdated dependencies. Secure coding ensures the protections of sensitive data, compliance with law regulations, and maintains the company’s reputation.

# Which part of the vulnerability assessment was challenging or helpful to you?
Static testing with tools like the Maven Dependency-Check was both helpful and challenging.  While it gave me the run-down overview to conceptualize many common vulnerabilities and weaknesses within code, I had a very tough time getting it to work the first time. This was my first run taking Software Security, and setting up the program was extremely user unfriendly. Though I tend to enjoy working with software under reasonable deadlines and expectations. A lot of my free time is spent modding video games and making edits to the game engine. 

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use? 
I addressed the weaknesses with common recommendations that accommodate them, things such has improving input validations, updating outdated libraries, and enforcing secure API practices. In the future, I would use tools like OWASP zap for dynamic application security testing and implement a secure development lifecycle framework to continuously assess and mitigate vulnerabilities. 

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After identifying vulnerabilities, and refactoring the code. I ran the application again to see if it was working in Eclipse. I also ran another dependency check to see if any new vulnerabilities were added. I concluded that both operations ran smoothly with no new vulnerabiltiies showing up, and the refactoring code running as intended.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I mainly relied on the Maven Dependency Check tool fitted into the Eclipse coding software to analyze and document the vulnerabiltiies. The OWASP guidelines were also utilized for secure coding practices, but it was really just a lot of googling to find various articles and suggestions. 

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I can show my ability to perform comprehensive security assessments, identify and mitigate vulnerabilies, and recommend best practices. The project highlights my technical skills, knowledge of advanced security concepts, and proficiency in tools like Maven Dependency-Check and secure coding frameworks.
