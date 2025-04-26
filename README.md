# CS-305-Module-Eight-Journal
Client Summary:
The client for this project was Artemis Financial, a company focused on providing secure financial services to its customers. Artemis needed help ensuring that their SSL server application remained protected against vulnerabilities. Their main concern was maintaining secure communication between clients and servers by updating their codebase and verifying that no known security flaws existed.

Software Security Approach:
During the assessment, I identified and mitigated vulnerabilities by implementing OWASP Dependency-Check, updating project dependencies, and securing the server’s SSL configurations. I focused on preserving the existing security of the application while strengthening areas that could be improved. Practicing secure coding standards ensures data confidentiality and integrity, which is critical for any company dealing with sensitive information. Strong software security reduces operational risks, protects customer trust, and reinforces a company's long-term success.

Challenges and Insights:
One of the more challenging but rewarding aspects of this project was setting up and running the dependency scanning tool correctly. It highlighted just how important it is to stay alert to third-party risks and provided a clear path for addressing them. This experience showed me that vulnerability management is not a one-time task but an ongoing process.

Security Enhancements:
To strengthen security, I configured SSL encryption through a properly secured keystore and verified that communications occurred over HTTPS. Going forward, I would incorporate additional security scanning tools, such as dynamic application security testing (DAST), to catch vulnerabilities during live application testing and prioritize remediation based on severity.

Maintaining Application Integrity:
After refactoring, I thoroughly tested the application to confirm that it launched successfully and that secure endpoints remained active. I also re-ran the dependency-check report to ensure that no new vulnerabilities had been introduced during my changes, maintaining both functionality and security.

Resources and Tools:
I relied heavily on Maven for build automation, OWASP tools for vulnerability analysis, and SSL/TLS configuration best practices. These tools provided strong support and would definitely be assets for future security assessments and coding projects.

Work Showcase for Employers:
This project would make a great portfolio example to demonstrate my skills in secure coding, vulnerability assessment, and problem-solving. It highlights my ability to work with real-world security tools, update legacy codebases securely, and document my process clearly, all of which are highly valuable to potential employers in the cybersecurity or software development fields.
