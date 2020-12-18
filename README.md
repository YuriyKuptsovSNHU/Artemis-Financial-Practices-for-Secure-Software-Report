# Artemis-Financial-Practices-for-Secure-Software-Report
### Project for 2, CS-305

## Artemis Financial Practices for Secure Software Report

*Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?*

Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their patrons. Artemis Financial’s desire to modernize its operations and as a crucial part of the success of their custom software, they want to implement and apply the most current and effective software security. Artemis Financial is seeking to add a file verification step to their web application to ensure secure communications, they will need a data verification step in the form of a checksum.

*What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?*

I identified that the client needed an SSL compliant website and a certificate for SSL. I also identified that the client needed a secure checksum. I created an SSL server, a certificate for the server, and implemented a file verification step employing the SHA-256 Cipher to generate a checksum.
The changes I implemented improved the company’s overall wellbeing by using a secure transport layer for communications and a secure method to verify files.
Coding securely is essential to eliminating intrusion threats and violations of data privacy.

*What about the process of working through the vulnerability assessment did you find challenging or helpful?*

I found the existence and easy incorporation of a vulnerability assessment tool, based on data from NIST, very helpful and convenient. The challenging aspect is identifying whether a specific vulnerability applies to the particular instance of code (does the code engage in the use that has been found to be vulnerable and are the steps taken to protect against the exploit sufficient?).

*How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?*

I used the Vulnerability Assessment Process Flow Diagram to guide my approach to discovering and eliminating vulnerabilities combined with the NIST vulnerabilities report. I believe I will continue to use this approach in the future unless I encounter a better approach.

*How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?*

I reviewed the initial vulnerabilities report and then reviewed the code to determine whether the application was vulnerable to the reported vulnerabilities. In any cases where said vulnerabilities were discovered, I read the recommended solutions to the vulnerabilities and modified the code to protect against them. After refactoring, I once again assessed the application for vulnerabilities and reiterated the process. I also tested the software through manual testing.

*What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?*

I used best programming practices and the MAVEN “dependency-check-maven” plugin to eliminate/discover vulnerabilities.

*Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?*

I would showcase my implementation of the checksum using the SHA-256 Cipher.
