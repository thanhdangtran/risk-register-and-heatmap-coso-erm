# Enterprise Risk Management Framework
## Risk Register & Risk Heatmap for Digital Lending Platform

**Framework**: COSO ERM 2017  
**Organization**: Neo Finance Bank (Case Study)  
**Sector**: Digital Unsecured Lending / Fintech  
**Date**: November 2025

---

## 📋 Project Overview

This project demonstrates the implementation of a comprehensive Enterprise Risk Management (ERM) framework following COSO ERM 2017 guidelines for a digital lending platform targeting underserved customers in Vietnam's banking sector.

**Business Context:**
- **Target Market**: 5 million thin-file customers (70% without traditional credit history)
- **Digital Ecosystem**: 10M NEO users, 5M Cake customers
- **Technology Stack**: AWS SageMaker, Mixture of Experts (MoE) architecture
- **Data Sources**: Traditional credit data + Alternative data (e-wallet, telco, e-commerce)
- **Strategic Goal**: Scale to 100K+ loan applications per day by 2026

---

## 📦 Deliverables

### 1. **Neo_Finance_Risk_Register.xlsx** (16 KB)
Comprehensive risk register with 4 worksheets:

#### Sheet 1: Risk Register (18 Risks)
- **Risk ID**: Unique identifier (R001-R018)
- **Risk Category**: Credit, Operational, Technology, Fraud, Compliance, Model, Strategic, Market, Concentration, Third-party
- **Risk Description**: Detailed description of each risk scenario
- **Risk Owner**: Accountable executive (CCO, CTO, CFO, etc.)
- **Inherent Assessment**: Probability (1-5) × Impact (1-5) = Inherent Score
- **Current Controls**: Existing risk mitigation measures
- **Control Effectiveness**: High/Medium/Low rating
- **Residual Assessment**: Probability × Impact after controls
- **Risk Appetite**: Risk tolerance threshold
- **Risk Status**: Above Appetite / Within Appetite / At Limit
- **KRI**: Key Risk Indicator with threshold
- **Review Cycle**: Daily/Weekly/Monthly/Quarterly monitoring frequency
- **COSO Component**: Mapping to COSO ERM framework

#### Sheet 2: Risk Matrix
- Probability scale: 1 (Very Rare <10%) to 5 (Very Likely >75%)
- Impact scale: 1 (Negligible <10M VND) to 5 (Catastrophic >500M VND)
- Risk score interpretation:
  - 1-6: Low Risk (Green)
  - 7-12: Medium Risk (Yellow)
  - 13-20: High Risk (Orange)
  - 21-25: Critical Risk (Red)

#### Sheet 3: COSO Components Mapping
Five COSO ERM 2017 components with implementation details:
1. **Governance & Culture**: Board oversight, risk appetite, ethical values
2. **Strategy & Objective-Setting**: Risk integration in strategic planning
3. **Performance**: Risk identification, assessment, prioritization
4. **Review & Revision**: Monitoring and effectiveness evaluation
5. **Information, Communication & Reporting**: Data quality and stakeholder reporting

#### Sheet 4: KRI Dashboard
10 Key Risk Indicators with current values and thresholds:
- Default Rate: 6.8% (Target: <8%)
- Alt-Data Gini: 0.58 (Target: >0.55)
- Liquidity Coverage Ratio: 135% (Target: >100%)
- System Uptime: 99.8% (Target: >99.5%)
- Model PSI: 0.18 (Target: <0.25)
- Fraud Rate: 1.2% (Target: <2%)
- SBV Violations: 0 (Target: 0)
- Processing Throughput: 65,000/day (Target: >50K/day)
- Net Promoter Score: 42 (Target: >30)
- Net Interest Margin: 6.2% (Target: >4%)

**Technical Features:**
- ✅ Formula-driven calculations (36 formulas verified with zero errors)
- ✅ Color-coded cells: Blue (inputs), Black (formulas), Green (cross-sheet links)
- ✅ Conditional formatting for risk levels
- ✅ Professional banking/finance styling

---

### 2. **Neo_Finance_Risk_Management.pptx** (281 KB)
Professional 7-slide presentation deck:

#### Slide 1: Title Slide
- Enterprise Risk Management branding
- Neo Finance Bank identification
- COSO ERM 2017 framework reference

#### Slide 2: Executive Summary
- **Metrics Dashboard**: 18 total risks, 2 above appetite, 14 within appetite, 2 at limit
- **Key Findings**:
  - Credit risk concentration in thin-file segment requires immediate attention
  - Technology infrastructure is robust with effective controls
  - COSO ERM framework fully implemented across all five components
  - Monthly KRI monitoring shows all 10 indicators in green status

#### Slide 3: COSO ERM Framework
- Visual representation of 5 components
- Implementation details for each component
- Risk mapping summary (18 risks across all components)

#### Slide 4: Risk Heatmap Matrix
- **Scatter chart**: 18 risks plotted on Probability (x-axis) vs Impact (y-axis)
- **Risk distribution analysis**:
  - High Impact, High Probability: R001 (Default rate), R009 (Identity theft)
  - High Impact, Medium Probability: R004 (Liquidity), R007 (AWS outage)
  - Medium Impact: 10 risks with various probabilities
- **Key Insight**: Residual risk scores range from 3 to 16 after controls

#### Slide 5: Risk Register Overview
- **Risk Categories breakdown** (18 risks across 8 categories)
- **Top 9 Risks Table** with Risk ID, Category, Description, Residual Score, Status
- **Control Effectiveness**: 8 High, 9 Medium, 1 Low effectiveness ratings

#### Slide 6: KRI Dashboard
- **Visual KRI Cards** for 8 key indicators:
  - Default Rate: 6.8% vs <8% target
  - Alt-Data Gini: 0.58 vs >0.55 target
  - System Uptime: 99.8% vs >99.5% target
  - Fraud Rate: 1.2% vs <2% target
  - LCR: 135% vs >100% target
  - Model PSI: 0.18 vs <0.25 target
  - Throughput: 65K vs >50K/day target
  - NPS Score: 42 vs >30 target
- **Status Summary**: All 10 KRIs in GREEN status

#### Slide 7: Action Plan & Recommendations
- **Priority Actions**:
  1. Credit Risk - Thin-File Segment: Implement MoE architecture, target default rate <6% by Q3 2025
  2. Segment Concentration Risk: Diversify customer base beyond gig economy workers
- **Ongoing Monitoring**:
  - Monthly: Risk Register review, KRI dashboard monitoring, Model PSI tracking
  - Quarterly: Board Risk Committee reporting, Stress testing, Control effectiveness testing

**Design Features:**
- Professional banking/finance color palette (Navy #1F4E78, Teal #5EA8A7)
- Risk-level color coding: Green (Low), Yellow (Medium), Orange (High), Red (Critical)
- Data visualizations: Scatter chart, metrics boxes, risk table
- Consistent branding and layout across all slides

---

## 🎯 COSO ERM 2017 Framework Implementation

### Component 1: Governance & Culture
**Implementation:**
- Board Risk Committee meets quarterly
- Risk appetite: NPL <4%, ROE >15%
- Code of Conduct training mandatory for all employees
- Tone at the top: CEO and Board champion risk-aware culture

**Related Risks:** R009 (Identity theft), R010 (Agent collusion), R011 (SBV compliance), R012 (PDPA), R018 (Vendor risk)

---

### Component 2: Strategy & Objective-Setting
**Implementation:**
- Strategic goal: Serve 5M thin-file customers by 2026
- Risk-adjusted pricing model integrated into product design
- Target underserved segments: gig economy, informal sector workers
- MoE architecture designed to handle 100K+ applications/day

**Related Risks:** R002 (Alternative data reliance), R014 (MoE scaling), R017 (Segment concentration)

---

### Component 3: Performance
**Implementation:**
- Monthly risk dashboard tracking 18 risks across 8 categories
- KRI monitoring with automated alerts for threshold breaches
- Quarterly stress testing scenarios: economic downturn, funding crisis, cyber attack
- Risk-response strategies: Accept, Mitigate, Transfer, Avoid

**Related Risks:** R001 (Credit default), R003 (Geographic concentration), R004 (Liquidity), R005 (System downtime), R007 (AWS outage), R016 (Interest rate)

---

### Component 4: Review & Revision
**Implementation:**
- Quarterly risk register review with updates to risk scores
- Annual model validation by independent third party
- Control effectiveness testing semi-annually
- Risk appetite review annually by Board

**Related Risks:** R008 (Model drift), R013 (Model bias)

---

### Component 5: Information, Communication & Reporting
**Implementation:**
- Real-time risk dashboard for C-suite executives
- Monthly Board risk report with KRI traffic lights
- Incident escalation protocol: <4 hours to senior management
- Whistleblower hotline for compliance concerns

**Related Risks:** R006 (Data pipeline failure), R015 (Reputation risk)

---

## 📊 Risk Categories & Key Findings

### Credit Risk (5 risks)
- **R001 - CRITICAL**: Default rate in thin-file segment (Residual Score: 12)
  - Inherent: Prob 4 × Impact 5 = 20
  - Controls: Basic credit scoring, manual review
  - Residual: Prob 3 × Impact 4 = 12
  - Status: **Above Appetite** (target: 8-12)
  - Action: Implement MoE architecture to improve predictive power

- **R002**: Alternative data reliance (Residual: 8)
- **R003**: Geographic concentration (Residual: 6)
- **R017**: Segment concentration (Residual: 9) - **At Limit**

### Technology Risk (2 risks)
- **R007**: AWS outage (Residual: 4) - High impact, low probability after multi-region backup
- **R008**: Model drift (Residual: 6) - Monthly monitoring with A/B testing

### Fraud Risk (2 risks)
- **R009**: Identity theft with deepfake (Residual: 8) - eKYC with liveness detection
- **R010**: Agent-customer collusion (Residual: 6) - Behavior analytics, random audits

### Compliance Risk (2 risks)
- **R011**: SBV Circular 39 non-compliance (Residual: 4) - Automated compliance checks
- **R012**: PDPA violations (Residual: 3) - Privacy-by-design, DPO oversight

### Operational Risk (2 risks)
- **R005**: System downtime (Residual: 3) - 99.9% SLA, AWS multi-AZ
- **R006**: Data pipeline failure (Residual: 6) - Real-time monitoring, backup pipeline

### Other Categories (5 risks)
- Model risk (R013), Strategic risk (R014), Liquidity risk (R004), Market risk (R016), Third-party risk (R018)

**Overall Assessment:**
- **Above Risk Appetite**: 2 risks (R001, R017)
- **Within Risk Appetite**: 14 risks
- **At Appetite Limit**: 2 risks
- **All KRIs**: Green status (10/10 within thresholds)

---

## 🔍 Methodology

### Risk Identification
1. **Top-Down Analysis**: Strategic objectives → potential risks
2. **Bottom-Up Analysis**: Process-level risk identification workshops
3. **External Scan**: Regulatory changes, market trends, competitor analysis
4. **Historical Data**: Past incidents, near-misses, audit findings

### Risk Assessment
- **Probability Scale**: 1-5 based on frequency (annual occurrence rate)
- **Impact Scale**: 1-5 based on financial loss (VND) and operational disruption
- **Inherent Risk**: Before considering controls
- **Residual Risk**: After applying current controls
- **Formula**: Risk Score = Probability × Impact

### Risk Appetite Setting
- **Low Risk (1-6)**: Accept with monitoring
- **Medium Risk (7-12)**: Accept with enhanced controls
- **High Risk (13-20)**: Mitigate or escalate to Board
- **Critical Risk (21-25)**: Immediate action required, Board notification

### Control Effectiveness
- **High**: Controls reduce residual risk by >50%
- **Medium**: Controls reduce residual risk by 30-50%
- **Low**: Controls reduce residual risk by <30%

### KRI Design
- **Leading Indicators**: Predict future risk events (e.g., Model PSI)
- **Lagging Indicators**: Measure past risk events (e.g., Default Rate)
- **Threshold Setting**: Based on risk appetite, historical data, industry benchmarks
- **Monitoring Frequency**: Daily (operational), Weekly (fraud), Monthly (credit), Quarterly (strategic)

---

## 💡 Key Insights & Recommendations

### Immediate Actions (Priority 1)
1. **R001 - Credit Default Risk**
   - **Current State**: 6.8% default rate, above target for thin-file segment
   - **Root Cause**: Limited predictive power of traditional credit scoring for customers without credit history
   - **Recommendation**: Accelerate MoE architecture implementation to leverage alternative data sources
   - **Target**: Reduce default rate to <6% by Q3 2025
   - **Investment**: $500K for model development, $200K for infrastructure

2. **R017 - Segment Concentration**
   - **Current State**: 45% of portfolio in gig economy workers
   - **Risk**: Economic downturn affecting gig economy could trigger portfolio-wide defaults
   - **Recommendation**: Product diversification to target formal employment segment
   - **Target**: Reduce gig economy concentration to <40% by Q4 2025

### Medium-Term Actions (6-12 months)
- **R002**: Validate alternative data sources with 2-year backtesting
- **R014**: Conduct load testing for 100K+ applications/day throughput
- **R008**: Implement champion-challenger framework for continuous model improvement

### Ongoing Monitoring & Governance
- **Monthly Risk Committee**: Review all 18 risks, KRI dashboard, incident log
- **Quarterly Board Report**: Risk appetite adherence, top 5 risks, stress test results
- **Annual Risk Assessment**: Full review of risk universe, emerging risks, control updates

### Strengths
✅ Strong technology infrastructure (99.8% uptime)  
✅ Effective fraud prevention (1.2% fraud rate vs 2% target)  
✅ Robust compliance framework (zero SBV violations)  
✅ Adequate liquidity (135% LCR vs 100% minimum)  

### Areas for Improvement
⚠️ Credit risk management for thin-file segment  
⚠️ Portfolio diversification across customer segments  
⚠️ Alternative data validation and model governance  

---

## 📚 Technical Specifications

### Excel File
- **Format**: .xlsx (Microsoft Excel 2016+)
- **Formulas**: 36 formulas, zero errors verified
- **Color Coding**: Industry-standard financial modeling conventions
- **Compatibility**: Excel, Google Sheets, LibreOffice Calc

### PowerPoint File
- **Format**: .pptx (Microsoft PowerPoint 2016+)
- **Aspect Ratio**: 16:9 (960×540px)
- **Charts**: Scatter plot (risk heatmap), tables (risk register)
- **Fonts**: Arial (web-safe)
- **File Size**: 281 KB (optimized for email sharing)

---

## 🎓 Use Cases

### For Portfolio / CV
- Demonstrate understanding of COSO ERM framework
- Showcase Excel modeling skills (formulas, data structures)
- Evidence of PowerPoint presentation design
- Risk quantification and prioritization expertise

### For Interviews
- **Risk Manager**: Discuss risk appetite setting, control effectiveness assessment
- **Data Scientist**: Explain KRI selection, threshold determination, monitoring frequency
- **Chief Risk Officer**: Present COSO implementation, Board reporting structure
- **Fintech Consultant**: Analyze digital lending risks, alternative data challenges

### For Learning
- Study template for enterprise risk management
- Reference for COSO ERM 2017 framework application
- Example of risk register structure and risk matrix design
- Best practices for KRI dashboard development

---

## 👤 Author & Purpose

**Created by**: Risk Management Portfolio Project  
**Purpose**: Demonstrate comprehensive ERM framework implementation for banking/fintech sector  
**Framework**: COSO ERM 2017  
**Industry**: Digital Lending / Fintech  
**Geography**: Vietnam (VPBank context)  

**Disclaimer**: This is a case study for educational and portfolio purposes. Neo Finance Bank is a fictional organization created to demonstrate risk management methodologies. All data, risks, and recommendations are illustrative examples based on industry best practices and do not represent any actual financial institution.

---

## 📖 References

1. **COSO Enterprise Risk Management Framework** (2017)
   - Committee of Sponsoring Organizations of the Treadway Commission
   - *Enterprise Risk Management - Integrating with Strategy and Performance*

2. **State Bank of Vietnam Regulations**
   - Circular 39/2016/TT-NHNN on Consumer Lending
   - Circular 41/2016/TT-NHNN on Credit Limits

3. **Basel Committee on Banking Supervision**
   - *Principles for the Management of Credit Risk* (2000)
   - *Principles for Sound Stress Testing Practices and Supervision* (2009)

4. **Risk Management Standards**
   - ISO 31000:2018 Risk Management Guidelines
   - IRM (Institute of Risk Management) Risk Appetite and Tolerance Guidance

---

## 📞 Contact

For questions about this portfolio project or risk management methodology:
- **Email**: Available upon request
- **LinkedIn**: Available upon request
- **GitHub**: Available upon request

---

**Last Updated**: November 15, 2025  
**Version**: 1.0  
**Status**: Final
