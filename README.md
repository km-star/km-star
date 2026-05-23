# Hi, I'm Kumar Mahat 👋

**MS Computer Science @ Texas Tech University** | AI/ML Researcher | Ex-Honeywell Software Engineer

---

## 🔬 Current Research

**Multi-Omic ML — Pancreatic Cancer Survival Prediction** *(IEEE BIBM 2026, under review)*

Reproduced and extended the [Molecular Twin platform](https://doi.org/10.1038/s43018-023-00697-7) (Osipov et al., *Nature Cancer* 2024) for PDAC post-resection survival prediction on 74 patients across 10 analyte modalities.

- Identified **5 implementation corrections** from Zenodo source code — all 11 analytes exceed published Table 1 baseline
- Proposed **6 novel ML method families** for small imbalanced multi-omic cohorts (SMOTE+L1+RF, RFECV+XGBoost, Stacking meta-learner, Survival discriminant filter, NearMiss undersampling, LightGBM DART)
- **8/11 analytes beat Paper Table 1** in fair same-dataset comparison
- **LightGBM DART:** AUC=0.857, Sensitivity=0.929 on multi-omic (n=39, 28/11 class imbalance)
- First mechanistic explanation of **majority-class collapse** in high-dimensional small-cohort settings: L1 sparse feature selection is the critical ingredient (RF without L1 → TN=0; with L1 → TN=11)
- All experiments on **TTU HPCC** (Tesla V100-PCIE-32GB) · Strict LOOCV · No data leakage
- Stack: Python · LightGBM · XGBoost · Scikit-learn · SMOTE · SLURM · Pandas · NumPy · Matplotlib

📁 [pdac-survival-prediction](https://github.com/km-star/pdac-survival-prediction)

---

## 🛠 What I Build

```
AI & ML          →  LLMs · RAG Pipelines · Agentic AI · XGBoost · LightGBM
                     CNN · LSTM · TensorFlow · Scikit-learn · Feature Engineering

Backend & APIs   →  Java · Spring Boot · Python · REST APIs · Apigee API Gateway
                     OAuth2 · JWT · Microservices · ASP.NET Core · Django · Flask

Cloud            →  Azure (Function Apps · Logic Apps · RBAC · ARM · AZ-900 Certified)
                     AWS (EC2 · S3 · CloudWatch · IAM) · GCP (Apigee X)

DevOps           →  Docker · Kubernetes · Jenkins · CI/CD · Git · Linux · SLURM
```

---

## 📄 Publication

**Image Caption Generator Using CNN and LSTM**
*Design Engineering Journal, 2021*
End-to-end deep learning pipeline combining ResNet feature extraction and LSTM sequence generation across 8,000+ image-caption pairs.

---

## 💼 Experience

| Role | Organization | Period |
|------|-------------|--------|
| Graduate Assistant – Analyst I | Texas Tech University | 2026 – Present |
| Software Engineer – Analyst II | Honeywell | 2024 – 2025 |
| Software Engineer – Analyst I | Honeywell | 2022 – 2024 |
| Software Engineering Intern | Honeywell | 2022 |

**Honeywell highlights:** Cloud automation (Azure/AWS/GCP), Java microservices, Apigee API Gateway (1M+ monthly API calls), FinOps dashboards, CI/CD pipelines. Bravo Award 2023.

---

## 🏆 Awards & Certifications

- 🥇 Microsoft Certified: Azure Fundamentals (AZ-900)
- 🎓 Machine Learning Nanodegree — Udacity
- 🏆 Honeywell Bravo Award (2023)
- 🎓 COMPEX Scholarship — Indian Embassy Nepal (2018)
- 🎓 Merit Scholarship — VIT University (2021)

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kumar_Mahat-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/kumar-mahat-b4a431178/)
[![Email](https://img.shields.io/badge/Email-kmahat@ttu.edu-D14836?style=flat&logo=gmail)](mailto:kmahat@ttu.edu)
[![GitHub](https://img.shields.io/badge/GitHub-km--star-181717?style=flat&logo=github)](https://github.com/km-star)

---

*F-1 Student Visa · CPT/OPT Eligible · Open to AI/ML and Software Engineering roles*
*Updated May 2026*
