





Universidad Nacional Andres Bello
Magister Ingeniería Informática
**Participantes:**
- Eric Silva
- Brian Guzmán





---
<div style="page-break-after: always;"></div>

# Introducción
El cáncer colorrectal (CRC) constituye uno de los principales desafíos en salud pública a nivel mundial, con una incidencia y mortalidad que han venido en aumento constante en las últimas décadas. Este tipo de cáncer afecta significativamente la calidad de vida de los pacientes y representa una carga considerable para los sistemas de salud, particularmente en países como Chile, donde las políticas públicas buscan implementar estrategias más eficaces para su detección y tratamiento. En este contexto, la detección temprana del CRC es fundamental para mejorar las tasas de supervivencia y optimizar los recursos disponibles.

El presente informe se fundamenta en el estudio realizado por Benavides et al. (2025), que propone un modelo predictivo basado en síntomas específicos para el diagnóstico temprano del cáncer colorrectal. Este modelo está diseñado conforme a las directrices de la política pública chilena, específicamente en el marco de las Garantías Explícitas en Salud (GES), que establecen la derivación rápida y prioritaria de pacientes con sospechas clínicas para la realización de colonoscopías en centros hospitalarios especializados. La importancia de este modelo radica en su capacidad para mejorar la priorización y eficiencia de las colonoscopías, procedimientos que, aunque imprescindibles para el diagnóstico, implican altos costos y limitaciones logísticas cuando se aplican masivamente.

El estudio destaca el uso de técnicas de ciencia de datos, tales como regresión logística y análisis ROC, para identificar las variables clínicas más relevantes que permiten predecir con mayor exactitud la presencia de cáncer colorrectal en pacientes sintomáticos. El desarrollo de este modelo predictivo no solo permite optimizar la asignación de recursos médicos, sino que también puede contribuir a disminuir tiempos de espera y mejorar el diagnóstico oportuno.

La evaluación y construcción del modelo se basa en un análisis de datos clínicos retrospectivos, lo que garantiza que las predicciones se apoyen en evidencia empírica y que respondan a las necesidades específicas del sistema de salud chileno. Este enfoque integral, que combina la investigación médica con herramientas avanzadas de ciencia de datos, representa un avance significativo hacia la incorporación de soluciones tecnológicas para la mejora del diagnóstico en salud pública.

En resumen, este informe tiene como objetivo analizar detalladamente el modelo predictivo basado en síntomas propuesto en el estudio, evaluando su metodología, resultados y potencial impacto en el sistema de salud. De esta manera, se busca contribuir a la comprensión y difusión de aplicaciones prácticas de la ciencia de datos en el ámbito sanitario, promoviendo estrategias que faciliten la detección temprana de enfermedades críticas como el cáncer colorrectal.
<div style="page-break-after: always;"></div>

---
# Objetivos
## Objetivo General
Desarrollar y validar un modelo predictivo basado en síntomas clínicos para el diagnostico temprano del cáncer colorrectal en pacientes derivados para colonoscopía, optimizando la priorización de procedimientos según las directrices de la política pública en salud.

## Objetivos Específicos
1. Identificar y analizar las variables clínicas y sintomáticas más relevantes asociadas al diagnóstico de cáncer colorrectal en pacientes derivados para colonoscopía bajo el marco de las Garantías Explícitas en Salud (GES).
2. Aplicar técnicas estadísticas y de ciencia de datos, incluyendo regresión logística y análisis ROC, para construir un modelo predictivo que permita estimar el riesgo de cáncer colorrectal en función de dichos síntomas.
3. Evaluar el rendimiento y la capacidad predictiva del modelo a través de métricas estadísticas como sensibilidad, especificidad, valor predictivo positivo y valor predictivo negativo.
4. Proponer recomendaciones para la implementación del modelo predictivo dentro del sistema público de salud, con el fin de optimizar la asignación de recursos médicos, mejorar la priorización de colonoscopías y contribuir a la detección temprana y el manejo oportuno del cáncer colorrectal.
<div style="page-break-after: always;"></div>
---
# Descripción de la Aplicación específica
## Breve explicación del problema o situación
El estudio aborda el problema del diagnóstico temprano del cáncer colorrectal (CRC), una enfermedad con alta incidencia y mortalidad que representa un desafío significativo para los sistemas de salud. En particular, se enfoca en la dificultad para priorizar adecuadamente a los pacientes sintomáticos que requieren colonoscopía para confirmar la presencia de CRC, dado que estos procedimientos son costosos y con capacidad limitada. La falta de herramientas predictivas precisas basada en síntomas clínicos dificulta la optimización de recursos y puede retrasar la detección oportuna, afectando la efectividad del tratamiento y la supervivencia de los pacientes. Por ello, el estudio busca desarrollar un modelo predictivo que permita mejorar la priorización y diagnóstico temprano en el marco de las políticas públicas de salud.

## Técnicas o métodos específicos de Ciencia de Datos aplicados
El estudio utiliza principalmente técnicas estadísticas y de modelado predictivo para construir un modelo capaz de diagnosticar cáncer colorrectal a partir de síntomas reportados. En particular, se emplea la **regresión logística binaria** para identificar las variables clínicas y sintomáticas que tienen mayor poder predictivo. Esta técnica permite estimar la probabilidad de presencia de la enfermedad en función de múltiples variables independientes.

Además, para evaluar la capacidad discriminativa del modelo, se realiza un análisis **ROC (Receiver Operating Characteristic)**, que mide la sensibilidad y especificidad del modelo a diferentes umbrales de decisión, facilitando la selección del umbral óptimo para la predicción.

Complementariamente, el estudio calcula métricas de rendimiento clínico como sensibilidad, especificidad, valor predictivo positivo y valor predictivo negativo para cada variable significativa, lo que ayuda a interpretar la utilidad práctica del modelo en el contexto médico.

## Resultados obtenidos o beneficios esperados del problema que se abordó en la investigación seleccionada


# Discusión crítica
## Ventajas y beneficios observados de la aplicación.
## Limitaciones y dificultades identificadas
## Propuestas de mejora o futuros desarrollos

# Discusión crítica
## Ventajas y beneficios observados de la aplicación
## Limitaciones y dificultades identificadas
## Propuestas de mejora o futuros desarrollos
# Conclusiones
# Referencia bibliográfica
- Benavides, C., & Alvarado, J. (2025). Modelo predictivo basado en síntomas para el diagnóstico de cáncer colorrectal: Optimización según las directrices de la política pública de salud chilena. _Revista Médica De Chile_, _153_(03). Recuperado a partir de https://revistamedicadechile.cl/index.php/rmedica/article/view/10992
- WHO. Colorectal cancer – IARC. [citado en May 14, 2023]. Recuperado a partir de: https://www.iarc.who.int/cancer-type/colorectal-cancer/
- Colorectal cancer trends in Chile: A Latin-American country with marked socioeconomic inequities PLOS ONE. [citado en May 14, 2023]. Recuperado a partir de: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0271929
- Cancer today. [citado en August 9, 2022]. Recuperado a partir de: http://gco.iarc.fr/today/home
- Colorectal Cancer Awareness Month 2021–IARC. [citado en September 29, 2021]. Recuperado a partir de: https://www.iarc.who.int/featured-news/ccam2021/.