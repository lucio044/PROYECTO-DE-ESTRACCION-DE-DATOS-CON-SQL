# PROYECTO-DE-ESTRACCION-DE-DATOS-CON-SQL
 Investigación de patrones de viaje y preferencias de clientes en Chicago, integrando fuentes externas como condiciones climáticas. El análisis incluyó consultas SQL, análisis exploratorio en Python y pruebas de hipótesis, proporcionando información estratégica sobre el impacto del clima en la demanda de viajes.
### Cómo planteaste las hipótesis nula y alternativa

- #### Identificar el problema

Queríamos comprobar si la duración de los viajes entre Loop y el Aeropuerto Internacional O'Hare cambia en sábados lluviosos.
Este análisis nos ayuda a entender cómo el clima influye en los tiempos de traslado.

- #### Planteamiento de hipótesis

Para realizar una prueba estadística, formulamos dos hipótesis:
  - Hipótesis nula:
    "No hay diferencia significativa en la duración promedio de los viajes en sábados lluviosos y sábados no lluviosos." 
    Esto significa que el clima no afecta los tiempos de viaje. En otras palabras, cualquier diferencia observada podría deberse     al azar.
  - Hipótesis alternativa:
    "La duración promedio de los viajes sí cambia en sábados lluviosos."
    Esto implica que el clima sí influye en la duración del viaje. Si esta hipótesis se confirma, podríamos concluir que los         días lluviosos provocan tiempos de viaje más largos o diferentes patrones de tráfico.

- #### Método de prueba

Para comparar las duraciones de viaje en ambos grupos, utilizamos una prueba t de Student para muestras independientes.
Esto nos permitió evaluar si la diferencia de tiempos de viaje es estadísticamente significativa.