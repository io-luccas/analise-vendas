# Análise de Vendas

## Sobre o projeto

Projeto de análise exploratória de dados desenvolvido em Python com o objetivo de analisar o desempenho comercial de uma empresa a partir de uma base de vendas.

A análise busca responder perguntas relacionadas a faturamento, produtos, regiões e clientes, transformando os dados em informações úteis para apoiar a tomada de decisões.

## Objetivos da análise

O projeto busca responder às seguintes perguntas:

* Quanto a empresa faturou?
* Qual produto apresentou o maior volume de vendas?
* Qual região gerou o maior faturamento?
* Quem são os principais clientes?

## Análises realizadas

### Faturamento da empresa

Identificação do faturamento total da empresa a partir dos registros de vendas.

**Resultado:** `df_faturamento_empresa`

### Produto mais vendido

Análise dos produtos para identificar aquele com maior lucro.

**Resultado:** `df_produto_mais_vendido`

### Região com maior faturamento

Comparação do faturamento entre as diferentes regiões de atuação da empresa.

**Resultado:** `df_regiao_maior_fat`

### Principais clientes

Identificação dos clientes com maior quantidade de pedidos realizados.

**Resultado:** `df_principais_clientes`

## Tecnologias utilizadas

* Python
* Pandas
* Jupyter Notebook
* Numpy
* VS Code

## Estrutura do projeto

```text
analise-vendas/
│
├── vendas_tech.csv
├── gerentes_lojas.xlsx
│
├── app.ipynb
│
└── README.md
```

## Principais etapas

1. Importação das bibliotecas
2. Carregamento da base de dados
3. Análise e tratamento dos dados
4. Análise exploratória
5. Cálculo dos indicadores
6. Identificação dos principais resultados

## Conclusão

A análise permite obter uma visão geral do desempenho comercial da empresa, destacando faturamento, produtos, regiões e clientes com maior relevância para o negócio.

O projeto demonstra a aplicação de Python e Pandas na exploração e análise de dados comerciais.
