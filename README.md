# CS-305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Here, Artemis Financial deals with financial services, such as savings, retirement, investments, and insurance products. They have a RESTful web application to which they wanted security updates implemented in order to better protect against vulnerabilities. As a client of my employer, Global Rain,  I was tasked with upgrading the security to their application. Dealing with financial data, they were right in wanting to better protect their information. 

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I became familiar with running dependency checks and extrapolating the data from these reports to determine where in the code could use refactoring or upgrading. I was also able to implement suppression of false positives to reduce the reporting to legitimate vulnerabilities that could be addressed. Coding securely is imperative from the very start of development, as mitigating vulnerabilities during coding is much easier and safer than revisiting the product after it's built and in use. At that point, the program may very well have been penetrated. Due to the fact that as we rely on technology more as time goes on, hackers are more pressed to attempt to access confidential information (Jena, 2022). If companies value their data and information, they absolutely need good security practices to help mitigate the risk of unauthorized access and unnecessary loss of financials and public opinion.

What part of the vulnerability assessment was challenging or helpful to you?

Initially I had a problem creating a locally hosted server to test the application. This was something experienced by another student in the course as well. I would have to run a Maven build before I could run a Java application for it to work, but when I moved to a different system for later assignments, I did not have that issue. It could possibly be something configured on my original computer I need to look at to verify no issues pop up again in the future. I also initially had some trouble identifying which of the VAPFD were to be the security aspects that applied to particular sets of code. I had thought that every aspect of the VAPFD was important to all types of code, but as time passed and with instructor feedback, I was able to better determine which particular security aspects were relevant to the situation.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Through this course, we utilized implementing dependency checks, cryptography, and certificate authentication to help create a more secure environment for the server. Through OWASP, we were able to determine existing vulnerabilities that needed address. We added SHA-256 messaged digest encryption to better protect potential user input as opposed to using plain text. In using certificate generation and authentication, we added SSL and HTTPS that will authenticae connections between the server and clients. I enjoyed the OWASP Dependency Check plug in, and will likely use that for future use due to this open source nature and its thoroughness of reporting.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

In refactoring the code, there were additional tools that needed to be imported into the program to ensure the refactoring of the code would run properly, such as Message Digest and Big Integer. Paying attention to the Errors panel helped me out tremendously by indicating which lines of code needed to be revisited. Using Eclipse for this feature has been thoroughly beneficial, as it helps create working code before any building occurs. Before and after refactoring and running the application, I utilized the OWASP Dependency check to gather the total number of vulnerabilities and compared the pre-factor report to the post-factor report. If both had the same number of vulnerabilities and the same vulnerabilities listed, my refactor did not introduce new vulnerabilities. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

As mentioned before, using OWASP will be helpful in the future. Plugging in the dependency check to the POM.xml file will be incredibly useful for future code vulnerability checks. Learning how to generate self-signed certificates will be useful in testing secure server type of applications. Of course knowing how to implement the SHA-256 message digest cypher will help protect sensitive information future users may input compared to attempting to compare plain texts values for validation. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

Aside from sharing the knowledge learned from this course verbally, I think most companies like to have a small coding test provided to demonstrate skills. They will ask to create a small program to demonstrate proficiencies in a particular subject or general skills. Whether it's focused for software security or not, I think implementing encryption and secure client/server properties into any type of code is likely to impress employers and show them I am serious about security at any levels. Coding securely from the onset of development immensely indicates skill and knowledge of programming.


References
Jena, B. K. (2022, November 15). What Is Software Security and What Makes It So Important Now? Simplilearn.com. https://www.simplilearn.com/tutorials/cyber-security-tutorial/what-is-software-security
