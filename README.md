Problema
O objetivo deste projeto é desenvolver um sistema de recomendação de filmes utilizando a técnica de similaridade do cosseno. O sistema permite que o usuário insira o nome de um filme e, com base nisso, retorne uma lista de filmes semelhantes. Esse tipo de recomendação pode ser útil para ajudar os usuários a encontrar filmes que eles provavelmente irão gostar, com base em suas preferências passadas.

Metodologia Utilizada
Captura de Dados : O usuário insere o nome de um filme na interface web.
Manipulação de Dados : Os dados dos filmes e suas avaliações são carregados de arquivos CSV.
Processamento dos Dados :
Os dados são mesclados para criar uma tabela unificada.
Utilize-se uma tabela dinâmica para preparar os dados para o cálculo de similaridade.
A semelhança do cosseno é calculada entre os filmes.
Recomendação :
Verifique se o filme inserido está presente no banco de dados.
Retorna uma lista de filmes similares planejados por similaridade.
Exibição dos Resultados : Os resultados são exibidos em uma tabela HTML na interface web.
Resultados Obtidos
O sistema é capaz de retornar uma lista de filmes semelhantes ao filme inserido pelo usuário, mostrando as recomendações com uma porcentagem de similaridade.

Conclusões
O projeto demonstra as diretrizes de utilização de técnicas de similaridade para criar sistemas de recomendação recomendadas, utilizando bibliotecas de Python como pandas e scikit-learn para manipulação de dados e cálculos de similaridade.
