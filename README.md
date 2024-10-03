# Dados globais de políticas de aborto

Este projeto analisa dados globais acerca de políticas de aborto, utilizando o banco de dados desenvolvido pela *Human Reproduction Programme* (HRP) da *World Health Organization* (WHO) (Oganização Mundial da Saúde (OMS)).

```python
Fonte:
**Human Reproduction Programme**
https://abortion-policies.srhr.org/
```

## Introdução

O *Global Abortion Policies Database* (GAPD) (Banco de Dados de Políticas Globais de Aborto) foi criado para fortalecer os esforços globais para eliminar o aborto inseguro, produzindo um banco de dados interativo de acesso aberto e um repositório de leis, políticas e padrões e diretrizes nacionais atuais sobre o aborto. Ele tem como objetivo ajudar os estados a identificar e eliminar as barreiras que as mulheres encontram no acesso a serviços de aborto seguro. Ele também tem como objetivo aumentar a transparência das leis e políticas de aborto e garantir a responsabilização pela proteção da saúde das mulheres e seus direitos humanos.

## Objetivo

O objetivo é entender as barreiras enfrentadas por mulheres na obtenção de um aborto seguro em diferentes localidades. \
O GAPD é um banco de dados extenso e bem completo, com, também, acesso a documentos que embasam as respostas do questionário utilizado para o levantamento. Ao todo são 30 questões, contudo nesta análise focaremos em apenas 3 (entre parênteses a correspondência no questionário original):

* Aborto permitido a partir de pedido da mulher (1)
* Fundamentos legais pelos quais o aborto induzido é atualmente permitido (1)
* Restrições adicionais aplicáveis em caso de aborto induzido legal, em alguns ou todos os motivos (2)
* Quem pode ser acusado criminalmente por aborto ilegal (8)

## Instalação e Pré-Requisitos

Para executar o código, você precisará das seguintes bibliotecas Python:

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

## Uso

* Clone este repositório para sua máquina local.
* Navegue até o diretório do projeto.
* Abra o arquivo `ETL_Abortion_Dataset.ipynb` em um ambiente Jupyter Notebook.
* Execute as células de código sequencialmente para carregar e analisar os dados.

## Estrutura dos Dados

Os dados são carregados a partir de um arquivo CSV:

```python
df_backup = pd.read_csv("Abortion_Dataset.csv")
```

## Análise Inicial

A análise inicial inclui a verificação da estrutura dos dados, limpeza prévia do arquivo csv, verificação da integridade dos dados, presença de valores nulos e duplicatas e limpeza de dados. \
O dataframe com os dados tratados foram salvos em novo arquivo csv "Abortion_Dataset_clean.csv".


### Lidando com Erros

Para correções de erros apontadas pelos códigos e aperfeiçoamento da execução foram feitas consultas às IAs Perplexity, GhatGPT, Copilot e Gemini.


## Contribuições

Contribuições e sugestões são bem-vindas!