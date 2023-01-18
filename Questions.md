## Hashing and Encryption

1. What's the difference between hashing and encryption? 
   - One-way hashing/non-reversible
   - Encrypted data can be decrypted using keys.
2. What's your favourite programming language? And in your favourite language, what method would you use to reverse the MD5 hash?
   - To assess candidates' understanding of hashing, any type of hash cannot be reversed; it is one way.
3. Where would you use slow hashing algorithms? Explain salted hash?
  - Typically, when hashing passwords,
   - 
4. Where would you use fast hashing algorithms?
   - Message integrity checks
5. What are different types of encryption? Give an example/use-case of each? Name the encryption algorithms that you have used.
   - Symmetric
   - Asymmetric
6. A developer needs to use the AWS KMS service. What recommendations would you provide?
- Consider key storage, whether in an HSM or in AWS internal storage; selecting between CMKs and AWS managed keys; and key rotation and revoking keys, securing access to keys

7. Have you used any key management services? How does KMS work? 

8. Explain end-to-end encryption. Give an example of an app using e2e encryption.

## Authentication and Authorization

1. Explain identification and how it's different from authentication.

2. What are the various authentication methods you have worked with?

3. Do you think one authentication method, like single sign-on, two-factor authentication, or multifactor authentication, is more effective than another?

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


## OWASP TOP 10

1. Explain XSS? What are the different types of XSS and how do you prevent them?

2. What is the distinction between XSS and CSRF?

3. How would you mitigate CSRF vulnerabilities?

4. Explain indirect object references. IDOR? How would you mitigate IDOR?

## Extras

1. How would you approach the security assessment of a web application/SPA? 

2. Could you describe your process for handling client RFIs (requests for information)?

3. How would you secure a CI/CD pipeline? 

4. Explain the DevSecOps approach.

5. What's the difference between a session and a cookie?


## Secure Development

A developer is working on a payment app, and BA/dev needs your assistance in gathering security requirements.What would you consider?

What's your experience with software development methodologies? 
 - agile, secure SDLC, devOps model 

What is the difference between static and dynamic analysis?

Why are code reviews performed? How would you conduct a manual code review? 

Which SAST and DAST tools have you used? How would you triage SAST, DAST findings?

Have you used the SAST tool with cloud native applications? Tell me more about that experience? 

What is threat modeling? Why do we conduct threat modelling? 

How would you threat model a web application or payment app?


## General
What's one challenge you experienced in your previous role?

Can you recall any vulnerabilities you discovered? How did you fix it?

How would you relate the severity of an issue to business risk?

How would you persuade stakeholders from various backgrounds to prioritise fixes for the issues you discovered?

What challenges could you face while performing a security assessment of a web application?





