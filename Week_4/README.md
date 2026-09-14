# 📊 Tata Motors — Risk Management & Sensitivity Analysis in Financial Decision-Making

<p align="center">
  <img src="https://img.shields.io/badge/Project-Week%204-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Risk%20Management-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Analysis-Sensitivity%20Analysis-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Excel-Financial%20Model-orange?style=for-the-badge" />
</p>

<p align="center">

### 🎯 Risk • Sensitivity • Scenario Analysis • Financial Decision-Making

</p>

---

## 🏆 Week 4 Task

This project was completed as part of my **Junior Financial Analyst – Virtual Internship**.

The Week 4 assignment focuses on:

> **Risk Management and Sensitivity Analysis in Financial Decision-Making**

The purpose of the project is to identify financial and operational risks that can affect forecasted outcomes, model the effect of changing key assumptions, and evaluate how those changes can influence financial performance and investment decisions.

The analysis uses **Tata Motors FY2025–26 financial information** as the historical financial base and develops a structured Excel-based risk and sensitivity framework.

---

# 🎯 Project Objectives

The project was designed to:

- 🔍 Identify potential risks affecting financial forecasts
- 📊 Build a financial model incorporating key risk assumptions
- 📈 Perform detailed sensitivity analysis
- 🔄 Evaluate downside, base and upside scenarios
- 💰 Measure the financial impact of changing assumptions
- ⚠️ Understand how risks affect valuation and investment decisions
- 🛡️ Develop practical risk-mitigation strategies
- 💼 Apply an investment-banking perspective to financial decision-making

---

# 📁 Project Deliverables

| File | Description |
|---|---|
| 📊 `Tata_Motors_Risk_Management_Sensitivity_Analysis_Redesigned_with_Raw_Data_FIXED.xlsx` | Complete risk-management and sensitivity-analysis financial model |
| 📄 Week 4 Risk Management Report | Detailed explanation of risks, methodology, sensitivity testing and recommendations |
| 📑 Tata Motors FY2025–26 Annual Report | Primary financial and risk-information source |

---

# 🧮 Financial Model Structure

The Excel model is designed as a risk-focused financial decision-support tool.

```text
                    ┌─────────────────────┐
                    │   FY26 Financials   │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │    Risk Inputs      │
                    └──────────┬──────────┘
                               ↓
              ┌────────────────┼────────────────┐
              ↓                ↓                ↓
       Revenue Growth     EBITDA Margin     WACC / Rates
              ↓                ↓                ↓
              └────────────────┼────────────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Sensitivity Model   │
                    └──────────┬──────────┘
                               ↓
                 ┌─────────────┼─────────────┐
                 ↓             ↓             ↓
              Revenue       EBITDA         UFCF
                 ↓             ↓             ↓
                 └─────────────┼─────────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Valuation Outcomes  │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Investment Decision │
                    └─────────────────────┘
```

---

# 📚 Workbook Structure

The redesigned workbook contains dedicated sheets for both analysis and raw supporting data.

| Sheet | Purpose |
|---|---|
| 📌 Risk Dashboard | Executive summary of major risk and sensitivity results |
| ⚙️ Risk Inputs | Core financial and risk assumptions |
| 🔄 Scenario Manager | Downside / Base / Upside scenario testing |
| 📊 Sensitivity Analysis | Multi-variable sensitivity testing |
| 💰 DCF Stress Test | Measures risk impact on DCF valuation |
| 💳 Financial Impact | Examines interest-rate and financing effects |
| ⚠️ Risk Register | Identifies risks, severity, likelihood and mitigation |
| 📈 Raw Financials | Historical FY26 financial data |
| 🚚 Raw Operations | Volume, segment and market information |
| 🔍 Raw Risk Drivers | Risk variables and financial transmission channels |
| 📉 Raw Sensitivity Data | Underlying sensitivity tables and outputs |
| 💵 Raw Valuation Inputs | Scenario and valuation assumptions |
| 📚 Sources | Source documentation and model references |

---

# 💰 FY2025–26 Financial Base

The financial model is anchored to Tata Motors' FY2025–26 reported results.

| Financial Metric | FY2025–26 |
|---|---:|
| Revenue from Operations | ₹83,855 Cr |
| Underlying EBITDA | ₹10,314 Cr |
| Underlying EBIT | ₹8,538 Cr |
| Profit After Tax | ₹3,030 Cr |
| Operating Cash Flow | ₹14,981 Cr |
| Free Cash Flow | ₹12,438 Cr |
| Total Debt | ₹4,817 Cr |
| Cash & Cash Equivalents | ₹6,899 Cr |
| Net Cash — Model Calculation | ₹2,082 Cr |

These financial figures form the starting point for the forecast and stress-testing framework.

---

# ⚠️ Risk Identification

The project identifies key risks that can influence Tata Motors' future financial performance.

### 🚚 1. Commercial Vehicle Demand Risk

Commercial vehicle demand can fluctuate with infrastructure activity, freight utilisation, replacement cycles, financing availability and broader economic conditions.

A weaker demand environment can reduce:

```text
Vehicle Volumes
      ↓
Revenue
      ↓
EBITDA
      ↓
UFCF
      ↓
Valuation
```

---

### ⛓️ 2. Commodity Price Risk

The automotive business is exposed to input costs including:

- Aluminium
- Copper
- Platinum
- Palladium
- Steel and other manufacturing inputs

Higher commodity prices can increase production costs and compress EBITDA margins when price increases cannot be passed on to customers.

---

### 💳 3. Interest Rate Risk

Changes in interest rates can affect:

- Financing costs
- Borrowing costs
- Customer vehicle financing demand
- Cost of capital
- WACC
- DCF valuation

This is particularly important because changes in the discount rate can materially change the present value of future cash flows.

---

### 💱 4. Foreign Exchange Risk

Foreign-currency movements can affect:

- International revenues
- Imported components
- Export profitability
- Foreign-currency liabilities
- Reported earnings

The company uses financial instruments such as forward contracts and other hedging mechanisms to manage portions of these exposures.

---

### 🌍 5. Geopolitical and Supply-Chain Risk

International operations may be affected by geopolitical developments, logistics disruptions, energy costs and supply-chain interruptions.

These risks can influence:

> Revenue → Costs → Working Capital → Cash Flow → Valuation

---

### ⚡ 6. EV & Technology Transition Risk

Investment in electric, hydrogen, connected and digital technologies can create long-term growth opportunities but also requires significant:

- R&D investment
- Capital expenditure
- Technology development
- Infrastructure investment
- Product execution

The financial risk is that investment may occur before the expected commercial returns are fully realized.

---

# 📈 Sensitivity Analysis

A major component of the project is the sensitivity framework.

The model evaluates how changing key financial assumptions affects:

- Revenue
- EBITDA
- UFCF
- Enterprise Value
- Equity Value
- Implied Share Value
- Investment outcomes

---

## 🔢 Key Sensitivity Variables

### 📊 Revenue Growth

Revenue-growth assumptions are varied to test how demand and operating performance affect the valuation.

```text
Lower Growth
      ↓
Lower Revenue
      ↓
Lower EBITDA
      ↓
Lower UFCF
      ↓
Lower Enterprise Value
```

Higher revenue growth produces the opposite effect.

---

### 📈 EBITDA Margin

Margin sensitivity tests the effect of operating efficiency, product mix, pricing and input-cost pressures.

A decline in EBITDA margin can have a significant impact because the effect flows directly through operating profitability and free cash flow.

---

### 💳 WACC

WACC is one of the most important valuation variables.

```text
Higher WACC
      ↓
Higher Discount Rate
      ↓
Lower Present Value
      ↓
Lower Enterprise Value
```

Conversely:

```text
Lower WACC
      ↓
Lower Discount Rate
      ↓
Higher Present Value
      ↓
Higher Enterprise Value
```

---

### 💰 Interest Rate Sensitivity

The model evaluates the potential effect of interest-rate shocks on financing costs and financial outcomes.

The analysis helps determine how sensitive the company's financial profile is to changes in funding costs.

---

### 🏭 Capex Sensitivity

Higher capital expenditure can support long-term growth but can reduce near-term free cash flow.

The model therefore examines changes in **Capex as a percentage of revenue** and measures their impact on financial outcomes.

---

# 🔥 Two-Way Sensitivity Analysis

The workbook contains two-way sensitivity matrices to examine interactions between important assumptions.

## Revenue Growth × WACC

This table evaluates how combinations of:

> **Revenue Growth + Cost of Capital**

affect implied valuation.

The analysis helps determine whether a lower cost of capital can offset slower growth or whether stronger growth is required to justify a higher discount rate.

---

## EBITDA Margin × WACC

This framework measures the interaction between:

> **Operating Profitability + Cost of Capital**

This is particularly useful for investment decisions because it demonstrates how operational improvements and financial-market conditions can jointly influence valuation.

---

# 🔄 Scenario Analysis

The model includes three primary scenarios:

| Scenario | Interpretation |
|---|---|
| 🔴 Downside | Lower growth, weaker margins and higher financial risk |
| 🟡 Base Case | Central operating assumptions |
| 🟢 Upside | Stronger growth, stronger margins and improved conditions |

The Scenario Manager makes it possible to understand how an investment case changes under different assumptions.

---

# 📊 Risk-to-Financial-Outcome Framework

The model links identified risks to measurable financial consequences.

```text
Risk Event
   ↓
Operating Assumption Changes
   ↓
Revenue / Cost / Margin Impact
   ↓
EBITDA Impact
   ↓
Cash Flow Impact
   ↓
Valuation Impact
   ↓
Investment Decision
```

This converts qualitative risk discussion into quantitative financial analysis.

---

# 🛡️ Risk Mitigation Strategies

The project develops practical recommendations to reduce financial risk.

### 💱 1. Hedging Strategy

Use foreign-exchange and commodity hedging selectively to reduce the impact of major market fluctuations.

Potential tools include:

- Forward contracts
- Options
- Commodity hedging
- Natural hedges

Hedging should be aligned with actual exposure rather than used purely for speculation.

---

### 🌍 2. Geographic Diversification

Expanding across multiple international markets can reduce dependence on a single geography.

Diversification can help offset weakness in one market with stronger performance elsewhere.

---

### 🏭 3. Supply-Chain Diversification

The company can reduce supply-chain concentration through:

- Multiple suppliers
- Strategic inventory buffers
- Long-term supplier agreements
- Alternate sourcing channels

---

### 💰 4. Capital Restructuring

Maintain a disciplined capital structure and preserve sufficient liquidity.

The objective is to ensure that:

> **Growth investments do not compromise financial resilience.**

---

### ⚡ 5. Stage-Gated Technology Investment

Large EV, hydrogen and technology investments should be assessed using:

- Expected IRR
- NPV
- Payback period
- Scenario testing
- Cost-of-capital thresholds

Capital should be released progressively as commercial milestones are achieved.

---

### 📊 6. Continuous Sensitivity Monitoring

Sensitivity analysis should not be performed only once.

A professional financial-planning process should periodically update:

- Revenue assumptions
- EBITDA margins
- Interest rates
- WACC
- Commodity costs
- Capex
- Working capital

This creates an ongoing financial-risk monitoring framework.

---

# 💼 Investment Banking Application

Sensitivity analysis is an important tool in investment banking because transaction and investment decisions often depend on assumptions that can change rapidly.

This project demonstrates how an analyst can move from:

```text
Historical Data
      ↓
Forecast
      ↓
Risk Assessment
      ↓
Sensitivity Testing
      ↓
Scenario Analysis
      ↓
Valuation
      ↓
Investment Recommendation
```

Rather than relying on one forecast, the model provides a **range of possible outcomes**.

This improves decision-making by highlighting:

- Key value drivers
- Downside exposures
- Assumption dependencies
- Financial resilience
- Potential catalysts
- Risk-management priorities

---

# 📊 Visual Dashboard

The workbook includes presentation-focused visuals such as:

📌 Risk dashboard  
📈 Revenue and UFCF forecast charts  
🔥 Sensitivity heatmaps  
💳 Interest-rate sensitivity charts  
🏭 Capex sensitivity visuals  
📊 Scenario valuation charts  
⚠️ Risk-priority analysis  

These visuals are linked to the underlying model so that changes in assumptions can flow through the analytical outputs.

---

# 🧠 Key Learning Outcomes

Through this project, I strengthened my understanding of:

- Financial Risk Management
- Sensitivity Analysis
- Scenario Analysis
- Financial Forecasting
- DCF Stress Testing
- Investment Decision-Making
- Capital Structure Analysis
- Interest Rate Risk
- Commodity Risk
- Foreign Exchange Risk
- Operational Risk
- Risk Mitigation
- Excel Financial Modelling
- Financial Data Visualization
- Investment Banking Analysis

---

# ✅ Key Takeaways

### 1️⃣ Risk should be quantified

Identifying a risk is only the first step. A financial analyst should understand how that risk can affect:

> Revenue → EBITDA → Cash Flow → Valuation

### 2️⃣ Valuation depends on assumptions

A single valuation number can provide a false sense of precision. Sensitivity analysis reveals how much the outcome changes when assumptions move.

### 3️⃣ WACC is a critical variable

Changes in the discount rate can materially affect present value even when operating forecasts remain unchanged.

### 4️⃣ Operational and financial risks interact

Demand, margin, capex, interest rates and market conditions can affect the valuation simultaneously.

### 5️⃣ Risk mitigation should be actionable

Hedging, diversification, liquidity management, capital discipline and staged investment can reduce downside exposure.

---

# 📚 Data Sources

The analysis is primarily based on:

1. **Tata Motors Limited — Integrated Annual Report FY2025–26**
2. Consolidated financial statements
3. Management Discussion and Analysis
4. Liquidity and funding disclosures
5. Risk-management disclosures
6. Company hedging and market-risk disclosures
7. Financial modelling assumptions developed for this internship project

---

# 👨‍💼 Project Information

**Prepared by:**  
### Sandeep Singh

**Role:**  
💼 Junior Financial Analyst – Virtual Intern

**Project:**  
📊 Week 4 — Risk Management and Sensitivity Analysis in Financial Decision-Making

**Academic Programme:**  
🎓 MBA

---

# ⭐ Final Conclusion

This Week 4 project demonstrates how financial risk management can be integrated directly into a financial model.

The combination of **risk identification, scenario analysis, sensitivity testing and mitigation planning** provides a more complete framework for financial decision-making than a single-point forecast.

The model is designed to answer an important investment-banking question:

> **“What happens to financial outcomes and investment decisions when the assumptions change?”**

By quantifying those changes, the analyst can identify the most important value drivers, understand downside exposure, evaluate alternative outcomes and recommend practical strategies to protect financial performance.

---

<p align="center">

### 🚀 Risk Analysis • Financial Modelling • Sensitivity Testing • Investment Decision-Making

**© 2026 Sandeep Singh**

</p>

---

### 🔖 Tags

`Risk Management` `Sensitivity Analysis` `Financial Modelling`  
`Investment Banking` `Scenario Analysis` `DCF` `Excel`  
`Financial Risk` `Capital Structure` `Interest Rate Risk`  
`Commodity Risk` `FX Risk` `Tata Motors` `Junior Financial Analyst`  
`MBA` `Virtual Internship` `Financial Analysis`
