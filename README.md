# forage-client-support-casestudy.
# Financial Services Client Support Simulation

## Project Overview
A detailed case study based on a virtual job simulation via Forage Academy. This project demonstrates real-world client support workflows within a financial institution, focusing on security authentication, active listening, account maintenance, and high-value transactions.

## Key Competencies Demonstrated
* **Active Listening & Empathy:** Uncovering client milestones (e.g., marriage, home closing) to provide personalized service.
* **Technical & Digital Navigation:** Directing clients through self-service portals and internal knowledge bases.
* **Financial Operations:** Explaining trade settlement periods ($T+2$), cash availability, and payment rails (EFT vs. Bank Wire).

## Case Studies Included

### Task 1: Security Authentication & Account Maintenance
* **Scenario:** Client locked out of online banking due to failed login attempts; needs beneficiary updates due to marriage.
* **Key Actions:** De-escalated lockout frustration, validated identity, initiated password reset workflow, and routed client to self-service beneficiary forms.
* **Document:** [Task 1 Script & Analysis](scripts-and-notes/task1-password-reset-script.md)

### Task 2: High-Value Withdrawal & Payment Options Analysis
* **Scenario:** Client requesting a $100,000 withdrawal for a home closing on a short deadline.
* **Key Actions:** Evaluated account liquidity ($10k available cash vs $310k invested), guided trade placement with $T+2$ settlement context, and recommended Bank Wire over EFT due to critical timing constraints.
* **Document:** [Task 2 Analysis & EFT vs Wire Breakdown](scripts-and-notes/task2-withdrawal-and-wire-vs-eft.md)

---

## Payment Transfer Analysis: EFT vs. Bank Wire

| Feature | Electronic Funds Transfer (EFT / ACH) | Bank Wire Transfer |
| :--- | :--- | :--- |
| **Processing Time** | 1–3 Business Days (Batch) | Same-Day / Near Instant (Real-Time) |
| **Cost Structure** | Free or Low Cost | Higher Fee ($15–$50 average) |
| **Primary Use Case** | Routine payments, direct deposit, non-urgent transfers | Time-sensitive, high-value transactions (e.g., real estate closing) |
| **Reversibility** | Higher flexibility | Irrevocable once initiated |
