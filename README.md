# Task 2: Phishing Email Analysis

## Objective
The objective of this task is to analyze a phishing email sample and identify common phishing indicators such as email spoofing, suspicious links, urgency, and social engineering techniques.

## Tools Used
- Sample phishing email (text file)
- Manual analysis
- Online header analysis

## Phishing Email Overview
The analyzed email claims to be from **Payoneer** and informs the recipient about a received payment of **$9100**. The email urges the recipient to verify their account within 24 hours to prevent the payment from being returned.

## Analysis Performed

### 1. Sender Address Analysis
The email appears to be from Payoneer, but the sender address uses a third-party domain:
payoneer.gps@alerting-services.com

Legitimate Payoneer emails are expected to originate from the official `@payoneer.com` domain. This indicates **email spoofing**.

### 2. Urgent and Threatening Language
The email uses urgency to pressure the recipient:
- Mentions a **24-hour deadline**
- States the payment will be returned if verification is not completed
- Includes a countdown start time

This is a common **social engineering tactic** used in phishing attacks.

### 3. Suspicious Verification Link
The email includes a verification link and instructs the user to log in via the email:
http://payouts.payoneer.com/Verify/Gateway.aspx

Requesting account verification through email links is unsafe and commonly used to steal credentials.

### 4. Social Engineering Techniques
The attacker uses a **large payment amount ($9100)** to create excitement and panic, encouraging the victim to act quickly without verification.

### 5. Lack of Personalization
The email does not address the recipient by name and uses generic language, which is typical of mass phishing campaigns.

### 6. False Sense of Legitimacy
A professional tone and legal disclaimer are included to make the email appear authentic, even though these do not guarantee legitimacy.

## Conclusion
The email contains multiple phishing indicators including sender spoofing, urgency, suspicious links, lack of personalization, and social engineering tactics. Based on this analysis, the email is identified as a **phishing attempt** intended to steal user credentials.

## Learning Outcome
Through this task, I gained practical experience in identifying phishing emails, understanding common attacker techniques, and analyzing email-based threats to improve cybersecurity awareness.
