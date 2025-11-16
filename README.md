# Projeto Integrador IV – Sistema Inteligente para Gestão de Oficina de Bombas Injetoras Diesel

## 📌 Visão Geral
Este projeto tem como objetivo otimizar o sistema de gestão de uma oficina de bombas injetoras diesel por meio de análise de dados em escala, Machine Learning, dashboards em tempo real e automação de relatórios.  
A solução melhora a tomada de decisão, aumenta a eficiência operacional e eleva a qualidade do atendimento ao cliente.

---

## 🎯 Objetivos do Projeto

### **Objetivo Geral**
Desenvolver uma plataforma integrada capaz de analisar dados operacionais de forma automatizada, aplicar Machine Learning e disponibilizar insights em dashboards dinâmicos.

### **Objetivos Específicos**
- Implementar modelos de Machine Learning (Árvore de Decisão e Rede Neural).  
- Criar dashboards interativos com Streamlit.  
- Automatizar relatórios para apoio à gestão.  
- Realizar análise qualitativa (etnografia) com observação de processos reais.  
- Integrar banco de dados e arquitetura escalável em nuvem.

---

## 🧪 Metodologia
Foi utilizada uma **metodologia mista**, combinando:

- **Método Quantitativo**:  
  - Tratamento de dados  
  - Construção de modelos de ML  
  - Análises estatísticas

- **Método Qualitativo/Etnográfico**:  
  - Observação dos funcionários  
  - Identificação de dores e gargalos  
  - Proposição de melhorias reais no sistema

---

## 🏗️ Arquitetura da Solução

A arquitetura implementada inclui:

- **Python** (pandas, scikit-learn, numpy, streamlit)  
- **Machine Learning**  
- **Banco de Dados** (Google Drive / local, adaptável para MySQL/PostgreSQL)  
- **Dashboard Web** (Streamlit)  
- **Cloud Storage** (Google Drive API)  

Veja o diagrama completo abaixo.

<img width="1536" height="1024" alt="1c252ff9-10e4-4c5c-a414-a20141e6beab" src="https://github.com/user-attachments/assets/8af0e719-81f2-4fc6-b451-2fad5a28767b" />

---

## 📊 Funcionalidades Implementadas

- Dashboard com indicadores chave (tempo de execução, frequência, serviços, retrabalho, etc.)
- Automação de relatórios
- Pipeline de ML para previsão e classificação
- Interface Web simples e funcional
- Exportação automática para Excel

---

## 🛠️ Tecnologias Utilizadas

| Componente | Tecnologia |
|-----------|------------|
| Linguagem | Python 3.10+ |
| Dashboard | Streamlit |
| ML | Scikit-learn, TensorFlow/Keras |
| Armazenamento | Google Drive API / Excel |
| Manipulação de Dados | Pandas, NumPy |
| Versionamento | Git + GitHub |
| Cloud | Google Drive |

---
## 📁 Estrutura de Pastas Recomendada
📦 projeto-integrador-IV
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── models/
│
├── src/
│   ├── preprocessing/
│   ├── ml/
│   ├── utils/
│   └── dashboard/
│       └── main.py
│
├── notebooks/
├── reports/
├── streamlit_app/
├── requirements.txt
└── README.md




