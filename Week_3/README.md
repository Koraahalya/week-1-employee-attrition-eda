# Week 3 Internship Task
## Statistical Analysis and Hypothesis Testing in Python

### Dataset
IBM HR Analytics Employee Attrition & Performance

### Domain
Human Resources / Employee Attrition

### Objective
The objective of Week 3 was to perform statistical analysis and hypothesis testing using Python. The analysis investigated whether employee overtime status has a significant association with employee attrition.

### Hypotheses

**Null Hypothesis (H₀):** There is no significant association between overtime status and employee attrition.

**Alternative Hypothesis (H₁):** There is a significant association between overtime status and employee attrition.

### Statistical Method
A Chi-Square Test of Independence was used because both OverTime and Attrition are categorical variables. Cramér's V was additionally calculated to measure the strength of the association.

### Results
- Chi-Square Statistic: 87.5643
- Degrees of Freedom: 1
- P-value: p < 0.001
- Significance Level: 0.05
- Cramér's V: 0.2441
- Decision: Reject H₀

### Conclusion
The analysis provides strong statistical evidence of a significant association between overtime status and employee attrition in the dataset. The result indicates that overtime status should be considered for further investigation in employee-retention analysis. However, statistical association does not prove that overtime alone causes employee attrition.

### Author
**Kora Ahalya**
