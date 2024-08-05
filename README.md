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
 
