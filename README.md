Anderson Nascimento Mota
Inicialmente foi feito o carregamento da base de dados e foi observado que existem 9 tipos de crimes diferentes, diante disso na etapa de pré-processamento dos dados foi calculado o somatório de cada crime em cada estado brasileiro durante todo o período. Após os cálculos foi criado um data frame com os resultados para cada estado brasilerio.


Na etapa de análise dos dados foi observado que alguns  crimes tinham forte relação, foram eles:
*    Estupro e Furto de veículo;
*    Estupro e roubo de veículo;
*    Estupro e latrocínio;
*    Furto de veículo e roubo de veículo;
*    Furto de veículo e roubo de carga;
*    Latrocínio e homicídio doloso.

E foi plotado um gráfico de barras para identificar o estado brasileiro com maior número de no qual foi constatado que São Paulo foi o estado com o maior número de ocorrências. Na clusterização o valor de Kmeans com maior score foi 2, apresentando grande diferença dos demais e na criação dos clusters o estado de São Paulo por ter um número muito alto de ocorrências acabou ficando sozinho em um cluster.
