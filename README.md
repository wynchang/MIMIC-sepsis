# MIMIC-sepsis

Project: Sepsis Risk Classifier
This project is to build a binary classification system to classify patients’ risk of sepsis based on their age, gender, and relevant chart events (blood pressure, temperature, heart rate and white blood count) at each hospital admission. Selected linear and non-linear classifier algorithms will be used to train the models to predict if the patient of each hospital admission has sepsis risk or no risk.

The project uses these files from the MIT MIMIC-III database:
- ADMISSIONS.csv
- PATIENTS.csv
- CHARTEVENTS.csv
- D_ITEMS.csv

They are stored under MIMIC-data subfolder.
Because CHARTEVENTS.csv is very large, data extraction and trimming are done on a local computer. The preprocessed information from CHARTEVENTS.csv is stored as 5 files under MIMIC-data:

- Heartrate_220045.csv
- BPsys_220050.csvv
- BPdia_220051.cs
- Temp_223761.csv
-  WBC_220546.csv

The notebooks are numbered in sequence. First 2 scripts are run on local computer.

Dataset:
MIT MIMIC-III (Medical Information Mart for Intensive Care III) Patient Database consists of de-identified Intensive Care Unit health-related data at the Beth Israel Deaconess Medical Center between 2001 and 2012.
https://mimic.physionet.org/about/mimic/



Citation:
Johnson, A., Pollard, T., Mark, R. (2016). MIMIC-III Clinical Database. PhysioNet. doi:10.13026/C2XW26

Johnson, A. E. W., Pollard, T. J., Shen, L., Lehman, L. H., Feng, M., Ghassemi, M., Moody, B., Szolovits, P., Celi, L. A., & Mark, R. G. (2016). MIMIC-III, a freely accessible critical care database. Scientific Data, 3, 160035.

Goldberger AL, Amaral LAN, Glass L, Hausdorff JM, Ivanov PCh, Mark RG, Mietus JE, Moody GB, Peng C-K, Stanley HE. PhysioBank, PhysioToolkit, and PhysioNet: Components of a New Research Resource for Complex Physiologic Signals (2003). Circulation. 101(23):e215-e220.
