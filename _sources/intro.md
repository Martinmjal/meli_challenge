# Intro

La presente compilación de Jupyter Notebooks contiene la solución a la prueba técnica de Mercado Libre por parte de mi persona, `Martin Alvarez`. A continuación dejo un enlace a mi perfil de Linkedin junto a una descripción de cómo se llevó a cabo esta solución:

[LinkedIn Martin Alvarez](https://www.linkedin.com/in/martinalvarez2000/)

El proceso de `Feature engineering` se desarrolló a cabo iterativamente junto con el `EDA`, esto se dió porque los datos crudos tenían muchos campos `anidados`, lo cuál dificultaba convertir el archivo `JSON` en `dataframe`. Las `features` se fueron construyendo durante el proceso de llevar los registros en formato `JSON` a una forma `flat`, lo cuál posteriorimente permitió que se pudiese convertir a `dataframe`. Lo que finalmente  permitió construir visualizaciones y servir como `input data` para entrenar el modelo.

Se entrenó un modelo `XGBOOST` con hiperparametrización, luego se evaluaron las métricas en la partición de `Test` obteniendo un `AUC` de `0.94` y un `F1-score` de `0.86`. Lo cuál satisfactoriamente logra cumplir con los requerimientos de la prueba.

Espero la solución propuesta sea de su agrado, los pasos seguidos fueron:

```{tableofcontents}
```
