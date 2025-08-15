<div align="center">

![Wallpaper_ONE_8_-_Blackk](https://github.com/user-attachments/assets/61c95a8f-86db-4f3e-9d53-4a412be43c2a)

</div>

<h1 align="center"> Análise de Evasão de Clientes na TelecomX </h1>

Esse é o terceiro projeto da ONE onde tenho de fazer uma análise de dados da empresa Telecom X, gerar Gráficos, e apontar possíveis motivos de evasão de clientes com a empresa. Apresentando também uma ideia de possíveis soluções.

<img width="1295" height="673" alt="image" src="https://github.com/user-attachments/assets/b06fbe25-82a4-48bb-93a9-061f3c5e028b" />


## Descrição do Projeto 📄

Este projeto apresenta uma análise exploratória aprofundada dos dados de
clientes da TelecomX, com o objetivo principal de identificar os fatores
mais relevantes que contribuem para a evasão de clientes.

## Fonte de Dados 📊

Os dados utilizados nesta análise foram obtidos a partir de um arquivo
no formato JSON fornecido especificamente para este estudo.

[Conjunto de Dados Utilizado](https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/refs/heads/main/TelecomX_Data.json)


## Etapas da Análise 🔍

1.  **Extração e Carregamento**
    -   Carregamento dos dados a partir da fonte fornecida e conversão
        para um DataFrame utilizando a biblioteca Pandas.
2.  **Exploração Inicial**
    -   Análise das informações básicas do conjunto de dados, incluindo
        tipos de variáveis e verificação de valores ausentes.
3.  **Transformação e Limpeza**
    -   Renomeação das colunas para o idioma português.
    -   Conversão de valores categóricos (como "Sim", "Não", "Sem serviço de telefone", etc) para valores numéricos (1 e 0).
    -   Tratamento de inconsistências e valores ausentes nas colunas
        "evasão" e "gasto_total".
    -   Garantia de consistência entre a presença de serviços de
        telefone/internet e os serviços adicionais.
4.  **Análise Exploratória de Dados (AED)**
    -   Avaliação da distribuição geral da variável alvo (evasão).
    -   Estudo da relação entre evasão e variáveis categóricas (gênero,
        parceiro, dependentes, faixa etária, tipo de contrato, método de
        pagamento, serviço de internet e serviços adicionais).
    -   Análise da relação entre evasão e variáveis numéricas (meses de
        contrato, valor mensal, gasto total), incluindo agrupamento por
        trimestres de meses de contrato.
    -   Cálculo da matriz de correlação entre variáveis selecionadas,
        considerando apenas clientes com serviço de internet.
5.  **Visualização de Dados**
    -   Criação de gráficos (histogramas, boxplots, gráficos de
        contagem) para melhor compreensão da distribuição das variáveis
        e de sua relação com a evasão.

## Principais Descobertas 💡

-   A taxa geral de evasão é de aproximadamente **26,6%**.
-   Clientes com contratos do tipo **"mês a mês"** apresentam taxas de
    evasão significativamente maiores.
-   O método de pagamento **"cheque eletrônico"** está fortemente
    associado à evasão.
-   Clientes que utilizam internet via **fibra óptica** apresentam maior
    taxa de evasão.
-   A evasão é mais acentuada nos primeiros meses de contrato, reduzindo
    à medida que o cliente permanece mais tempo.
-   Clientes com valores mensais mais elevados tendem a apresentar maior
    taxa de evasão.
-   Certos serviços adicionais de internet, como backup, proteção de
    dispositivo, streaming de TV e filmes, possuem relação com a evasão.

## Recomendações 📌

-   Implementar programas de integração e suporte aprimorado para novos
    clientes nos primeiros meses de contrato.
-   Oferecer incentivos para adesão a contratos de maior duração (um ou
    dois anos).
-   Investigar possíveis problemas relacionados ao método de pagamento
    **"cheque eletrônico"**.
-   Avaliar a qualidade da experiência de clientes que utilizam internet
    via **fibra óptica** para identificar possíveis pontos de
    insatisfação.
-   Criar estratégias de retenção voltadas para clientes com valores
    mensais mais elevados.


## 

<div align="center">
  
![HTML](https://img.shields.io/badge/Python-red)
<p align="center">
<img alt="Static Badge" src="https://img.shields.io/badge/STATUS-FINALIZADO-Green">
</p>
