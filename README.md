# Repositorio de proyectos Machine Learning con Python


## Instalación
1. Instalar Docker https://www.docker.com/
2. Utilizar los siguientes comandos para ejecutar docker<sup>[1](#myfootnote1)</sup>.
```
git clone https://github.com/mmartglez/python_machine_learning.git
cd python_machine_learning
docker-compose up
```
3. Ir a `192.168.99.100:9000` en el navegar para empezar a utilizar los notebooks de jupyter.


## Objetivo

El objetivo de este repositorio es analizar un supuesto de predicción desde varias perspectivas. 
- Partiendo de un dataset con las características y precio de activos (viviendas), vamos a entontrar un modelo que nos sirva para predecir el precio de otro activo. Ejemplo: tenemos una cartera con varios activos adjudicados y queremos saber su valor de mercado y poder así posicionarlos por ejemplo, en una franja media-baja que nos permita venderlos rápido. 
- Utilizaremos Python métodos supervisados de regresión lineal, arboles de decisión, etc y no supervisados de clusterización. 
- Se describe en cada módulo procedimiento y comparación de modelos.

## Contenido

#### Analisis de datos
A. [Analisis Exploratorio de datos](https://github.com/mmartglez/python_machine_learning/blob/master/0A.%20Analisis%20Exploratorio%20de%20datos.ipynb)

B. [Limpieza de datos y preparación DataFrame](https://github.com/mmartglez/python_machine_learning/blob/master/0B.%20Limpieza%20de%20datos%20y%20preparacion%20df.ipynb) 

#### Regression lineales
1. [Introduccion a la regression.](https://github.com/mmartglez/python_machine_learning/blob/master/1.%20Introduccion%20a%20la%20regression.ipynb)
2. [Ridge regression](https://github.com/mmartglez/python_machine_learning/blob/master/2.%20Ridge%20regression.ipynb)

#### Arboles de decision
3. [Decision Tree sin NA imputation](https://github.com/mmartglez/python_machine_learning/blob/master/3.%20Decision%20tree%20sin%20NA%20imputation.ipynb)
4. [Random Forest con NA imputation](https://github.com/mmartglez/python_machine_learning/blob/master/4.%20Random%20Forest%20con%20NA%20imputation.ipynb)
5. [XGBoost](https://github.com/mmartglez/python_machine_learning/blob/master/5.%20XGBoost.ipynb)

#### Clustering
6. [Componentes Pricipales PCA y K-Means](https://github.com/mmartglez/python_machine_learning/blob/master/6.%20Componentes%20Principales%20y%20K-Means.ipynb)
7. K-Vecinos

#### SVM
8. [SVM](https://github.com/mmartglez/python_machine_learning/blob/master/8.%20SVM.ipynb)

#### Ensamblado de modelos
9. [Cross validation: Gradient Bossting vs RandomForest](https://github.com/mmartglez/python_machine_learning/blob/master/9.%20Cross%20validation%20Gradient%20Bossting%20vs%20RandomForest.ipynb)
10. [Pipeline + Ensamblado]()




### Notes
<a name="myfootnote1">1</a>: Refer to this [Dockerfile](https://github.com/sachinruk/Dockerfiles/blob/master/ML_class/Dockerfile) and [this](https://github.com/sachinruk/Dockerfiles/blob/master/DS_base/Dockerfile) for information on how the docker image was built.

