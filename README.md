# Artemis Financial Security Enhancement Project

## Project Overview
This project focused on enhancing the security of Artemis Financial’s web application, which serves as a key tool in delivering personalized financial plans for clients. The security enhancements addressed potential vulnerabilities in the application’s data handling and transmission mechanisms to ensure the protection of sensitive financial data and maintain client trust.

## Client and Requirements Summary
**Client**: Artemis Financial  
**Objective**: To enhance the security of Artemis Financial's web application by identifying and addressing software vulnerabilities to protect sensitive client data.

Artemis Financial is a consulting firm specializing in creating tailored financial plans. Their software requirements included a need for robust security features to safeguard client data during web transactions. Specifically, they required a comprehensive vulnerability assessment and the implementation of secure coding practices to prevent data breaches and support compliance standards.

## Success in Identifying Vulnerabilities
Through a meticulous security assessment, I identified several vulnerabilities in the software, such as outdated dependencies and specific data handling risks. This analysis emphasized the importance of secure coding practices. Addressing these vulnerabilities helped improve Artemis Financial's digital security posture, which is critical for building trust with clients and maintaining a resilient software environment.

## Challenges and Learning Opportunities
One of the key challenges in this project was accurately identifying and handling false positives in the dependency check results. This process required a deep understanding of how each dependency was utilized in the project, which enhanced my skills in vulnerability analysis and expanded my knowledge of security practices within real-world applications.

## Increased Security Layers
To add layers of security to the application, I implemented SSL/TLS protocols to secure communications, generated self-signed certificates, and used the SHA-256 algorithm for checksum generation. In future projects, I would consider using advanced tools such as OWASP ZAP for dynamic analysis and SonarQube for static code analysis. I would also continue to use vulnerability scanning tools like OWASP Dependency-Check for efficient identification and mitigation of security risks.

## Functional and Secure Code Assurance
After refactoring the code to resolve identified vulnerabilities, I performed extensive functional tests and ran the dependency check tool to validate the code’s security. This process ensured that no new vulnerabilities were introduced and that the application remained fully functional, meeting the secure communication standards required by Artemis Financial.

## Resources, Tools, and Coding Practices for Future Use
The following resources and tools were instrumental in this project:
- **Maven Dependency-Check**: For identifying known vulnerabilities in dependencies.
- **Java Keytool**: For generating self-signed SSL certificates to enable HTTPS.
- **Tomcat's HexUtils**: For converting SHA-256 hash bytes to hexadecimal strings, ensuring secure checksum verification.

These tools and secure coding practices, including dependency suppression and secure HTTPS communication, provide a solid foundation for maintaining application security. I will continue to use these resources in future assignments and projects.

## Artifacts to Show Future Employers
This project demonstrates my ability to conduct detailed vulnerability assessments and implement secure coding practices. My work in identifying, analyzing, and mitigating security risks is reflected in the project report and codebase. This experience is invaluable for a career in software development and security, showcasing my commitment to creating secure and reliable software solutions.
