# telecom_plan_recommendation_ml
Creación de modelos de machine learning para recomendar a los clientes un plan tarifario de acuerdo a su comportamiento. ***Proyecto desarrollado como evaluación final del Sprint de Aprendizaje automático aplicado a negocios del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
La compañía móvil Megaline no está satisfecha al ver que muchos de sus clientes utilizan planes heredados. Quieren desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra.

## Objetivo del proyecto
1. Crear un modelo que escoja el plan correcto.

    2. Desarrollar un modelo con la mayor exactitud posible. El umbral de exactitud es 0.75. 
    
        3. Usar el dataset para comprobar la exactitud.

## Modelos de machine learning creados
- Logistic Regression
- Random Forest Classifier
- Decission Tree Classifier

## Librerías principales utilizadas
- pandas
- sklearn

## Resultados
1. Se evaluaron 3 modelos de clasificación, probando diferentes hiperparámetros en cada uno: 
    - árbol de decisión
    - bosque aleatorio
    - regresión logística
2. El modelo de bosque aleatorio con n_estimators igual a 8 obtuvo el mejor score, igual a 0.824
3. La exactitud del modelo de bosque aleatorio con el conjunto de prueba fue de 0.765. El umbral de exactitud solicitado era de 0.75, por lo que el modelo creado es aceptable. 
4. La prueba de cordura consistió en cambiar los valores target, de numérico (0 y 1) a su descripción textual (Smart y Ultra). El score de exactitud fue igual al primer score obtenido. Se puede decir que la prueba de cordura fue superada. 