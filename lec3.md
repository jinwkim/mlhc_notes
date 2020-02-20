# Lecture 3: Deep dive into clinical data

[Link to slides](https://mlhc19mit.github.io/slides/lecture3.pdf)

## Types of data
* Demographics
	* Age, sex, socio-economic status, insurance, location, religion, work, language, etc.
* Vital signs
	* Weight, height, pulse, temperature, etc.
* Medications
	* Prescriptions, over-the-counter drugs, alcohol, etc.
* Laboratory
	* Blood, urine, etc.
	* Lab values can vary by time of day
	* LOINC - Logical Observation Identifiers Names and Codes
![Sample HL7 for lab results](/hl7_loinc.png)
* Pathology
	* Biopsy samples, cell-level measurements, qualitative/quantitative examination of tissue
* Notes (unstructured data)
	* Discharge summary
	* Specialist notes from radiology, pathology, social workers, etc.
	* May need NLP to extract discrete data
* Billing
	* Diagnoses (ICD-9/ICD-10)
	* Procedures (CPT / ICD)
* Imaging
	* X-ray, ultrasound, CT, MRI, PET, etc.

## Harmonization of data is difficult and time consuming