📊 Almanaque Financeiro da Série A – 2024
Uma aplicação interativa construída com Streamlit que apresenta análises financeiras e comparativas dos clubes da Série A do Campeonato Brasileiro. A ferramenta permite explorar receitas, despesas, resultados operacionais e índices de transparência com foco em dados auditados de 2024 e comparações históricas com anos anteriores.

🚀 Funcionalidades
Análise Individual - 2024: Visualize a demonstração de resultado de um clube específico através de um diagrama de Sankey e gráficos radar comparativos com a média da liga e com o desempenho de 2023.

Análise Individual - Histórica: Explore a evolução financeira dos clubes ao longo do tempo (em desenvolvimento).

Análise Comparativa Simples: Compare clubes em diferentes indicadores (em desenvolvimento).

Análise Conjunta: Veja gráficos e relações entre variáveis esportivas, financeiras e de gestão (em desenvolvimento).

Compare 2 clubes!: Confronte dois clubes lado a lado usando gráficos radar com múltiplas dimensões de desempenho.

Índice de Transparência: Compare o nível de transparência contábil entre os clubes da Série A.

📁 Estrutura de Arquivos
Financials.py: Script principal que define a interface da aplicação e lógica das visualizações.

resultado.csv, índices.csv, índices_2023.csv, etc.: Bases de dados utilizadas pela aplicação (devem estar no mesmo diretório do app).

Imagens dos clubes hospedadas externamente via GitHub raw links.

🖼️ Tecnologias Utilizadas
Streamlit – Para criação da interface interativa.

Plotly – Para visualização dos fluxos financeiros com Sankey charts.

Radar Chart (soccerplots) – Para comparar indicadores visuais em múltiplas dimensões.

Pandas/Numpy – Para manipulação de dados.

Matplotlib/PIL – Para imagens e gráficos complementares.

📦 Como Executar Localmente
Clone este repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/Financials-2025.git
cd Financials-2025
Instale os pacotes necessários (recomenda-se uso de um ambiente virtual):

bash
Copiar
Editar
pip install -r requirements.txt
Execute a aplicação:

bash
Copiar
Editar
streamlit run Financials.py
Acesse no navegador: http://localhost:8501

📌 Observações
Os dados são derivados exclusivamente de demonstrações financeiras auditadas.

O foco da aplicação é educacional, analítico e comparativo, sem fins lucrativos.

As imagens dos clubes estão armazenadas via links GitHub raw e são utilizadas apenas para fins ilustrativos.

✍️ Autor
José Américo Pereira Antunes
Contato: LinkedIn | GitHub



## English
# Almanaque Financeiro da Série A

## Overview

The "Almanaque Financeiro da Série A" (Financial Almanac of Serie A) is a Streamlit application designed to provide comprehensive financial analysis of Brazilian Serie A football clubs. This dashboard offers users multiple ways to visualize, compare, and understand the financial status and performance of clubs across various metrics.

## Features

The application offers six main analysis modules:

1. **Análise Individual - 2024**: Analyze individual clubs' financial data for the 2024 season
2. **Análise Individual - Histórica**: View historical financial trends for individual clubs
3. **Análise Comparativa Simples**: Perform simple comparisons between multiple clubs on specific metrics
4. **Análise Conjunta**: Access comprehensive analysis across all clubs simultaneously
5. **Compare 2 clubes!**: Direct side-by-side comparison of two selected clubs
6. **Índice de Transparência**: Review transparency metrics for financial reporting across clubs

## Data Categories

The application analyzes financial and performance data across several categories:

### Financial Results
- Revenue streams (broadcasting rights, sponsorships, ticket sales, etc.)
- Operational expenses
- Player transfers
- Net financial results

### Cash Flow
- Cash generation
- Operational expenses
- Investments
- Financing activities

### Sport Performance Metrics
- League points
- Average attendance
- Season ticket holders
- Squad value
- Youth development expenses

### Management Indicators
- Player wages to revenue ratio
- Debt to revenue ratio
- Revenue per fan
- Administrative expenses

## Installation

1. Clone this repository
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Run the Streamlit app:
```
streamlit run app.py
```

## Requirements

- Python 3.7+
- Streamlit
- Pandas
- Matplotlib/Plotly (for visualizations)
- Other dependencies listed in requirements.txt

## Usage

Navigate through the application by selecting one of the six main options from the home screen. Each analysis module provides interactive visualizations and data tables for exploring the financial data of Brazilian Serie A clubs.

## Data Sources

The financial data is compiled from official financial statements, annual reports, and public disclosures from the clubs. Sport performance metrics are sourced from official league statistics.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Specify your license here]

## Acknowledgments

- Brazilian Serie A clubs for their financial transparency
- Contributors and data providers

---

Developed with ❤️ for Brazilian football fans and financial analysts.
