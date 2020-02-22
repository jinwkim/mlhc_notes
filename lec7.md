# Lecture 7: NLP / Clinical Text (Part 1)

[Link to slides](https://mlhc19mit.github.io/slides/lecture7.pdf)

## Value of data in clinical text
* Bulk of valuable data are embedded in narrative text (i.e. discharge summary)
![Sample narrative text](/narrative.png)
* Case: Finding a cohort of rheumatoid arthritis (RA) cases
* Typical goals of MNLP
	* Assign meaningful terminology to words (i.e. rheumatoid arthritis -> 714.0 ICD9)
	* Extract discrete values
	* De-identification
	* Cohort selection based on inclusion-exclusion criteria

## Hyper-simplified linguistics
* How to make sense of relationship between syntax and semantics, ultimately to represent the real world?
	* Map to meaning

## Term spotting + handling negation, uncertainty
* Generalize terms
	* Use synonymous terms and take advantage of related terms
* Negation - "NegEx"
	* Find patterns of negation - i.e. "no signs of", "unlikely", "no", "not"
* Unified Medical Language Systems project (UMLS)
	* Map biomedical text to UMLS Metatheaurus
	* Metathesaurus - large, multi-lingual vocabulary DB with info on biomedical/health related concepts, names, relationships
	* Synonym mappings across vocabularies
	* "heart attack" = "actue myocardial infarct" = etc.

## ML to expand terms

## Pre-NN ML to identify entities and relations

## Language models

## Neural methods
