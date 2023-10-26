# PDA - DADOS BDMEP - Utilizando Algoritmo de Arvore Aleatória

## * Dados retirados do site -> https://bdmep.inmet.gov.br/
### requisição feita no site e dados recebidos em formato csv codificação "UTF-8", Florianópolis - 31-01-2003 até 30-09-2023 e Itajaí 30-06-2010 até 30-09-2023, os dados são enviados por e-mail e a consulta é apagada em 48H, data da consulta 11-10-2023, os filtros utilizados foram:
 * Valores separados por virgulas
 * Dados Mensais
 * Tipo de Estação Convencionais
 * Abrangência Regional - Sul
 * Data de Inicio 01-01-1980, Data Fim 01-09-2023
 * Precipitação Total/Mensal, Pressão Atmosférica/Media Mensal, Temperatura Media Compensada/Mensal,

Identificadores de estação A806 - Florianópolis, A868 - Itajai
Ambos os arquivos apresentam muita incidência de valores nullos, incorretos ou misturados.

# Dados_BDMEP

Este repositório contém um Jupyter Notebook que realiza a análise e visualização dos dados do BDMEP (Banco de Dados Meteorológicos do INMET).

## Resumo do Notebook

O Jupyter Notebook "Dados_BDMEP.ipynb" é uma ferramenta para análise e visualização de dados meteorológicos do BDMEP. Aqui estão alguns destaques do que o notebook faz:

1. **Coleta de Dados**: O notebook coleta dados meteorológicos do BDMEP. Os dados coletados incluem informações sobre temperatura, pressão atmosférica, umidade relativa, precipitação, entre outros.

2. **Análise de Dados**: Após a coleta dos dados, o notebook realiza uma série de análises para entender melhor os padrões e tendências nos dados meteorológicos.

3. **Visualização de Dados**: O notebook utiliza várias técnicas de visualização de dados para representar os resultados da análise de maneira intuitiva e fácil de entender.

Por favor, consulte o notebook "Dados_BDMEP.ipynb" para obter detalhes completos sobre a análise e visualização dos dados.

## Treinamento do Modelo de Árvore Aleatória

O modelo de Árvore Aleatória foi treinado usando a biblioteca `sklearn.ensemble.RandomForestClassifier` do Python. Aqui estão os passos que foram seguidos:

1. **Preparação dos Dados**: Os dados foram primeiro preparados dividindo-os em conjuntos de treinamento e teste. As variáveis de entrada e saída foram separadas.

2. **Criação do Modelo**: Um objeto do modelo RandomForestClassifier foi criado com os parâmetros desejados. Por exemplo, o número de árvores na floresta aleatória (n_estimators) foi definido como 100.

3. **Treinamento do Modelo**: O modelo foi então treinado usando o método `fit` no conjunto de treinamento.

4. **Avaliação do Modelo**: O desempenho do modelo foi avaliado no conjunto de teste usando várias métricas, como a acurácia.

5. **Ajuste dos Parâmetros**: Os parâmetros do modelo foram ajustados conforme necessário para melhorar o desempenho.

6. **Uso do Modelo**: Finalmente, o modelo treinado foi usado para fazer previsões sobre novos dados.

Por favor, consulte o notebook "Dados_BDMEP.ipynb" para obter detalhes completos sobre o treinamento e uso do modelo de Árvore Aleatória.


## Como usar

Para usar este notebook, você precisará ter o Jupyter Notebook instalado em seu computador. Depois de clonar este repositório, você pode abrir o arquivo "Dados_BDMEP.ipynb" no Jupyter Notebook e executar as células para realizar a análise e visualização dos dados.

Espero que este resumo seja útil para você! Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para abrir uma issue ou enviar um pull request.

