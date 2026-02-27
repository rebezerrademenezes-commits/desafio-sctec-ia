# Análise Exploratória de Dados - Empreendedorismo em Santa Catarina

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.2-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-orange)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab)

Este projeto foi desenvolvido como parte do **desafio prático** do processo seletivo para a trilha **IA para DEVs** do Programa SCTEC. O objetivo é realizar uma análise exploratória de dados (AED) sobre o cenário de empreendedorismo no estado de Santa Catarina, utilizando um dataset simulado com base em estatísticas públicas.

## 📊 Dataset

Os dados foram **simulados** a partir de informações do IBGE, SEBRAE e dados abertos do governo de Santa Catarina. O arquivo `empreendedorismo_sc.csv` contém 200 registros com as seguintes colunas:

- `municipio`: nome do município catarinense (20 municípios)
- `setor`: setor econômico (Comércio, Serviços, Indústria, etc.)
- `num_empresas`: número de empresas no setor/município
- `faturamento_medio_mil`: faturamento médio das empresas (em R$ mil)
- `empregados`: total de empregados no setor/município
- `ano_fundacao_medio`: ano médio de fundação das empresas
- `populacao`: população do município (estimada)

> **Nota:** Por se tratar de dados simulados, os valores não representam a realidade exata, mas são coerentes com as distribuições observadas nas fontes oficiais.

## 🛠️ Tecnologias utilizadas

- **Python 3.12** – linguagem principal
- **Google Colab** – ambiente de desenvolvimento
- **Pandas** – manipulação e análise de dados
- **NumPy** – operações numéricas
- **Matplotlib** e **Seaborn** – visualização de dados
- **Warnings** – supressão de avisos (opcional)

## 📁 Estrutura do repositório

