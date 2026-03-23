# Superstore Sales Analysis - Previsão de Rentabilidade
Este projeto consiste em uma análise detalhada dos dados de vendas de uma varejista (Superstore), com o objetivo de identificar padrões de prejuízo e desenvolver um modelo preditivo para apoiar a tomada de decisão comercial.

## 📌 Contexto do Desafio
O projeto foi desenvolvido como parte de um desafio técnico para a posição de Cientista de Dados. O foco principal foi transformar dados brutos de vendas em insights estratégicos, focando em:

- Organização e tratamento de dados.
- Criação de indicadores de desempenho (KPIs).
- Modelagem preditiva para antecipação de prejuízos.

## 📊 Principais Descobertas
- **Acurácia do Modelo:** O modelo de Random Forest atingiu 94% de acurácia na previsão de transações que resultariam em prejuízo.
- **Driver de Perda:** O Desconto foi identificado como a variável de maior impacto (85% de importância), revelando que políticas de desconto agressivas são a principal causa de margens negativas.
- **Eficiência Logística:** O tempo de entrega (Lead Time) não apresentou correlação direta com o prejuízo, indicando custos logísticos bem dimensionados.

## 🛠️ Tecnologias Utilizadas
- **Python 3.x**
- **Pandas & Numpy:** Manipulação e tratamento de dados.
- **Matplotlib & Seaborn:** Visualização de dados e gráficos estatísticos.
- **Scikit-Learn:** Machine Learning (Random Forest, Label Encoding, Métricas de Avaliação).

## 🚀 Como Rodar o Projeto

**1. Pré-requisitos**  
Certifique-se de ter o Python instalado em sua máquina. Recomenda-se o uso de um ambiente virtual.

**2. Instalação das Dependências**  
Clone o repositório ou baixe os arquivos e instale as bibliotecas necessárias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

**3. Base de Dados**  
O arquivo `superstore.csv` deve estar na mesma pasta que o notebook para que o carregamento funcione corretamente.

**4. Executando o Notebook**  
Para abrir o projeto, execute o comando abaixo no seu terminal:

```bash
jupyter notebook
```
No navegador que abrir, clique em `sales-notebook.ipynb` e execute as células em ordem (`Cell > Run All`).

## 📂 Estrutura do Repositório
- `sales-notebook.ipynb`: Jupyter Notebook com todo o código de tratamento, EDA e modelagem.
- `superstore.csv`: Base de dados original utilizada na análise.
- `Relatorio_Analise_Superstore.pdf`: Relatório explicativo com decisões técnicas e insights de negócio.
- `superstore_clean.csv`: Base de dados consolidada e tratada exportada após o processamento.

## 📈 Evoluções Futuras
Para elevar a maturidade analítica deste projeto, sugere-se:

- Inclusão de Custos Unitários para análise real de margem de contribuição.
- Integração de dados de Estoque e CRM para modelos de previsão de demanda e segmentação de clientes.