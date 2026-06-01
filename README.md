Task 2 - Phishing Email Analysis
Cyber Security Internship | ElevateLabs

📌 Objective
Identify and analyze phishing characteristics in a suspicious email sample to develop awareness of email-based cyber threats.

🛠️ Tools Used
ToolPurposeMxToolbox Header AnalyzerAnalyze raw email headersGoogle Admin ToolboxVerify SPF / DKIM / DMARCVirusTotalScan suspicious URLsWhoisXMLCheck domain registration info

📧 About the Sample Email
A phishing email impersonating PayPal was analyzed. The email attempted to steal sensitive financial and personal information by:

Faking the sender address using typosquatting (paypa1 instead of paypal)
Creating urgency with threats of account suspension
Directing victims to a malicious URL


🔍 Phishing Indicators Found
#IndicatorSeverity1Spoofed sender domain (paypa1)🔴 High2Malicious URL with fake domain (.xyz)🔴 High3Urgent and threatening language🔴 High4Requesting sensitive info (card, SSN)🔴 High5Spelling and grammar errors🟡 Medium6SPF / DKIM / DMARC all FAILED🔴 High7Email sent at 3 AM (unusual time)🟡 Medium8Generic greeting used🟡 Medium
Verdict: ⛔ CONFIRMED PHISHING EMAIL

📂 Files in This Repository
FileDescriptionphishing_email_sample.txtThe sample phishing email with raw headersphishing_analysis_report.mdDetailed analysis of all phishing indicatorsREADME.mdProject overview (this file)

💡 Key Concepts Learned

Phishing — impersonating trusted entities to steal information
Email Spoofing — forging sender address to appear legitimate
Typosquatting — using misspelled domains (paypa1 vs paypal)
Social Engineering — urgency, fear, and authority manipulation
SPF / DKIM / DMARC — email authentication mechanisms
Header Analysis — detecting discrepancies in email metadata


🛡️ How to Stay Safe

Never click links in unsolicited emails
Always verify the sender's email domain carefully
Check for SPF/DKIM/DMARC using header analyzers
Never share sensitive info via email
Report phishing emails to your IT/security team
