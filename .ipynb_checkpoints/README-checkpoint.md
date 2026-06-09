# Analisando o Engajamento do Instagram

## Sobre o Projeto

Este projeto tem como objetivo analisar o desempenho das publicações de uma empresa no Instagram e identificar quais características estão mais associadas ao engajamento dos usuários.

A análise foi realizada a partir do histórico de publicações da marca até 27 de março, utilizando métricas de curtidas, comentários e interações.

O foco do estudo é responder à seguinte pergunta:

> Quais fatores contribuem para aumentar o engajamento das publicações no Instagram?

---

## Objetivos da Análise

Durante o projeto foram investigadas características presentes nas postagens para entender seu impacto no engajamento:

- Presença de pessoas nas publicações
- Participação em campanhas
- Utilização de carrossel
- Tipo de conteúdo (Foto, Vídeo ou IGTV)
- Quantidade de curtidas
- Quantidade de comentários

A coluna de visualizações foi removida da análise conforme orientação do negócio.

---

## Tecnologias Utilizadas

- Python
- Pandas
- Jupyter Notebook

---

## Etapas do Projeto

### 1. Importação dos Dados

Carregamento da base de dados e inspeção inicial das informações.

### 2. Limpeza e Tratamento

Foram realizados procedimentos como:

- Remoção da coluna de visualizações
- Tratamento de valores nulos
- Verificação de tipos de dados
- Análise da consistência das informações

### 3. Análise Exploratória

Foram utilizadas estatísticas descritivas e agrupamentos para entender o comportamento dos dados.

Entre as análises realizadas:

- Distribuição das curtidas
- Distribuição dos comentários
- Postagens com maior engajamento
- Comparações entre formatos de conteúdo
- Comparações entre campanhas e não campanhas
- Comparações entre publicações com e sem pessoas

### 4. Agrupamentos com GroupBy

Foram realizados agrupamentos para identificar padrões de engajamento entre diferentes categorias de publicação.

Exemplos:

- Pessoas × Curtidas
- Campanhas × Curtidas
- Tipo × Pessoas
- Pessoas × Campanhas × Tipo

---

## Principais Insights

A análise encontrou alguns padrões relevantes:

### Publicações com pessoas geram mais engajamento

Posts que apresentam pessoas obtiveram médias significativamente maiores de curtidas e comentários quando comparados a publicações sem pessoas.

### Campanhas aumentam o alcance e a interação

Postagens relacionadas a campanhas apresentaram desempenho superior em relação às publicações comuns.

### Carrossel não apresentou vantagem significativa

Na base analisada, o uso de carrossel não demonstrou aumento relevante de engajamento.

### O desempenho dos vídeos depende do contexto

Inicialmente os vídeos apresentavam média inferior de engajamento.

Após segmentar os dados, foi possível observar que:

- Vídeos mostrando apenas produtos tiveram desempenho baixo.
- Vídeos com pessoas e relacionados a campanhas apresentaram resultados muito melhores.

Isso mostra que o formato do conteúdo, isoladamente, não explica o engajamento.

---

## Conclusão

Os resultados sugerem que o principal fator associado ao aumento de engajamento é a presença de pessoas nas publicações.

Além disso, campanhas de marketing demonstraram potencial para aumentar significativamente a interação dos usuários.

Por outro lado, características como o uso de carrossel tiveram impacto reduzido quando comparadas aos demais fatores analisados.

---

## Aprendizados

Neste projeto foram praticados conceitos importantes de análise de dados:

- Limpeza de dados
- Tratamento de valores nulos
- Estatística descritiva
- Filtragem de dados
- Agrupamentos com `groupby`
- Geração de insights de negócio
- Análise exploratória de dados (EDA)

---