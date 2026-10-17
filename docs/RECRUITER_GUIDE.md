# Recruiter evidence guide — Bellabeat Wellness Analysis

[**Full case study on Mulero Analytics**](https://tosinmulero.github.io/data-analytics-portfolio/case-studies/bellabeat-wellness-analysis.html) · [Repository README](../README.md) · [Main portfolio](https://tosinmulero.github.io/data-analytics-portfolio/projects.html)

> **Data provenance:** Limited public Fitbit observational sample from April–May 2016. This is behavioural exploration, not a clinical or causal health study.

## The question

What do a small Fitbit activity and sleep sample show about steps, sedentary time and sleep patterns, and which wellness-marketing ideas might warrant further research?

## Technical approach

- Assess coverage and data quality across daily activity and sleep tables.
- Build day-of-week, activity-level, sedentary and sleep descriptive metrics in Python.
- Show patterns through Power BI while explicitly noting sampling and inference limits.

## Documented results to review

- Mean valid daily activity is approximately 7,801 steps.
- Average observed sleep duration is 419 minutes and reported efficiency is 91.65%.
- Daily steps and calories show an approximately 0.58 correlation in the analysed sample.

## Evidence map

| Review item | Source | What it supports |
|---|---|---|
| Recruiter summary | [Open](../docs/RECRUITER_PROJECT_SUMMARY.md) | What was analysed and why |
| Technical architecture | [Open](../docs/TECHNICAL_ARCHITECTURE.md) | Processing and reporting stages |
| Power BI dashboard | [Open](../images/bellabeat_dashboard.png) | Activity and sleep KPIs |
| Weekday activity aggregates | [Open](../powerbi/data/weekday_activity_summary.csv) | Report-ready grouped metrics |

## Reproducibility and limitations

The repository README documents methodology and limitations. Findings are descriptive for a limited, non-representative sample; they should not be presented as personalised medical advice.

The repository README and linked source files remain the primary technical record. Figures in this guide summarise documented project artefacts, not independently verified third-party business outcomes.

## Suggested review path

1. Start with the [standalone case study](https://tosinmulero.github.io/data-analytics-portfolio/case-studies/bellabeat-wellness-analysis.html) for an accessible summary.
2. Inspect the linked screenshots and technical documentation.
3. Check the README and source files for workflow, caveats and reproduction guidance.
4. Inspect analytical code or quality workflows as required.

---

*Independent portfolio work by Oluwatosin Mulero. Project evidence is maintained in this repository.*
