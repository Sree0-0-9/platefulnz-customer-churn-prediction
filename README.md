# PlatefulNZ Customer Churn Prediction

This project applies predictive analytics to identify churn risk for a New Zealand meal-kit subscription business.

## Business Problem

Subscription businesses need to identify customers at risk of churn before they cancel. This project models retention behaviour and highlights the customer attributes and engagement patterns that can inform targeted retention strategies.

## What This Project Demonstrates

- Customer churn framing for a subscription business
- Data preparation and feature engineering
- Classification modelling for retained vs churned customers
- Comparison of interpretable and higher-performing models
- Business recommendations from predictive analytics

## Key Findings

- Churn modelling is most useful when it identifies actionable retention drivers, not only high-risk customer labels.
- Customer satisfaction, purchase behaviour, payment issues, and engagement patterns can provide useful retention signals.
- Comparing interpretable models with higher-performing models helps balance business explainability and predictive strength.

## Business Recommendation

Prioritise early intervention for at-risk customers through billing reliability improvements, targeted offers, and service recovery actions for low-satisfaction segments.

## Tools Used

- R
- tidyverse
- Classification modelling
- Logistic regression
- Random forest
- LightGBM
- Business analytics reporting

## Repository Structure

```text
.
|-- Businfo704_PlatefulNZ_Poster.jpg
|-- platefulnz_churn_analysis.qmd
`-- README.md
```

## Project Poster

The repository includes a poster artifact summarising the churn prediction problem, modelling approach, and business recommendations.

![PlatefulNZ churn prediction poster](Businfo704_PlatefulNZ_Poster.jpg)

## How To Open

Open `platefulnz_churn_analysis.qmd` in RStudio or another Quarto-compatible editor. The poster image is included for quick portfolio preview inside GitHub.
