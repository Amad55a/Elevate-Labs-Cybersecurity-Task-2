# Task 2: Analyze a Phishing Email Sample

**Program:** Elevate Labs Cybersecurity Internship  
**Task:** Phishing Email Analysis  
**Sample Type:** Simulated Training Email

## 1. Objective

Identify phishing characteristics in a suspicious email and learn how to examine sender information, email headers, links, attachments, and message content.

## 2. What is Phishing?

Phishing is a cyberattack in which an attacker pretends to be a trusted person or organization to trick people into sharing sensitive information, clicking malicious links, or opening harmful attachments.

## 3. Email Sample

The following is a fictional training example.

**From:** security-alert@account-verification-example.com  
**Subject:** URGENT! Your account will be suspended today!

**Message:**

Dear Customer,

We detected unusual activity in your account. Your account will be permanently blocked within 24 hours.

To avoid suspension, verify your account immediately by clicking the link below:

http://account-verification-example.com/login

Failure to verify will result in permanent account closure.

Thank you,  
Security Support Team

## 4. Phishing Indicators Found

| Indicator | Observation |
|---|---|
| Suspicious sender | Unfamiliar sender domain |
| Urgent language | Uses "URGENT" and a 24-hour deadline |
| Threatening language | Threatens permanent account closure |
| Suspicious link | Unfamiliar account-verification URL |
| Generic greeting | Uses "Dear Customer" |
| Sender identity | No clearly identified organization |
| Attachment | No attachment included |

These characteristics suggest phishing because the message uses fear and urgency to pressure the recipient into clicking an unfamiliar link.

## 5. Email Header Analysis

Email headers help identify the source and route of a message.

Important fields include:

- **From:** Sender address.
- **Return-Path:** Email return address.
- **Received:** Mail server routing information.
- **SPF:** Checks whether the sending server is authorized.
- **DKIM:** Checks the email's digital signature.
- **DMARC:** Checks domain alignment and authentication policy.

Header analysis tools:

- [Google Admin Toolbox Messageheader](https://toolbox.googleapps.com/apps/messageheader/)
- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

**Important:** This is a simulated email. No original email headers were provided, so SPF, DKIM, DMARC, and sender spoofing could not be verified.

## 6. Suspicious Link Analysis

The email contains this link:

http://account-verification-example.com/login

The domain is unfamiliar and asks the recipient to verify an account. It should not be clicked.

The destination was not tested. No attachment was included in the sample.

## 7. Social Engineering Techniques

The email uses:

- **Fear:** Threatens account closure.
- **Urgency:** Gives a 24-hour deadline.
- **Trust:** Pretends to be a security support team.
- **Pressure:** Encourages immediate action.

## 8. Recommended Actions

1. Do not click suspicious links.
2. Do not open unexpected attachments.
3. Verify the sender using official contact information.
4. Report suspicious emails to the IT/security team.
5. Never share passwords or sensitive information through unexpected email links.

## 9. Conclusion

The sample contains several common phishing indicators, including an unfamiliar sender, urgent language, threatening messages, a generic greeting, and a suspicious link.

This exercise demonstrates how to recognize phishing attempts and respond safely.

**Scope:** This is a simulated training exercise, not a forensic analysis of a real phishing email.
