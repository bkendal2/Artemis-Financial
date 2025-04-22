Artemis Financial is a consulting company that provides personalized financial planning services, including savings, retirement, investment, and insurance plans. The company partnered with Global Rain, a custom software development firm, to modernize its operations and improve the security of its web-based application. Specifically, Artemis wanted to ensure that sensitive client data was protected through the implementation of secure communication and verification mechanisms.

During the project, I identified and addressed several software security vulnerabilities in Artemis Financial’s application. I successfully implemented encryption using 128-bit AES and added checksum functionality for data verification. These steps are essential because secure coding protects against data breaches, preserves user trust, and helps a company avoid legal and financial consequences associated with insecure systems.

One of the more challenging parts of the vulnerability assessment was configuring and using tools like OWASP Dependency-Check and generating a self-signed SSL certificate using Java Keytool. However, these were also some of the most helpful learning experiences, as they gave me hands-on experience with real-world security practices.

I increased the application’s security by enabling HTTPS communication, generating encryption keys, and using secure hash algorithms to verify data. In the future, I would use both static and dynamic analysis tools and threat modeling to assess vulnerabilities and select appropriate mitigation techniques.

After refactoring the code, I verified that the application was still functional and error-free by running it and checking responses over HTTPS. I also used the Dependency-Check plugin to confirm that no new security vulnerabilities were introduced. Manual code reviews and testing also played a role in validating the changes.

Some of the most useful tools and practices included Eclipse, Maven, Java Keytool, Spring Boot, and OWASP Dependency-Check. Secure coding guidelines, like avoiding hardcoded credentials and validating input, were also helpful and will be valuable in future development work.

This assignment is a strong portfolio piece because it shows my ability to conduct a vulnerability assessment, apply encryption, configure secure communications, and follow industry-standard secure coding practices. It demonstrates technical knowledge, critical thinking, and an understanding of real-world security concerns—skills that are highly valuable to future employers.
