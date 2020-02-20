# Lecture 1: What makes healthcare unique?

[Link to slides](https://mlhc19mit.github.io/slides/lecture1.pdf)

## Brief overview of healthcare and AI/ML
* Cost of healthcare expenditures rising, over $3 trillion
* Chronic conditions are often diagnosed late and inappropriately managed
* Difficult to apply AI/ML due to challenges in getting enough data, fitting into clinical workflow, and poor generalizability to new cases

## Why now?
* EHR adoption rate is soaring
* Large datasets are becoming available (i.e. MIMIC - De-ID'ed ~40k critical care patients)
* Standardization
	* Diagnosis codes: ICD-9/ICD-10
	* Laboratory tests: LOINC
* Major acquitions to get big data for ML

## Examples of how ML will transform healthcare
* Emergency Department - limited resources, time sensitive, critical decisions
	* Decision support algorithms, suggest inferred conditions and best practices
* Anticipating the clinicians' needs, lay out procedures
* Operationalize ML to reduce the need for specialist consults (i.e. radiology for chest x-rays)
* Autmoated documentation and billing
* Track and predict a patient's future disease progression
* Aid in discovering and designing new drugs, better targeted clinical trials

## What is unique about ML in healthcare?
* Need fail-proof, robust algorithms in life-or-death situations
* Many cases in healthcare are **causal**
* Very little labeled data in healthcare
* Difficult to get hands on patient data, sometimes small samples are available
* Lots of missing data
* Commerical EHR is difficult to modify, harder to deploy ML