# K-Nearest Neighbors - KNN

Este projeto foi desenvolvido como parte do primeiro módulo do curso da Ada Tech e é uma implementação do algoritmo K-Nearest Neighbors (KNN), um modelo de machine learning supervisionado que pode ser utilizado tanto para classificação quanto para regressão.

## Colaboradores

        Giorggia Talynska Malheiros
        Helouise Dayane Dos Santos Silva
        Rafael Assis Esteves Dos Santos
        Patricia Adania De Oliveira
        Vanderlândio Zeferino Da Rocha
        
## Descrição
O K-Nearest Neighbors (KNN) é um algoritmo amplamente utilizado em machine learning devido à sua simplicidade, interpretabilidade e eficácia em muitos cenários. Ele é capaz de classificar ou estimar valores com base na proximidade entre os pontos de dados.

## Características
A complexidade do KNN varia dependendo da implementação, podendo ser O(n*m) ou O(log(n)).
É um algoritmo simples e facilmente interpretável.
É amplamente conhecido e estudado na área de machine learning.
Oferece um desempenho razoavelmente rápido, tornando-o adequado como benchmark.
Algoritmo
O algoritmo K-Nearest Neighbors consiste nos seguintes passos<br>

- Passo 1: Definir um valor para K, que representa o número de vizinhos mais próximos a serem considerados.
- Passo 2: Encontrar os K vizinhos mais próximos do ponto a ser classificado de acordo com uma função de distância, como a distância Euclidiana.
- Passo 3:
Se o problema é de Regressão, calcule a média dos valores-alvo dos K vizinhos.
Se o problema é de Classificação, calcule a moda das classes dos K vizinhos.
- Passo 4: Atribuir o valor/classe ao ponto de interesse com base no cálculo realizado no Passo 3.

## Definição do Problema
Dados <br>
O projeto utiliza dados relacionados ao cadastro de clientes de uma empresa de logística de entrega de alimentação. Os dados incluem informações sobre quanto cada cliente gastou em suas últimas 4 compras e uma classificação do Net Promoter Score (NPS) em três categorias: Promotor, Neutro e Detrator. O objetivo é utilizar o KNN para estimar a classificação de NPS para os clientes que ainda não foram classificados, com o intuito de melhorar o atendimento a esses novos clientes.

Os dados de entrada seguem o seguinte padrão:

- CPF: Número de identificação do cliente (INT).
- Classificação NPS: Classificação do cliente (STRING).
- Valor das últimas compras feitas pelo cliente: Tupla de valores (TUPLA).

## Regras do Projeto
É permitido criar funções para calcular valores ou realizar operações específicas.
Não é permitido o uso de módulos externos, como numpy e math.
Deve-se utilizar apenas objetos e fluxos de controle vistos até o momento no curso.
Este projeto demonstra a aplicação do algoritmo KNN na classificação de clientes com base em seu histórico de compras e NPS, oferecendo uma solução valiosa para a empresa de logística de entrega de alimentação.
