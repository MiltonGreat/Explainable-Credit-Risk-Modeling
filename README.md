# Explainable-Credit-Risk-Modeling
This project demonstrates how explainable AI and machine learning can be used to build transparent credit risk models that satisfy regulatory requirements under Basel III, IFRS 9, and OSFI's E-23 guidelines. The framework provides comprehensive model interpretability using SHAP and LIME.

## Key Features

- Probability of Default (PD) Modeling with fairness auditing
- Loss Given Default (LGD) Estimation with multiple model approaches
- Bias & Fairness Monitoring across protected attributes
- Model Explainability using SHAP (global) and LIME (local)
- Regulatory Compliance with stress testing and capital calculation
- Comprehensive Documentation for audit readiness

## Methodology

**Tier 1: Pre-Modeling Bias Audit**
- Comprehensive fairness assessment
- Proxy variable detection
- Data quality validation

**Tier 2: Model Development & Fairness**
- Multiple model comparison
- Bias metric calculation
- Regulatory alignment

**Tier 3: Explainability & Documentation**
- SHAP/LIME integration
- Model passport creation
- Compliance reporting
  
## Regulatory Compliance

## Implemented Frameworks

- Basel III	PD/LGD models, Regulatory capital, Stress testing	
- IFRS 9	Expected Credit Loss, 3-stage impairment
- OSFI E-23	Model governance, Fairness monitoring, Documentation

## Key Regulatory Metrics

- Capital Ratio: 40.39% (vs 8% minimum requirement)
- Stress Testing: 4 economic scenarios implemented 
- Model Explainability: SHAP + LIME integration
- Bias Monitoring: Multiple protected attributes 

## Explainability Framework

**Global Interpretability (SHAP)**
- Feature importance rankings
- Directional impact analysis
- Portfolio-level risk drivers

**Local Interpretability (LIME)**
- Individual prediction explanations
- Regulatory audit trail
- Customer-facing rationale

## Limitations & Caveats

### Data Quality
- High Default Rate: 70% indicates potential data issues
- Sample Size: 1,000 observations may limit model robustness
- LGD Data: Simulated rather than historical recovery data

### Model Performance
- Fairness Concerns: Significant bias detected across age groups
- LGD Modeling: Poor explanatory power (R² = 0.0062)
- Feature Engineering: Limited transformations applied

## Business Applications

### Risk Management
- Portfolio Analysis: €1.25M expected loss identified
- Concentration Risk: Top 5 purposes account for 90% of losses
- Stress Testing: 125% EL increase under crisis scenarios

### Regulatory Reporting
- Capital Adequacy: €1.32M regulatory capital calculated
- IFRS 9 Compliance: ECL staging implemented
- Model Documentation: Comprehensive audit trail

## Source

[UCI Machine Learning Repository - Statlog (German Credit Data)](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)
