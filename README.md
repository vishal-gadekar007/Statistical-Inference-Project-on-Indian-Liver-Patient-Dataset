1. Introduction
Liver disease is a major health concern in India, with high
mortality rates due to late diagnosis and limited access to
healthcare. Early detection using biomarkers (like bilirubin, liver
enzymes, and proteins) can significantly improve patient
outcomes.
This project uses the Indian Liver Patient Dataset (ILPD) to
analyze key risk factors and statistically determine which
biomarkers are most associated with liver disease.

2. Objectives
1. Statistical Analysis:
o Identify significant differences in biomarkers (e.g.,
bilirubin, albumin) between liver patients and healthy
individuals.
o Test associations (e.g., gender vs. disease prevalence).
2. Clinical Relevance:
o Provide insights for early diagnosis and targeted
treatment.
3.Reason for choosing this Topic
 High Prevalence: Liver disease is a leading cause of death
in India.
 Preventable: Early detection via biomarkers can save lives.
 Data-Driven Approach: Statistical inference helps validate
real-world diagnostic criteria.

2. Dataset Description
Data Set Information - This data set contains 416 liver patient records
and 167 non-liver patient records. The data set was collected from test
samples in North East of Andhra Pradesh, India. 'is_patient' is a class
label used to divide into groups(liver patient or not). This data set
contains 441 male patient records and 142 female patient records. Any
patient whose age exceeded 89 is listed as being of age "90".

Attributes:
 age - Age of the patient
 gender - Gender of the patient
 tot_bilirubin - Total Bilirubin
 direct_bilirubin - Direct Bilirubin
 alkphos - Alkaline Phosphotase
 sgpt- Alamine Aminotransferase
 sgot - Aspartate Aminotransferase
 tot_proteins - Total Protiens
 albumin - Albumin
 ag_ratio - Albumin and Globulin Ratio
 is_patient - Selector field used to split the data into two sets (labeled by the
experts)

Preprocessing:
o Handling missing values (e.g., ag_ratio).

Result and Conclusion:
 Total Bilirubin (TB) is a key differentiator between liver and
non-liver patients.
 Correlation analysis shows TB and DB are strongly related,
hinting at biological linkage.
 Most tests revealed statistically significant patterns
between liver-related measures and disease status.

Chi-square:
o "Males have a higher prevalence of liver disease”.
 t-test:
o "Total bilirubin is significantly higher in patients”.
 F-test:

o
“No significant difference in variance between liver
and non-liver groups”.

 Z-test:

o
“Significant difference in means between liver and
non-liver groups”.
 Correlation Analysis:

o
“Some features strongly correlated”.

References
 Dataset source:-

https://www.kaggle.com/datasets/jeevannagaraj/indian-
liver-patient-dataset

 Statistical textbooks( Fundamental of Mathematical
Statistics).
