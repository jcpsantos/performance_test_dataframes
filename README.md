# Testando a performance de bibliotecas Python para se trabalhar com Dataframes

O primeiro teste realizado foi de uma leitura de um dataframe em **csv** com as seguintes caracteristicas:
- **Tamanho: 1.1GB**
- **Total de Colunas: 19**
- **Total de Linhas: 5012957**

As bibliotecas utilizadas foram:
- [Pandas](https://pandas.pydata.org/)
- [Modin](https://modin.readthedocs.io/en/latest/)
- [Vaex](https://vaex.readthedocs.io/en/latest/)
- [Dask](https://dask.org/)
- [Pyspark](https://spark.apache.org/docs/latest/api/python/index.html)

[**Notebook**](https://github.com/jcpsantos/performance_test_dataframes/blob/master/performance_test_read_dataframes.ipynb)

O segundo teste realizado foi de uma pequena analise de um datafram em **parquet** com as seguintes caracteristicas:
- **Tamanho: 193MB**
- **Total de Colunas: 23**
- **Total de Linhas: 2688711**

As bibliotecas utilizadas foram:
- [Pandas](https://pandas.pydata.org/)
- [Modin](https://modin.readthedocs.io/en/latest/)
- [Koala](https://koalas.readthedocs.io/en/latest/getting_started/install.html)
- [Dask](https://dask.org/)
- [Pyspark](https://spark.apache.org/docs/latest/api/python/index.html)

[**Notebook**](https://github.com/jcpsantos/performance_test_dataframes/blob/master/performance_test_read_dataframes_parquet.ipynb)

## Gráfico de Performance
![alt text](https://github.com/jcpsantos/performance_test_dataframes/blob/master/path/versao_parquet.png)
