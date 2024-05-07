# ⚖️ NER Models - eCFR Title 12 🏦

Group 6's final project for DSBA 6188.

## Group Members
- Sydney Kelly
- Eric Phann
- Jake Stallard
- Kristen Zhang
- Yaxin Zhao

## Contents
- __corpuses folder__ (configs, .spaCy, etc. for each pipeline)
- __data folder__ (few-shot, manual, and unlabeled data)
- __models folder__ (best/last model for each type)
- __milestones 2 & 3 folder__ (prior deliverables)
- __spacy-llm folder__ (stuff to make few-shot annotations)
- __ecfr_ner_models.ipynb__ (step-by-step Colab notebook)
- __write-up.pdf__ (executive summary; conclusions)
- __requirements.txt__ (for reproducibility)

## Dateset
- Domain: Banking compliance and risk
- Possible applications: NER, semantic search, classification, policy 
- eCFR Title 12 (https://github.com/ericphann/dsba6188-group6-project/tree/main/data)

## Processing
- Generate Entity Labels, Definitions, and Few-shot Data
- Train/Test a Model Using ecfr-few-shot.jsonl
- Compile Metrics and Review
- Label ecfr-200-unlabeled.jsonl
- Review Labels and Refine Annotation Guidelines
- Create a Final Test Dataset
- Model Development

## Models
- few-shot-model
- manual-model
- mixed-model

## Future Work
- Refine Annotation Guidelines
- Expand Dataset
- Fine-tuning with Prodigy and SpaCy
- Chunking Data
- Data Privacy and Security