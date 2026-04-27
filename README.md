# AnaliseDados-VarClimatica-X-Estoque-regiao-

Análise de Estoques Agrícolas e Variáveis Climáticas no Brasil

Este projeto tem como objetivo analisar a associação entre variáveis climáticas (temperatura média e precipitação) e os níveis de estoque de commodities agrícolas no Brasil, no período de 2018 a 2024.
A análise utiliza dados públicos de fontes governamentais e combina técnicas de tratamento de dados, análise estatística, SQL e visualização.

Objetivo
Qual a possível associação entre temperatura média, precipitação acumulada e níveis de estoque de commodities agrícolas nas regiões brasileiras?

⚠️ Importante:
A análise busca identificar associações, não estabelecer causalidade.

Estoque (IBGE / SIDRA)
Fonte: https://sidra.ibge.gov.br/tabela/254
Dados semestrais de estoque por produto e região

Clima (INMET)
Fonte: https://tempo.inmet.gov.br/
Dados mensais de: Temperatura média e precipitação acumulada convertidos para escala semestral

Tecnologias Utilizadas
Python (Pandas, NumPy)
DuckDB (SQL)
Matplotlib / Seaborn (visualização)
Power BI (dashboard)
Google Colab (execução)


Foram gerados gráficos como:
Série temporal (estoque ao longo do tempo)
Barras (estoque por região)
Dispersão (clima x estoque)
Histograma (distribuição)

Dashboard desenvolvido no Power BI.
Principais Resultados
Regiões Sul e Centro-Oeste apresentam maiores níveis de estoque
Região Norte apresenta menor volume
A correlação entre clima e estoque foi fraca, indicando baixa associação direta
