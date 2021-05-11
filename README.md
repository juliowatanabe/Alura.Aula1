# Alura - Imersão Dados

## Introdução

Este projeto faz parte das aulas "Imersão Dados" promovido pela [Alura](https://www.alura.com.br/?gclid=CjwKCAjw1uiEBhBzEiwAO9B_HZ7Uzf_oRIP1ScFP2EBn7tjs1rN_Es7DmiZMLAC5MK53VWl0YS0P7hoC2_EQAvD_BwE).
As aulas de Análise de Dados e Machine Learning foram realizadas com base em um projeto/competição do MIT onde foi apresentado um desafio com o objetivo de avançar o desenvolvimento de medicamentos por meio de melhorias nos algoritmos de previsão do MoA.

Qual é o mecanismo de ação (MoA) de uma droga? E por que isto é importante?

No passado, os cientistas derivavam drogas de produtos naturais ou eram inspirados por remédios tradicionais. Drogas muito comuns, como o paracetamol, conhecido nos Estados Unidos como acetaminofeno, foram colocadas em uso clínico décadas antes que os mecanismos biológicos que impulsionam suas atividades farmacológicas fossem compreendidos. Hoje, com o advento de tecnologias mais poderosas, a descoberta de medicamentos mudou das abordagens inesperadas do passado para um modelo mais direcionado baseado na compreensão do mecanismo biológico subjacente de uma doença. Nessa nova estrutura, os cientistas buscam identificar um alvo proteico associado a uma doença e desenvolver uma molécula que possa modular essa proteína alvo. Como uma abreviação para descrever a atividade biológica de uma determinada molécula, os cientistas atribuem um rótulo conhecido como mecanismo de ação ou MoA.

Como determinamos os MoAs de um novo medicamento?

Uma abordagem é tratar uma amostra de células humanas com a droga e, em seguida, analisar as respostas celulares com algoritmos que buscam semelhança com padrões conhecidos em grandes bancos de dados genômicos, como bibliotecas de expressão gênica ou padrões de viabilidade celular de drogas com MoAs conhecidos.

Neste projeto temos um conjunto de dados exclusivo que combina a expressão gênica e os dados de viabilidade celular. Os dados são baseados em uma nova tecnologia que mede simultaneamente (nas mesmas amostras) as respostas das células humanas aos medicamentos em um pool de 100 tipos de células diferentes (resolvendo assim o problema de identificação ex-ante, quais tipos de células são mais adequados para um determinado medicamento). Além disso, temos acesso às anotações do MoA para mais de 5.000 medicamentos neste conjunto de dados.

O conjunto de dados foi dividido em subconjuntos de teste e treinamento. Portanto, a tarefa é usar o conjunto de dados de treinamento para desenvolver um algoritmo que rotula automaticamente cada caso no conjunto de teste como uma ou mais classes MoA. Observe que, uma vez que os medicamentos podem ter várias anotações MoA, a tarefa é formalmente um problema de classificação com vários rótulos.

Como avaliar a precisão de uma solução?

Com base nas anotações de MoA, a precisão das soluções será avaliada comparando o resultado predicto com o resultado real.

## Dados

Os dados utilizados neste projeto se encontram no [Kaggle](https://www.kaggle.com/c/lish-moa).

## Objetivo

Aprender a manipular os dados, efetuar as análises estatísticas, criar o modelo de pedição e análise dos resultados.

## Procedimento

Todo o procedimento será feito em Python utilizando se o Jupyter Notebook.
