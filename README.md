# Student Performance Analytics

### Predicting Mathematics Performance Using Python and Machine Learning

## Project Overview

This project analyses the academic performance of 395 secondary-school mathematics students in Portugal.

The objective is to identify factors associated with academic performance and investigate whether machine learning can help identify students at risk of failing mathematics.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Key Questions

1. Which student characteristics are associated with mathematics performance?
2. Can we identify students at risk before examination grades become available?
3. How does prediction accuracy improve when academic grades become available?
4. Do more complex machine learning models outperform simpler alternatives?

## Key Findings

- Students with previous academic failures had substantially higher final mathematics failure rates.
- The simplified early-warning logistic regression model achieved a repeated cross-validation ROC-AUC of **0.713**.
- On the exploratory test set, the simplified model achieved a ROC-AUC of **0.649** and identified **38.5%** of failing students.
- A later-stage model using second-period mathematics grades identified **96.2%** of failing students in its test sample.
- Random forest classification did not meaningfully outperform logistic regression.

## Project Limitations

The dataset contains only 395 students, and the early-warning model demonstrated limited predictive reliability.

Model selection involved exploratory analysis, meaning the reported performance estimates should not be interpreted as independently validated results.

The models are intended for educational analysis, not for making automated decisions about individual students.

## Dataset

Source: UCI Machine Learning Repository — Student Performance Dataset.

https://archive.ics.uci.edu/dataset/320/student+performance

## How to Explore the Project

Open `Student_Performance_Analysis.ipynb` to view the Python analysis, visualisations, model comparisons and conclusions.

The accompanying `student-mat.csv` file contains the mathematics dataset used in the analysis.

## Conclusion

This project demonstrates skills in exploratory data analysis, statistical interpretation, predictive modelling, model validation and communicating findings.

The results highlight the importance of academic history and ongoing assessment while demonstrating the limitations of predicting student outcomes using background characteristics alone.
