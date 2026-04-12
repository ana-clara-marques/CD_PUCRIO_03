# Análise de Dados Meteorológicos no Estado do Rio de Janeiro

Este projeto tem como objetivo analisar a relação entre altitude e variáveis de temperatura em estações meteorológicas do estado do Rio de Janeiro, utilizando dados do Instituto Nacional de Meteorologia (INMET).

## Objetivo

Investigar como a temperatura do ar varia em função da altitude das estações, bem como analisar a amplitude térmica diária e sua possível relação com a umidade do ar.

## Estrutura do Projeto

- `weather_rj.csv` → Dados meteorológicos (temperatura, umidade, vento, etc.)
- `stations_rj.csv` → Informações das estações (localização e altitude)
- `notebook.ipynb` → Notebook com análise completa (EDA, limpeza e conclusões)

## Metodologia

O projeto foi desenvolvido seguindo boas práticas de análise de dados:

1. Verificação inicial dos dados
   - Estrutura, tipos e valores nulos

2. Limpeza e preparação
   - Conversão de tipos (datas e variáveis numéricas)
   - Tratamento de valores inconsistentes
   - Integração dos datasets
   - Criação de variáveis derivadas (ex: amplitude térmica)

3. Análise exploratória (EDA)
   - Distribuições das variáveis
   - Boxplots por faixa de altitude
   - Relações entre variáveis (ex: temperatura × altitude)
   - Matriz de correlação

4. Avaliação das hipóteses
   - Validação com base em gráficos e estatísticas

## Principais Resultados

- Foi observada uma relação inversa entre altitude e temperatura, com temperaturas mais baixas em regiões mais elevadas.
- Não foi identificada uma relação clara entre altitude e amplitude térmica.
- Foi encontrada uma forte relação entre amplitude térmica e umidade, indicando maior variação de temperatura em condições de menor umidade.

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Observações

- Os dados foram tratados para garantir consistência e qualidade antes das análises.
- As variáveis foram mantidas em suas unidades originais para preservar a interpretação física dos resultados.
- Técnicas como normalização e padronização não foram aplicadas, pois o foco do trabalho é análise exploratória.

## Fonte dos Dados

- Instituto Nacional de Meteorologia (INMET)

## Como Executar

