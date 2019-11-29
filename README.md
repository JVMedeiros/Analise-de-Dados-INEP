ANÁLISE DE DADOS - INEP

Análise dos dados do INEP afim de comparar a curva de crescimento das inscrições normais e inscrições especiais (deficientes auditivos e fisicos) no ENEM entre os anos de 2012 a 2018.
Os dados podem ser adquiridos em: http://inep.gov.br/microdados

Esta análise foi feita utilizando a linguagem python (3.7) em conjunto com o ambiente Jupyter Notebook. Pelos arquivos baixados no site do INEP estarem no formato .csv, foi utilizada a biblioteca PANDAS para fazer a leitura desses arquivos enquanto as bibliotecas NUMPY e MATPLOTLIB para gerar os gráficos exibidos no final.

Como o número de inscrições especiais nos anos descritos não passaram de 100 mil, nos gráficos foram expostas apenas os dados dessas inscrições, sem comparar com as inscrições normais pois são irrisórios perto dos aproximados 7 milhões de inscritos no ENEM. Para que esses dados fossem expostos, foi gerada uma tabela ao final para que esses dados possam ser comparados.

