# Project1

For the project #1 I've used a dataset from https://www.kaggle.com. The original CSV file includes 14 columns and 1,025 rows of data.

The goal of the project is to analyze population of patients enrolled for the study of Cardiovascular deseases, evaluating influence of major factors like Cholesterol, age, etc.

Major columns, that have been used in the Project analysis, are listed out below:

Age: Age of patients
Sex: Sex of petients where 1 = male, 0 = female
cp: Types of chest pain experienced by patients where 0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic
trestbps: Resting blood pressure of patients (in mm Hg)
chol: Cholesterol level of patients in mg/dl
thalach: MAX heart rate of patients
exang: Angina caused by exercise, where 1 = yes and 0 = no
target: Patients with heart desease (0 = yes) and without (1 = no)

Action Steps:

1. Upload CSV data source and create a DataFrame;
2. Transform data into the view that further will be used for the analysis;
3. Find out average of major metrics 
4. Plot gender population of patients with Heart desease conditions
5. Create a box plot of patients with reference to their Cholesterol level
6. Create a scatter plot of patients population age correlated to the cholesterol level
7. Plot bar charts of patients with angina caused by excercise or not
8. Plot chart of patients by chest pain types with heart desease conditions and with non-exercise induced angina

Create a slide deck with summary and major findings, draw a conclusion.

Conclusion: 
1. Males are at higher risk of getting cardiovascular diseases.
2. Out of 499 patients participated in the study, nearly 83% were males who had Heart disease conditions.
3. All 1025 patients were selected for the study as they experienced chest pain. Plot on the slide 5 showed that the majority of patients had non-exercise induced angina and over 90% of them had a typical angina, that is one of the symptoms of myocardial ischemia or other cardiovascular diseases. 
4. Cholesterol level of patients wasn’t an obvious factor to conclude whether it triggers or not heart disease conditions and required further analysis.
5. Scatter plot visually represented correlation between patient’s age and their cholesterol level. It appears that patients of 60+ age category had a higher rate of cholesterol level, that supposedly led to cardiovascular disease conditions.
