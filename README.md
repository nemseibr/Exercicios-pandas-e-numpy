# Exercícios-pandas-e-numpy

Este notebook explorou diversas funcionalidades essenciais das bibliotecas pandas e NumPy para manipulação e análise de dados, desde a criação de DataFrames até a extração de insights mais complexos. Cobrimos os seguintes tópicos e operações:

Criação e Inspeção de DataFrames: Você aprendeu a criar DataFrames (pd.DataFrame()) e a inspecionar sua estrutura usando shape (número de linhas e colunas), columns (nomes das colunas), dtypes (tipos de dados das colunas), info() (visão geral) e describe() (estatísticas descritivas).

Seleção de Dados: Demonstrou como selecionar colunas específicas (df['coluna']) e como acessar linhas por posição numérica (iloc).

Filtragem de Dados: Explorou a filtragem de linhas com base em condições simples (df[df['valor'] > 200]) e múltiplas condições (& para 'e', | para 'ou'), e também o uso do isin() para filtrar por múltiplos valores.

Análise Exploratória Básica: Calculou estatísticas como média (.mean()), máximo (.max()) e mediana (.median()) de colunas numéricas, e identificou valores ausentes (.isnull().sum(), .isnull().any()).

Ordenação e Contagem: Ordenou DataFrames por valores de colunas (.sort_values()) e contou a frequência de ocorrência de valores únicos (.value_counts()), além de identificar o valor mais frequente (.idxmax()).

Agregação de Dados (groupby() e agg()): Realizou agregações complexas, como calcular o valor total, valor médio e quantidade de pedidos por grupos (e.g., por UF), utilizando groupby() combinado com agg().

Combinação de DataFrames (merge() e concat()): Aprendeu a combinar tabelas usando merge() (para unir dados com base em uma coluna comum, como IDs de cliente) e concat() (para empilhar DataFrames, como vendas de diferentes meses).

Criação de Novas Colunas: Adicionou colunas calculadas com base em dados existentes (e.g., valor_com_frete e entrega_rapida).

Tabelas Dinâmicas (pivot_table()): Criou tabelas dinâmicas para resumir e reorganizar dados, facilitando a visualização de faturamento por diferentes dimensões (UF e mês).

Operações com NumPy: Aplicou funções NumPy para calcular estatísticas (mínimo, máximo, média, desvio padrão) de colunas de forma eficiente.

Em resumo, o notebook forneceu uma base sólida para a manipulação e análise de dados utilizando pandas e NumPy, cobrindo desde operações básicas até técnicas mais avançadas para extrair informações valiosas de conjuntos de dados. O desafio final integrou muitos desses conceitos em uma análise de negócios completa.
