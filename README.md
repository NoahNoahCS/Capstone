

## Brain Tumor ID and Recommendation System
=========================

### Executive Summary

... As cancer rates rise it is crucial increase hospital efficiency if we want to continue to give quality care to our most at-risk patients. The project will help diagnose brain tumors and create a priliminary treatment plan per the findings of the diagnostic portion.
... The project consists of three parts. 
    1. Using MRI data, a support vector machine will be used to identify the presence of a brain tumor and then classify what kind of tumor is found. 
    2. Using collected patient data a classification model will be created to help identify what subtype of tumor is most likely per patient information. 
    3. A recommendation model will provide a suggestion for a treatment plan for the patient given their patient info, past treatment info, and the subtype of tumor of the patient. 
... Key takeaways

### Demo

... Show your work:
...     Data visualizations
...     Interactive demo (e.g., `streamlit` app)
...     Short video of users trying out the solution


### Methodology

... High-level diagrams of entire process:
*     Support Vector Machine w/ MRI Data
        - 1. Image Acquisition and Preprocessing
        - 2. Feature Extraction
        - 3. Feature Transformation
        - 4. Data splitting
        - 5. SVM Model Training
        - 6. Model Evaluation
*     Classifier Model w/ Patient Data
        - 1. Combining data frames 
        - 2. EDA
        - 3. Feature Selection
        - 4. Model Creation
        - 5. Model Evaluation
*     Recommender Model w/ Treatment and Patient Data
        - 1. Combining data frames w/ patient data
        - 2. EDA
        - 3. Feature Selection
        - 4. Model Creation
        - 5. Model Evaluation
...     various modelling directions
...     various prototyping directions


### Organization

#### Repository 

* `data` 
    - https://docs.google.com/document/d/1YxfU2WQrP9JgYS0MiYoAdp6zUTAPDMq4n6r_pMbP9oI/edit?usp=sharing
    - saved copy of aggregated / processed data as long as those are not too large (> 10 MB)

* `model`
    - `joblib` dump of final model(s)

* `notebooks`
    - contains all final notebooks involved in the project

* `docs`
    - contains final report, presentations which summarize the project

* `references`
    - contains papers / tutorials used in the project

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `conda.yml`
    - Conda environment specification

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

#### Dataset

... https://docs.google.com/document/d/1YxfU2WQrP9JgYS0MiYoAdp6zUTAPDMq4n6r_pMbP9oI/edit?usp=sharing

### Credits & References

... Include any personal learning
