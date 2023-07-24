### JupySQL - Performing-ETL

#### JupySQL allows you to run SQL and plot large datasets in Jupyter via a %sql, %%sql, and %sqlplot magics. 

#### JupySQL is compatible with all major databases (e.g., PostgreSQL, MySQL, SQL Server), data warehouses (e.g., Snowflake, BigQuery, Redshift), and embedded engines (SQLite, and DuckDB).  [Access the User Guide here!](https://jupysql.ploomber.io/en/latest/quick-start.html)

The dataset heart_disease.csv used for the analysis is avaiable here:  [Access the dataset here!](https://github.com/mfigueiro/JupySQL---Performing-ETL/blob/main/heart_disease.csv) where

> 1. **age**: Age in years
2. **sex**: Sex (**1** = male; **0** = female)
3. **cp**: Chest pain type (**1** = typical angina, **2** = atypical angina, **3** = non-anginal pain, **4** = asymptomatic)
4. **trestbps**: Resting blood pressure (in mm Hg on admission to the hospital)
5. **chol**: Serum cholesterol in mg/dl 6 fbs: (fasting blood sugar > 120 mg/dl) (**1** = true; **0** = false)
6. **fbs**: Fasting blood sugar > 120 mg/dl (**1** = true; **0** = false)
7. **restecg**: Resting electrocardiographic results (**0** = normal, **1** = having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), **2** = showing probable or definite left ventricular hypertrophy by Estes' criteria)
8. **thalach**: Maximum heart rate achieved
9. **exang**: Exercise induced angina (**1** = yes; **0** = no)
10. **oldpeak**: ST depression induced by exercise relative to rest
11. **slope**: The slope of the peak exercise ST segment (**1** = upsloping, **2** = flat, **3** = downsloping)
12. **ca**: Number of major vessels (0-3) colored by fluoroscopy
13. **thal**: **3** = normal; **6** = fixed defect; **7** = reversible defect  
14. **target**: **1** indicating that the patient has heart disease and **0** indicating that they do not.
