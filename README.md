# 📊 Modelo de Regressão para Análise de Impacto de Marketing

<div align="center">
   <img src="img/banner.jpg" alt="Banner do Projeto" width="400"/>
</div>

Bem-vindo ao repositório do projeto de **Modelo de Regressão** desenvolvido como parte do curso de Engenharia de Dados da Escola DNC! Este projeto tem como objetivo avaliar o impacto dos investimentos em publicidade sobre as vendas, utilizando técnicas de análise de dados e machine learning.

---

## 🚀 **Sobre o Projeto**

Este projeto foi desenvolvido para entender como diferentes canais de marketing (TV, Rádio, Jornal) impactam as vendas de um produto. Utilizamos um modelo de regressão linear para prever o retorno sobre o investimento (ROI) e identificar quais canais são mais eficazes.

### **Objetivos:**
- 📈 Analisar o impacto dos investimentos em marketing nas vendas.
- 🛠 Construir e ajustar um modelo de regressão linear.
- 📊 Gerar insights estratégicos para tomada de decisão.

---
## 🛠 **Tecnologias Utilizadas**

Aqui estão as principais ferramentas e tecnologias utilizadas no projeto:

<table align="center" style="text-align: center;">
  <tr>
    <td align="center"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/></td>
    <td align="center"><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/></td>
    <td align="center"><img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/></td>
  </tr>
  <tr>
    <td align="center"><img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"/></td>
    <td align="center"><img src="https://img.shields.io/badge/Seaborn-1F72B6?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn"/></td>
    <td align="center"><img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn"/></td>
  </tr>
  <tr>
    <td align="center"><img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white" alt="Google Colab"/></td>
    <td align="center"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/></td>
    <td align="center"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></td>
  </tr>
</table>
---

## 📂 **Estrutura do Repositório**

O repositório está organizado da seguinte forma:


---

## 📊 **Análise Exploratória**

Aqui estão alguns dos insights gerados durante a análise exploratória:

### **Gráfico de Correlação entre Variáveis**
![Gráfico de Correlação](img/2025-02-08-12-16-10.png)

### **Impacto dos Investimentos por Canal**
![Impacto por Canal](img/impacto.png)

---

## 🧠 **Modelagem**

Utilizamos um modelo de regressão linear para prever as vendas com base nos investimentos em marketing. Abaixo estão os principais resultados:

### **Coeficientes do Modelo**
| Canal     | Coeficiente |
|-----------|-------------|
| TV        | 0.045       |
| Rádio     | 0.188       |
| Jornal    | 0.001       |

### **Avaliação do Modelo**
- **R² (Coeficiente de Determinação):** 0.89
- **Erro Médio Quadrático (MSE):** 2.56
