🏥 Healthcare Revenue Cycle & Denial Analytics (SQL)
🚀 Project Overview
As a former US Healthcare Payment Posting Specialist transitioning into Data Analytics, I developed this project to demonstrate how SQL can be used to optimize the Revenue Cycle Management (RCM) process.

This project simulates a real-world billing environment where I identify "leaking revenue" by analyzing insurance denials, aged receivables (AR), and payer performance.

🛠️ Technical Skills Demonstrated
Relational Database Design: Created a structured schema with PRIMARY KEY and FOREIGN KEY constraints to ensure patient-claim integrity.

Data Filtering & Logic: Advanced use of IS NULL, IN, and BETWEEN operators to isolate high-value denials.

Financial Reporting: Aggregating billed vs. allowed amounts to calculate collection rates.

Domain Expertise: Deep understanding of US Healthcare Claim lifecycles (EOBs, ERAs, and Denial Codes like CO-16, PR-1).

📊 Key Analytics Scenarios
I have included scripts to solve three critical business problems:

Denial Trend Analysis: Using the IN operator to group and count specific denial categories (e.g., Missing Info vs. Coverage issues).

Aged Receivables (AR) Tracking: Using the BETWEEN operator to find claims older than 60 days that remain unpaid.

Revenue Gap Identification: Using IS NULL to find processed claims that have not yet been posted to the patient account.
