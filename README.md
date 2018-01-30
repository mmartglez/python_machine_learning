# Repositorio de proyectos Machine Learning con Python


### Instalación
1. Instalar Docker https://www.docker.com/
2. Utilizar los siguientes comandos para ejecutar docker<sup>[1](#myfootnote1)</sup>.
```
git clone https://github.com/mmartglez/python_machine_learning.git
cd python_machine_learning
docker-compose up
```
3. Ir a `192.168.99.100:9000` en el navegar para empezar a utilizar los notebooks de jupyter.

### Contenido

#### Analisis de datos
0. Analisis Exploratorio de datos (https://www.kaggle.com/pmarcelino/comprehensive-data-exploration-with-python)

#### Regression lineales
1. Introduction to regression. (https://www.kaggle.com/rbyron/simple-linear-regression-models)
2. Ridge (https://www.kaggle.com/dfitzgerald3/optimizing-ridge-regression-parameterization)

#### Arboles de decision
3. Decision tree sin NA imputation
4. Random Forest con NA imputation
5. XGBoost (https://www.kaggle.com/dansbecker/learning-to-use-xgboost)

#### Clustering
6. Componentes Pricipales y K-Means (https://www.kaggle.com/arthurtok/principal-component-analysis-with-kmeans-visuals)
7. K-Vecinos

#### SVM
8. SVM (https://www.kaggle.com/emptycasket/regression-with-svm-python)

#### Ensamblado de modelos
9. Pipeline + Ensamblado  https://www.kaggle.com/serigne/stacked-regressions-top-4-on-leaderboard


### Notes
<a name="myfootnote1">1</a>: Refer to this [Dockerfile](https://github.com/sachinruk/Dockerfiles/blob/master/ML_class/Dockerfile) and [this](https://github.com/sachinruk/Dockerfiles/blob/master/DS_base/Dockerfile) for information on how the docker image was built.

