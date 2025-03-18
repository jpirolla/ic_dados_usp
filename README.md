
# Análise de Possíveis Correlações na Saúde Mental da Comunidade USP

Este repositório contém notebooks e arquivos relacionados à análise das correlações entre diferentes variáveis e a autopercepção da saúde mental dos estudantes da Universidade de São Paulo (USP). O estudo foi conduzido com base nos dados coletados pelo Questionário PRIP (QPRIP), aplicado em 2022, e em informações complementares do auxílio PAPFE 2023/2024 e do Portal de Transparência da USP.

**Importante**: Este projeto foi desenvolvido com a colaboração de todo o grupo de pesquisa liderado pela Profa. Cibele, tanto nas análises quanto na elaboração dos materiais. Os notebooks apresentados, em particular, foram desenvolvidos por mim, com a coautoria de Pedro Augusto Martins Gagini.

## Motivação

A crescente preocupação com a saúde mental dos estudantes universitários levou a USP a criar a Pró-Reitoria de Inclusão e Pertencimento (PRIP), responsável por desenvolver políticas institucionais que garantam um ambiente mais inclusivo e acolhedor. Com base nos dados do QPRIP, este projeto busca identificar possíveis correlações entre a saúde mental e fatores como gênero, condições socioeconômicas e experiências acadêmicas.

## Estrutura do Repositório

O diretório contém os seguintes notebooks:

- `exploracao_possiveis_correlacoes.ipynb`: Análise exploratória inicial sobre possíveis correlações entre variáveis relacionadas à saúde mental.
- `analise_genero_icmc.ipynb`: Estudo sobre a relação entre gênero e a progressão na carreira acadêmica no cenário dos departamentos do ICMC.
- `analise_semestral_grad.ipynb`: Análise semestral dos dados de desempenho de alunos bolsistas.
- `analises_sociodemograficas.ipynb`: Exploração de características sociodemográficas dos estudantes.
- `associacoes_genero_experienciasAcademicas.ipynb`: Avaliação da influência do gênero nas experiências acadêmicas dos estudantes.
- `associacoes_saudeMental_expIndividuais.ipynb`: Análise da relação entre saúde mental e experiências individuais.
- `associacoes_saude_mental.ipynb`: Estudo aprofundado das associações entre fatores diversos e a saúde mental dos estudantes.

## Metodologia

A análise se baseia em técnicas estatísticas e ferramentas de visualização, incluindo:

- **Tabelas Cruzadas:** Organização tabular para comparar variáveis.
- **Gráficos de Mosaico:** Visualização de associações entre variáveis categóricas.
- **Gráficos de Barras:** Comparação de percentuais de respostas.
- **Testes de Hipótese:** Uso do teste qui-quadrado (método `chi2_contingency` da biblioteca `scipy.stats`) para avaliar a significância das associações.
- **Resíduo de Pearson:** Análise da disparidade entre frequências observadas e esperadas, permitindo a detecção de padrões nos dados.

## Ferramentas Utilizadas

- **Linguagens:** Python e R
- **Bibliotecas principais:** `scipy.stats`, `numpy`, `pandas`, `matplotlib`, `plot-likert`

## Objetivo

Nosso objetivo é aprimorar a compreensão do impacto da USP na saúde mental dos estudantes, identificando correlações estatisticamente significativas que possam fundamentar políticas institucionais mais eficazes.

 
## Referências
- RUSSO, 2023. Relatório Final do Questionário PRIP.
- HURTADO et al., 2008. Campus Climate Surveys.
- FERREIRA; PATINO, 2015. Métodos Estatísticos em Saúde.
- FENG; LI; SADEGHPOUR, 2020. Residuals in Contingency Tables.


---
