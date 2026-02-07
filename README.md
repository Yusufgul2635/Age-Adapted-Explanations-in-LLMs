# Age-Adapted Explanations in LLMs

Project for DTU course **02445 – Statistical Evaluation of AI and Data**.

We evaluate how well three large language models adapt the fluency of their explanations to different age groups (10, 25, 50 years old).

Models compared:
- ChatGPT-4o
- Claude Sonnet 3.7
- Gemini 2.0 Flash

---

## What we did

- Generated explanations for 64 topics across 3 age groups using the official APIs
- Collected 576 model responses
- Human evaluators rated fluency (vocabulary, tone, analogy, clarity)
- Computed readability and perplexity scores
- Performed statistical analysis (ANOVA and Kruskal-Wallis)
- Visualized results and wrote a full report

---

## Repository structure

- `data/` – model outputs and evaluation data
- `scripts/` – data collection and analysis code
- `plots/` – figures used in the report
- `pilot_experiment/` – initial setup and testing

---

## Result (short)

All models showed very high fluency and ability to adapt explanations by age.  
No statistically significant differences were found between models.

---

Authors:  
Yusuf Gül · Hsuan Jung Lai · Rasmus Johansen Rieneck
