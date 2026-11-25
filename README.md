# SME Accounting & GST Compliance — A 2 Z Stores

An end-to-end accounting, statutory compliance, and MIS reporting project built in **TallyPrime** and **Microsoft Excel** for a wholesale business (**A 2 Z Stores**, FY 2026–27: 1 Apr 2026 – 31 Mar 2027). The project covers voucher entry, financial statement finalization, GSTR-3B Input Tax Credit (ITC) reconciliation, TDS & receivables auditing, and profitability analysis.

## Tools Used
* **TallyPrime:** Item-wise & accounting vouchers, Trial Balance, Balance Sheet, Profit & Loss A/c, GSTR-3B, TDS, Bill-wise Ageing
* **Microsoft Excel:** MIS reporting, gross margin analysis, expense breakdown, overdue receivables tracking
* **AI Tools (Gemini, ChatGPT, Claude):** Troubleshooting TallyPrime/GST exceptions, structuring MIS analysis, and refining documentation

## Key Financial Summary (FY 2026–27)

| Metric | Verified Value | Context |
| :--- | :--- | :--- |
| **Transactions Recorded** | 41 Vouchers | Full-year wholesale cycle (29 in GSTR-3B, 12 non-GST, 0 uncertain) |
| **Trial Balance Total** | ₹69,26,450 | Balanced (Debit = Credit, zero variance) |
| **Balance Sheet Total** | ₹48,60,280 (₹48.60L) | Finalized with reconciled P&L and Closing Stock |
| **Net Sales** | ₹18,54,600 (₹18.55L) | Gross Sales ₹18.76L less ₹21K returns (**16.1% Gross Margin**) |
| **Net Purchases** | ₹24,40,000 (₹24.40L) | Gross Purchases ₹24.51L less ₹11K purchase returns |
| **Closing Stock** | ₹8,84,620 (₹8.85L) | COGS of ₹15,55,380; Gross Profit of ₹2,99,220 |
| **Net ITC Available (GSTR-3B)** | ₹1,67,510 | ₹1,79,570 Input Tax less ₹12,060 Table 4B(1) reversal |
| **Duties & Taxes Net Credit** | ₹66,430 (₹66.43K) | Books net credit (₹1,79,570 Input − ₹1,13,140 Output Tax) |
| **TDS Deducted & Paid** | ₹9,300 | Sec 194-I (₹6,000), 194J (₹2,500), 194C (₹800) paid via HDFC Bank |
| **Overdue Receivables** | ₹1.89L | Flagged via party-wise ageing schedule |
| **Net Operating Loss** | ₹4,59,780 (₹4.60L) | Driven by ₹5.65L Salaries (74.4% of ₹7.59L indirect expenses) |

## Project Workflow

1. **Bookkeeping & Financial Statements (TallyPrime)**
   * Configured company books, ledgers, GST tax heads, and stock items.
   * Recorded 41 wholesale transactions across purchase, sales, payment, receipt, contra, debit/credit note, and journal vouchers.
   * Finalized the ₹69.26L Trial Balance, ₹48.60L Balance Sheet, and Profit & Loss statement with zero variance.

2. **GST Compliance & GSTR-3B Reconciliation**
   * Cleared all uncertain transactions in TallyPrime (0 pending) by resolving UOM mapping and taxability errors.
   * Applied ₹12,060 in GSTR-3B Table 4B(1) reversals (CGST ₹6,030 + SGST ₹6,030), arriving at **₹1,67,510** Net ITC Available against ₹1,13,140 Output Tax (₹54,370 net excess ITC after reversal; ₹66,430 net credit in books).

3. **TDS Audit & Receivables Ageing**
   * Deducted and remitted **₹9,300** in TDS across Sections 194-I, 194J, and 194C.
   * Generated bill-wise ageing schedules to isolate **₹1.89L** in overdue receivables for collection follow-up.

4. **MIS Reporting & Profitability Analysis (Excel)**
   * Exported TallyPrime summaries into structured Excel MIS reports.
   * Compared ₹18.55L net sales (16.1% gross margin) against ₹8.85L closing stock and ₹7.59L indirect expenses, identifying fixed payroll overhead (₹5.65L Salaries) as the primary driver of the ₹4.60L net loss.

## AI Usage Disclosure
AI tools (Gemini, ChatGPT, Claude) were used as a technical assistant during this project to troubleshoot GST/TallyPrime exceptions, structure the MIS report layout, and refine documentation. All voucher entries, ledger reconciliations, GSTR-3B adjustments, and final financial figures were executed and verified manually in TallyPrime and Excel.

## Repository Contents
* `01_TallyPrime_Exports/` — `BSheet.pdf`, `PandL.pdf`, `TrialBal.pdf`, `DayBook.pdf`
* `02_GST_Report/` — `GSTR-3B.pdf`
* `03_Excel_MIS_Reports/` — Excel MIS workbook and expense/margin analysis

## Author
**Tharun S** — Data Analyst | Finance & Accounting Associate  
[Portfolio](https://tharuns.pages.dev) · [LinkedIn](https://linkedin.com/in/tharun-s-17-x) · [Email](mailto:tharun.s.work@gmail.com)
```[cite: 14, 15, 16, 18, 19, 20, 21]
