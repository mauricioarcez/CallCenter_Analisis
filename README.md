# "Anonymous Bank" Call-Center

## Introducción

En este proyecto, se ha aplicado una limpieza y analisis exploratorio de los datos a travez de python para luego visualizarlo en un Dashboard integral para el Call Center con el objetivo de medir y evaluar los niveles de calidad de servicio, eficiencia y productividad. Este Dashboard está diseñado para ofrecer una visión clara y detallada del desempeño operativo de la empresa, permitiendo a los gestores identificar áreas de mejora y optimizar la experiencia del cliente.

## Descripción de los Datos

El dataset utilizado en este análisis contiene información detallada sobre las llamadas gestionadas por el call center, incluyendo las siguientes columnas:

- ```vru.line```: Código de la unidad de respuesta de voz.
- **call_id**: Código de la llamada.
- **costumer_id**: Código de cliente.
- **Priority**: Prioridad de la llamada.
- **type**: Tipo de llamada.
- **date**: Fecha de la llamada.
- **vru_entry**: Hora de entrada a la unidad de respuesta de voz.
- **vru_exit**: Hora de salida de la unidad de respuesta de voz.
- **vru_time**: Tiempo que duró la unidad de respuesta de voz.
- **q_star**: Hora de entrada a la cola.
- **q_exit**: Hora de salida de la cola.
- **q_time**: Duración en la cola.
- **outcome**: Resultado de la llamada (tomada por agente, colgaron, fantasma).
- **ser_star**: Hora en que el agente contesta.
- **ser_exit**: Hora en que el agente cuelga.
- **ser_time**: Duración de la llamada con el agente.
- **server**: Nombre del agente.

## Respuestas a las Preguntas Planteadas

- **¿Cuál es el nivel de servicio para los clientes Prioritarios?**  
  El nivel de servicio para los clientes prioritarios es del 72.55%, lo cual indica un buen desempeño, aunque hay margen para mejoras.
