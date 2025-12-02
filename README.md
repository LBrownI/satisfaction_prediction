# Prediccion de satisfaccion de servicio en base a hábitos de compra

Usted ha sido recientemente contratado como científico de datos en una tienda de venta de ropa online. Dado el gran volumen de ventas que tiene la tienda los asistentes de la empresa trabajan sin descanso ayudando a los clientes con el proceso de compra. Dado que recientemente se han empezado a registrar esperas muy largas para ser atendido por uno de los asistentes, a alguien en la junta directiva se le ocurrio que se podia ahorrar tiempo si los asistentes no realizaran una “breve” encuesta de satisfaccion a cada cliente. Esta encuensta se traduce internamente en un puntaje único, lo que ayudaria a predecirlo  a partir de datos de los clientes recogidos de manera automática, y si es cierto, a disminuir los tiempos de espera de los clientes por un asistente sin tener que contrar mas personas para ese cargo.

El archivo dataset3.csv contiene un dataset con los resultados de información recogida de manera automática (17 variables) para 3900 clientes.

*Con esta información, determine si es posible predecir de manera robusta un predictor de puntaje de satissfacionen a partir de otra información que se recoge de manera automática para los clientes .*

Deben asegurarse de que sus sistema generaliza  y que han usado el mejor algoritmo regrersor con los mejores parametros posibles para reolver esta tarea. Documenten el proceso y explique cada una de las decisiones que toma y que criterios las sustentan.

## Tarea:
Aprovechando la gran cantidad de datos existentes en el dataset, construya un sistema que a través de  algoritmos de regresión nos permita establecer la viabilidad de predecir el puntaje de satisfaccion a paritr de otra data de facil recoleccion.

El procedimiento a seguir debe ser el siguiente:

1. Utilicen al menos 3 algoritmos de los explicados en la unidad 3 con distintos parametros y los 17 descriptores del dataset. Asegurense de las capacidades de generalización de cada algoritmo/set de parametros y comparen el desempeño de todos ellos.

2. Usen al menos un metodo para seleccionar los mejores 10 descriptores y compare el desempeño con las versiones de los mismos algoritmos del punto anteriors. Expliquen la diferencia en desempeños

3. Estudien ahora el efecto de normalizar los datos. ¿Los parametros optimos y el desempeño son distintos?, expliquen las diferencias observadas