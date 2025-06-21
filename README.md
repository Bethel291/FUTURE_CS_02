FUTURE_CS_02 - Phishing Simulation using Gophish

This project is part of my cybersecurity internship under the Future Interns program. The goal of this task was to simulate a phishing campaign to assess how users respond to social engineering attacks.

---

Objective:

Simulate a phishing email campaign using Gophish and analyze user interactions such as email opens, link clicks, and credential submissions.

---

Tools Used:

- Gophish (Self-hosted phishing framework)
- Gmail (for testing purposes)
- HTML (for crafting email and landing page templates)

---

Setup Details:

- Target Email: bethelamankwah00@gmail.com
- Campaign Name: Task 2 - Future Interns Phishing Simulation
- SMTP Used: Gmail SMTP (via App Password)
- Landing Page: Fake Microsoft Login Page
- Email Template: Account Verification Notice

---

Landing Page Description:

The phishing page mimicked a Microsoft login interface and captured email and password inputs submitted by the target.

---

Phishing Email Template:

Subject: Action Required: Verify Your Account Immediately

Email Body:
Dear User,

We have detected unusual activity in your account and need you to verify your login details immediately to avoid suspension.

[Verify Account] (link inserted via Gophish {{.URL}} placeholder)

---

Results:

- Email Delivered: ✅
- Link Clicked: ✅
- Credentials Captured: ✅

---

Skills Gained:

- Social engineering awareness
- Phishing campaign planning
- Gophish setup and operation
- Ethical phishing simulation
- HTML email crafting

---

Conclusion:

This simulation highlights the importance of training users to identify suspicious emails and avoid falling for phishing attempts. Organizations should enforce two-factor authentication, email filtering, and employee awareness programs.

