# Análise de Infrações Ambientais do IBAMA

Este projeto apresenta uma análise exploratória utilizando Python e Pandas das infrações ambientais registradas pelo IBAMA, com base no conjunto de dados `auto_infracao_IBAMA.csv`.

## 📌 Objetivos

- Carregar e tratar o conjunto de dados.
- Identificar tipos distintos de infração e determinar a menos frequente.
- Apontar estados com maior incidência de infrações e o valor acumulado de multas.
- Analisar a distribuição mensal das infrações através de gráficos.

## 🚀 Tecnologias Usadas

- **Python**
- **Pandas**
- **Matplotlib**

## 📂 Estrutura dos Arquivos

```
projeto-ibama/
├── auto_infracao_IBAMA.csv  # Dataset original
├── analise_ibama.ipynb      # Notebook Jupyter com a análise completa
└── README.md                # Descrição e documentação do projeto
```

## 📊 Principais Resultados

- Existem **3 tipos de infração** diferentes.
- A infração menos comum é **"Multa diaria"**, com **22 ocorrências**.
- O estado com mais infrações é **Minas Gerais (MG)**, com um total de **10.940 infrações**, totalizando multas que ultrapassam **R$ 1,81 bilhões**.
- O gráfico mensal das infrações permite identificar padrões sazonais importantes para estratégias preventivas e de fiscalização.

## 📈 Como Executar o Projeto

1. Clone este repositório:

```bash
git clone <URL do seu repositório>
```

2. Instale as dependências necessárias:

```bash
pip install pandas matplotlib
```

3. Abra o notebook `analise_ibama.ipynb` no Jupyter Notebook para executar a análise interativamente.

## 📝 Autor

- **Seu Nome**
- [Seu GitHub](https://github.com/seuperfil)
- [LinkedIn](https://linkedin.com/in/seuperfil)

---

Projeto desenvolvido como parte do MBA em Ciência de Dados (USP/ICMC).

