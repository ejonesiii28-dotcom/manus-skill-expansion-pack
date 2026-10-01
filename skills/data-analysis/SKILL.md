---
name: data-analysis
description: Structured data inspection, cleaning, statistical analysis, visualization, and reproducible reporting. Use for CSV, TSV, JSON, spreadsheets, metrics, and analytical questions.
---

# Data Analysis

Use this skill for data-backed decisions and reproducible analysis.

## Workflow
1. Inventory files, schemas, row counts, types, units, missingness, duplicates, and time ranges.
2. Preserve raw inputs; create a derived working copy and document transformations.
3. Validate assumptions with profiling and spot checks before calculating results.
4. Choose methods that match the question; distinguish descriptive statistics from causal claims.
5. Produce readable tables or charts with labels, units, denominators, uncertainty, and source notes.
6. Re-run the analysis from a clean start and record the command or script used.

## Guardrails
- Never silently coerce malformed values or drop rows; quantify and explain exclusions.
- Check timezone, currency, population, sampling, and join-key assumptions.
- Protect personal and sensitive data; minimize and redact outputs.
- State limitations and avoid overclaiming from correlation.

## Output
Use: **Question**, **Method**, **Findings**, **Quality checks**, **Limitations**, and **Reproducibility**.
