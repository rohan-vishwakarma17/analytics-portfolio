# E-Commerce Sales Performance Analysis

> Strategic analysis of 100K+ Brazilian marketplace orders to inform Q4 planning.
> AI-integrated workflow with semantic clustering, narrative generation, and anomaly hypothesis.

## Status

🚧 **In progress** — completion target: 21 days

## The Business Context

A growing e-commerce marketplace needs to understand sales drivers, customer behavior, and operational efficiency across 100K+ orders. This analysis delivers an executive briefing across 5 strategic questions to inform Q4 planning.

## The 5 Business Questions

1. **Which product categories are driving revenue and growth — and which are bleeding revenue?**
2. **What's our customer lifetime value distribution, and how concentrated is revenue?**
3. **How does delivery performance impact reviews and repeat orders?**
4. **What's seasonal vs structural in our sales trend?**
5. **Which sellers drive disproportionate value, and what's the long-tail risk?**

## Tools & Stack

- **SQL** (DuckDB) — joins, aggregations, window functions
- **Python** (pandas, numpy, scikit-learn) — analysis
- **Claude API** — semantic categorization, executive summaries, anomaly hypothesis
- **Power BI / Tableau Public** — dashboard
- **Jupyter** — analysis notebooks

## Where AI Adds Value

This project integrates Claude at three specific points where AI handles ambiguity better than traditional methods:

1. **Semantic category clustering** — 71 messy product categories → ~9 meaningful meta-categories
2. **Executive narrative generation** — auto-summaries for each dashboard page
3. **Anomaly hypothesis** — explains *why* a metric changed, not just *that* it changed

The analysis remains mine. AI handles the parts where it's measurably better.

## Dataset

Brazilian E-Commerce Public Dataset by Olist (Kaggle, 100K+ orders, 9 tables, 2016–2018)

## Repository Structure

01-ecommerce-sales-analysis/
├── data/              ← raw and processed data
├── notebooks/         ← Jupyter analysis notebooks
├── sql/               ← SQL files for analysis
├── ai/                ← AI integration scripts
├── dashboards/        ← Power BI / Tableau files
├── outputs/           ← findings, case study
├── requirements.txt   ← Python dependencies
└── README.md          ← this file

## About

Built by **Rohan Vishwakarma** as Project 1 of a 90-day data analyst portfolio.

[LinkedIn](https://www.linkedin.com/in/rohanvishwakarma17/) · [GitHub](https://github.com/rohan-vishwakarma17)