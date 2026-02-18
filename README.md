# 📊 Mivera Financial Feasibility Engine

### 🚀 Project Overview
**From "Gut Feeling" to Data-Driven Decisions.**

Early-stage D2C founders often launch with optimistic modeling, failing to account for hidden platform fees and tax compliance. This leads to capital erosion.

As a **Data Engineer**, I refused to launch a business on assumptions. I architected this **Python Automation Tool** to programmatically generate a dynamic Financial Model. It stress-tests unit economics against rising logistics costs and GST compliance, enabling a "Go/No-Go" decision in seconds.

### 🛠️ The Solution
Instead of manual data entry, this script acts as a **Financial ETL Pipeline**:
1.  **Ingests** variable cost structures (Referral Fees, Weight Slabs).
2.  **Transforms** logic based on 2026 Amazon India Rate Cards.
3.  **Loads** a fully interactive Financial Model into Excel.

### ⚡ Key Technical Features
* **Automated Excel Generation:** Uses `XlsxWriter` to generate a client-ready `.xlsx` file in under 2 seconds.
* **Live Formula Injection:** Unlike standard scripts that just dump static numbers, this tool **injects live Excel formulas** (e.g., `=IF(C2<300, 0, ...)`).
    * *Benefit:* The end-user (non-tech stakeholder) can change a price in the Excel sheet, and the Net Profit updates instantly without re-running Python.
* **Smart Logic:** Automatically detects if a product is under ₹300 (Zero Referral Fee) or triggers specific weight slab costs.

### 🛠️ Tech Stack
* **Python** (Core Logic & Control Flow)
* **Pandas** (Data Structuring & DataFrame Management)
* **XlsxWriter** (Automated Formatting & Formula Injection)

### 📂 How to Run Locally
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Kaitou-debug/Mivera_Financial_Tools.git](https://github.com/Kaitou-debug/Mivera_Financial_Tools.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas xlsxwriter
    ```
3.  **Run the generator:**
    ```bash
    python generate_profit_model.py
    ```
4.  **Output:** A fully formatted file named `Mivera_Amazon_Profit_Calculator_2026.xlsx` will be generated in your folder.

### 👤 Author
**Kaitou-debug**
*Data Engineer & Python Automation Specialist*
*Focus: Building Scalable ETL Pipelines & Financial Data Tools*
