# Exploring the Acceptability of HELP-XR among Instructors: A Tool for XR Pedagogical Content Creation
[![Static Badge](https://img.shields.io/badge/Orignal%20paper%20DOI-10.1145%2F3656650.3656681-green)](https://doi.org/10.1145/3656650.3656681)

[![Static Badge](https://img.shields.io/badge/Data%20%20DOI-XXXXX-green)](https://doi.org/10.1145/3656650.3656681)
[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ERPI-UL/helpxr-instructor-acceptability/)

This repository contains the dataset and the analysis done for research work about the acceptability of the HELP-XR authoring tool among instructors. 

Data analysis are avaialbe in the 'step2' and 'step6' folder. [The first one](/step2-GCASSurvey/step2-GCASAnalysis.ipynb) analyse demographic data and GCAS data. [The second one](/step6-UTAUT2/Step6-UTAUT2.ipynb) analyses UTAUT2 score in regards to the demographic and GCAS score.

__Authors:__ 
* Alex Gabriel
* Josselin Deborde

__Coordinators:__ 
* Alex Gabriel
* Alaa Hassan

## Details 
This experimentation involved 14 persons in a 6-step process. Among these 6 steps, this analysis consider the step 2 and 6. 
![experimentation process schema](docs/Process2.png)
* The step two consited to collect demographic data and pass a Greek Computer Attitude Scale [(Roussos, 2017)](http://doi.org/10.1016/j.chb.2004.10.027) to every participant. Although the survey was done in french, metadata concerning questions are avaialbe in [french](/step2-GCASSurvey/step2-metadata-FR.csv) and in [english](/step2-GCASSurvey/step2-metadata-EN.csv), an export of the questionnaire done with limesurvey is also alvailable the step2 folder : [here](/step2-GCASSurvey/step2-GCASSurvey-backup.lss)  
* The step six consited to evaluate the UTAUT2 [(Venkatesh et al., 2012)](http://doi.org/10.2307/41410412) score for each participant.  QUestions was ine french but metada are available both in [french](/step6-UTAUT2/step6-metadata-EN.csv) and in [english](/step6-UTAUT2/step6-metadata-FR.csv). An export of the limesurvey questionnaire with is also alvailable the step6 folder: [here](/step6-UTAUT2/step6-UTAUT2-limesurvey_survey_backup.lss).

## Reproduce the analysis 

### Online
Open this repository using Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ERPI-UL/helpxr-instructor-acceptability/)

### Locally 
1. Install the environment
    ```sh
    python -m venv .

    # for windows 
    Scripts\activate
    # Linux
    source bin/activate

    pip install -r requirements.txt
    ```
2. Start jupyter
    ```sh
    jupyter notebook
    ```
3. Use jupyter interface (in the browser though) to access to the file

4. Run the notebook