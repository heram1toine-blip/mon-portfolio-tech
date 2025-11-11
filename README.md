# mon-portfolio-tech
my journey to IT competency
# 💻 Portfolio Tech – 12-Semester Challenge
**Objectif :** 4 domaines, 4 projets finaux, 3 certifications → prêt pour le marché du travail.

---

## 🧪 Domaines couverts
| Domaine | Compétences clés | Certification cible |
|---------|------------------|---------------------|
| 🔍 Analyse de données | Python, Pandas, SQL, EDA | Kaggle Certificates |
| ☁️ Cloud Computing | AWS, Azure, Terraform | AWS CCP, AZ-900 |
| 🤖 Intelligence artificielle | CNN, NLP, Transfer Learning, MLOps | AI-900 |
| 🔐 Cybersécurité | OWASP, Blue-Team, Forensics | TryHackMe « Jr PenTester » |

---

## 📁 Projets par semaine
| Semaine | Titre | Livrable | Langage / Outils | Statut |
|---------|-------|----------|------------------|--------|
| S1 | Titanic EDA | [notebooks/S1_titanic_eda.ipynb](notebooks/S1_titanic_eda.ipynb) | Python, Pandas | ✅ |
| S2 | SQL E-commerce | [sql/S2_ecommerce_queries.sql](sql/S2_ecommerce_queries.sql) | SQL | ✅ |
| S3 | AWS EC2 Static Site | [cloud/S3_ec2_static_site/](cloud/S3_ec2_static_site/) | AWS, SSH | ✅ |
| S4 | Azure SQL + Python | [cloud/S4_azure_sql_python/](cloud/S4_azure_sql_python/) | Azure, pyodbc | 🔄 |
| S5 | CNN CIFAR-10 | [ml/S5_cifar10_cnn.ipynb](ml/S5_cifar10_cnn.ipynb) | PyTorch, Fast.ai | 🔄 |
| S6 | NLP Hugging Face | [ml/S6_nlp_finetune.ipynb](ml/S6_nlp_finetune.ipynb) | Transformers | ⏳ |
| S7 | OWASP Top10 Write-up | [sec/S7_owasp_writeup.md](sec/S7_owasp_writeup.md) | TryHackMe | ⏳ |
| S8 | Log Analysis | [sec/S8_blue_team_forensics.md](sec/S8_blue_team_forensics.md) | CyberDefenders | ⏳ |
| S9 | Kaggle Compete | [ml/S9_kaggle_houseprices/](ml/S9_kaggle_houseprices/) | scikit-learn | ⏳ |
| S10 | Terraform Infra | [cloud/S10_terraform_azure/](cloud/S10_terraform_azure/) | Terraform, Azure | ⏳ |
| S11 | ML Model API | [apis/S11_flask_ml_api/](apis/S11_flask_ml_api/) | Flask, Docker | ⏳ |
| S12 | DVWA Audit | [sec/S12_dvwa_audit_report.pdf](sec/S12_dvwa_audit_report.pdf) | Burp, DVWA | ⏳ |

---

## 🏆 Badges & Certifications
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebooks-20BEFF?logo=kaggle)](https://www.kaggle.com/tonpseudo)  
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Jr%20PenTester-%234d4d4d?logo=tryhackme)](https://tryhackme.com/p/tonpseudo)  
[![Microsoft](https://img.shields.io/badge/Microsoft-AI--900-blue?logo=microsoft)](https://www.credly.com/users/tonpseudo)  
[![AWS](https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?logo=amazon-aws)](https://www.credly.com/users/tonpseudo)  

---

## 🚀 Lancer un projet localement
```bash
git clone https://github.com/tonpseudo/mon-portfolio-tech.git
cd mon-portfolio-tech
# Ex. environnement data
conda env create -f envs/data.yml
jupyter lab
