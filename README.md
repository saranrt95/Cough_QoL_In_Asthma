# Cough_QoL_In_Asthma

This repository contains the data used in the paper Narteni, S., Baiardini, I., Braido, F., & Mongelli, M. (2023). Explainable artificial intelligence for cough-related quality of life impairment prediction in asthmatic patients. medRxiv, 2023-10. Currently under revision in PLOS One.

This work presents an innovative application of a rule-based classification model to identify the main factors involved in chronic cough-related quality of life (QoL) impairment in a cohort of asthmatic patients. The proposed approach first involves the design of a suitable symptoms questionnaire, and the subsequent analyses via explainable machine learning. 
The questionnaire driving the input features creation has the following structure

<img width="761" alt="Schermata 2023-12-12 alle 12 28 14" src="https://github.com/saranrt95/Cough_QoL_In_Asthma/assets/77918497/54759468-f799-4d57-a0bc-39ed694c8bf6">

# Data description

Two datasets are made available:

- _CoughInAsthmaDatabase.xlsx_ is the final dataset used after building the blocks from the symptoms questionnaire. The following columns are available:
    - `ID`: Patient ID
    - `Age`
    - `FEV1`
    - `AsthmaRelated`: average of symptoms questionnaire items related to asthma
    - `PharynxLarynx`: average of symptoms questionnaire items related to the throat
    - `RhinoSinusitis`: average of symptoms questionnaire items related to the nose
    - `GastroEsoReflux`: average of symptoms questionnaire items related to the stomach
    - `CCIQ GLS`: score measuring the impact of chronich cough on QoL
    - `ACT TOT`: total score from the Asthma Control Test
    - `output`: binary target label (near normal QoL or abnormal QoL)
    - `ACT_group`: binary asthma control level (controlled asthma for ACT > 20, not controlled asthma otherwise)
      
-_CoughInAsthmaDatabase_Full.xlsx_: same as the above, but we also share the single patients' responses to the questionnaire items.

# Citation
For usage in research works, please cite: Narteni, S., Baiardini, I., Braido, F., & Mongelli, M. (2023). Explainable artificial intelligence for cough-related quality of life impairment prediction in asthmatic patients. medRxiv, 2023-10

For further information: sara.narteni@ieiit.cnr.it

