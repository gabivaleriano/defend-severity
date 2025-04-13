# defend-prognosis

This repository provides code and data to **generate machine learning models** that predict **COVID-19 severity**, and to **compare model performance across hospitals**.

## 📁 Contents

- **Two `.csv` files**: Preprocessed datasets from two major Brazilian hospitals.
- **Five Jupyter notebooks** for:
  - Data integration
  - Data preprocessing
  - Model training and evaluation

---

## 📓 Notebooks Overview

### 🔗 `bp_integration` and `hsl_integration`

These notebooks contain all code used to **integrate the raw data** from each hospital.

In the original dataset (`tests`), there were cases where the **same test had similar but conflicting labels**. These inconsistencies were **resolved with the help of a domain expert**.

📝 The corrected version of the dataset (`HSL_Exames_4_labels.csv`) and the corresponding code are available at:  
👉 [github.com/gabivaleriano/defend-prognosis](https://github.com/gabivaleriano/defend-prognosis)

---

### `preprocessing_bp_severity_hospitalized` and `preprocessing_hsl_severity_hospitalized`

Include all code used to **preprocess COVID-19 data** from:

- **Hospital Beneficência Portuguesa (BP)**
- **Hospital Sírio-Libanês (HSL)**

📌 Raw data is publicly available at:  
https://repositoriodatasharingfapesp.uspdigital.usp.br/

---

### `models_training`

Contains code for training machine learning models to **predict patient severity outcomes**, using clinical parameters collected **within four days of initial hospital attendance**.

---

## 📂 Datasets

### `.csv` Files

- `hosp1.csv`: Preprocessed data from **Hospital Sírio-Libanês**
- `hosp2.csv`: Preprocessed data from **Hospital Beneficência Portuguesa**

These files reflect the cleaned and integrated datasets ready for model development, as described in the notebooks.

---

## 🔍 Looking for More Refined and Documented Data?

A refined and better-documented version of these datasets (and others) is available in:  
👉 [HealthDataBR](https://github.com/gabivaleriano/HealthDataBR) 

---

## 📢 Citation

If you use these datasets or code in a scientific publication, we kindly ask that you cite the associated paper:  

@inproceedings{valeriano2022supporting,
  title={Supporting decision making in health scenarios with machine learning models},
  author={Valeriano, Maria Gabriela and Kiffer, Carlos Roberto Veiga and Lorena, Ana Carolina},
  booktitle={Anais do 54° Simpósio Brasileiro de Pesquisa Operacional (SBPO 2022)},
  year={2022},  
  address={Juiz de Fora}
}
