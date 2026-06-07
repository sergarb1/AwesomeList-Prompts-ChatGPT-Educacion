<div align="center">
# Prompts — Asistentes de código con IA para docentes![Logo](../../../logo.png)
</div>
Basado en la charla "Asistentes de código con IA para docentes" de [Formación IA para Docentes](https://sergarb1.github.io/FormacionIADocentes/codigo-cli-ia.html) por Sergi García Barea. Herramientas: OpenCode, Codex CLI, Gemini CLI, Claude Code.

## Contenido
- [Prompt 01 — Generar una circular informativa en HTML](#prompt01)
- [Prompt 02 — Crear un horario de clase semanal](#prompt02)
- [Prompt 03 — Generador de exámenes imprimibles](#prompt03)
- [Prompt 04 — Plantilla de registro de notas](#prompt04)
- [Prompt 05 — Generador de diplomas personalizados](#prompt05)
- [Prompt 06 — Crear un formulario de encuesta para alumnos](#prompt06)
- [Prompt 07 — Página web de recursos del aula](#prompt07)
- [Prompt 08 — Flashcards interactivas en HTML+JS](#prompt08)

## Prompts
## <a name="prompt01"></a> Prompt 01 — Generar una circular informativa en HTML
```
Actúa como un asistente de código que crea materiales educativos.
Genera un documento HTML que sea una circular informativa para enviar a las familias.
La circular debe incluir:
- Encabezado con el nombre del centro y logo (usa un placeholder).
- Título: "Comunicado importante" o similar.
- Fecha y referencia.
- Cuerpo del texto con los siguientes apartados:
  1. Saludo inicial.
  2. Motivo de la comunicación.
  3. Información detallada (usa texto de ejemplo).
  4. Fecha y lugar de eventos si aplica.
  5. Despedida y firma.
- Pie con datos de contacto del centro.

El diseño debe ser limpio, profesional, y listo para imprimir en A4. Usa CSS inline o incrustado.
Genera el archivo HTML completo.
```

## <a name="prompt02"></a> Prompt 02 — Crear un horario de clase semanal
```
Actúa como un asistente de código para docentes.
Genera un archivo HTML que muestre un horario de clase semanal con las siguientes características:
- Una tabla con las horas (de 8:00 a 15:00 en intervalos de 1 hora) y los días (lunes a viernes).
- Cada celda debe permitir escribir la asignatura.
- Colores distintos para cada asignatura (usando clases CSS).
- Una leyenda al pie con el significado de los colores.
- Capacidad de edición: haz que el contenido de las celdas sea editable (contenteditable).
- Botón para imprimir el horario.
- Botón para guardar el horario en localStorage.

El diseño debe ser responsivo y verse bien en móvil y ordenador.
```

## <a name="prompt03"></a> Prompt 03 — Generador de exámenes imprimibles
```
Actúa como un asistente de código educativo.
Crea un generador de exámenes en HTML+JS que permita:
1. Un formulario donde el profesor introduzca:
   - Título del examen.
   - Asignatura.
   - Curso.
   - Número de preguntas (5-15).
2. Al hacer clic en "Generar", se cree un examen con:
   - Encabezado con nombre del centro, asignatura, curso, fecha.
   - Instrucciones generales.
   - Preguntas numeradas con espacio para responder (líneas punteadas).
   - Una puntuación total al final.
3. Cada pregunta debe tener un campo de texto para escribir la pregunta y un selector de puntuación (0.5, 1, 1.5, 2 puntos).
4. Botón de imprimir que oculte el formulario y muestre solo el examen listo para imprimir.

Todo en un solo archivo HTML con CSS y JS incrustados.
```

## <a name="prompt04"></a> Prompt 04 — Plantilla de registro de notas
```
Actúa como un asistente de código para gestión educativa.
Crea una aplicación web simple en HTML+JS para llevar un registro de notas de alumnos:
La aplicación debe permitir:
1. Añadir alumnos (nombre y apellidos).
2. Añadir evaluaciones o exámenes (nombre, fecha, nota máxima).
3. Introducir notas para cada alumno en cada evaluación.
4. Calcular automáticamente:
   - Nota media de cada alumno.
   - Nota media de la clase por evaluación.
   - Porcentaje de aprobados.
5. Mostrar los datos en una tabla dinámica.
6. Botón para exportar a CSV.
7. Botón para resetear todos los datos.
8. Los datos deben persistir usando localStorage.

Diseño responsive, colores suaves, interfaz intuitiva para un profesor no técnico.
```

## <a name="prompt05"></a> Prompt 05 — Generador de diplomas personalizados
```
Actúa como un asistente de código creativo para docentes.
Genera una aplicación HTML+JS que cree diplomas personalizados para alumnos.
Características:
1. Formulario con campos:
   - Nombre del alumno.
   - Curso.
   - Motivo del diploma (ej: "por su excelente trabajo en...", "por completar el curso de...").
   - Fecha.
   - Nombre del profesor.
2. Al hacer clic en "Generar diploma", se muestre un diploma con:
   - Marco decorado con bordes.
   - Título "DIPLOMA" o "CERTIFICADO" en grande.
   - Texto personalizado con los datos introducidos.
   - Línea de firma del profesor.
   - Logo del centro (placeholder).
3. El diseño debe ser elegante, apto para imprimir en A4 apaisado.
4. Botón de imprimir que oculte el formulario.

Todo en un solo archivo HTML con CSS y JS.
```

## <a name="prompt06"></a> Prompt 06 — Crear un formulario de encuesta para alumnos
```
Actúa como un asistente de código para evaluación educativa.
Crea una encuesta interactiva en HTML+JS para obtener feedback de los alumnos después de una unidad didáctica.
La encuesta debe incluir:
1. Preguntas tipo:
   - Escala Likert (1-5) para: claridad, interés, dificultad, utilidad.
   - Pregunta abierta: "¿Qué te ha gustado más?"
   - Pregunta abierta: "¿Qué mejorarías?"
   - Pregunta sí/no: "¿Recomendarías esta unidad a otros compañeros?"
2. Diseño atractivo y adaptado a adolescentes.
3. Al enviar, mostrar un mensaje de agradecimiento animado.
4. Los datos deben guardarse en localStorage y mostrarse en una página de resultados accesible con una contraseña (ej: "profesor").
5. La página de resultados debe mostrar gráficos de barras simples (usando CSS) con las respuestas.

Todo en un único archivo HTML.
```

## <a name="prompt07"></a> Prompt 07 — Página web de recursos del aula
```
Actúa como un asistente de código para creación de sites educativos.
Crea una página web HTML+CSS para servir como centro de recursos de una asignatura.
La página debe tener:
1. Encabezado con nombre de la asignatura y curso.
2. Menú de navegación a secciones: Inicio, Temas, Recursos, Calendario, Contacto.
3. Sección "Temas" con tarjetas para cada unidad didáctica (título, descripción breve, icono).
4. Sección "Recursos" con enlaces clasificados (videos, PDFs, webs, ejercicios interactivos) — usa enlaces de ejemplo.
5. Sección "Calendario" con una tabla de fechas importantes (exámenes, entregas).
6. Pie de página con información del profesor y centro.
7. Diseño responsive con CSS Grid o Flexbox.
8. Un interruptor claro/oscuro (modo oscuro).

Todo en un solo archivo HTML con CSS y JS incrustados.
```

## <a name="prompt08"></a> Prompt 08 — Flashcards interactivas en HTML+JS
```
Actúa como un asistente de código para crear materiales de estudio interactivos.
Crea una aplicación de flashcards (tarjetas de estudio) en HTML+JS para repasar conceptos educativos.
Características:
1. Un conjunto precargado de al menos 10 flashcards sobre [tema: vocabulario, historia, ciencia, etc.].
2. Cada flashcard tiene anverso (pregunta o concepto) y reverso (respuesta o definición).
3. Al hacer clic en la tarjeta, gira y muestra el reverso (animación 3D con CSS).
4. Botones: "Siguiente", "Anterior", "Me lo sé" (marca como revisada), "No me lo sé" (vuelve al final del mazo).
5. Contador de tarjetas revisadas y total.
6. Posibilidad de añadir nuevas tarjetas mediante un formulario.
7. Los datos se guardan en localStorage.

Diseño limpio y centrado en la usabilidad. Toda en un único archivo HTML.
```

### Licencia y autores
CC BY-SA 3.0 ES. Basado en [Formación IA para Docentes](https://sergarb1.github.io/FormacionIADocentes/codigo-cli-ia.html) por Sergi García Barea.
