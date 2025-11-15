





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

Los objetivos del estudio “Modelo Predictivo Basado en Síntomas para el diagnóstico de cáncer colorrectal: Optimización según las directrices de la política pública de salud chilena” son:

1. Analizar las variables vinculadas al diagnóstico de cáncer colorrectal (CRC), incluyendo aquellas establecidas en las guías de Garantías Explícitas en Salud (GES) y otras de interés clínico.

2. Desarrollar un modelo predictivo basado en síntomas para mejorar el diagnóstico de CRC en pacientes derivados para colonoscopía según las directrices GES en Chile.

3. Optimizar la priorización de colonoscopías para mejorar la detección temprana de CRC, reduciendo el número de procedimientos innecesarios y haciendo un uso más eficiente de los recursos sanitarios.

El estudio realiza un análisis retrospectivo de pacientes derivados para colonoscopía entre 2016 y 2021, empleando regresión logística binaria y análisis ROC para identificar las variables más significativas en la predicción de CRC y construir el modelo.
<div style="page-break-after: always;"></div>

---
# Descripción de la Aplicación
