# LaAutopsIA - Open Datasets Hub by ApisDom

Repositorio público indexador de los conjuntos de datos abiertos del observatorio LaAutopsIA. Este nodo sirve como puntero técnico y centraliza el acceso a las plataformas oficiales de distribución, análisis y preservación de los corpus de datos sobre Inteligencia Artificial en español.

## Canales Oficiales de Distribución

* [Acceder al Dataset en Hugging Face](https://huggingface.co/apisdom)
  Para integración directa en entornos de ejecución, modelos LLM y pipelines de desarrollo con Python.

* [Explorar el Dataset en Kaggle](https://www.kaggle.com/apisdom)
  Para análisis de datos, evaluaciones estadísticas, notebooks de ejecución y uso de la comunidad de Google.

* [Citar Snapshot Científico en Zenodo](https://zenodo.org)
  Para referencias académicas, de auditoría técnica y descarga de los snapshots históricos inmutables con registro DOI.

## Taxonomía y Estructura del Proyecto

El ecosistema de datos está diseñado bajo una arquitectura de alta disponibilidad y se divide en tres corpus estructurados de forma nativa en formatos JSON y CSV:

1. Índice de Benchmarks: Evaluaciones analíticas de fiabilidad en modelos de lenguaje.
2. Registro de Incidentes: Base de datos estructurada de fallos, alucinaciones y errores reportados en entornos de producción.
3. Repositorio de Vulnerabilidades: Alertas técnicas de seguridad y debilidades explotables en sistemas inteligentes.

## Estándar de Validación de Datos

Antes de cada compilación y volcado mensual en las plataformas de distribución, el backend de la plataforma ejecuta de manera automatizada una suite estricta de procesos de verificación de calidad en memoria para garantizar la integridad absoluta de la información:

* Control estricto de tipos de datos y eliminación de residuos.
* Consecución de consistencia de registros entre snapshots JSON y estructuras CSV.
* Sanitización UTF-8 e inmutabilidad de los identificadores de auditoría.
