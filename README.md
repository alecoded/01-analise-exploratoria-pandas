**Análise Exploratória de Vendas - E-commerce Olist (Pandas) **

Este projeto faz parte de um portfólio de análise de dados e foca na extração de insights e manipulação de grandes volumes de dados utilizando a biblioteca Pandas. O objetivo principal é consolidar diferentes fontes de dados para entender o desempenho financeiro e o comportamento de vendas da Olist.

**Objetivos da Análise**
Consolidar múltiplos datasets (pedidos, pagamentos, itens e produtos) em uma única base mestra para análise.

Calcular métricas financeiras chave, como o faturamento total bruto (R$ 16.008.872,12).

Analisar a distribuição da receita por status do pedido para identificar o volume de entregas concluídas.

Identificar tendências temporais de faturamento mensal para detectar períodos de pico e sazonalidade.

Mapear as categorias de produtos que mais contribuem para a receita da plataforma.

**Tecnologias e Bibliotecas**
Python 3.x

Pandas: Limpeza, transformação e agregação de dados.

Matplotlib & Seaborn: Criação de visualizações gráficas (gráficos de barras e linhas).

Zipfile: Extração automatizada do dataset.

**Etapas do Projeto**
Extração de Dados: Automatização da extração dos arquivos .csv a partir de um arquivo comprimido (archive.zip).

Limpeza e Consolidação: Junção (merge) das tabelas de pedidos e pagamentos utilizando o order_id como chave, seguida pela integração com itens e produtos para criar uma base rica em detalhes.

**Análise de Receita:**

Cálculo da receita total.

Agrupamento por status (ex: delivered, canceled, shipped) com visualização em gráfico de barras horizontais.

**Série Temporal: **Conversão de strings para formato datetime e criação de colunas de período (Ano-Mês) para plotar a evolução mensal das vendas.

**Análise de Produtos:** Ranking das categorias campeãs em faturamento, identificando setores como "cama_mesa_banho" e "beleza_saude" no topo da lista.

** Principais Insights Obtidos**
**Dominância de Entregas:** A esmagadora maioria da receita provém de pedidos com status "entregue", garantindo a saúde operacional do faturamento.

**Pico Histórico:** Novembro de 2017 foi identificado como o mês de maior faturamento, com mais de R$ 1,58 milhão em vendas.

**Concentração de Receita**: O Top 5 de categorias de produtos representa uma fatia significativa do faturamento total, com destaque para artigos de uso doméstico e bem-estar.

**Nota:** Este notebook foca na abordagem programática e estatística com Pandas. Para uma análise focada em consultas estruturadas de banco de dados, consulte o arquivo 02-analise-avancada-sqlite.ipynb.
