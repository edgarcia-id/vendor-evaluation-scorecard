# Vendor Evaluation Scorecard (SPK) ⚖️

**A Decision Support System (DSS) tool to objectively select vendors using the Weighted Scoring Method.**

Live Demo: [https://edgarcia-id.github.io/vendor-evaluation-scorecard/](https://edgarcia-id.github.io/vendor-evaluation-scorecard/)

### 🧐 The Problem
Choosing a vendor (for ERP, Infrastructure, or Services) is often subjective.
* "Vendor A is cheaper, but Vendor B has better experience."
* "How do we decide fairly?"

### 💡 The Solution
This tool helps Procurement Managers and IT Consultants to:
1.  **Define Weighted Criteria:** e.g., Price (40%), Portfolio (30%), SLA Guarantee (30%).
2.  **Input Vendor Data:** Add unlimited vendors to the list.
3.  **Score & Rank:** The system calculates the weighted average automatically using the **Simple Additive Weighting (SAW)** method.

### 🔢 How it Works
The formula used is simple yet powerful:
`Final Score = Σ (Criteria Weight % * Vendor Score)`

**Example:**
* **Price (Weight 50%):** Vendor score 80 -> Contributes 40 points.
* **Quality (Weight 50%):** Vendor score 60 -> Contributes 30 points.
* **Total Score:** 70/100.

### 🛠️ Tech Stack
* HTML5 & Bootstrap 5
* Vanilla JavaScript (Real-time Sorting Algorithm)
* Responsive Mobile Design

---
**Maintained by:** Ed Garcia - [NusaIT.com](https://nusait.com)
*Need a partner for IT Procurement or Tender Management? [Contact Me](https://nusait.com/about)*
