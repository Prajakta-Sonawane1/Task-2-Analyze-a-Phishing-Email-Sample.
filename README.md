# Task-2-Analyze-a-Phishing-Email-Sample.
Phishing Email Header &amp; Body Analysis Task


Return-Path: <hr@company-payroll.com>
Received: from smtp49.freehosters.net (203.0.113.45)
Authentication-Results: spf=fail dkim=none dmarc=fail
Subject: Payroll Verification Required
From: HR Support <hr@company-payroll.com>
To: employee@company.com
Date: Mon, 20 Oct 2025 10:23:11 +0530


Sender Email	hr@company-payroll.com
	Unknown domain
Return-Path	bounce@company-payroll.com
	Doesn’t match official HR
URL	hxxps://company-payroll.com.login-verify[.]xyz	Fake domain
IP	203.0.113.45	Public hosting
Attachment	invoice.docm	Macro malware risk

“Dear Employee, please verify your payroll information immediately at the link below.”
Link → https://company-payroll.com.login-verify.xyz/update

**Suspicious indicators:**
Domain login-verify.xyz pretending to be company-payroll.com
Urgent tone, fake login site.
