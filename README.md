# ![alt text](Imagenes/Consesionario.png)

# Modelo de prediccion de precio de vehiculos 

​​Machine Learning en investigación de mercado automotor: El mercado automotor esta muy ligado a la cultura de cada país, según los gustos de cada uno, el mercado norteamericano, por ejemplo, valora mucho los motores y vehículos muy grandes, el mercado europeo prefiere el bajo consumo, el mercado latinoamericano, los precios finales bajos y asi varía según región, país, nivel socioeconómico y cultura. Un mismo vehículo puede tener un valor muy distinto de un pais al otro, y no solo por los impuestos o costos de producción, sino por cómo cotiza el modelo en el mercado.

## Planteamiento del problema

​Hemos sido contratados en el equipo de ciencias de datos en una consultora de renombre. Nos han asignado a un proyecto de estudio de mercado de una importante automotriz china. Nuestro cliente desea ingresar a nuestro mercado de automóviles, por lo que nos han encomendado analizar las características de los vehículos presentes en el mercado actual. Dado que tienen en su catálogo una amplia colección de modelos de todo tipo, cuyo catálogo está estratificado en gamas según el gusto de cada región, desean saber qué características presentan los vehículos de gama alta y los de gama baja en nuestro mercado, para poder abarcar todo los públicos objetivos ajustándose a toda la demanda y, en base a estos datos, poder cotizar correctamente los vehículos que ofrecerá.

# EDA (Analisis exploratorio de los datos)

Como primer paso realizamos una analisis del data set, buscando que este equilibrado, que no tenga valores faltantes o que no tenga algun valor atipico, y notamos que todos los datos estan bien.

# ![alt text](Imagenes/Inspeccion_dataset.png)

Graficando este histograma notamos que la mayoria de autos son de bajo precio en comparacion con los mas costosos.

# ![alt text](Imagenes/Histograma.png)

Despues realizamos una matriz de correlacion para analizar que aspectos influyen mas con respecto al precio del automovil.

# ![alt text](Imagenes/Matriz-correlacion.png)

Vemos por medio de un grafico de dispersion el comportamiento de las tres variables que tuvieron mas correlacion con respecto al precio

# ![alt text](Imagenes/Dispersion.png)

# Modelado de ML

Teniendo en cuenta el analisis anterior se usaran las caracteristicas que mas correlacion tuvieron con respecto a este, y se aplicara un Random Forest para predecir los precios de los vehiculos.

Como primer paso escalamos los datos parra entrenar el modelo

# ![alt text](Imagenes/Datos%20escalados.png)

Despues de escalados entrenamos el modelo

# ![alt text](Imagenes/Modelo%20entrenado.png)

Analizamos su presicion de prediccion

# ![alt text](Imagenes/Presicion.png)

Se concluye que el modelo tiene un buen rendimiento y que da buenas predicciones de a cuerdo con los datos reales

![alt text](Imagenes/Predicciones.png)