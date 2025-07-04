# Project Charter - Entendimiento del Negocio

## Nombre del Proyecto
Proyecto_FakeNews

## Objetivo
Desplegar en producción un modelo de NLP que permita clasificar automáticamente noticias como reales o falsas con base en su contenido textual.

## Trasfondo del Negocio
El presente proyecto está dirigido principalmente a entidades que enfrentan los desafíos de la desinformación digital, como lo son las plataformas de redes sociales, medios de comunicación, agencias de noticias, organizaciones de verificación de datos (fact-checking), y gobiernos. Estas entidades son los principales beneficiarios de una solución automatizada que permita identificar y clasificar contenido informativo como verdadero o falso.

El dominio del proyecto se ubica en el ámbito del periodismo digital, la tecnología de la información y la seguridad informativa, con un enfoque particular en el análisis de contenido textual. Dado el impacto social y político que puede tener la difusión de noticias falsas, este proyecto también puede ser de utilidad para organizaciones que promuevan la alfabetización mediática y la protección de la información veraz en entornos digitales.

El proyecto busca abordar el creciente problema de la difusión masiva de noticias falsas a través de medios digitales, un fenómeno que ha generado desinformación, polarización social, y pérdida de confianza en las fuentes de información. En la actualidad, millones de usuarios consumen contenido en línea sin filtros ni verificación, lo que permite que noticias engañosas se propaguen rápidamente y tengan un impacto significativo en la opinión pública, procesos electorales, decisiones de salud, y otros aspectos críticos de la sociedad.

Desde la perspectiva del negocio y del dominio, se pretende desplegar una solución basada en técnicas de procesamiento de lenguaje natural (NLP) probada que permite clasificar de forma eficiente noticias como verdaderas o falsas. Este proyecto contempla el despliegue en una interfaz de uso fácil un identificador de noticias falsas a través de su url.

## Dominio del Proyecto
Periodismo digital, seguridad informativa, alfabetización mediática y tecnología de la información.



## Alcance
La solución propuesta consiste en implementar un modelo de clasificación de texto utilizando técnicas de procesamiento de lenguaje natural (NLP), orientado a identificar si una noticia es falsa o verdadera. Esto se logrará mediante un enfoque supervisado, entrenando un modelo de machine learning sobre un conjunto de noticias previamente etiquetadas.

El proceso incluirá técnicas de preprocesamiento textual como limpieza, tokenización y vectorización. Posteriormente, se aplicarán algoritmos como regresión logística con TF-IDF, random forests o modelos más avanzados basados en redes neuronales profundas. Además, se utilizarán representaciones vectoriales del texto mediante embeddings para capturar el significado semántico.

El modelo resultante podrá ser integrado por el cliente en plataformas existentes, como sistemas de moderación de contenido, generación de reportes sobre la calidad informativa, o iniciativas educativas para ayudar a los usuarios a identificar noticias falsas.

## Metodología
Enfoque TDSP: desde la comprensión del negocio hasta la evaluación y despliegue. Uso de algoritmos como Naive Bayes, Logistic Regression y redes neuronales.

## Cronograma

| Etapa                                           | Duración estimada | Fechas                     |
|------------------------------------------------|-------------------|----------------------------|
| Entendimiento del negocio y carga de datos     | 2 semanas         | 1 de julio - 15 de julio   |
| Preprocesamiento y análisis exploratorio       | 4 semanas         | 16 de julio - 15 de agosto |
| Modelamiento y extracción de características   | 4 semanas         | 16 de agosto - 15 de sept. |
| Despliegue                                     | 2 semanas         | 16 de sept. - 30 de sept.  |
| Evaluación y entrega final                     | 3 semanas         | 1 de oct. - 21 de oct.     |

## Equipo del Proyecto
- John Mendoza – Analista de datos y líder del proyecto
- Edison Molano – Analista de datos y líder del proyecto
- Luis Cardon – Analista de datos y líder del proyecto

## Presupuesto
Sin costo. Herramientas de código abierto y Google Colab

## Partes interesadas
- Plataformas sociales, fact-checkers, gobiernos, medios y ONGs

## Aprobaciones
- John Mendoza – Responsable del proyecto
- Fecha: 3 de julio de 2025
