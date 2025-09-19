# U.S. Medical Insurance Cost Analysis 🩺

### Project Description
This project is an exploratory data analysis of a U.S. medical insurance costs dataset. It was proposed by the Codecademy platform as part of the "Data and Programming Foundations for AI" course to practice and demonstrate foundational data analysis skills.

---
### Dataset
The dataset is a single `.csv` file containing 1338 patient records with the following 7 columns:
* `age`: Age of the primary beneficiary.
* `sex`: Gender of the beneficiary.
* `bmi`: Body Mass Index.
* `children`: Number of children covered by insurance.
* `smoker`: Whether the person is a smoker or not.
* `region`: The beneficiary's U.S. region (northeast, southeast, southwest, northwest).
* `charges`: Individual medical costs billed by health insurance.

---
### 🎯 Project Scope
This project aims to answer the following questions:
1.  Is there a significant difference in insurance costs between sexes?
2.  How does each variable (age, BMI, children, smoker status, region) relate to the insurance cost?
3.  Which factor has the strongest impact on insurance costs, and which has the weakest?
4.  Which US region has the highest average insurance cost?

---
### 🛠️ Tools Used
* **Python**
* **Pandas** for data manipulation and analysis.
* **Matplotlib** & **Seaborn** for data visualization.
* **Jupyter Notebook** for code development and presentation.

---
### ✅ Conclusions
After analyzing the data, we found clear answers to our initial questions:

* **Smoking is the most important factor.** Smokers pay significantly more for insurance than non-smokers, with a correlation of **+0.79** to the charges.
* **Age and BMI are the next biggest factors.** Costs rise as people get older (**+0.30** correlation) or have a higher BMI (**+0.20** correlation).
* **Other variables have little effect.** A person's sex, number of children, and region do not have a strong impact on their insurance costs.
* The **southeast region has the highest average costs**, likely because the data for that region includes more smokers and people with a higher BMI.

This concludes the analysis proposed in the scope of this project.
