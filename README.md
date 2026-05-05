# Tech-Challenge-1
Objetivo: O objetivo do projeto é verificar a partir de um conjunto de dados quais são os principais fatores que impactam o indicador NPS de uma empresa de e-commerce e, a partir dos insights, desenvolver um plano de ação para melhorar este score.

Base de Dados: o arquivo csv contendo a base de dados pode ser encontrada neste repositório dentro da pasta "Notebook_Analise" com o nome 'desafio_nps_fase_1.csv'.
A base de dados contém 2.500 pedidos únicos e contém informações como NPS ('nps_score'), dados do pedido (valores, frete, descontos, quantidade, atraso), dados de interação do cliente com o Customer Service, região e histórico de recompra.

Metodologia Utilizada: para medir o NPS utiizou-se a pontuação dada pelo cliente no final da jornada de 0 até 10, onde de 0 a 6 o cliente foi considerado como detrator, 7 a 8 como neutro, 9 a 10 como promotor. Para a análise de dados utilizou se um notebook em Python e como correlação utilizou-se o coeficiente de Pearson.

Como reproduzir os Resultados: faça o download do notebook 'Desafio_FIAP_1.ipynb' e do arquivo csv  'desafio_nps_fase_1.csv'. Caso seja necessário, altere o comando " df_nps = idhm = pd.read_csv('desafio_nps_fase_1.csv') " com o diretório onde o arquivo for salvo.

