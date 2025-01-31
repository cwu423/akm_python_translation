# AKM Model Translation from R to Python

This repository contains a Python implementation of the Abowd, Kramarz, and Margolis (1999) **AKM two-way fixed effects model**, translated from an original R implementation by Stephen Tino (University of Toronto). The AKM model is widely used in labor economics to estimate worker and firm contributions to earnings inequality using matched employer-employee data.

## 📌 Project Goals  
- Convert the R-based AKM estimation to Python  
- Maintain equivalent model estimation, variance decomposition, and fixed-effects computation  
- Extend the model to support **gender-specific AKM estimation**  

## 📂 Repository Structure  
- `r_version/` – Original R scripts for reference  
- `python_version/` – Translated Python implementation  
- `data/` – Simulated employer-employee dataset for testing  
- `README.md` – Project documentation  

## 🔗 Original R-based Implementation  
The original R implementation was developed by **Stephen Tino (University of Toronto)**.  
Author: Stephen Tino, PhD Candidate in Economics, University of Toronto, s.tino@mail.utoronto.ca
GitHub Repository: https://github.com/stephentino/estimate_akm

## 📄 License  
This project retains the **LGPL-2.1 license** as required by the original repository.  

## 👥 Contributors  
- Chiayi (Aiden) Wu
- Mia Zhang
- Brenda

## 🚀 Getting Started  
### 1. Clone the Repository  
```bash
git clone https://github.com/cwu423/akm_python_translation.git
cd akm_python_translation
