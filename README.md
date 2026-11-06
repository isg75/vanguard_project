# Project Title

*Replace this title with the name of your project.*

## 1. Project Overview

Provide a brief description of the Vanguard A/B testing project.

Explain:

- What business problem is the experiment trying to address?
- What changes are being evaluated in the new user interface?
- What are the main objectives of your analysis?
- What are the roles of the Control and Test groups?

**Final Presentation:** Add a link to your final presentation here when it is available.

## 2. Research Questions

List the main questions your analysis aims to answer.

Consider questions related to:

- Differences in user behavior between the Control and Test groups.
- Completion and abandonment of the process.
- User progression through the different interface steps.
- Whether the observed differences provide sufficient evidence to support a business decision.

Formulate your research questions clearly before presenting your analysis.

## 3. Dataset Description

Describe the datasets used in the project.

Include:

- Data sources and their origin.
- Main variables and their meaning.
- Dataset size and structure.
- Relationships between datasets, when applicable.
- Any relevant limitations.

### Main Data Quality Issues

Describe the most important data quality problems identified during the initial exploration.

Consider issues such as missing values, duplicated records, inconsistent event sequences, or incomplete user journeys, when applicable.

### Data Cleaning and Preparation

Summarize how you addressed these issues and prepared the data for analysis.

Explain any important decisions that could affect the interpretation of your results.

## 4. Methodology

Explain the analytical approach followed to evaluate the experiment.

Your methodology should cover the relevant aspects of the analysis, including:

- **Exploratory Data Analysis (EDA):** How did you explore the datasets and identify relevant patterns?
- **User Journey Analysis:** How did you examine user progression through the interface steps?
- **Performance Metrics:** Which KPIs did you define, and why are they appropriate for evaluating the experiment?
- **Group Comparison:** How did you compare user behavior and performance between the Control and Test groups?
- **Statistical Analysis:** Which statistical tests did you use, what assumptions did you consider, and why were these methods appropriate?

Explain the reasoning behind your methodological choices rather than simply listing the Python libraries used.

## 5. Key Findings

Summarize the most relevant results of your analysis.

Support your findings with appropriate evidence, including:

- Summary statistics and relevant KPIs.
- Charts and visualizations.
- Comparisons between the Control and Test groups.
- Results of statistical hypothesis tests, including their interpretation.

Where appropriate, distinguish between **statistical significance** and **practical or business relevance**.

Avoid presenting conclusions that are not supported by the available evidence.

## 6. Conclusions

Explain how your findings address the original research questions.

In particular:

- What does the experiment reveal about the new interface?
- Are the observed differences supported by statistical evidence?
- What are the main limitations of your analysis?
- What recommendation would you make regarding the new interface?

Justify your recommendation using the results of your analysis and their business implications.

## 7. Next Steps

Describe possible improvements, additional analyses, or future work.

Consider what additional information or investigation could strengthen the conclusions of the experiment.

## 8. Repository Structure

The project follows this directory structure:

```text
├── data/
│   ├── raw/           # Original datasets
│   └── clean/         # Processed datasets
├── notebooks/         # Jupyter notebooks
├── figures/           # Charts and visualizations
├── slides/            # Final presentation or link
├── config.yaml        # Project file paths
├── pyproject.toml     # Python dependencies
└── uv.lock            # Locked dependency versions
```

Each directory contains its own README with additional information about file organization and naming conventions.

## 9. Team Members

| Name | Role | Main Contributions |
|---|---|---|
| ... | Project Manager | ... |
| ... | Team Member | ... |
| ... | Team Member | ... |
