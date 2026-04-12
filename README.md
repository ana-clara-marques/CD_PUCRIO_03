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

O notebook pode ser executado diretamente no Google Colab.

1. Acesse o notebook pelo GitHub:
   https://github.com/ana-clara-marques/CD_PUCRIO_03

2. Abra o arquivo `.ipynb`.

3. Clique em **"Open in Colab"** ou copie o link do notebook e abra no Colab manualmente:
   https://colab.research.google.com/

4. Execute as células em ordem.

Os dados são carregados diretamente a partir dos arquivos CSV disponíveis neste repositório, não sendo necessário realizar download manual.

