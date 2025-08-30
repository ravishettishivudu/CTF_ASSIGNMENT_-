 Overview
 
 This project is part of the CTF Internship Assignment, focusing on analyzing JSON Web Token
 (JWT) vulnerabilities and implementing a secure authentication system. The repository
 demonstrates common JWT attack vectors along with a secure API implementation that follows
 best practices.
 
 Project Structure
 
 - jwt_attack_demo.py – Proof-of-Concept scripts demonstrating JWT attack techniques:
- alg=none bypass-
-  Weak secret brute-forcing-
-  Key confusion attacks-
-   secure_api.py – Flask-based secure API with the following features:-
-    User registration (/register)-
- Login and token generation (/login)-
- Protected profile access (/profile)-
- jwt_research_report.md – Research report (1–2 pages) analyzing JWT vulnerabilities and security
 mitigations.-
 README_API.md – Setup and testing instructions (includes curl examples).- README.md – Top-level documentation (this file).
 Features
- Hands-on demonstration of JWT exploitation techniques.-
- Secure API implementation following:-
- Strong secret management-
-  HS256 signing algorithm-
-  Proper token validation-
-   Documentation and testing steps for reproducibility.
-   
 Setup Instructions

 1. Clone the repository:
 git clone https://github.com/ravishettishivudu/CTF_ASSIGNMENT_-.git
 cd CTF_ASSIGNMENT_
2. Install dependencies:
 pip install -r requirements.txt
 3. Run the secure API:
 python secure_api.py
 4. (Optional) Test attack scripts:
 python jwt_attack_demo.py

Deliverables

- Attack Demonstrations → Proof-of-Concept scripts showing weaknesses in poorly implemented
 JWT systems.- Secure Implementation → Hardened Flask API resisting common JWT attacks.- Research Report → Key findings and recommended security practices.

 Security Best Practices Implemented-
 
 Enforcing HS256 algorithm- 
 Strong secret keys with sufficient entropy- 
 Proper error handling and token validation-
 Principle of least privilege in API endpoint

 Author
 
 Ravishetti shivudu
 
 Internship Assignment Submission
 
 Github: https://github.com/ravishettishivudu/CTF_ASSIGNMENT_-.git
