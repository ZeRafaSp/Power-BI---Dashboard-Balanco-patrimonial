# 📊 Dashboard de Balanço Patrimonial no Power BI

## 📌 Sobre o Projeto

Este projeto foi desenvolvido utilizando **Microsoft Power BI** com o objetivo de apresentar uma análise do **Balanço Patrimonial** de uma empresa por meio de uma visualização em matriz, permitindo acompanhar a evolução das contas contábeis ao longo dos anos.

O dashboard foi estruturado para facilitar a leitura das demonstrações financeiras, utilizando hierarquia de contas, indicadores visuais e modelagem de dados para tornar a análise mais intuitiva.

---

## 📊 Funcionalidades do Dashboard

O dashboard oferece os seguintes recursos:

- 📈 Análise da evolução patrimonial entre os anos de 2019 a 2023
- 📋 Visualização em matriz com hierarquia de contas
- 📊 Comparação anual dos valores contábeis
- 🟢 Indicadores visuais para destacar crescimento das contas
- 🔴 Identificação de contas com valores negativos
- 📂 Navegação por níveis do Plano de Contas

---

## 🗂 Modelagem dos Dados

O projeto utiliza duas tabelas relacionadas por meio do campo **ID_Conta**.

### PlanoContas

Responsável pela estrutura hierárquica das contas contábeis:

- Conta Nível 1
- Conta Nível 2
- Conta Nível 3
- Conta Nível 4
- Tipo Relatório
- ID_Conta

### DadosContabeis

Tabela contendo os valores contábeis por exercício:

- Ano_2019
- Ano_2020
- Ano_2021
- Ano_2022
- Ano_2023
- ID_Conta

A modelagem permite realizar análises comparativas entre exercícios mantendo a organização do plano de contas.

---

## 🛠 Tecnologias Utilizadas

- Microsoft Power BI
- Power Query
- DAX
- Modelagem de Dados
- Visual Matriz
- Formatação Condicional
- Business Intelligence

---

## 📈 Principais Análises

Com este dashboard é possível:

- Analisar a evolução do Ativo, Passivo e Patrimônio ao longo dos anos;
- Comparar o crescimento das contas contábeis entre diferentes exercícios;
- Visualizar rapidamente contas com maior impacto financeiro;
- Identificar tendências positivas e negativas através da formatação condicional;
- Navegar pela estrutura hierárquica do Plano de Contas.

---

## 📷 Prévia do Dashboard

### Dashboard Principal

> *(Inserir aqui a imagem `dashboard.png`)*

### Modelo de Dados

> *(Inserir aqui a imagem `modelo_dados.png`)*

---

## 🎯 Competências Demonstradas

Este projeto demonstra conhecimentos em:

- Power BI
- Power Query
- DAX
- Modelagem de Dados
- Relacionamento entre tabelas
- Visualização de Dados
- Business Intelligence
- Análise Financeira
- Demonstrações Contábeis
- Storytelling com Dados

---

## 📁 Estrutura do Repositório

```
📂 PowerBI-Balanco-Patrimonial
│
├── Dashboard.pbix
├── README.md
├── imagens
│   ├── dashboard.png
│   └── modelo_dados.png
└── dataset
```

---

## 👨‍💻 Autor

**José Rafael Santos Pereira**

Profissional de Tecnologia da Informação em transição para a área de **Análise de Dados**, desenvolvendo projetos práticos com foco em **Power BI**, **SQL**, **Python** e **Business Intelligence**.

📌 GitHub: https://github.com/ZeRafaSp
