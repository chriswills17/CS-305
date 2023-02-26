# CS-305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Here, Artemis Financial deals with financial services, such as savings, retirement, investments, and insurance products. They have a RESTful web application to which they wanted security updates implemented in order to better protect against vulnerabilities. Dealing with financial data, they were right in wanting to better protect their information. 

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I became familiar with running dependency checks and extrapolating the data from these reports to determine where in the code could use refactoring or upgrading. Coding securely is imperative from the very start of development, as mitigating vulnerabilities during coding is much easier and safer than revisiting the product after it's built and in use. At that point, the program may very well have been penetrated. Due to the fact that as we rely on technology more as time goes on, hackers are more pressed to attempt to access confidential information (Jena, 2022). If companies value their data and information, they absolutely need good security practices to help mitigate the risk of unauthorized access.

What part of the vulnerability assessment was challenging or helpful to you?

Initially I had a problem creating a locally hosted server to test the application. I would have to run a Maven build before I could run a Java application for it to work, but when I moved to a different system for later assignments, I did not have that issue. It will be something configured on my original computer I need to look at to verify no issues pop up again in the future.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Through this course, we utilized implementing dependency checks, cryptography, and certificate authentication to help create a more secure environment for the server. I enjoyed the OWASP Dependency Check plug in, and will likely use that for future use due to this open source nature and its thoroughness of reporting.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

In refactoring the code, there were additional tools that needed to be imported into the program to ensure the refactoring of the code would run properly, such as Message Digest and Big Integer. Before and after refactoring and running the application, I utilized the OWASP Dependency check to gather the total number of vulnerabilities and compared the pre-factor report to the post-factor report. If both had the same number of vulnerabilities and the same vulnerabilities listed, my refactor did not introduce new vulnerabilities. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

As mentioned before, using OWASP will be helpful in the future. Learning how to generate self-signed certificates will be useful in testing secure server type of applications, and of course knowing how to implement the SHA-256 message digest cypher will help protect sensitive information future users may input.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

Aside from sharing the knowledge learned from this course verbally, I think most companies like to have a small coding test provided to demonstrate skills. Whether it's focused for software security or not, I think implementing encryption and secure client/server properties into any type of code is likely to impress employers and show them I am serious about security at any levels.


References
Jena, B. K. (2022, November 15). What Is Software Security and What Makes It So Important Now? Simplilearn.com. https://www.simplilearn.com/tutorials/cyber-security-tutorial/what-is-software-security
