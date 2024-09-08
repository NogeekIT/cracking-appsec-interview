## Hashing and Encryption

1. What's the difference between hashing and encryption?
	- One-way hashing/non-reversible
	- Encrypted data can be decrypted using keys.
2. What's your favourite programming language? And in your favourite language, what method would you use to reverse the MD5 hash?
	- To assess candidates' understanding of hashing, any type of hash cannot be reversed; it is one way.
3. Where would you use slow hashing algorithms? Explain salted hash?
	- Typically, when hashing passwords,
4. Where would you use fast hashing algorithms?
	- Message integrity checks
5. What are different types of encryption? Give an example/use-case of each? Name the encryption algorithms that you have used.
	- Symmetric
	- Asymmetric
6. A developer needs to use the AWS KMS service. What recommendations would you provide?
	- Consider key storage, whether in an HSM or in AWS internal storage; selecting between CMKs and AWS managed keys; and key rotation and revoking keys, securing access to keys

7. Have you used any key management services? How does KMS work?

8. Explain end-to-end encryption. Give an example of an app using e2e encryption.
	- Whats App	
## Authentication and Authorization

1. Explain identification and how it's different from authentication. 

2. What are the various authentication methods for web applications you have worked with?
   - Cookie-Based Authentication.
   - Token-Based Authentication.
   - Third-Party Access (OAuth, API-token)
   - OpenID Connect (OIDC)
   - Security Assertion Markup Language (SAML)
4. Explain token based authentication vs session/cookie based authentication?

5. Do you think one authentication method, like single sign-on, or multifactor authentication, cookie based, API key based is more effective than another?

3. Explain authorization. A developer needs help with a new authorization module or scheme—what would you suggest?
	- JWT's
	- ACLs
	- IAM

4. Have you worked with OAuth2/OpenID standards? What's its purpose? How does it work?

5. In the OAuth2 context, explain Resource owner, resource server, authorization server, and client application?

6. Does any framework that you have worked with support OAuth2?

- Spring Security, Laravel, and so on.


7. What is the difference between Auth0 and OAuth?

8. What do you understand about a federated identity infrastructure?

9. What are the IAM solutions and tools you prefer working with the most?

10. Have you ever implemented IAM solutions or products before?

11. How do you rename IAM policies in cloud systems?

12. How do you trace a user's activity with IAM?

13 What is the distinction between IAM policy and IAM role?

14. Difference between SOP and CORS? 
	- https://kevincox.ca/2024/08/24/cors/?utm_source=tldrnewsletter&_bhlid=526a869a4002a0b92cd6a4ee5609fce0867a5942


## OWASP TOP 10

1. Explain XSS? What are the different types of XSS and how do you prevent them?

2. What is the distinction between XSS and CSRF?

3. How would you mitigate CSRF vulnerabilities?

4. Explain indirect object references. IDOR? How would you mitigate IDOR?

5. SQL Injection Vs Blind SQL Injection? Mitigations against SQL Injections
  
6. How can an attacker exploit SSRF and what an application developer must do to prevent SSRF? how to bypass SSRF protection?
	- https://vickieli.medium.com/bypassing-ssrf-protection-e111ae70727b 

## Extras

1. How would you approach the security assessment of a web application/SPA?

2. Could you describe your process for handling client RFIs (requests for information)?

# Software Supply Chain Security

1. What is Software composition Analysis?
   - SCA tools used before, stale dependency vs top-level dependency
   - Integration challenges
   - ASPM
2. How is software supply chain security different from software composition analysis?
   
3. 

## DevSecOps

1. How would you secure a CI/CD pipeline?

2. Explain the DevSecOps approach.

## API Security

1. What have you done so far for API Security?
   - experince with Api security scanners
   - API inventory, API security testing etc

2. What is BOLA? How is BOLA different from IDOR?
   - https://shoutrange.com/insights/bola-vs-idor-what-is-the-difference#:~:text=Contextual%20Relevance%3A%20IDOR%20is%20often,a%20more%20granular%20object%20level
  
3. Explain Broken Funcation Level Access (BFLA)?
   - certain function level access are avail to special users - like admin, super admins


## Secure Development

1. A developer is working on a payment app, and BA/dev needs your assistance in gathering security requirements. What would you consider?

2. What's your experience with software development methodologies?
	- agile, scrum, devOps model, kanban, waterfall

3. What is the difference between static and dynamic analysis?

4. Why are code reviews performed? How would you conduct a manual code review?

5. Which SAST and DAST tools have you used? How would you triage SAST, DAST findings?

6. Have you used the SAST tool with cloud native applications? Tell me more about that experience?

7. What is threat modeling? Why do we conduct threat modelling?

8. How would you threat model a web application or payment app?

9. Difference between an Object and class?

10. What's the difference between a session and a cookie?


## General

1. What's the most difficult problem that you have fixed in your previous role?

2. What's one challenge you experienced in your previous role?

3. Can you recall any recent vulnerabilities you discovered/read? 

4. How would you relate the severity of an issue to business risk?

5. How would you persuade stakeholders from various backgrounds to prioritise fixes for the issues you discovered?

6. What challenges could you face while performing a security assessment of a web application?

**Case Study**

Scenario:
Your organisation has a critical legacy web application that has been in production for over a decade.
While it still serves its purpose, its security posture is outdated and vulnerable to modern attack vectors. You've been tasked assessing and remediating the application's security vulnerabilities.

Initial Assessment:

* How would you approach the initial assessment of the application's security? What tools and techniques would you employ?
* What specific vulnerabilities would you prioritise for immediate attention, given the application's age and complexity?

Risk Assessment: 

* What factors would you consider when determining the severity and priority of vulnerabilities?
* How would you conduct a comprehensive risk assessment to understand the potential impact of vulnerabilities on the business?

Remediation Strategy: 

* Outline a remediation strategy that balances security improvements with the need to maintain the application's functionality.
* How would you address legacy components or dependencies that may be difficult to replace or update?

Secure Development Lifecycle (SDLC):

* How would you integrate secure coding practices and automated testing into the application's development and maintenance processes?
* What specific tools or frameworks would you recommend for implementing a secure SDLC?

Incident Response:

* Develop an incident response plan for the application, considering potential security breaches and data leaks.
*  What key stakeholders would be involved in the incident response process, and what are their roles and responsibilities?


