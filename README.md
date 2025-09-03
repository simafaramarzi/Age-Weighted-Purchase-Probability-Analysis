# Project Overview
This project is a detailed data-driven analysis that explores the relationship between a person's age and their likelihood of making a purchase. It serves as a practical example of a complete data science workflow, from data generation and statistical analysis to visualization. The primary goal is to provide a clear, quantitative understanding of how age affects consumer behavior by calculating and comparing various conditional and joint probabilities.

# Key Features & Analytical Steps#
The project follows a rigorous, multi-step process to ensure a reliable and comprehensive analysis:

**Data Generation:** The project begins by simulating a large, synthetic dataset of 30,000 samples. This allows for a controlled environment to study purchasing behavior.

**Probability Calculation:** For each age group, the project calculates three key probability metrics:

* P(B) (Probability of Occurrence): The probability of a randomly selected person belonging to a specific age group.

* P(A∣B) (Conditional Probability): The probability of a person making a purchase, given their specific age. This is the core metric for understanding the effect of age.

* P(AcapB) (Joint Probability): The probability of a person being in a specific age group and making a purchase.

**Weighted vs. Unweighted Analysis:** The project performs two distinct types of analysis to showcase different modeling approaches:

* Weighted Analysis (Simulation-based): Based on a uniform age distribution, this method reflects how probabilities would behave in a random population.

* Unweighted Analysis (Scenario-based): This method uses predefined probability values, demonstrating an analysis based on a fixed scenario or prior knowledge.

**Data Visualization:** All results are presented through clear and informative bar charts created with Matplotlib. These visualizations make complex statistical findings easy to understand and interpret.

# Technologies Used
* Python: The foundational programming language for the entire analysis.

* NumPy: Used for high-performance numerical operations and efficient data generation.

* Pandas: For flexible and powerful data manipulation and analysis.

* Matplotlib: The primary library for creating professional-quality data visualizations
