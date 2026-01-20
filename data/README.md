# Data Directory: Heart Disease Dataset

This folder contains the clinical data used for predicting the presence and severity of heart disease. The data is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease) and consists of records from four different clinical sites:
* **Cleveland Clinic Foundation**
* **Hungarian Institute of Cardiology, Budapest**
* **University Hospital, Zurich, Switzerland**
* **University Hospital, Basel, Switzerland**
* **V.A. Medical Center, Long Beach, CA**


## Dataset Files
| File Name | Description |
| :--- | :--- |
| `cleveland.data` | Clinical records from the Cleveland Clinic Foundation. |
| `hungarian.data` | Clinical records from the Hungarian Institute. |
| `switzerland.data` | Clinical records from Zurich and Basel. |
| `long-beach-va.data` | Clinical records from the V.A. Medical Center in Long Beach. |

---

## Feature Information
This project focuses on a subset of 14 features:

1.  **age:** Age in years.
2.  **sex:** (1 = male; 0 = female).
3.  **cp:** Chest pain type (Value 1: typical angina; 2: atypical angina; 3: non-anginal pain; 4: asymptomatic).
4.  **trestbps:** Resting blood pressure (in mm Hg on admission to the hospital).
5.  **chol:** Serum cholestoral in mg/dl.
6.  **fbs:** Fasting blood sugar > 120 mg/dl (1 = true; 0 = false).
7.  **restecg:** Resting electrocardiographic results (0: normal; 1: ST-T wave abnormality; 2: left ventricular hypertrophy).
8.  **thalach:** Maximum heart rate achieved.
9.  **exang:** Exercise induced angina (1 = yes; 0 = no).
10. **oldpeak:** ST depression induced by exercise relative to rest.
11. **slope:** The slope of the peak exercise ST segment.
12. **ca:** Number of major vessels (0-3) colored by flourosopy.
13. **thal:** 3 = normal; 6 = fixed defect; 7 = reversable defect.
14. **num (Target):** Diagnosis of heart disease (angiographic disease status).
    * Value 0: < 50% diameter narrowing (Absence).
    * Value 1, 2, 3, 4: > 50% diameter narrowing (Presence).

---

## Citation & License
> Janosi, A., Steinbrunn, W., Pfisterer, M., & Detrano, R. (1989). [Heart Disease](https://doi.org/10.24432/C52P4X) [Dataset]. UCI Machine Learning Repository.

**License:** This dataset is licensed under a [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.
