# Multiple Sclerosis Patient Analytics 
## Overview
This project explores clinical and demographic data from patients evaluated for Multiple Sclerosis (MS). The goal is to identify factors associated with the development of Clinically Definite Multiple Sclerosis (CDMS) and present the results through an interactive Tableau dashboard.
The project combines Python, PostgreSQL, and Tableau to demonstrate an end-to-end healthcare analytics workflow, including data cleaning, exploratory analysis, statistical analysis, and interactive visualization.
<img width="1438" height="825" alt="ms_patients_dashboard" src="https://github.com/user-attachments/assets/2caff887-1fbc-49a2-8dcb-1be8b5c6b82c" />

## Project Questions
- Clean and prepare a clinical dataset for analysis.
- Explore patient demographics and clinical characteristics.
- Compare CDMS and non-CDMS patient groups.
- Investigate associations between clinical variables and disease outcome.
- Build an interactive dashboard to support data exploration.

## Dataset
### Source: Kaggle “Multiple Sclerosis Disease”
(https://www.kaggle.com/datasets/desalegngeb/conversion-predictors-of-cis-to-multiple-sclerosis/data)

### The dataset contains anonymized patient information, including:
1. ID: Patient identifier (int)
2. Age: Age of the patient (in years)
3. Schooling: time the patient spent in school (in years)
4. Gender
5. Breastfeeding (yes, no, unknown)
6. Varicella: Another name for Chickenpox, or chicken pox, is a highly contagious disease caused by the initial infection with varicella zoster virus (VZV), a member of the herpesvirus family.
7. Initial_Symptoms: 1=visual, 2=sensory, 3=motor, 4=other, 5= visual and sensory, 6=visual and motor, 7=visual and others, 8=sensory and motor, 9=sensory and other, 10=motor and other, 11=Visual, sensory and motor, 12=visual, sensory and other, 13=Visual, motor and other, 14=Sensory, motor and other, 15=visual,sensory,motor and other
8. Mono _or_Polysymptomatic: 1=monosymptomatic, 2=polysymptomatic, 3=unknown
9. Oligoclonal_Bands: Oligoclonal bands (OCBs) are bands of immunoglobulins that are seen when a patient's blood serum, or cerebrospinal fluid (CSF) is analyzed. They are used in the diagnosis of various neurological and blood diseases. Oligoclonal bands are present in the CSF of more than 95% of patients with clinically definite multiple sclerosis.
10. LLSSEP (positive, negative): lower limb SSEP. Somatosensory evoked potentials (SSEP) are recorded from the central nervous system following stimulation of peripheral nerves. 
11. VEP (positive, negative): Visual evoked potential (VEP) is an evoked potential elicited by presenting light flash or pattern stimulus which can be used to confirm damage to visual pathway including retina, optic nerve, optic chiasm, optic radiations, and occipital cortex.
12. ULSSEP (positive, negative): upper limb SSEP. 
13. BAEP (positive, negative): BAEP: In human neuroanatomy, brainstem auditory evoked potentials (BAEPs), also called brainstem auditory evoked responses (BAERs), are very small auditory evoked potentials in response to an auditory stimulus, which are recorded by electrodes placed on the scalp.
14. Periventricular_MRI (positive, negative) result
15. Cortical_MRI (positive, negative) result
16. Infratentorial_MRI (positive, negative) result
17. Spinal_Cord_MRI  (positive, negative) result
18. initial_EDSS: The Expanded Disability Status Scale (EDSS) is a method of quantifying disability in multiple sclerosis and monitoring changes in the level of disability over time. It is widely used in clinical trials and in the assessment of people with MS. 2
19. final_EDSS
20. Group (CDMS, non-CDMS)

## Tools Used
- Python
- Pandas
- Matplotlib
- PostgreSQL
- Data querying
- Aggregation
- Correlation analysis
- Tableau
- Interactive dashboard
- Data visualization
- KPIs

## Skills Demonstrated
- Data cleaning
- Exploratory Data Analysis (EDA)
- SQL querying
- Statistical analysis
- Correlation analysis
- Healthcare data analytics
- Interactive dashboard design
- Data storytelling

## Future Improvements
- Build a logistic regression model to estimate the contribution of each clinical feature to CDMS prediction.
- Evaluate model performance using ROC-AUC, precision, recall, and confusion matrices.
- Investigate feature importance using machine learning methods.
- Incorporate additional statistical tests to compare patient groups.

## Disclaimer
This project is intended for educational and portfolio purposes. The analyses presented here are exploratory and should not be interpreted as clinical recommendations or medical advice.


