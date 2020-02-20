# Lecture 5: Risk Stratification (continued)

[Link to slides](https://mlhc19mit.github.io/slides/lecture5.pdf)

## Risk stratification -> drives interventions
* Deriving labels on data
	* Manually label by chart review
	* Use business logic or machine learning to assign labels
* Evaluation of models
	* Need to calibrate
	* Determine true positive rate, minimize false positives
* No big wins from deep models on structured data/text due to significant amounts of missing data, many time scales, not enough data

## Survival modeling
* Right-censored data - above a certain value but unknown by how much
* Left-censored data - below a certain value but unknown by how much
* Kaplan-Meier estimator - good for unconditional density estimation
* Concordance-index (C-statistic) - examines model's ability to predict relative survival times

