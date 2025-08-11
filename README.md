# InsightSalaries
Este projeto é um dashboard interativo construído com o framework Streamlit e as bibliotecas Pandas e Plotly para analisar salários na área de dados. Ele permite explorar e visualizar dados salariais, oferecendo filtros para refinar a análise por ano, senioridade, tipo de contrato e tamanho da empresa.
## Estrutura do projeto
```
📁 InsightSalaries
├── app.py
├── dados-imersao-final.csv
├── requirements.txt
└── README.md
```
## Funcionalidades
1. Métricas Chave: 
    - Visualização rápida de métricas como salário médio e máximo, total de registros e o cargo mais frequente.

2. Gráficos Interativos:
    - Top 10 Cargos por Salário Médio: Um gráfico de barras que mostra os cargos com os maiores salários médios;
    - Distribuição de Salários: Um histograma que exibe a distribuição de salários anuais;
    - Proporção de Tipos de Trabalho: Um gráfico de pizza que detalha a proporção entre trabalho presencial, remoto e híbrido;
    - Salário por País: Um mapa-múndi que mostra o salário médio de Cientistas de Dados por país.

3. Filtros Dinâmicos: 
    - A barra lateral permite filtrar os dados por múltiplos critérios, como ano, senioridade, tipo de contrato e tamanho da empresa.

4. Dados Detalhados: 
    - Uma tabela com os dados brutos que se atualiza em tempo real conforme os filtros são aplicados.

## Tecnologias utilizadas
- Python
- Pandas
- Plotly
- Streamlit

## Como rodar o projeto
1. Clone o repositório
```bash
git clone https://github.com/IsabellaPassarelli/InsightSalaries.git
```
2. Navegue até a pasta principal do projeto
```bash
cd InsightSalaries
```
3. Instale as dependências
```bash
pip install -r requirements.txt
```
4. Rode o arquivo
```bash
streamlit run app.py
```