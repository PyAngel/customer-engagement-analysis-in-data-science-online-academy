# Análisis de Participación del Cliente en la Academia en Línea de Ciencia de Datos
## Este repositorio contiene el análisis y desarrollo para la participación del cliente, contenido y calificaciones de evaluación de cursos en la Academia de Ciencia de Datos.

Esta base de datos es proporcionada por 365datascience.com, y su uso es estrictamente academico.

si a usted le gustaria observar el tablero ONLINE, por favor dar [clic aquí](https://lookerstudio.google.com/reporting/24a9a17c-7c7e-436c-b65a-7a2b25a14109).

## OBJETIVO

Nuestra meta es recopilar información cuantificable sobre la participación de nuestros clientes con nuestro contenido. 365DataScience.com es una plataforma en línea de educación en ciencia de datos y análisis financiero. Parte de nuestro crecimiento se centra en proporcionar calidad en nuestro contenido académico, lo cual debería ayudar a nuestros estudiantes a contribuir de manera satisfactoria a su educación.

Este proyecto tiene como objetivo responder a las siguientes preguntas:

- ¿Cuál es la cantidad promedio y total de minutos observados por nuestros estudiantes?
- ¿Cuál es la cantidad por país de estudiantes activos y cuántos minutos totales se ven agrupados por países?
- ¿Cuántos minutos se visualizan y cuál es la calificación promedio de cada curso por parte de nuestros estudiantes?
- ¿Cuál es la cantidad de nuevos estudiantes para cada mes?

## DATOS
Nuestro cliente nos proporcionó un (1) archivo de base de datos. En este archivo, tienen registros de todos los estudiantes almacenados en diferentes tablas.

- T1. Información del Curso: Esta tabla contiene todos los títulos de los cursos con sus respectivos ID.
- T2. Calificación del Curso: Esta tabla contiene todos los registros que nuestros estudiantes proporcionaron para cada curso en el rango de tiempo de junio a octubre de 2022.
- T3. Información del Estudiante: Esta tabla registra a todos los nuevos estudiantes y sus nacionalidades.
- T4. Aprendizaje del Estudiante: Esta tabla contiene todos los registros de tiempo observado para cada curso. Estos registros incluyen todas las interacciones de los estudiantes desde enero hasta octubre de 2022.
- T5. Compras de Estudiantes: Esta tabla contiene todas las compras o renovaciones de suscripciones, incluyendo la fecha, tipo e ID del estudiante.

## TECNOLOGIAS

En este proyecto se utilizaron:

- BI tool: Google Looker Studio
- Base de datos: MySQL 8
- Otros: Microsoft Excel


## CONCLUSIONES

- El usuario promedio consume 28 minutos por sesión.
- Los países con menos usuarios consumen más minutos por usuario que otros países con una diferencia significativa en usuarios activos (como Estados Unidos, India). Esto podría deberse a hábitos de consumo, estilo de vida, entre otros factores.
- Es destacable que en India, siendo el país con el mayor número de usuarios activos, han consumido solo alrededor de 26 minutos por usuario en promedio en diez meses. Esto podría ser motivo de preocupación, ya que sugiere que la estrategia de marketing en ese país podría estar atrayendo a clientes que no están muy interesados en utilizar el servicio. Esto podría llevar a una falta de suscripciones a largo plazo por parte de nuestros clientes actuales en India.
- Siguiendo con las premisas anteriores en este análisis, es importante destacar que nuestros cursos introductorios sobre datos y ciencia de datos, así como SQL, tienen el mayor tiempo de visualización acumulado a nivel mundial. En contraste, nuestros cursos más avanzados (como PyTorch, etc.) tienen menos visualizaciones acumuladas. Esto puede ocurrir como una tendencia natural cuando las personas se inscriben en cursos de duración intermedia, donde progresivamente menos personas continúan a medida que avanza el curso.
