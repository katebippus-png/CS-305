Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  Artemis Financial was the client for this project. They work with financial and customer information, so they needed their web application to be more secure. The main goal was to find weaknesses in the application and improve things like secure communication, data protection, input validation, and outdated software dependencies.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

  I think I did well looking at both the code itself and the dependency-check report. I found issues like missing input validation and outdated dependencies. Secure coding is important because even a small weakness can turn into a bigger problem if someone takes advantage of it. For a financial company, good security also helps protect customer information and keeps trust in the company.

Which part of the vulnerability assessment was challenging or helpful to you?

  The OWASP Dependency-Check was probably the most challenging part because the report showed a lot of vulnerabilities and not all of them were equally important. I struggled a bit to figure out what was actually relevant and what could be a false positive. It was also helpful because it showed how many security problems can come from third-party libraries and not just the code I wrote myself.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  I added more security by using HTTPS, creating a self-signed certificate and adding SHA-256 hashing. I also used the dependency-check tool to look for known issues in the libraries. In the future, I would use OWASP tools, dependency reports and manual code reviews to decide which problems need to be fixed first.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  I rebuilt and ran the application after making changes to make sure everything still worked. I tested the HTTPS connection in the browser and made sure the SHA-256 checksum worked correctly. After the changes, I ran another dependency check to make sure I had not introduced any new vulnerabilities and to review what was still being reported.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

  Some of the tools I used were Maven, Java keytool, SHA-256, HTTPS certificates and OWASP Dependency-Check. I also got more practice with reviewing dependencies, checking code manually and thinking about security while developing instead of only checking for problems at the end.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show the vulnerability assessment report, the dependency-check results and the changes I made to improve the security of the application. 
