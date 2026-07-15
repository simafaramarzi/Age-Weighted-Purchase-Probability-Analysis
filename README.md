# Age-Weighted Purchase Probability Analysis

A probability theory exercise exploring how age affects the likelihood of a purchase, using a simulated dataset of 30,000 samples to calculate and compare conditional, joint, and marginal probabilities.

## What I Did

1. **Data Generation**
   - Simulated a synthetic dataset of 30,000 samples with age groups and purchase outcomes, to study purchasing behavior in a controlled setting

2. **Probability Calculations**
   For each age group, calculated three core metrics:
   - **P(B)** — probability of a randomly selected person belonging to that age group
   - **P(A|B)** — conditional probability of a purchase, given age (the core metric for understanding age's effect)
   - **P(A∩B)** — joint probability of being in that age group *and* making a purchase

3. **Two Analysis Approaches**
   - **Weighted (simulation-based):** probabilities computed from a uniform age distribution, reflecting a random population
   - **Unweighted (scenario-based):** probabilities computed from fixed, predefined values, representing a specific scenario

4. **Visualization**
   - Bar charts comparing probabilities across age groups for both approaches

## How to Run

```bash
pip install numpy pandas matplotlib
jupyter notebook "Age-Weighted Purchase Probability Analysis.ipynb"
```

No external dataset needed — data is generated within the notebook.

## Tools

Python · NumPy · Pandas · Matplotlib

## Note

This is a probability/statistics exercise built on simulated data, not a real-world business dataset. It demonstrates conditional and joint probability calculations rather than predictive modeling.
