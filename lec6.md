# Lecture 6: Physiological time-series

[Link to slides](https://mlhc19mit.github.io/slides/lecture6.pdf)

## Recap of risk stratification
* See [lecture 5 notes](https://github.com/jinwkim/mlhc_notes/blob/master/lec5.md)

## Physiological time-series
* Typical use cases:
	1. Infer true physiological signal from noisy observations
	2. Risk stratification - i.e. predict clinical deterioration or diagnosis
	* Highly depends on availability of labeled data, how much training data
* Important to help mitigate **alarm fatigue** by not alerting clinicians when unnecessary
	* Identify and remove artifactual processes (error) from data (i.e. measurement errors) for use in downstream predictive tasks

### Detecting atrial fibrillation
* No matter how good the model, there are so many parameters and hyperparameters to tune, the search space can be enormous
* We are nearly always in realm of **"not enough data"**