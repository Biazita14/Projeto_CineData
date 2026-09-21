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

## ⚙️ Descrição dos Componentes

| Arquivo / Caminho | Descrição |
| :--- | :--- |
| `notebooks/00_Organizacao_do_Ambiente.ipynb` | Configuração inicial do catálogo, esquemas (*schemas*) e diretórios de trabalho no ambiente Databricks. |
| `notebooks/01_Landing_to_Bronze.ipynb` | Ingestão dos dados brutos (*Landing*) para a camada de armazenamento persistente (*Bronze*). |
| `notebooks/02_Bronze_to_Silver.ipynb` | Limpeza, tratamento de nulos, tipagem de dados e modelagem relacional na camada intermediária (*Silver*). |
| `notebooks/03_Silver_to_Gold.ipynb` | Criação de agregações de negócio, tabelas fato/dimensão e tabelas consolidadas para consumo analítico (*Gold*). |
| `notebooks/04_Analytics_Challenge.ipynb` | Consultas analíticas avançadas e validação das regras de negócio utilizando *Surrogate Keys*. |
| `job.yaml` | Arquivo de configuração de orquestração do Databricks Workflows automatizando a execução sequencial do pipeline. |

---

## 📊 Comprovante de Execução do Pipeline (DAG)

A imagem abaixo demonstra o sucesso na execução orquestrada das tarefas de ponta a ponta:

![Comprovante de Execução do Pipeline](caminho/para/sua/imagem.png)

---

## 🛠️ Tecnologias Utilizadas

* **Databricks** (Unity Catalog & Workflows)
* **Apache Spark** / **PySpark**
* **Python** / **Jupyter Notebooks**
* **Git** & **GitHub**

---

## 📄 Licença

Distribuído sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
