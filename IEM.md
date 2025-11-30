# Industrial Engineering and Management: Financial Accounting & Investment Analysis
Consolidated notes for TU-A1300 – clean, complete, and fully compatible with GitHub + Obsidian.

## 1. Introduction to Financial Administration
Financial administration is divided into two main areas:

1. **External Accounting (Financial Accounting)**  
   Public reporting (Financial Statements) for investors, banks, authorities.
2. **Internal Accounting (Management Accounting)**  
   Internal decision-making, budgeting, cost analysis, planning.

## 2. The Three Financial Statements

### 2.1 Income Statement (Profit & Loss) – Accrual Basis
| Line                          | Explanation                                      |
|-------------------------------|--------------------------------------------------|
| Revenue (Net Sales)           | Sales excl. VAT                                  |
| – Cost of Goods Sold (COGS)   | Variable costs (materials, direct labor)         |
| = **Gross Margin**            |                                                  |
| – Operating Expenses          | Fixed costs (rent, salaries, marketing, R&D)     |
| = **EBITDA**                  | Operational cash flow proxy                      |
| – Depreciation & Amortization | Non-cash expense                                 |
| = **EBIT** (Operating Profit) |                                                  |
| – Interest                    | Financial expenses                               |
| = EBT                         |                                                  |
| – Taxes (e.g., 20% Finland)   |                                                  |
| = **Net Profit**              | Bottom line                                      |

### 2.2 Balance Sheet – Snapshot at a Point in Time
$$
\text{Assets} = \text{Equity} + \text{Liabilities}
$$

**Assets**  
- Non-current (fixed): machinery, buildings, intangibles  
- Current: Inventories, Accounts Receivable, Cash  

**Equity & Liabilities**  
- Equity = Share Capital + Retained Earnings + Current Net Profit  
- Liabilities: Long-term debt + Short-term debt + Accounts Payable

### 2.3 Statement of Cash Flows
$$
\Delta \text{Cash} = CF_{\text{ops}} + CF_{\text{inv}} + CF_{\text{fin}}
$$
- CFops = cash from core business ± ΔWorking Capital  
- CFinv = usually negative (CapEx)  
- CFfin = debt/equity issuance, repayments, dividends

## 3. Financial Analysis – Key Ratios

### 3.1 Profitability
- **Operating Margin (%)**  
  $$\frac{EBIT}{Revenue} \times 100$$
- **Return on Equity (ROE)**  
  $$\frac{Net\ Profit}{Average\ Equity} \times 100$$
- **Return on Capital Employed (ROCE)**  
  $$\frac{EBIT}{Average\ (Equity + Interest\text{-}bearing\ Debt)} \times 100$$

### 3.2 Capital Structure / Solvency
- **Equity Ratio**  
  $$\frac{Equity}{Total\ Assets} \times 100 \quad \text{(higher = safer)}$$
- **Debt-to-Equity**  
  $$\frac{Interest\text{-}bearing\ Debt}{Equity}$$
- **Gearing (Net Debt / Equity)**  
  $$\frac{Interest\text{-}bearing\ Debt} - {Cash}{Equity}$$

### 3.3 Liquidity
- **Current Ratio**  
  $$\frac{Current\ Assets}{Current\ Liabilities} \quad \text{(good: 1–2)}$$
- **Quick Ratio (Acid Test)**  
  $$\frac{Current\ Assets - Inventories}{Current\ Liabilities} \quad \text{(good ≈ 1)}$$
- **Cash Ratio**  
  $$\frac{Cash\ and\ Equivalents}{Current\ Liabilities}$$

## 4. Operational Analysis (Management Accounting)

### 4.1 Cost-Volume-Profit (CVP) Analysis
- Fixed Costs → unchanged with volume  
- Variable Costs → proportional to volume  

**Break-Even Point**  
- Critical Volume (Q):  
  $$Q = \frac{Fixed\ Costs}{Price\ per\ unit - Variable\ Cost\ per\ unit}$$
- Critical Price (P):  
  $$P = \frac{Fixed\ Costs}{Volume} + Variable\ Cost\ per\ unit$$

### 4.2 Working Capital (WC)
$$WC = Inventories + Accounts\ Receivable - Accounts\ Payable$$
- ↑ WC → consumes cash (negative CFₒₚₛ)  
- ↓ WC → releases cash (positive CFₒₚₛ)

## 5. Investment Analysis

### 5.1 Free Cash Flow (FCF) – used for NPV/valuation
$$FCF = EBIT(1-t) + Depreciation - \Delta WC - CapEx$$

### 5.2 Key Investment Metrics
| Method               | Rule                                      |
|----------------------|-------------------------------------------|
| **NPV**              | $$NPV = \sum_{t=0}^{n} \frac{FCF_t}{(1+WACC)^t} - Initial\ Investment$$ → Accept if ≥ 0 |
| **IRR**              | Accept if IRR > WACC                      |
| **Payback Period**   | Shorter = better (ignores time value)     |

### 5.3 WACC (Discount Rate)
$$WACC = \frac{E}{V}r_e + \frac{D}{V}r_d(1-t)$$

## 6. Master Formula Summary 

| Category         | Measure                    | Formula                                                               |
|------------------|----------------------------|-----------------------------------------------------------------------|
| Balance Sheet    | Working Capital            | $$Inventories + A/R - A/P$$                                           |
|                  | Equity Ratio               | $$\frac{Equity}{Total\ Assets} \times 100$$                           |
|                  | Gearing                    | $$\frac{Interest\text{-}bearing\ Debt - Cash}{Equity}$$               |
| Liquidity        | Current Ratio              | $$\frac{Current\ Assets}{Current\ Liabilities}$$                      |
|                  | Quick Ratio                | $$\frac{Current\ Assets - Inventories}{Current\ Liabilities}$$       |
| Profitability    | Operating Margin           | $$\frac{EBIT}{Revenue} \times 100$$                                   |
|                  | ROE                        | $$\frac{Net\ Profit}{Average\ Equity} \times 100$$                    |
|                  | ROCE                       | $$\frac{EBIT}{Avg\ (Equity + Int\text{-}bearing\ Debt)} \times 100$$  |
| CVP              | Break-even Volume          | $$\frac{Fixed\ Costs}{Price - VC\ per\ unit}$$                        |
| Investment       | WACC                       | $$\frac{E}{V}r_e + \frac{D}{V}r_d(1-t)$$                              |
|                  | Free Cash Flow (FCF)       | $$EBIT(1-t) + Depreciation - \Delta WC - CapEx$$                      |
|                  | NPV                        | $$\sum \frac{FCF_t}{(1+WACC)^t} - Initial\ Investment$$               |
