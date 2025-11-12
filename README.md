# 🧹 Mini-Projeto 4 — Limpeza e Pré-Processamento de Dados Transacionais com Python

Projeto desenvolvido durante o curso **Fundamentos de Linguagem Python — Do Básico a Aplicações de IA**, da **Data Science Academy (DSA)**.  
O objetivo é transformar dados transacionais brutos de um e-commerce em informações limpas, consistentes e úteis para apoiar decisões estratégicas.

---

## 🧭 1. Contexto do Negócio

Empresas em crescimento frequentemente enfrentam desafios relacionados à **qualidade dos dados**: bases volumosas e desorganizadas, com valores ausentes, registros duplicados, inconsistências de tipo, erros de digitação e outliers que distorcem resultados.  

Esses problemas comprometem a **confiabilidade das análises** e dificultam a tomada de decisões nas áreas de **marketing, vendas, estoque e logística**.

---

## 🎯 2. Objetivo do Projeto

Desenvolver um **pipeline de limpeza e pré-processamento de dados** em Python utilizando a biblioteca **Pandas**, com o propósito de gerar um dataset confiável e preparado para análises estatísticas e dashboards de desempenho.

---

## 🧮 3. Escopo Analítico

As principais etapas realizadas foram:

1. **Criação de base fictícia** simulando dados reais de um e-commerce.  
2. **Tratamento de valores ausentes:** substituições, remoções e preenchimentos condicionais.  
3. **Remoção de duplicatas e inconsistências de tipo.**  
4. **Correção de erros e digitação em colunas categóricas.**  
5. **Identificação e eliminação de outliers** com base em medidas estatísticas (IQR e desvio-padrão).  
6. **Engenharia de atributos:** criação de colunas derivadas, como valor total da venda (`quantidade * preço`).  
7. **Análise Exploratória de Dados (EDA):**  
   - Faturamento total e médio por categoria.  
   - Produtos mais vendidos.  
   - Evolução temporal das vendas.  
   - Distribuição de status de entrega.  
8. **Visualização de dados** com Matplotlib, Seaborn e Plotly.

---

## 📊 4. Resultados Obtidos

- **Base de dados limpa e validada**, pronta para uso em relatórios e modelos analíticos.  
- **Identificação de padrões** de vendas e desempenho por categoria de produto.  
- **Gráficos e indicadores visuais** para comunicação clara dos resultados.  
- **Insights de negócio** que suportam decisões sobre:
  - Otimização de estoque.  
  - Estratégias de marketing direcionado.  
  - Ajustes logísticos e operacionais.

---

## 🧰 5. Tecnologias Utilizadas

| Categoria | Ferramenta / Biblioteca |
|------------|------------------------|
| Linguagem | Python 3.12 |
| Bibliotecas Principais | Pandas, NumPy |
| Visualização | Matplotlib, Seaborn, Plotly |
| Ambiente | Jupyter Notebook (VS Code) |
| Controle de Versão | Git e GitHub |

---

## 📂 6. Estrutura do Projeto

Python-MiniProjeto4/
│

├── Python-MiniProjeto4.ipynb # Notebook principal do projeto

└── README.md # documentação do projeto


---

## 👩‍💻 7. Autora

**Myrelle Torres**  

---

> 📈 *Este projeto reforça boas práticas de tratamento e validação de dados, etapa essencial para qualquer processo analítico e pilar fundamental da Ciência de Dados.*

---
