# 🎬 Projeto CineData - Pipeline de Engenharia de Dados (Medallion Architecture) - RocketLab

Pipeline de Engenharia de Dados desenvolvido no **Databricks** utilizando a **Arquitetura Medallion** (Camadas Bronze, Silver e Gold) com o Unity Catalog. O projeto processa e modela dados para análises analíticas avançadas no domínio de cinema.

---

## 📂 Estrutura do Repositório

```text
📁 Projeto_CineData/
│
├── 📁 notebooks/
│   ├── 00_Organizacao_do_Ambiente.ipynb
│   ├── 01_Landing_to_Bronze.ipynb
│   ├── 02_Bronze_to_Silver.ipynb
│   ├── 03_Silver_to_Gold.ipynb
│   └── 04_Analytics_Challenge.ipynb
│
├── 📁 assets/
│   └── job_execution_success.png
│
├── job.yaml
├── LICENSE
└── .gitignore
