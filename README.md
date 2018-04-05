# Introducción a la minería de medios sociales 

## Objetivo

El objetivo de esta práctica es realizar una introducción a la minería de datos aplicada a los medios sociales. Se aprenderá a recolectar tuits a partir del flujo continuo que provee Twitter, y se calcularán algunas métricas y visualizaciones básicas utilizando el lenguaje de programación Python. 

Para la realización de la práctica se proveen dos _notebooks_ que contienen el grueso del código. Los _notebooks_ incluyen la mayor parte de la funcionalidad para poder realizar la práctica. Además, de ejecutarlos y entender cómo han sido implementados se solicitarán realizar modificaciones para responder a preguntas similares a las planteadas en los mismos.

## Descargar los notebooks

Primeramente debemos realizar una clonación del repositorio que contiene todos los archivos que conforman la práctica. Desde un directorio vacío ejecutamos el siguiente comando:

```
git clone https://github.com/phaya/python-twitter-mining.git
```

creándose un directorio `python-twitter-mining` con los archivos correspondientes. 

## Instalación

Para poder ejecutar los _notebooks_ necesitamos disponer de una entorno con _Jupyter_, y con las siguientes bibliotecas:

- tweepy (3.6.0)
- json (2.0.9) built-in
- matplotlib (2.2.2)
- pandas (0.22.0)
- re (2.2.1) built-in

Para facilitar la configuración se recomienda emplear la plataforma [Conda](https://conda.io) para instalar y ejecutar los _notebooks_. 

Una vez dispongamos de una instalación de Conda es preciso crear un nuevo entorno donde instalar las bibliotecas necesarias y los _notebooks_. Se facilta un archivo `environment.yml` con toda la información necesaria para realizar este paso mediante el siguiente comando:

```
conda env create -f environment.yml
```

Al finalizar la instalación deberíamos tener creado un nuevo entorno, denominado `tweet-mining` que debemos activar con el siguiente comando:

```
source activate tweet-mining
```

Finalmente procedemos a lanzar `jupyter` para poder ejecutar los _notebooks_

```
jupyter notebook
```

## Referencias

- [An Introduction to Text Mining using Twitter Streaming API and Python](http://adilmoujahid.com/posts/2014/07/twitter-analytics/)
- [Mining Twitter Data with Python](https://marcobonzanini.com/2015/03/02/mining-twitter-data-with-python-part-1/)
- [Mastering Social Media Mining with Python](https://marcobonzanini.com/2016/08/02/mastering-social-media-mining-with-python/)
