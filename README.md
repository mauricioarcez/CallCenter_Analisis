# "Anonymous Bank" Call-Center

## Introducción

En este proyecto, se ha aplicado una limpieza y analisis exploratorio de los datos a travez de python para luego visualizarlo en un Dashboard integral para el Call Center con el objetivo de medir y evaluar los niveles de calidad de servicio, eficiencia y productividad. Este Dashboard está diseñado para ofrecer una visión clara y detallada del desempeño operativo de la empresa, permitiendo a los gestores identificar áreas de mejora y optimizar la experiencia del cliente.

## Descripción de los Datos

El dataset contiene información detallada sobre las llamadas, incluyendo las siguientes columnas:

- ```vru.line```: Código de la unidad de respuesta de voz.
- ```call_id```: Identificador de llamada.
- ```costumer_id```: Identificador de cliente.
- ```Priority```: Prioridad de la llamada. 2 Importante, 0 prospectos.
- ```type```: Tipo de llamada.
Hay 6 tipos diferentes de servicio:
• PS - Actividad Regular
• PE - Actividad Regular en inglés
• IN - Actividad / Consulta por internet
• NE - Actividad por Acciones (stock exchange)
• NW - Cliente potencial (prospecto) solicitando información
• TT – clientes que dejan un mensaje pidiendo al banco que le devuelvan su llamado pero que cuando el sistema automático devuelve el llamado, el agente pasó a estado “ocupado”, dejando al cliente en espera en la cola.
- ```date```: Fecha de la llamada.
- ```vru_entry```: Hora de entrada al bot de llamada.
- ```vru_exit```: Hora de salida al bot de llamada.
- ```vru_time```: Tiempo que duró el bot, calculado por su diferencia en entrada y salida.
- ```q_star```: Hora de entrada a la cola.
- ```q_exit```: Hora de salida de la cola.
- ```q_time```: Duración en la cola de espera.
- ```outcome```: Resultado de la llamada. Atendido, abandonado, fantasma(pocos datos que no se saben que paso).
- ```ser_star```: Hora en que comienza el servicio.
- ```ser_exit```: Hora en que termina el servicio.
- ```ser_time```: Duración del servicio.
- ```server```: Nombre del agente o especificacion si no fue atendido.

## Preguntas Planteadas 

- **¿Cuál es el nivel de servicio para los clientes Prioritarios?**
  El análisis de los tiempos de espera y el volumen de llamadas ha proporcionado hallazgos clave sobre el nivel de servicio para los clientes prioritarios en comparación con otros segmentos:

- **Promedio de Tiempo de Espera:** El promedio general de tiempo de espera para todas las llamadas es de 59 segundos. Sin embargo, se observa una variación significativa entre los tipos de clientes:
  - **Clientes No Identificados:** 26 segundos
  - **Clientes Regulares:** 65 segundos
  - **Clientes Prioritarios:** 87 segundos

- **Distribución del Volumen de Llamadas:**
  - **Clientes Prioritarios:** 30%
  - **Clientes Regulares:** 29%
  - **Clientes No Identificados:** 40%

- **Desempeño por Cuartos:**
  - En el primer y segundo cuarto del período analizado, el volumen de llamadas prioritarias era mayor en comparación con otros tipos de clientes, con un tiempo de espera promedio de 85 segundos, frente a 80 segundos para clientes regulares y 30 segundos para clientes no identificados.
  - En los últimos dos cuartos, aunque el volumen de llamadas prioritarias disminuyó, el tiempo de espera para estos clientes solo se redujo ligeramente a 84 segundos. En contraste, los clientes regulares y no identificados experimentaron una notable mejora en sus tiempos de espera, con promedios reducidos a 40 segundos.

Estos hallazgos sugieren que, a pesar de una disminución en el volumen de llamadas prioritarias, el tiempo de espera para estos clientes sigue siendo considerablemente alto en comparación con otros segmentos. La ligera mejora en los últimos cuartos no ha sido suficiente para igualar el nivel de servicio ofrecido a los clientes regulares y no identificados.
 
