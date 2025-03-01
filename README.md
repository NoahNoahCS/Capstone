# BrainStation Data Science Capstone Template

This is a template repository for setting up your capstone project: it includes a simple folder structure and placeholder files for the most important assets you will be creating.

## Usage

1. Start a new GitHub repo using this template.
2. Update your `LICENSE` file with date and owner.
3. Update your `README.md` file to reflect the project - see a sample structure below and please refer to Synapse on what needs to be included here. 
4. Set up and activate your conda environment:
    - Create a new `conda` environment for your capstone project.
    - Activate the environment and export:
        ```bash
        conda env export > conda.yml
        ```
    - Make sure re-export every time after you update the environment.
    - You can reset your conda environment by running:
        ```bash
        conda env create -f conda.yml
        conda activate <your-env-name>
        ```
5. Add your own notebooks in `./notebooks/` and remove placeholders.
6. Add your own data in `./data/` and remove placeholder. Note: `.gitignore` will ignore the data folder when you push to github, save a copy of your raw and processed data, pickled models in a Google Drive folder and add the link in the `data_links.md` file.
7. Add your project documents, figures, reports, presentation pdf's in the `./docs` and remove placeholders.
8. Add your references (tutorials, papers, books etc.) in `./references`. 
9. Add your own scripts in `./src/` and remove unnecessary folders.

Feel free to rename the folder and customize the project structure to best fit your work - this template is just the starting point.

------------------------------------------------------------------------------

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
...     MRI Data 
        1. Image Acquisition and Preprocessing
        2. Feature Extraction
        3. Feature Transformation
        4. Data splitting
        5. SVM Model Training
        6. Model Evaluation
...     Patient Data
        1. Combining data frames 
        2. EDA
        3. Model Creation
        4. Model Evaluation
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
