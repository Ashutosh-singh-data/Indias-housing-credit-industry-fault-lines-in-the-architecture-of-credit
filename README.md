# DataQuest — Inceptum 2026 | Hansraj College
## India's Housing Credit Industry: Fault Lines in the Architecture of Credit

![Competition](https://img.shields.io/badge/Competition-DataQuest%20Inceptum%202026-blue)
![Result](https://img.shields.io/badge/Result-Top%206%20Finalist-gold)
![Tools](https://img.shields.io/badge/Tools-Python%20%7C%20PowerBI%20%7C%20Excel-green)

---

## 🏆 About
**Top 6 Finalist** at DataQuest — a Data Analytics Case Competition organized by the 
Department of Economics, Hansraj College, University of Delhi as part of Inceptum 2026.

**Team DataQuant | MNNIT Allahabad**
- Ashutosh Singh
- Vivek Anand

---

## 📋 Problem Statement
India's housing credit system has grown to ₹31.17 lakh crore by FY2025 — 
but has it grown equitably?

Which borrowers and geographies are being systematically underserved, 
and what does the data reveal about why?

---

## 📊 Dataset
Official dataset provided by DataQuest — Inceptum 2026, Hansraj College

| Sheet | Contents |
|-------|----------|
| 1_SectorFinancials | AUM, NIM, CoF, GrossNPA, CRAR by player type (FY2020–25) |
| 2_CreditAccess | Loan volumes, rejection rates by borrower segment & city tier |
| 3_FundingStructure | NCD, bank borrowings, commercial paper mix for HFCs & NBFCs |
| 4_MacroIndicators | RBI Repo Rate, G-Sec yield, CPI, House Price Index (quarterly) |

---

## 🔍 Key Findings

### Q1A — Credit Growth
- Total AUM grew from ₹17.99L Cr (FY2020) to ₹31.17L Cr (FY2025)
- CAGR = 11.6% over 5 years
- PSU Banks and Private Banks captured 90% of all growth
- HFCs and NBFCs serving poor borrowers remained marginal

### Q1B — Who Serves Whom
- EWS/LIG receives LOWEST total disbursements → ₹373.6 Cr avg
- Private Banks give EWS/LIG only ₹38.9 Cr vs ₹326 Cr to Salaried
- **8x disparity** — structural discrimination, not market failure
- PSU Banks dominant across Salaried (₹418 Cr) and MSME (₹178 Cr)

### Q1C — Rejection Analysis
| Rank | Segment | City | Player | Rejection Rate |
|------|---------|------|--------|---------------|
| 1 | MSME | Tier-3 | NBFCs | 42.5% |
| 2 | MSME | Tier-3 | Private Banks | 42.3% |
| 3 | EWS/LIG | Tier-3 | Private Banks | 41.3% |

- Metro avg rejection → 15-20%
- Tier-3 avg rejection → 35-43%
- Geographic gap = 27%

### Q1D — Financial Health
| Player | Gross NPA | NIM | CoF | Stress |
|--------|-----------|-----|-----|--------|
| PSU Banks | 7.88% 🔴 | 2.88% | 6.11% | NPA Crisis |
| NBFCs | 4.84% | 3.19% | 8.78% 🔴 | Funding Crisis |
| HFCs | 3.67% | 2.09% 🔴 | 7.95% | Margin Squeeze |
| Private Banks | 3.24% ✅ | 3.82% ✅ | 6.33% | Healthiest |

---

## 💡 Policy Recommendation

### Root Cause Diagnosis
Two structural failures identified from data:

**Failure 1 — Information Gap**
EWS/LIG borrowers have no credit history → banks reject them 
even when willing to lend → 41.3% rejection in Tier-3

**Failure 2 — Funding Gap**
NBFCs pay 2.67% more than banks to borrow money → 
loans become unaffordable for poor borrowers

### Recommended: Option C + Option D

**Option C — NHB Refinance Window**
- NHB provides funds to HFCs/NBFCs at Repo Rate + 0.5% = ~6.75%
- Currently NBFCs pay 8.78% → saves 2.03%
- Condition: Only for EWS/LIG lending
- Fixes: Funding Gap directly

**Option D — Unified Credit Bureau**
- Aggregate GST + UPI + Utility bill data
- Build credit scores for informal borrowers
- EWS/LIG DO pay electricity bills and do UPI transactions
- Fixes: Information Gap directly

**Why C+D together:**
- C alone → Cheaper loans but borrowers still rejected
- D alone → Credit score exists but loans still expensive
- C + D → Approval + Affordable rate ✅

### What C+D Does NOT Solve
- PSU Bank NPA crisis (7.88%) → unaddressed
- Cash-only informal borrowers → still excluded from Option D
- Developer loan concentration in metros → unchanged
- Private Bank reluctance → needs separate PSL reform

## 🛠️ Tools & Tech Stack

| Tool | Usage |
|------|-------|
| Python — Pandas | Data analysis & manipulation |
| Python — Matplotlib | Chart generation |
| Python — Seaborn | Heatmap visualization |
| Power BI Desktop | Interactive dashboard |
| Microsoft Excel | Data exploration |
