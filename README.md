# Life Sciences + Python Portfolio

**Owner:** Ugah Chinonso Valentine 
**Purpose:** Demonstrate practical Python workflows relevant to pharmacology, biomedical data analysis, and introductory bioinformatics.

> **Transparency notice:** These are portfolio learning demonstrations. The pharmacology and biomedical cohort notebooks use synthetic data. The sequence notebook uses an illustrative sequence. They are not publications, client projects, clinical research, or evidence of experimental findings.

## Projects

1. **Pharmacological dose–response analysis** — fit a four-parameter logistic model using SciPy and estimate EC50 from simulated observations.
2. **Biomedical cohort exploration** — validate a synthetic dataset, calculate descriptive statistics, compare two groups using Welch's t-test, and visualize distributions.
3. **DNA sequence basics** — use Biopython to calculate GC content, transcribe DNA, translate a coding sequence, and inspect nucleotide composition.

## Skills demonstrated

- Python, Jupyter Notebook
- NumPy and pandas
- SciPy optimization and statistical testing
- Matplotlib visualization
- Biopython sequence operations
- Reproducibility, data validation, interpretation, and limitations

## Environment setup

Python 3.10 or later is recommended.

```bash
python -m venv .venv
# Activate the environment using the command for your operating system
pip install -r requirements.txt
jupyter lab
```

Open each `.ipynb` notebook and run all cells from top to bottom.

## Scientific integrity

- Synthetic datasets are labelled as synthetic in the notebooks.
- Arbitrary units are not clinical units.
- Statistical association is not causation.
- Model estimates from simulated data are not real drug properties.
- The notebooks are educational demonstrations and must not be used for diagnosis, treatment, or clinical decision-making.
- Before publishing, run every notebook, inspect outputs, and add a short personal reflection describing what you learned and what you can independently explain.

## Suggested next improvements

- Add unit tests for helper functions.
- Add confidence intervals and residual diagnostics to the dose-response analysis.
- Add a real, appropriately licensed public biomedical dataset with provenance and a documented analysis plan.
- Add a sequence alignment example using a cited reference sequence and documented parameters.
