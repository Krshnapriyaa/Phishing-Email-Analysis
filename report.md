# Phishing Email Analysis Report

Student: krishna 
Task: Task 2 — Phishing Email Analysis  
Date: 2025-09-24

---

 1. Email sample
Attached file: `sample_phish.txt` (or screenshot `email_screenshot.png`)

Subject: Urgent: Account Suspended — Verify Now  
From: support@paypa1.com  
To: student@example.com  
Date: Mon, 22 Sep 2025 09:12:03 +0000

---

2. Observed phishing indicators
1. Spoofed sender address: `support@paypa1.com` (typo: paypa1).  
2. Urgent language: "verify your account within 24 hours" — pressure to act.  
3. Suspicious link: `http://secure-paypal-login.xyz` — domain not PayPal.  
4. Generic greeting: "Dear Customer" (not personalized).  
5. HTML email with link to external domain.

---

3. Header analysis
If available, paste output or screenshot of header analyzer here.*  
- SPF: FAIL (example)  
- DKIM: none / FAIL (example)  
- Received-from IP: 198.51.100.25 (example) — not associated with paypal.com

---

4. Link/attachment analysis
- Link text and actual URL mismatch.  
- No attachments present (or list suspicious attachment names if any).

---

5. Conclusion
This message is a phishing attempt using domain spoofing, urgent language, and a malicious link designed to harvest credentials.
