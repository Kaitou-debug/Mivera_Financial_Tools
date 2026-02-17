# 📊 Amazon India Profitability Calculator (2026 Edition)

> **💡 Not a coder? Just want the tool?** > [**Download the Ready-to-Use Excel Dashboard here for ₹199**](#) *(Link coming soon)*

---

### 🚀 Project Overview
As an **E-Commerce Operations Manager**, I realized that manual Excel calculations for Amazon fees were prone to error and time-consuming. One wrong calculation on a referral fee or weight slab can turn a profitable product into a loss-maker.

I built this **Python Automation Tool** to solve that problem. Instead of manual data entry, this script programmatically generates a **dynamic Financial Model** that calculates:
* **Referral Fees** (Based on 2026 Amazon India Category Slabs)
* **Closing Fees** (Dynamic logic based on price tiers)
* **Net Profit & Margins** (Real-time ROI calculation)
* **GST Input Credit** (Automatically calculated for tax planning)

### 🛠️ Tech Stack
* **Python** (Core Logic)
* **Pandas** (Data Structuring & DataFrame management)
* **XlsxWriter** (Automated Excel formatting & formula injection)

### ⚡ Key Features
* **Automated Dashboard Creation:** Generates a client-ready `.xlsx` file in under 2 seconds.
* **Live Formula Injection:** The script writes **Excel formulas** (e.g., `=IF(C2<300, 0, ...)`) directly into the cells. This means the end-user (a non-tech seller) can change prices and see profit updates **without** needing to run Python again.
* **Smart Logic:** Automatically detects if a product is under ₹300 (Zero Referral Fee) or above specific weight slabs.

### 📂 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kaitou-debug/Mivera_Financial_Tools.git
   
2. **Install dependencies:**
   ```bash
   pip install pandas xlsxwriter

3. **Run the generator:**
   ```bash
   python generate_profit_model.py

4. **Output:**
   A fully formatted file named Mivera_Amazon_Profit_Calculator_2026.xlsx will be generated in your folder



**👤 Author**

**Kaitou-debug** _Data Analyst & E-Commerce Strategist Specializing in Python Automation for Business Operations_

