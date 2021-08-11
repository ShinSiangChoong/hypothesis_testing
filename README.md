Statistical Hypothesis Testing
==============================
Python codes templates for various Statistical Hypothesis Testing. This repo includes various parametric and non-parametric statistical tests. The very high level theoretical assumptions and rationale of the tests are stated inconsistently in the notebooks.

Parametric tests:
1. *t*-test
2. *Z*-Test
3. Chi-Square test
4. ANOVA and post-hoc tests

Non-parametric tests:
1. Sign Test
2. Wilcoxon Signed-Rank Test
3. Mann–Whitney U Test (Equivalent to Wilcoxon Rank-sum Test)
4. Kruskal–Wallis Test and its Post-hoc Test
5. Friedman Test and its Post-hoc Test

Used libraries:
- Most codes in this repo use the [Pingouin](https://pingouin-stats.org/) library. 
- When certain tests/use-cases are not available in the library, custom functions and other libraries such as `scipy` and `statsmodel` are used.

Important notes: The data examples used in this repo may not fulfil the underlying assumptions/rules of the tests e.g. paired sample, normality, etc. 