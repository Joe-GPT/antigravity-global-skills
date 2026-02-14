---
name: Market_Intelligence
description: Automatically tracks market indices (US/TW), policy updates (FSC/MOI), and commercial real estate trends.
---

# Market Intelligence Skill

## Objective

To provide rapid, fact-based intelligence on key financial and real estate market indicators, focusing on significant deviations and critical policy updates.

## Capabilities

### 1. Market Tracking

- **Indices**:
  - US Markets: DJIA, S&P 500, Nasdaq, SOX.
  - TW Markets: TAIEX, TW Futures (Night Session).
- **Logic**: Compare current values with the previous trading day's close.
- **Reporting Threshold**: Only report if the absolute change is significant (e.g., > 1% for indices, specific key levels breached).

### 2. Policy Monitoring

- **Sources**:
  - Financial Supervisory Commission (FSC)
  - Ministry of the Interior (MOI)
  - Central Bank of the Republic of China (CBC)
- **Focus Areas**:
  - Real estate credit controls.
  - Pre-sale housing regulations.
  - Urban renewal and endangered building reconstruction policies.

### 3. Commercial Real Estate (CRE) Dynamics

- **metrics**:
  - Office vacancy rates (Grade A vs. B).
  - Rental yield trends.
  - Major transactions (land, whole buildings).

## Operational Rules

1. **Fact-First**: Prioritize official data sources over news commentary.
2. **Delta-Driven**: Focus on *changes* and *anomalies*. "No significant change" is a valid and valuable output.
3. **Contextualize**: When reporting a figure, briefly mention its immediate historical context (e.g., "highest in 3 months").
