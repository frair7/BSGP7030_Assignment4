# AI Prompts Log

## Tool Used

Cursor

## Prompt 1: AI Statistics Walkthrough

```
I am completing the AI-assisted portion of a statistics assignment. Create a new Jupyter notebook at:

`ai/stats_python.ipynb`

Important restrictions:

* Do not open, inspect, copy, summarize, or use `notebooks/stats_python.ipynb`.
* Do not use any code from my manual notebook.
* Do not reproduce the SciPy statistics tutorial line by line.
* Build the analysis independently from my description below.
* Use Python.
* Use clear Markdown section headings.
* Include detailed comments explaining what each analysis does and how to interpret the output.
* Keep the code appropriate for an introductory graduate data science course.
* Use reproducible code and set a random seed wherever randomness is involved.
* Use the datasets stored in the repository’s `data/` folder.

Create a prompt-driven statistics walkthrough using these datasets:

1. `data/brain_size.csv`

   * Inspect the dataset and summarize its variables.
   * Calculate descriptive statistics.
   * Compare intelligence-related measurements between groups, including gender where appropriate.
   * Use suitable hypothesis tests.
   * Fit and interpret at least one linear regression model.
   * Check relevant model assumptions.
   * Create appropriate plots.

2. `data/CPS_85_Wages.txt`

   * Inspect and clean the data as needed.
   * Summarize wage distributions and relevant demographic or employment variables.
   * Compare wages between meaningful groups.
   * Fit a regression model explaining wages using appropriate predictors.
   * Interpret coefficients, p-values, confidence intervals, and model fit.
   * Create appropriate plots and check assumptions.

3. `data/iris.csv`

   * Inspect and summarize the variables.
   * Compare measurements across species.
   * Use an appropriate multi-group statistical test.
   * Create visualizations showing relationships between measurements and species.
   * Explain the results in plain language.

Before writing the notebook, briefly outline the planned analyses and identify which statistical tests you selected and why. Then create the notebook.

Do not create the extension notebook yet. Only create `ai/stats_python.ipynb`.
```

## Prompt 2: Bootstrap Extension

```
Create a second Jupyter notebook at:

`ai/stats_extension.ipynb`

Do not inspect or copy code from `notebooks/stats_python.ipynb`.

Extend one of the analyses from `ai/stats_python.ipynb` using a statistical method that was not part of the original walkthrough. Use a bootstrap confidence interval as the extension.

Requirements:

* Explain why bootstrap confidence intervals are appropriate for the selected question.
* Clearly state the parameter being estimated.
* Use a fixed random seed.
* Perform a sufficiently large number of bootstrap resamples.
* Calculate and report a 95% bootstrap confidence interval.
* Compare the bootstrap result with the conventional confidence interval or hypothesis-test result from the main analysis.
* Include at least one visualization of the bootstrap distribution.
* Explain the findings in plain language.
* Discuss assumptions, limitations, and whether the extension changes the original conclusion.
* Use Markdown headings and detailed code comments.
* Keep the analysis appropriate for an introductory graduate data science course.

Before creating the notebook, briefly explain which dataset and statistical comparison you selected and why.
```

## Follow-up Prompts

Record any corrections or additional instructions given to Cursor.

- *(No corrections to the notebook analyses were requested.)*
- `mkdir -p ai` / `nano ai/PROMPTS.md` — create the `ai/` directory and start a prompts log file.
- Request to format `ai/PROMPTS.md` using the assignment template with sections for Tool Used, Prompt 1, Prompt 2, and Follow-up Prompts.
