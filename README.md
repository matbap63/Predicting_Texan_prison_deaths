Notebooks: this is where all the code is:
- TJI Baseline Models: initial dry-run of our project that serves as a baseline, consisting of logistic regressors trained on only three features
- TJI Gaussian NB: Gaussian Naive Bayes models with forward feature selection
- TJI SMOTE: SMOTE and related techniques, and why we shouldn't use them
- TJI complete logregs: Logistic Regression models with forward feature selection
- TJI preprocessing: EDA and pre-processing of the original dataset. This outputs a cleaned dataset that is hence used downstream
- TJI presentation: this contains all the code used for our final presentation. Code is mostly outdated and messier–refer to other notebooks for a more thorough understanding

Data: this is where the relevant data are:
- cleaned_custodial_death_reports.csv: original TJI dataset available on data.world
- preprocessed_TJI_deaths.csv: cleaned dataset outputted by TJI preprocessing notebook
