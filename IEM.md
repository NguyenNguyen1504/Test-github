# Industrial Engineering and Management: Financial Accounting & Investment Analysis
This document consolidates the key concepts from the TU-A1300 course.

## 1. Introduction to Financial Administration
Financial administration supports decision-making and ensures the company meets its obligations. It is divided into two main areas:

1. **External Accounting (Financial Accounting)**  
   Focuses on public reporting (Financial Statements) for external stakeholders (investors, lenders, authorities).

2. **Internal Accounting (Management Accounting)**  
   Produces information for internal management to support decision-making, budgeting, and cost analysis.

## 2. The Financial Statements (External Accounting)

### 2.1 The Income Statement (Profit & Loss)
Describes how profit or loss is formed during a financial year. Uses the **accrual basis** — revenue and expenses are recognized when earned/incurred, not when cash is exchanged.

**Structure:**
- **Revenue (Net Sales)** – Value of goods/services delivered (excl. VAT)  
- (-) **Cost of Goods Sold (COGS)** – Variable costs (materials, direct labor)  
- = **Gross Margin**  
- (-) **Operating Expenses** – Fixed costs (rent, salaries, marketing, R&D)  
- = **EBITDA** – Earnings Before Interest, Taxes, Depreciation & Amortization  
- (-) **Depreciation & Amortization** – Non-cash allocation of fixed/intangible asset cost  
- = **EBIT (Operating Profit)**  
- (-) **Financial Expenses (Interest)**  
- = **EBT (Earnings Before Tax)**  
- (-) **Taxes** (e.g., 20% in Finland)  
- = **Net Profit** – The bottom line

### 2.2 The Balance Sheet
Snapshot of financial position at a specific moment (usually 31 Dec).  
**Balance Sheet Equation:**
$$ \text{Assets} = \text{Equity} + \text{Liabilities} $$

**Assets (Uses of Funds)**
- **Non-Current Assets** (Fixed Assets >1 year): Intangible (patents, software), Tangible (machinery, buildings, land)  
- **Current Assets**: Inventories • Accounts Receivable • Cash & Cash Equivalents

**Equity & Liabilities (Sources of Funds)**
- **Equity**: Share Capital + Retained Earnings (+ current Net Profit)  
- **Liabilities**:  
  - Long-term debt (>1 year)  
  - Short-term debt (≤1 year) + Accounts Payable

### 2.3 The Statement of Cash Flows
Shows actual cash movements. Explains the change in cash balance.

- **Cash Flow from Operations (CFₒₚₛ)** – Core business cash ± ΔWorking Capital  
- **Cash Flow from Investments (CFᵢₙᵥ)** – Usually negative (CapEx)  
- **Cash Flow from Financing (CF𝒻ᵢₙ)** – New debt/equity, repayments, dividends  

**Link:**  
$$ \Delta \text{Cash} = CF_{ops} + CF_{inv} + CF_{fin} $$

## 3. Financial Analysis – Key Ratios

### 3.1 Profitability
- **Operating Margin (%)**  
  $$ \frac{EBIT}{Revenue} \times 100 $$
- **Return on Equity (ROE)**  
  $$ \frac{Net\ Profit}{Average\ Equity} \times 100 $$
- **Return on Capital Employed (ROCE)**  
  $$ \frac{EBIT}{Average\ (Equity + Interest\text{-}bearing\ Debt)} \times 100 $$

### 3.2 Capital Structure / Solvency
- **Equity Ratio**  
  $$ \frac{\text{Equity}}{\text{Total Assets}} \times 100 \quad \text{(higher = safer)} $$

- **Debt-to-Equity**  
  $$ \frac{\text{Interest-bearing Debt}}{\text{Equity}} $$

- **Gearing (Net Debt / Equity)**  
  $$ \frac{\text{Interest-bearing Debt} - \text{Cash}}{\text{Equity}} $$

### 3.3 Liquidity
- **Current Ratio**  
  $$ \frac{\text{Current Assets}}{\text{Current Liabilities}} \quad \text{(good range: 1–2)} $$

- **Quick Ratio (Acid Test)**  
  $$ \frac{\text{Current Assets} - \text{Inventories}}{\text{Current Liabilities}} \quad \text{(good ≈ 1)} $$

- **Cash Ratio**  
  $$ \frac{\text{Cash \& Equivalents}}{\text{Current Liabilities}} $$

## 4. Operational Analysis (Internal Accounting)

### 4.1 Cost Behavior & CVP Analysis
- **Fixed Costs (F)** – unchanged with volume (rent, depreciation)  
- **Variable Costs (V)** – proportional to volume (materials)

**Break-Even Point (Profit = 0)**

- Critical Volume (Q)  
  $$ Q = \frac{\text{Fixed Costs}}{\text{Price per unit} - \text{Variable Cost per unit}} $$
- Critical Price (P)  
  $$ P = \frac{\text{Fixed Costs}}{\text{Volume}} + \text{Variable Cost per unit} $$

### 4.2 Working Capital (WC)
$$ WC = Inventories + Accounts\ Receivable - Accounts\ Payable $$
- Increase in WC → consumes cash (negative CFₒₚₛ)  
- Decrease in WC → releases cash (positive CFₒₚₛ)

## 5. Investment Analysis

### 5.1 Core Principles
1. **Time Value of Money** → future cash flows must be discounted  
2. Only **future, incremental cash flows** are relevant (ignore sunk costs)  
3. Discount rate = **WACC** (Weighted Average Cost of Capital)

### 5.2 Free Cash Flow (FCF)
$$ FCF = EBIT \times (1 - t) + Depreciation - \Delta WC - CapEx $$

### 5.3 Investment Decision Rules
| Method                  | Formula / Rule                                      | Decision Rule                     |
|-------------------------|-----------------------------------------------------|-----------------------------------|
| **Net Present Value**   | $$ NPV = \sum_{t=0}^{n} \frac{FCF_t}{(1+WACC)^t} - Initial\ Investment $$ | Accept if NPV ≥ 0                |
| **Internal Rate of Return** | Discount rate that makes NPV = 0                  | Accept if IRR > WACC             |
| **Payback Period**      | Years until cumulative FCF = initial investment    | Shorter is better                |

## 6. Master Formula Summary
| Category          | Measure                        | Formula                                                                 |
|-------------------|--------------------------------|-------------------------------------------------------------------------|
| Balance Sheet     | Working Capital                | Inventories + A/R − A/P                                                 |
|                   | Equity Ratio                   | Equity / Total Assets                                                   |
|                   | Gearing                        | (Interest-bearing Debt − Cash) / Equity                                 |
| Liquidity         | Current Ratio                  | Current Assets / Current Liabilities                                    |
|                   | Quick Ratio                    | (Current Assets − Inventories) / Current Liabilities                   |
| Profitability     | Operating Margin               | EBIT / Revenue                                                          |
|                   | ROE                            | Net Profit / Average Equity                                             |
|                   | ROCE                           | EBIT / Avg (Equity + Interest-bearing Debt)                             |
| CVP               | Break-even Volume (Q)          | Fixed Costs / (Price − VC per unit)                                     |
|                   | Break-even Price (P)           | (Fixed Costs / Volume) + VC per unit                                    |
| Investment        | WACC                           | $$\frac{E}{V}r_e + \frac{D}{V}r_d(1-t)$$                                |
|                   | Free Cash Flow (FCF)           | $$EBIT(1-t) + Depreciation - \Delta WC - CapEx$$                        |
|                   | NPV                            | $$\sum \frac{FCF_t}{(1+WACC)^t} - Initial\ Investment$$                 |