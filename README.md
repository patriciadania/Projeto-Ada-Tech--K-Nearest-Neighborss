# K-Nearest Neighbors - KNN

Feito em parceria com:

        Giorggia Talynska Malheiros
        Helouise Dayane Dos Santos Silva
        Rafael Assis Esteves Dos Santos
        Patricia Adania De Oliveira
        Vanderlândio Zeferino Da Rocha

Modelo supervisionado de machine learning que pode ser utilizado tanto para classificação, isto é, rotular os dados; quanto para regressão, ou seja, aproximar valores.

## Características

- Dependendo da implementação pode ser $O(n*m)$ ou $O(log(n))$
- Simples
- Interpretável
- Largamente conhecido e estudado
- Razoavelmente rápido

Por conta disso é um ótimo benchmark

## Algoritmo

- Passo 1:
    Definir um valor para K
- Passo 2:
    Definir os K vizinhos mais próximos do ponto a ser classificado de acordo com uma função de distância.
- Passo 3:
    - Se for um problema de **Regressão**:
        Calcular a **média** de todos os vizinhos.
    - Se for um problema de **Classificação**:
        Calcular a **moda** de todos os vizinhos.
- Passo 4:
    Atribuir o valor/classe ao ponto de interesse conforme cálculo do Passo 3.

## Definição do Problema

### Dados
Os dados abaixo são referentes ao cadastro de clientes de uma empresa de logística de entrega de alimentação. Nesse cadastro, há quanto foi gasto pelo cliente nas últimas 4 compras e uma classificação de NPS: **Promotor**, **Neutro**, **Detrator**. O nosso intuito é, a partir das últimas compras de alguns clientes que já deu uma nota NPS, estimar esse calssificação para aqueles que ainda não estão classificado, afim de melhorar o atendimento desses novos clientes.

Os dados abaixo seguem o seguinte padrão:

[**CPF**: INT, **Classificação NPS**: STRING, **Valor das últimas compras feitas pelo cliente**: TUPLA


[NPS](https://assets-global.website-files.com/633ec8b202a7496fb9c9dda9/64020daae50d701ac16ebd7a_Net%20Promoter%20Score.jpeg)

### Regras
- Se você precisar de uma função para computar algo crie ela
- Não é permitido usar nenhum módulo externo como numpy e math
- Use apenas os objetos e fluxos visto até o momento no curso
