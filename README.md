# Predicción de las vacunas contra el virus H1N1 y la influenza estacional

El objetivo del proyecto es diseñar un modelo de Machine Learning que permita predecir la probabilidad de que una persona reciba las vacunas contra el virus H1N1 y la gripe estacional.

###### Contexto del negocio

En los últimos años, se han presentado a nivel mundial una serie de enfermedades respiratorias importantes. A partir de la primavera de 2009, una pandemia causada por el virus de la gripe H1N1, coloquialmente llamada "gripe porcina", se extendió por todo el mundo. Los investigadores estiman que, en el primer año, fue responsable de entre 151.000 y 575.000 muertes en todo el mundo.

En octubre de 2009 se puso a disposición del público una vacuna contra el virus de la gripe H1N1. Las vacunas proporcionan inmunización a las personas, y una inmunización suficiente en una comunidad puede reducir aún más la propagación de enfermedades a través de la "inmunidad colectiva".

A finales del 2009 y principios del 2010, en los Estados Unidos se llevó a cabo la Encuesta Nacional sobre la Influenza H1N1, esta encuesta telefónica preguntó a los encuestados si habían recibido las vacunas contra la gripe H1N1 y la gripe estacional, así como preguntas que abarcaron sus antecedentes sociales, económicos y demográficos, comportamientos para mitigar la transmisión, opiniones sobre los riesgos de enfermedad y la efectividad de la vacuna.

Una mejor comprensión de cómo estas características se asocian con los patrones de vacunación puede proporcionar una orientación clara para futuros esfuerzos de salud pública.


**Tabla de Contenido**
* [Librerías](#librerias)
* [Instrucciones de Ejecución](#instrucciones-de-ejecucion)
* [Conclusiones](#conclusiones)
* [Autores](#autores)


#### Librerías

Las librerías utilizadas para el análisis de los datos son las siguientes: 
- pandas
- numpy
- seaborn 
- matplotlib
- requests
- io
- sklearn
- scipy


#### Instrucciones de Ejecución

El análisis de los datos, el entrenamiento y la ejecución de los modelos se realizaron en el notebook [Proyecto_EDA.ipynb](https://github.com/Lperdoca/Modelo-de-prediccion-vacunas-influenza-y-H1N1/blob/main/Proyecto_EDA.ipynb) de Jupyter, el cual debe ser ejecutado secuencialmente. 


#### Conclusiones

1. Se evidencia un bajo porcentaje de vacunación tanto para el virus H1N1 como para la influenza estacional en el grupo de edad de 18 a 35 años y un porcentaje más alto en los mayores de 65.

2. Se evidencia que las variables relacionadas con los hábitos de salud no tienen un impacto directo con la decisión de vacunación. 

3. Se evidencia una fuerte correlación entre la opinión del riesgo que tiene contraer el virus H1N1 o la influenza estacional con la cantidad de personas vacunadas. 

4. Los encuestados que trabajan en el área de la salud muestran un comportamiento similar al del resto de los participantes, lo que sugiere que trabajar en el sector salud no implica una mayor probabilidad de vacunación. 

5. El algoritmo de Radom Forest y la Regresión Logística fueron los algoritmos con el mejor desempeño, ambos tuvieron un recall del 63%, lo que nos dice que el porcentaje de verdaderos positivos es significativo. 

6. Mediante la métrica ROC AUC podemos concluir que el modelo de Logistics Regression, determina sigficativamente si una persona se va a vacunar o no, ya que, nos dio una media superior al 80% 


#### Autores

| Organización   | Nombre | Correo electronico | 
|----------|-------------|-------------|
| Uniandes |  Andrés Fernando Delgado Pérez | af.delgadop@uniandes.edu.co |
| Uniandes |  David Esteban Fajardo Torres | de.fajardo@uniandes.edu.co |
| Uniandes |  Jairo Antonio Caro Vanegas | ja.carov1@uniandes.edu.co |
| Uniandes |  Lizeth Viviana Perdomo Castañeda | lv.perdomoc1@uniandes.edu.co |
