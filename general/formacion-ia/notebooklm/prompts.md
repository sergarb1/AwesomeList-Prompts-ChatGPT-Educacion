<div align="center">
# Prompts — NotebookLM de Google — Tutorial para docentes![Logo](../../../logo.png)
</div>
Basado en la charla "NotebookLM de Google · tutorial para docentes" de [Formación IA para Docentes](https://sergarb1.github.io/FormacionIADocentes/note-booklm-google.html) por Sergi García Barea.

## Contenido
- [Prompt 01 — Resumir un documento académico](#prompt01)
- [Prompt 02 — Generar una guía de estudio](#prompt02)
- [Prompt 03 — Preguntas tipo test sobre un texto](#prompt03)
- [Prompt 04 — Crear un podcast educativo (Audio Overview)](#prompt04)
- [Prompt 05 — Extraer ideas clave y conexiones](#prompt05)
- [Prompt 06 — Preparar materiales para una unidad didáctica](#prompt06)
- [Prompt 07 — Glosario de términos a partir de documentos](#prompt07)
- [Prompt 08 — FAQ automático sobre un tema](#prompt08)

## Prompts
## <a name="prompt01"></a> Prompt 01 — Resumir un documento académico
```
Actúa como un asistente de investigación educativa.
He subido un documento [PDF, artículo, texto] a NotebookLM sobre [tema].
Quiero que generes un resumen estructurado que incluya:
1. Idea principal del documento (máximo 2 líneas).
2. 3-5 ideas secundarias clave con su explicación breve.
3. Datos o cifras relevantes extraídos del texto.
4. Términos clave con definiciones sacadas del documento.
5. Conclusiones del autor.

Máximo 300 palabras. El resumen debe ser fiel al contenido del documento, sin añadir información externa.
```

## <a name="prompt02"></a> Prompt 02 — Generar una guía de estudio
```
Actúa como un preparador de materiales educativos.
Basándote en los documentos que he subido a NotebookLM sobre [tema/módulo/asignatura], crea una guía de estudio para alumnos de [curso] que incluya:
1. Un esquema general del tema con los puntos principales.
2. Preguntas de repaso (10) con sus respuestas basadas en los documentos.
3. Ejercicios prácticos (3) para aplicar los conceptos.
4. Conexiones entre los diferentes documentos subidos.
5. Recomendaciones sobre qué secciones leer primero.

La guía debe estar basada exclusivamente en las fuentes proporcionadas.
```

## <a name="prompt03"></a> Prompt 03 — Preguntas tipo test sobre un texto
```
Actúa como un generador de exámenes basados en documentos.
He subido [documentos sobre tema] a NotebookLM. Con base en ellos, genera:
- 15 preguntas tipo test con 4 opciones cada una.
- 5 preguntas de verdadero/falso con justificación.
- 3 preguntas de desarrollo corto.

Para cada pregunta, indica el número de página o sección del documento donde se encuentra la respuesta.
Incluye una plantilla de soluciones al final.
```

## <a name="prompt04"></a> Prompt 04 — Crear un podcast educativo (Audio Overview)
```
Actúa como un productor de contenido educativo multimedia.
He subido varios documentos sobre [tema] a NotebookLM y quiero generar un Audio Overview (podcast automático) para mis alumnos.

Dame un guión estructurado para el podcast que incluya:
1. Introducción (30 seg): presentación del tema y por qué es importante.
2. Desarrollo (3-4 min): puntos clave extraídos de los documentos, con ejemplos concretos.
3. Preguntas y respuestas simuladas (1 min): una conversación entre dos voces (presentador y experto).
4. Conclusión (30 seg): resumen y aplicación práctica.

Indica qué documentos debo subir a NotebookLM para obtener la mejor cobertura del tema.
```

## <a name="prompt05"></a> Prompt 05 — Extraer ideas clave y conexiones
```
Actúa como un analizador de contenido educativo.
He subido varios documentos a NotebookLM sobre [tema general, ej: "cambio climático" o "segunda guerra mundial"].

Analiza los documentos y genera:
1. Las 10 ideas principales que aparecen de forma transversal en los documentos.
2. Conexiones entre ideas de diferentes documentos (ej: "El documento A dice X que se relaciona con Y del documento B").
3. Contradicciones o puntos de vista divergentes entre las fuentes (si los hay).
4. Lagunas o aspectos importantes que no se cubren en las fuentes.
5. Una frase que resuma la visión global de todas las fuentes juntas.
```

## <a name="prompt06"></a> Prompt 06 — Preparar materiales para una unidad didáctica
```
Actúa como un diseñador curricular.
He subido a NotebookLM varios documentos (ley educativa, currículo oficial, libro de texto, artículos) sobre [asignatura/curso].

Con base en estas fuentes, ayúdame a preparar una unidad didáctica sobre [tema concreto] que incluya:
1. Objetivos didácticos (basados en el currículo oficial).
2. Contenidos estructurados en sesiones (6 sesiones).
3. Actividades de enseñanza-aprendizaje para cada sesión.
4. Criterios e instrumentos de evaluación.
5. Recursos y materiales necesarios (incluyendo los propios documentos subidos).
6. Medidas de atención a la diversidad.

Cita las fuentes específicas (documento y sección) de donde extraes cada elemento.
```

## <a name="prompt07"></a> Prompt 07 — Glosario de términos a partir de documentos
```
Actúa como un lexicógrafo educativo.
He subido documentos sobre [tema/asignatura] a NotebookLM.
Basándote en el contenido de los documentos, crea un glosario de términos que incluya:
1. Lista alfabética de términos clave (mínimo 20).
2. Definición breve de cada término (máximo 2 líneas).
3. Contexto de uso (ejemplo de frase extraída del documento).
4. Sinónimos o términos relacionados.
5. Referencia al documento fuente (título y página/sección).
6. Nivel de dificultad del término (básico, intermedio, avanzado).

Formato: tabla de 4 columnas (Término, Definición, Ejemplo, Fuente).
```

## <a name="prompt08"></a> Prompt 08 — FAQ automático sobre un tema
```
Actúa como un asistente de atención educativa.
He subido documentos sobre [tema: una asignatura completa, un procedimiento administrativo, un tema transversal] a NotebookLM.

Genera un documento de preguntas frecuentes (FAQ) basado en el contenido que incluya:
1. 15-20 preguntas que los alumnos suelen hacer sobre este tema.
2. Respuestas claras y concisas basadas en los documentos (máximo 3 líneas por respuesta).
3. Agrupación por categorías (conceptos básicos, aplicación, evaluación, etc.).
4. Para cada respuesta, indica en qué documento y sección basarse para ampliar.

Las preguntas deben reflejar dudas reales que tendría un estudiante de [curso/nivel].
```

### Licencia y autores
CC BY-SA 3.0 ES. Basado en [Formación IA para Docentes](https://sergarb1.github.io/FormacionIADocentes/note-booklm-google.html) por Sergi García Barea.
