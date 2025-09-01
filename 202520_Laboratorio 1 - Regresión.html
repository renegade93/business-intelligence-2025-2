# Laboratorio 1 - Regresión

[Objetivos](#objetivos)

[Herramientas](#herramientas)

[Caso de negocio](#enunciado)

[Entregables](#entregables)

[Rúbrica de clasificación](#rubrica)


## <a name="objetivos"></a> Objetivos

- Construir modelos analíticos para estimar una variable objetivo continua a partir de un conjunto de variables observadas.

- Comprender el proceso para la construcción de modelos analíticos que responden a una tarea de regresión.

- Automatizar el proceso de construcción de modelos analíticos con el uso de pipelines de tal forma que puedan ser usados en ambientes de producción.

- Extraer información útil para el negocio a partir de los resultados de los modelos de regresión.


## <a name="herramientas"></a> Herramientas

Durante este laboratorio se trabajará con las siguientes herramientas:

- Librerías de Python para el procesamiento y analisis de datos como: 
    - Pandas
    - Scikit-Learn
    - Matplotlib, Seaborn
- Entorno de desarrollo Jupyter Lab instalado localmente mediante Anaconda o en la nube mediante Google Colab.


## <a name="enunciado"></a> Caso de Negocio: FutAlpes F.C.

El análisis de datos en el fútbol es una de las herramientas más valiosas en la gestión deportiva moderna. No solo
permite optimizar el rendimiento de los equipos, sino que también facilita la toma de decisiones estratégicas en la contratación de jugadores. En un mercado cada vez más competitivo, donde los costos de los fichajes han alcanzado cifras históricas, los clubes buscan métodos más eficientes para evaluar el valor real de un futbolista y maximizar el retorno de inversión en su plantilla.

En la actualidad, el fútbol profesional está organizado en ligas nacionales, donde los clubes compiten cada temporada con el objetivo de obtener títulos, clasificar a torneos internacionales y evitar el descenso a divisiones inferiores. Las cinco grandes ligas de Europa (Premier League, LaLiga, Bundesliga, Serie A y Ligue 1) son las más competitivas y económicamente poderosas, atrayendo a los mejores jugadores del mundo. En este contexto, existe un mercado de fichajes en el que los clubes compran y venden futbolistas para reforzar sus plantillas. La tasación de un jugador en este mercado depende de múltiples factores, incluyendo su rendimiento estadístico, edad, posición, historial de lesiones, potencial de desarrollo, contrato vigente y la demanda de otros clubes. Además, aspectos externos como los ingresos del club, la inflación del mercado y la popularidad mediática del jugador también influyen en su valor. Tradicionalmente, estas valoraciones han sido realizadas por agentes, directivos y ojeadores basándose en experiencia e intuición, aunque en los últimos años el análisis de datos y modelos predictivos han cobrado un papel clave en la determinación de los precios y en la toma de decisiones estratégicas en las contrataciones.

Con este propósito, un equipo de fútbol de una de las cinco grandes ligas de Europa, recientemente adquirido por un nuevo grupo de inversores y que cambió su nombre a FutAlpes F.C., busca reforzar su plantilla en el mercado de fichajes actual de 2025 o, en su defecto, en la próxima ventana de invierno del mismo año. Para ello, han recopilado una amplia base de datos con información estadística sobre el rendimiento de los jugadores durante la temporada 2024/2025 (de junio de 2024 a junio de 2025), así como los valores de mercado más recientes de dichos jugadores en euros.

Si bien existen múltiples factores que pueden influir en la valoración de un jugador —como su popularidad, la posición en la que juega y la demanda en el mercado—, el club busca implementar un enfoque basado en datos que reduzca la incertidumbre en las negociaciones y permita tomar decisiones más fundamentadas.

En este sentido, el club ha decidido contratarlo para una fase inicial, cuyo objetivo es construir un modelo de aprendizaje automático capaz de predecir el precio de un jugador a partir de sus estadísticas. Este modelo servirá como apoyo para optimizar la selección de un refuerzo por cada zona del campo (1 arquero, 1 defensa, 1 mediocampista y 1 delantero), ajustándose a un presupuesto de 100 millones de euros.

Finalmente, se considera fundamental evaluar la calidad de los datos recopilados sobre jugadores y sus precios, garantizando que sean adecuados para la construcción de un modelo de aprendizaje automático sólido. Además, buscan asegurarse de que los datos utilizados en el modelo sean lo suficientemente representativos y proporcionen información relevante que explique los factores que influyen en la valoración de los jugadores en el mercado de fichajes.


* [Datos de entrenamiento](datos_entrenamiento_laboratorio1(train_data).csv)
* [Datos de prueba (no etiquetados)](datos_validacion_laboratorio1(test_data).csv)
* [Diccionario de datos](Diccionario%20de%20datos.xlsx)

## Soporte del experto

Para entender mejor los datos, un experto analista de datos que ya estaba trabajando en el equipo de fútbol nos dió un detalle más avanzado de los datos y que significan:

Para evaluar el rendimiento y valor de los jugadores en el mercado de fichajes, se utilizan diversas métricas estadísticas. Algunas de las más relevantes incluyen el "valor de mercado actual", que representa el precio estimado del jugador según su rendimiento y demanda; el "histórico del valor de mercado máximo", que indica el precio más alto que ha alcanzado en su carrera; y la "nacionalidad", que puede influir en su demanda dependiendo de las restricciones de cupos en algunos torneos. Además, otras métricas clave pueden incluir estadísticas de desempeño como goles anotados, asistencias, pases completados y duelos ganados, que ayudan a medir la contribución de un jugador en el campo. Estos datos permiten a los clubes tomar decisiones más informadas al momento de realizar fichajes y construir una plantilla equilibrada dentro de su presupuesto.

Las métricas avanzadas en fútbol, como xG (goles esperados), npxG (goles esperados sin penales), xA (asistencias esperadas) y PSxG (goles esperados post-disparo), han revolucionado la forma en que se evalúa el rendimiento de los jugadores, ya que permiten medir su impacto en el juego más allá de las estadísticas tradicionales. A continuación, explicaran cada una de ellas de manera sencilla:

• xG (Expected Goals - Goles Esperados): Esta métrica estima la probabilidad de que un disparo termine en
gol según diversos factores, como la distancia al arco, el ángulo de tiro, la parte del cuerpo utilizada y la
presión defensiva. Un xG de 0.75 significa que, en promedio, ese tipo de disparo se convierte en gol el 75%
de las veces.

• npxG (Non-Penalty Expected Goals - Goles Esperados sin Penales): Es la misma métrica de xG, pero
excluye los penales, ya que estos tienen una alta probabilidad de conversión y pueden inflar los valores de
xG de algunos jugadores. Sirve para evaluar mejor la capacidad de un jugador para generar ocasiones de
gol en juego abierto.

• xA (Expected Assists - Asistencias Esperadas): Calcula la probabilidad de que un pase dado por un
jugador termine en gol, considerando factores como la ubicación del receptor, la dirección del pase y la
calidad de la oportunidad generada. Un jugador con un alto xA es alguien que crea muchas oportunidades
de gol para sus compañeros.

• PSxG (Post-Shot Expected Goals - Goles Esperados Post-Disparo): A diferencia del xG tradicional, que se calcula en el momento del disparo, el PSxG evalúa la probabilidad de que un disparo específico se convierta en gol según la ubicación exacta y la calidad del tiro una vez ejecutado (por ejemplo, si va muy colocado al ángulo o directo al portero). De esta forma, mide la dificultad que tiene el guardameta para detener ese remate y permite analizar mejor tanto la calidad de los disparos de un atacante como las atajadas de un portero.

### Instrucciones

FutAlpes F.C. desea que usted los apoye en la construcción del modelo de regresión previamente descrito utilizando algunas de las etapas de la metodología "ASUM-DM":

1. **Entendimiento de los datos:** Describir las características más relevantes de los datos y todo el perfilamiento de datos, incluir el análisis de calidad de datos y hacer una preselección de las variables más importantes para la etapa de modelado.

2. **Preparación de datos:** Solucionar los problemas de calidad de datos previamente identificados que afecten el modelo a construir. Además, debe aplicar todos los proceso de preprocesamiento de datos necesarios para la construcción del modelo de regresión.

3. **Modelado:** Utilizando las variables previamente seleccionadas, construir un modelo de regresión que estime la variable objetivo con el menor error posible.

4. **Evaluación cuantitativa:** A partir de las métricas seleccionadas para evaluar y seleccionar el mejor modelo, explicar el resultado obtenido desde el punto de vista cuantitativo. Contestar a la pregunta: ¿Su equipo recomienda utilizar en producción el modelo de regresión para estimar el precio de un jugador de fútbol? ¿Por qué? En caso de no recomendar el uso del modelo, ¿qué recomendaciones haría para continuar iterando con el objetivo de la construcción de un mejor modelo?

5. **Evaluación cualitativa:** Debe estar compuesta de dos partes:

      **- Validación de supuestos:** Realizar los ajustes necesarios para que el modelo cumpla con los supuestos necesarios para la inferencia estadística con regresiones.

      **- Interpretación de los coeficientes:** Realizar la interpretación de los coeficientes de la regresión, identificando las variables más relevantes para la estimación y cómo afectan la variable objetivo.

6. **Presentación de los resultados:** Presentar en una breve diapositiva los resultados obtenidos con el modelo de regresión, justificando si este puede contribuir al cumplimiento del objetivo de la organización y qué decisiones se recomienda tomar a partir de dichos resultados.

7. Exportar el mejor modelo (utilizando pipelines) para poder ser usado sobre datos nuevos en el ambiente de producción del cliente.

8. Generar predicciones sobre los datos de prueba que no se encuentran etiquetados utilizando el mejor modelo. Exportar las predicciones en formato CSV utlizando como base el mismo archivo de datos de prueba.

### Construcción de pipelines

Para realizar esta sección se recomienda utilizar JupyterLab para la construcción del Pipeline y la exportación del modelo. 

El objetivo de crear un [pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html) es automatizar todos los 
pasos realizados sobre los datos, desde que salen de su fuente hasta que son ingresados al modelo de aprendizaje automático. 
Para un problema clásico, estos pasos incluyen: la selección de características o columnas, la imputación de valores no existentes, la codificación de variables categóricas utilizando diferentes técnicas como Label Encoding o One Hot Encoding, el escalamiento de variables numéricas en caso de ser necesario y en general las diferentes tareas de transformación requeridas para la preparación de los datos. Además, como último paso, el pipeline contiene el modelo que recibe los datos después de la tranformación para realizar predicciones. Finalmente, estos pipelines pueden resultar muy útiles a la hora de calibrar y comparar modelos, pues se tiene la certeza de que los datos de entrada son los mismos para todos. Incluso, pueden ser utilizados para realizar validación cruzada utilizando GridSerchCV o RandomizedSerchCV. Así mismo, pueden ser exportados para llevar los modelos a producción por medio de la serialización de estos en archivos .pkl o .joblib. 

La librería Scikit-Learn cuenta con API para la creación de pipelines en la que pueden ser utilizados diferentes pasos para la transformación de los datos que serán aplicados secuencialmente. Note que estos pasos implementan los métodos **fit** y **transform** para ser invocados desde el pipeline. Por otro lado, los modelos que serán la parte final del proceso de automatización solo cuentan con método fit. Una vez construido el modelo es posible serializar este, haciendo uso de la función **dump** de la librería joblib, para posteriormente deserializar, cargar (mediante la función **load**) y utilizar el modelo en cualquier otra aplicación o ambiente. Tenga en cuenta que la serialización de un modelo solo incluye la estructura y configuraciones realizadas sobre el pipeline, más no las instancias de los objetos que lo componen. Pues estos son provistos por la librería, por medio de la importación, en cualquiera que sea su ambiente de ejecución. Esto significa que si usted construye transformaciones personalizadas, debe incluir por separado estas, en el ambiente donde cargará y ejecutará el modelo una vez sea exportado, ya que estas no están incluidas en la serialización. 

En este punto, debe construir un pipeline que incluya todos los pasos necesarios para transformar los datos desde el archivo fuente y que estos puedan ser utilizados para realizar predicciones.

A continuación puede encontrar algunos artículos que pueden ser de utilidad para la construcción de pipelines
<br>
<br>
[Scikit-learn Pipeline Tutorial with Parameter Tuning and Cross-Validation](https://towardsdatascience.com/scikit-learn-pipeline-tutorial-with-parameter-tuning-and-cross-validation-e5b8280c01fb)
<br>
[Data Science Quick Tip #003: Using Scikit-Learn Pipelines!](https://towardsdatascience.com/data-science-quick-tip-003-using-scikit-learn-pipelines-66f652f26954)
<br>
[Data Science Quick Tip #004: Using Custom Transformers in Scikit-Learn Pipelines!](https://towardsdatascience.com/data-science-quick-tip-004-using-custom-transformers-in-scikit-learn-pipelines-89c28c72f22a)
<br>
[Creating custom scikit-learn Transformers](https://www.andrewvillazon.com/custom-scikit-learn-transformers/)

## <a name="entregables"></a> Entregables

* Informe del laboratorio, que puede ser el mismo notebook, con el desarrollo, análisis respetivo y la evidencia de las etapas del 1 al 5. Deben indicar los nombres de los estudiantes asociados al estudiante 1, 2 y 3 para calcular la nota individual.
* Presentación de diapositivas con los resultados para FutAlpes F.C.
* Notebook con todo el código fuente **ejecutado**.
* Modelo integrado con pipelines exportado en formato .joblib.
* Archivo de predicciones en formato CSV utilizando como base el mismo archivo de datos de prueba.
	
Se espera que el informe incluya **JUSTIFICACIONES** de las decisiones tomadas durante la construcción e interpretación de los modelos.

## Instrucciones de Entrega
- El laboratorio se entrega en grupos de mínimo 2 y máximo 3 estudiantes.
- Recuerde hacer la entrega por la sección unificada en Bloque Neón, antes del sábado 30 de Agosto a las 20:00. Este será el único medio por el cual se recibirán entregas.
- No olvide indicar en el informe los aportes realizados por cada uno de los integrantes del grupo, según la propuesta hecha en la rúbrica.

## <a name="rubrica"></a> Rúbrica de Calificación

A continuación se encuentra la rúbrica de calificación:

| Concepto | Porcentaje |
|:---|:---:|
| 1. Descripción del entendimiento de datos  | 10% |
| 2. Descripción del proceso de selección de variables | 5% |
| 3. **Estudiante 3:** Descripción e implementación del proceso de preparación de datos (incluye la limpieza de datos) | 15% |
| 4. **Estudiante 1:** Construcción del modelo de regresión lineal y cálculo de sus métricas de calidad  | 10% |
| 5. **Estudiante 1:** Implementación del pipeline con todas las transformaciones requeridas para la generación de predicciones, exportado en formato .joblib | 15% |
| 6. **Estudiante 2:** Exploración y conclusión sobre los supuestos de la regresión a partir del modelo construido | 10% |
| 7. **Estudiante 2:** Desarrollo de las transformaciones complementarias para cumplir con los supuestos de la regresión e interpretación de los coeficientes del modelo | 15% |
| 8. **Estudiante 3:** Presentación de diapositivas para  FutAlpes F.C con resultados a nivel cuantitativo y cualitativo del mejor modelo construido, recomendaciones dadas a la empresa y visualizaciones extraidas del notebook | 10% |
| 9. Archivo  y resultado de predicciones sobre los datos de prueba en formato CSV. Se tomará como base el RMSE para ordenar y asignar la nota del grupo. | 5% |
| 10. Notebook ejecutado, que incluye el detalle de los nombres de los estudiantes que representan el estudiante 1, 2 y 3. | 5% |
