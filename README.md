# Artemis-Financial-Security-Enhancement-Project
## Project Overview
This project was undertaken for Artemis Financial, a client seeking to enhance the security of their software systems. The primary objective was to identify and mitigate software security vulnerabilities, ensuring the robustness and integrity of their application.
 * **Client:** Artemis Financial, a financial services firm specializing in investment management and advisory services.
 * **Project Files:** [HERE](https://github.com/mubeenkh4u/CS-305-Artemis-Financial-Security-Enhancement-Project/tree/main/Project-Files)
## Software Requirements:
  * Secure communication channels between clients and servers.
  * Implementation of robust cryptographic methods to safeguard sensitive data.
  * Refactoring existing code to comply with modern security standards.
Key Issues: Artemis Financial required a thorough security audit of their software to address potential vulnerabilities that could expose sensitive financial data to unauthorized access. The project aimed to enhance their security posture by addressing these vulnerabilities and ensuring compliance with industry best practices.
## Security Vulnerability Assessment
**What Was Done Well:** The vulnerability assessment successfully identified critical areas where security could be compromised, particularly in input validation, cryptographic implementations, and dependency management. Secure coding practices were employed to refactor code, reducing the risk of injection attacks and improving data integrity.
**Importance of Secure Coding:** Coding securely is paramount in protecting sensitive data, maintaining user trust, and ensuring the longevity and reliability of software applications. Secure software acts as a barrier against cyber threats, safeguarding the company’s reputation and preventing financial losses due to breaches.
**Challenges and Insights:** The most challenging aspect of the vulnerability assessment was ensuring the accuracy and thoroughness of the static analysis while integrating secure coding practices without disrupting the application’s functionality. However, this process was instrumental in enhancing my understanding of secure coding frameworks and their application in real-world scenarios.
Enhancing Security Layers
### Security Enhancements:
  * **Input Validation:** Implemented strict input validation and encoding mechanisms to prevent common vulnerabilities such as SQL injection and cross-site scripting (XSS).
  * **Cryptographic Strengthening**: Integrated SHA-256 for secure data hashing, ensuring collision resistance and data integrity.
  * **Secure Communication:** Deployed a secure SSL/TLS communication channel to protect data in transit, utilizing a self-signed certificate to enforce HTTPS.
**Future Vulnerability Assessment Techniques:** In future projects, I would leverage tools like OWASP ZAP and Burp Suite for dynamic vulnerability assessment, alongside static analysis tools like SonarQube to detect and mitigate potential threats early in the development cycle. Prioritizing vulnerabilities based on risk assessment frameworks such as CVSS would guide mitigation strategies.
Ensuring Functionality and Security
Ensuring Code Integrity: After refactoring, the code was subjected to rigorous testing using both automated unit tests and manual testing to ensure that no new vulnerabilities were introduced. The Maven Dependency Check tool was used to scan for outdated or vulnerable dependencies, ensuring that the application remained secure post-refactor.
Verification of Security Enhancements: Static and dynamic testing methodologies were employed to validate that the security enhancements did not impair the application’s functionality. Continuous integration (CI) tools were utilized to automate these checks, ensuring a consistent and repeatable process.
## Tools and Practices for Future Use
  * SHA-256 for secure hashing.
  * SSL/TLS protocols for secure communication.
  * Maven Dependency Check for managing and mitigating vulnerabilities in third-party libraries.
  * OWASP guidelines as a framework for secure coding practices.
**Future Application:** These tools and practices will be instrumental in future projects, ensuring that security is integrated into every phase of software development. The use of automated testing and dependency management tools will help maintain code quality and security over time.
## Showcasing Work to Employers
Demonstrating Skills and Knowledge: For future employers, I can showcase the following from this project:
 •	Secure Coding Practices: Demonstrating the implementation of input validation, secure cryptographic methods, and secure communication channels.
 •	Vulnerability Assessment and Mitigation: Illustrating the process of identifying and mitigating software vulnerabilities.
 •	Automated Testing and Continuous Integration: Highlighting the use of automated tools to ensure code integrity and security throughout the development lifecycle.
This project not only strengthened the security of Artemis Financial’s software but also solidified my expertise in secure software development, making it a strong addition to my professional portfolio.
