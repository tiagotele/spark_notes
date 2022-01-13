# spark_notes
General notes about Spark API. For self and quick future reference.

## Executando Spark com Jupyter localmente via Docker
```bash
docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook
```

Para utilizar arquivos basta montar o volume:
```bash
docker run -v $(pwd):/home/jovyan/work -it --rm -p 8888:8888 jupyter/pyspark-notebook
```
