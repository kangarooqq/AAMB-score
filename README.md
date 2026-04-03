# AAMB Score Calculator

A simple web-based calculator for estimating the probability of low bone mineral density (BMD) in postmenopausal women.

---

## 🔍 Overview

The **AAMB Score Calculator** is a clinical decision-support tool developed based on a parsimonious multivariable logistic regression model.

It uses four routinely available variables:

- Age  
- Age at menarche  
- Age at menopause  
- Body mass index (BMI)  

to estimate an individual’s probability of low BMD.

This tool is designed to support **risk stratification** and **prioritisation of DXA referral**, particularly in primary care and community settings where access to bone density testing may be limited.

---

## 🌐 Online Calculator

👉 https://kangarooqq.github.io/AAMB-score/

---

## ⚙️ Model Description

The prediction model is based on the following logistic regression equation:

# AAMB Score Calculator

A simple web-based calculator for estimating the probability of low bone mineral density (BMD) in postmenopausal women.

---

## 🔍 Overview

The **AAMB Score Calculator** is a clinical decision-support tool developed based on a parsimonious multivariable logistic regression model.

It uses four routinely available variables:

- Age  
- Age at menarche  
- Age at menopause  
- Body mass index (BMI)  

to estimate an individual’s probability of low BMD.

This tool is designed to support **risk stratification** and **prioritisation of DXA referral**, particularly in primary care and community settings where access to bone density testing may be limited.

---

## 🌐 Online Calculator

👉 https://kangarooqq.github.io/AAMB-score/

---

## ⚙️ Model Description

The prediction model is based on the following logistic regression equation:
LP = 2.1186
+ 0.1591 × Age
− 0.1602 × Age at menopause
+ 0.1760 × Age at menarche
− 0.1646 × BMI


The predicted probability is calculated as:
P = 1 / (1 + exp(−LP))


---

## 🩺 Clinical Interpretation

The tool provides an estimated probability of low BMD and a corresponding risk profile:

- **Lower-risk profile**  
  → DXA referral may be considered based on clinical judgment  

- **Intermediate-risk profile**  
  → Consider DXA referral if clinically indicated  

- **High-risk profile**  
  → DXA referral may be prioritised  

This tool is intended as a **rule-in (high-risk identification) strategy**, rather than a universal screening or rule-out tool.

---

## 📊 Study Background

This calculator is based on the following study:

> Kang CW et al.  
> *A community-based prediction model for low bone mineral density in postmenopausal women: development and external validation*  
> (Under submission / or add DOI after publication)

- Development cohort: community-based Chinese population  
- External validation: NHANES 2009–2018 (Non-Hispanic Asian subgroup)

---

## ⚠️ Disclaimer

This tool is intended for **research and educational purposes only**.

- It is **not a diagnostic tool**
- It **does not replace DXA measurement**
- Results should always be interpreted in the context of **clinical judgment**

---

## 👨‍⚕️ Author

**Cheng-Wei Kang, MD, PhD**  
Department of Orthopaedics  
The Second Hospital of Shandong University  
Jinan, China  

---

## 📄 License

This project is open-source and intended to promote transparent and reproducible research.
