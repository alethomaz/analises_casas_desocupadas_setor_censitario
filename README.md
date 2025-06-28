# 🏠 Análise de Domicílios Desocupados no Brasil

Este repositório contém uma análise exploratória e visual por Setor Censitário dos **domicílios desocupados** no Brasil, com foco nos dados do Censo 2022 do IBGE. A análise visa identificar padrões regionais, proporções de desocupação e potenciais implicações sociais e urbanísticas.

## 📊 Sobre o Projeto

Com base nos dados divulgados pelo IBGE, este projeto busca responder perguntas como:

- Qual o número e percentual de domicílios desocupados por estado?
- Existe relação entre o número de domicílios desocupados e a população?

## 🗂 Estrutura

- `analise_domicilios_desocupados.ipynb`: notebook principal com toda a análise passo a passo
- `data/`: pasta sugerida para armazenar os dados de entrada (não inclusa por padrão)

## 🚀 Como rodar

- Escolha o estado e a cidade que você deseja analisar no Brasil, editando o trecho abaixo no início do notebook:

```python
# Estado alvo
sigla_uf = 'SC'

# Escolha a cidade
cidade_alvo = 'Florianópolis'
