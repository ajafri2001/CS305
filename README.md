# CS305

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

Artemis Financial is a financial firm that develops digital financial services for consumers, allowing them to select plans based on their individual needs. The company wanted to ensure that the information exchanged between clients and the system remained confidential, authentic, and secure from unauthorized access. The main issue Artemis Financial needed addressed was improving the security of their software by identifying and mitigating potential vulnerabilities through secure coding practices and encryption mechanisms.

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**

During the vulnerability assessment, I successfully identified security weaknesses using dependency testing tools that detect outdated or insecure libraries. I also verified the project’s build dependencies to ensure they did not introduce known vulnerabilities. Coding securely is vital because it minimizes weak points that attackers could exploit. Secure software increases consumer trust, reinforces the company’s credibility, and ultimately strengthens its overall business reputation and stability.

**Which part of the vulnerability assessment was challenging or helpful to you?**

One of the more challenging aspects of the assessment was identifying false positives in the vulnerability reports. Distinguishing between real and non-critical issues required careful analysis of dependency details, severity levels, and context. However, this process helped me better understand how automated tools report vulnerabilities and how to validate their results accurately.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

To increase the security layers, I implemented an SSL certificate to ensure encrypted communication over HTTPS and verified that the application used secure HTTPS POST methods for data transfer. In the future, I plan to continue using automated dependency checks, static code analysis, and manual code reviews to assess vulnerabilities. I will also focus on validating false positives more effectively and applying appropriate mitigation techniques such as updating dependencies, patching libraries, and following secure coding guidelines.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

To confirm that the software was both functional and secure, I ran the project multiple times during the testing phase and re-ran dependency checks after each refactor. This ensured that no new vulnerabilities were introduced during code changes. Each iteration of the project included a verification process to confirm that security and functionality were preserved.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

The most helpful resource throughout the process was running and testing the application directly within Eclipse’s environment. Automated tools like OWASP Dependency-Check proved valuable for identifying insecure libraries. Adhering to secure coding practices, such as validating input, using HTTPS, and maintaining updated dependencies, will be essential in future projects.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

For future employers, I would showcase my Vulnerability Assessment Report from this project. It demonstrates my ability to identify, interpret, and mitigate software security issues, as well as my understanding of secure software development practices. This report highlights my technical and analytical skills in creating reliable, secure applications that align with professional software engineering standards.
