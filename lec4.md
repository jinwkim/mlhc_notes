# Lecture 4: Risk Stratification

[Link to slides](https://mlhc19mit.github.io/slides/lecture4.pdf)

## Risk stratification
* With the goal of reducting cost and improving patient outcomes, **risk stratification** is separating high-risk and low-risk gropus from within a patient population
	* Interventions targeting high-risk patients
* Risk stratification was based on simple scores using human-entered data, but now automated with ML

## Case study: Early detection of Type 2 diabetes
* Diabetes cost $245 billion in 2012 within the US, $831 billion budgeted in 2014
* Requirements for large-scale prevention programs
	1. Identify true at-risk population
	2. Improve interventions being administered
	3. Lower the cost of intervention
* Traditional hand-written type 2 diabetes risk assessment forms
	* Why not embed in EMR's to capture data at point-of-care? eCRF?
* Looking at patients with diabetes today, examine which variables in their clinical histories could have predicted their health outcome
	* Example of data-driven approach to longitudinal data
	* **BUT** data might not be labeled, it might not have enough data