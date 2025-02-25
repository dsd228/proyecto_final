# proyecto_final.

Proyecto de curso de creación de IA
Predicción Salarial

##Resumen

Este proyecto predice aumentos salariales en función de las horas de estudio de Python. Se basa en un modelo de regresión entrenado con datos simulados.  
Proyecto de curso de creación de IA.
 
![Descripción de la imagen](prediccion_salaria.png.webp)

## Antecedentes

## Descripción del problema

En la era digital actual, mejorar el perfil profesional es una prioridad para muchos, y aprender Python se destaca como una de las mejores vías para lograrlo. No obstante, la falta de claridad sobre cuánto esfuerzo (en términos de horas de estudio) es necesario para alcanzar un aumento salarial significativo crea incertidumbre. Este proyecto aborda esta ambigüedad al analizar la relación entre las horas de estudio de Python y el incremento salarial esperado.

## Motivación personal

Motivado por un profundo interés en el impacto de la tecnología en el desarrollo profesional, mi objetivo es explorar cómo los datos pueden guiar decisiones informadas sobre la educación continua. A través de este proyecto, busco demostrar la importancia de basar las decisiones educativas en evidencia concreta.

## Frecuencia y relevancia del problema

Este proyecto es de gran relevancia para profesionales que desean perfeccionar sus habilidades y para empleados que buscan definir metas de desarrollo profesional claras basadas en el tiempo invertido en estudios. Al proporcionar una comprensión más precisa de la relación entre el esfuerzo educativo y los beneficios salariales, este estudio puede servir como una herramienta valiosa en la planificación de carreras.


## Datos y técnicas de IA - Fuentes de datos
Para este proyecto, utilizaremos datos sobre las horas de estudio de Python y los salarios de desarrolladores de software. En caso de no contar con datos reales, se generará un conjunto de datos simulado que represente la relación entre el tiempo de estudio y el impacto salarial.

Las variables clave incluirán:
- **Horas de estudio**: Tiempo semanal dedicado a aprender Python.
- **Salario inicial y posterior**: Comparación antes y después del estudio.
- **Factores adicionales**: Experiencia laboral, nivel de educación e industria.

![Descripción de la imagen](prediccion_salarial.png.png)


## Técnicas de IA

Métodos de Inteligencia Artificial: Este proyecto empleará técnicas avanzadas de regresión para predecir los aumentos salariales en función del número de horas dedicadas al estudio de Python. Para este propósito, el modelo de regresión lineal se presenta como una opción adecuada dada su simplicidad y eficacia en problemas de predicción continua. Se ajustará un modelo de regresión lineal a los datos para estimar la relación entre las horas de estudio y el salario. Además, se evaluará la precisión del modelo mediante técnicas de validación cruzada y métricas de error como el RMSE (Root Mean Squared Error) para garantizar la fiabilidad de las predicciones.

Desarrollo y Implementación: El proyecto seguirá un enfoque sistemático que incluirá las siguientes etapas:

Recopilación y Preparación de Datos: Obtención y limpieza del conjunto de datos, manejo de valores atípicos y faltantes, y normalización de las variables.

Análisis Exploratorio de Datos: Visualización y análisis preliminar de las variables para identificar patrones y relaciones significativas.

Construcción del Modelo: Selección del modelo de regresión lineal, ajuste a los datos y optimización de parámetros.

Evaluación del Modelo: Validación del modelo utilizando técnicas estadísticas y pruebas de rendimiento.

Interpretación de Resultados: Análisis de los coeficientes del modelo para entender la magnitud del impacto de las horas de estudio en el salario.

Conclusiones y Recomendaciones: Presentación de hallazgos clave y sugerencias prácticas basadas en los resultados del modelo.

## ¿Quién puede beneficiarse de este proyecto?

Este proyecto está diseñado para proporcionar información valiosa a empleados y estudiantes interesados en determinar la cantidad de tiempo que deben dedicar al estudio de Python para lograr un aumento salarial significativo. Es especialmente útil para profesionales de TI, analistas de datos y otros individuos que desean mejorar sus habilidades de programación y avanzar en sus carreras. Al ofrecer una comprensión clara de la relación entre el tiempo de estudio y el incremento salarial, este proyecto puede servir como una guía práctica para aquellos que buscan maximizar el retorno de su inversión en educación continua.

## Casos de uso

Los principales beneficiarios de este proyecto son los profesionales en el campo de la tecnología, incluidos desarrolladores de software, analistas de datos, ingenieros de sistemas y otros especialistas técnicos. Estos usuarios podrán utilizar los resultados del proyecto para medir el impacto de sus horas de estudio de Python en su salario y tomar decisiones informadas sobre su desarrollo profesional. Además, el proyecto puede atraer a estudiantes y recién graduados que buscan orientaciones claras sobre cómo sus esfuerzos educativos pueden traducirse en beneficios económicos tangibles en el mercado laboral.


## Desafíos y Limitaciones del Proyecto.

Este proyecto presenta varias limitaciones que deben considerarse al interpretar los resultados.

En primer lugar, no se incluyen factores como la experiencia laboral previa, la industria o la ubicación geográfica, los cuales pueden influir significativamente en los aumentos salariales.

Además, no se analiza la calidad del aprendizaje. No todas las horas de estudio tienen el mismo impacto, ya que factores como los materiales utilizados o las habilidades previas pueden afectar los resultados.

Otra limitación es que el modelo se basa en regresión lineal, lo que puede no capturar relaciones más complejas entre las variables. Factores no cuantificables, como habilidades interpersonales o políticas internas de las empresas, también influyen en el salario.

Por último, este análisis depende de datos históricos y puede no reflejar cambios recientes en el mercado laboral.

Estas limitaciones resaltan la necesidad de un enfoque más holístico en futuros estudios, incorporando más variables y técnicas avanzadas.

### Consideraciones éticas

Este proyecto maneja datos relacionados con los salarios y el desarrollo profesional, lo que implica consideraciones importantes sobre privacidad y ética en el uso de datos. Para garantizar la protección de la información, se seguirán las siguientes prácticas:

Anonimización de datos: Si se utilizan datos reales, se aplicarán técnicas de anonimización para eliminar cualquier información que pueda identificar a personas específicas.
Consentimiento informado: En caso de recopilar datos directamente de individuos, se solicitará su consentimiento explícito para el uso de su información con fines de investigación.
Fuentes abiertas y conformidad legal: Se dará preferencia a conjuntos de datos públicos que cumplan con regulaciones de privacidad, como el GDPR o la Ley de Protección de Datos Personales.
Uso responsable de los resultados: Los resultados del modelo no deben considerarse como una garantía de aumentos salariales, sino como una herramienta de análisis para la toma de decisiones informadas. Se evitará cualquier uso indebido que pueda llevar a interpretaciones sesgadas o discriminación en procesos de contratación o promoción laboral.

## ¿Qué sigue?

## Mejoras futuras
- Incluir variables adicionales como experiencia laboral, ubicación y nivel educativo.
- Explorar algoritmos avanzados como redes neuronales para mejorar la precisión.
- Recolectar datos reales para validar el modelo con información actualizada.
- Aplicar técnicas de validación más rigurosas y comparativas.


## Agradecimientos

Agradezco a las siguientes fuentes y personas por su apoyo en este proyecto:

1. Fuente de datos: Dataset Example por proporcionar datos bajo la licencia CC BY 2.0.
2. Inspiración y soporte: La comunidad de desarrolladores y entusiastas de la IA por sus ideas y recursos compartidos.
3. Herramientas y código: Las bibliotecas de Python, como Pandas, Scikit-learn y Matplotlib, que facilitaron la implementación y visualización.
4. Asesoramiento y colaboración: Colegas y mentores que contribuyeron con valiosos consejos y revisiones.
