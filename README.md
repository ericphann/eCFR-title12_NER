# ⚖️ NER Models - eCFR Title 12 🏦

Fine-tuned NER models for banking and regulation texts, trained on eCFR Title 12 using manual and few-shot (GPT 3.5 v3) annotations.  

Please see the [executive write-up](https://github.com/ericphann/eCFR-title12_NER/blob/main/write-up.pdf) for metrics and process details.

## Team
- Eric Phann (data, programming, modeling)
- Kristen Zhang (annotation, reporting, documentation)
- Yaxin Zhao (annotation, research, procedure)
- Sydney Kelly (annotation, future considerations)
- Jake Stallard (annotation, future considerations)

## Contents
- __corpuses folder__ (configs, .spaCy, etc. for each pipeline)
- __data folder__ (few-shot, manual, and unlabeled data)
- __models folder__ (best/last model for each type)
- __milestones 2 & 3 folder__ (prior deliverables)
- __spacy-llm folder__ (stuff to make few-shot annotations)
- __ecfr_ner_models.ipynb__ (step-by-step Colab notebook)
- __write-up.pdf__ (executive summary; conclusions)
- __requirements.txt__ (for reproducibility)

## Dataset
- Domain: Banking compliance and risk
- Possible applications: NER, text mining, classification, policy, regulations 
- eCFR Title 12 (https://github.com/ericphann/dsba6188-group6-project/tree/main/data)

## Processing
- Generate Entity Labels, Definitions, and Few-shot Data
- Train/Test a Model Using ecfr-few-shot.jsonl
- Compile Metrics and Review
- Label 100 examples from ecfr-unlabeled.jsonl
- Review Labels and Refine Annotation Guidelines
- Create a Final Test Dataset (ecfr-manual.jsonl)
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
