# Avaliação da Ferramenta de Análise Documental Automatizada

## Sobre o projeto

Este repositório contém os códigos utilizados para a avaliação de uma ferramenta de análise documental automatizada aplicada ao processo de licenciamento sanitário.

A ferramenta foi desenvolvida em Python com o objetivo de apoiar a identificação, extração e conferência de informações presentes nos documentos que compõem os processos de licenciamento sanitário.

## Avaliação da ferramenta

A avaliação foi realizada a partir de duas dimensões principais:

### 1. Identificação documental

Avaliação da capacidade da ferramenta de identificar corretamente a presença ou ausência dos documentos nos processos.

Os resultados foram classificados como:

- **Presente**
- **Ausente**

O desempenho foi avaliado por meio de matriz de confusão e das seguintes métricas:

- Acurácia
- Sensibilidade
- Especificidade
- Precisão
- F1-score

### 2. Conferência documental

Avaliação da capacidade da ferramenta de extrair e conferir corretamente as informações necessárias à análise documental.

Foram avaliados parâmetros relacionados a:

- Dados extraídos dos documentos;
- Cadastro Nacional da Pessoa Jurídica (CNPJ);
- Classificação Nacional de Atividades Econômicas (CNAE);
- Enquadramento de risco;
- Checklist documental.

O desempenho foi mensurado pelo percentual de acerto, considerando a correspondência entre os resultados apresentados pela ferramenta e os valores estabelecidos como referência.

## Tecnologias utilizadas

- Python
- Jupyter Notebook
- Pandas
- Google Sheets

## Estrutura do repositório

Os códigos disponíveis neste repositório correspondem às etapas de processamento e avaliação dos resultados da ferramenta.

## Objetivo

O projeto busca contribuir para a avaliação da aplicabilidade de soluções automatizadas na análise documental do licenciamento sanitário, identificando seu desempenho, limitações e possibilidades de aprimoramento.
