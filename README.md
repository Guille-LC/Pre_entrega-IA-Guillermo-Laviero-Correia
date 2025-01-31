# Pre_entrega-IA-Guillermo-Laviero-Correia

# Introduccion

## Presentacion del problema a abordar
El acceso a información clara y precisa sobre teoría política es fundamental para el estudio y la comprensión de los sistemas de gobierno, ideologías y pensamientos filosóficos. Sin embargo, muchas fuentes presentan información fragmentada, sesgada o difícil de interpretar, lo que dificulta el aprendizaje y la toma de decisiones informadas.

## Solucion:
Esta IA permite obtener respuestas inmediatas y estructuradas sobre temas políticos sin necesidad de buscar en múltiples fuentes. Facilita la comprensión de términos complejos, ayuda a contrastar ideas y brinda acceso a información organizada, permitiendo un aprendizaje más eficiente y accesible.

## Justificación de la viabilidad del proyecto
Una IA de politología resuelve este problema al ofrecer respuestas directas y estructuradas sobre teoría política, eliminando la necesidad de navegar entre múltiples fuentes. Su implementación es viable gracias a los avances en procesamiento de lenguaje natural, que permiten generar explicaciones precisas y accesibles para usuarios de diferentes niveles de conocimiento.

# Objetivos del proyecto
- Brindar respuestas precisas y accesibles sobre teoría política, evitando la desinformación y la complejidad innecesaria.
- Facilitar el aprendizaje autodidacta, ofreciendo una fuente confiable para estudiantes, académicos y cualquier persona interesada en política.
- Estandarizar la información, asegurando que los conceptos y teorías sean explicados de manera clara y sin sesgos.
- Optimizar el acceso al conocimiento, reduciendo el tiempo de búsqueda y permitiendo obtener información estructurada de forma inmediata.
- Promover el pensamiento crítico, proporcionando explicaciones que ayuden a los usuarios a analizar y comprender diferentes perspectivas políticas.

# Metodologia
El proyecto se llevará a cabo mediante el desarrollo de un Jupyter Notebook, donde se implementará un sistema de respuesta automatizada basado en teoría política. Se trabajará con un enfoque estructurado para garantizar que la información proporcionada sea clara, precisa y relevante para los usuarios.
### Recopilación y organización de la información:
- Se utilizarán fuentes confiables de teoría política para estructurar un conjunto de respuestas a preguntas frecuentes.
- Se organizará la información en secciones temáticas para facilitar su acceso y comprensión.
### Implementación de un sistema de consulta:
- Se diseñará un mecanismo para que el usuario pueda ingresar preguntas en el notebook.
- Se establecerá un método estructurado para devolver respuestas coherentes y bien fundamentadas.
### Interfaz de interacción en Jupyter Notebook:
- Se crearán celdas interactivas que permitan la consulta y visualización clara de las respuestas.
- Se crearán celdas interactivas que permitan la consulta y visualización clara de las respuestas.
### Evaluación y validación:
- Se realizarán pruebas con preguntas variadas para garantizar que las respuestas sean precisas y comprensibles.
- Se revisará el contenido para asegurar que esté correctamente estructurado y libre de ambigüedades.

# Herramientas
### Para el desarrollo del proyecto en Jupyter Notebook, se empleará un sistema basado en preguntas y respuestas estructuradas. Se utilizarán diferentes técnicas de prompting para optimizar la generación de respuestas y garantizar que la información sea clara, precisa y relevante.
- Prompting Directo: Se formularán preguntas de manera clara y específica para obtener respuestas concisas y enfocadas.
- Ejemplo: "¿Qué es la separación de poderes según Montesquieu?" en lugar de "Explícame sobre Montesquieu".
- Prompting Contextual: Se estructurarán respuestas con información relevante antes de formular una pregunta, asegurando que el modelo comprenda el contexto.
- Ejemplo: "La democracia representativa se basa en la elección de representantes. ¿Cuál es la diferencia entre esta y la democracia directa?".
- Few-shot Prompting: Se proporcionarán ejemplos previos para que el modelo genere respuestas en un formato específico.
- Ejemplo 1: "¿Qué es el liberalismo?" → "El liberalismo es una corriente política y económica que defiende..."
- Ejemplo 2: "¿Qué es el socialismo?" → "El socialismo es una ideología que busca..." Luego, al preguntar "¿Qué es el anarquismo?", se espera que la IA siga el mismo formato.
