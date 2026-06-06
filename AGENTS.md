# AGENTS - Awesome List Prompts ChatGPT Educación

## Descripción del proyecto

Awesome list de prompts para ChatGPT enfocados en educación. Organizado por niveles educativos del sistema español: ESO, Bachillerato, Ciclos Formativos (CFGM/CFGS) y Certificaciones Profesionales.

## Estructura del proyecto

```
/
├── general/               # Prompts transversales
│   ├── alumnado/          #   Para estudiantes
│   ├── profesorado/       #   Para docentes
│   └── oposiciones/       #   Para preparación de oposiciones
├── eso/                   # Educación Secundaria Obligatoria
│   ├── primero/
│   ├── segundo/
│   ├── tercero/
│   └── cuarto/
├── bachillerato/          # Bachillerato
│   ├── primero/
│   └── segundo/
├── cfgm/                  # Ciclos Formativos Grado Medio
│   └── smr/               #   Sistemas Microinformáticos y Redes
├── cfgs/                  # Ciclos Formativos Grado Superior
│   └── dam/               #   Desarrollo de Aplicaciones Multiplataforma
├── certificaciones/       # Certificaciones profesionales
│   └── informatica/
├── README.md              # Índice principal
├── template-prompts.md    # Plantilla para nuevos prompts
└── AGENTS.md              # Este archivo
```

## Convenciones

- Cada asignatura/módulo tiene su propia carpeta con un `prompts.md`
- La ruta dentro de cada categoría sigue: `nivel/curso/asignatura/prompts.md`
- Cada `prompts.md` tiene un índice al inicio con enlaces a cada prompt
- Todos los prompts usan el formato de bloque de código con triple backtick
- La licencia y autores se incluyen al final de cada archivo

## Cómo ampliar el proyecto

### Añadir una nueva asignatura/módulo

1. Crear la carpeta siguiendo la estructura: `nivel/curso/asignatura/`
2. Crear `prompts.md` basado en `template-prompts.md`
3. Añadir el enlace en `README.md` en la sección correspondiente

### Añadir nuevos prompts a una asignatura existente

1. Editar el `prompts.md` de la asignatura
2. Añadir entrada en el índice (lista de contenido)
3. Añadir el bloque del prompt con su anchor `#promptXX`
4. Numerar correlativamente (prompt01, prompt02...)

### Estilo recomendado para prompts

- Usar "Actúa como..." al inicio
- Incluir sistema educativo de referencia (español)
- Definir claramente el rol, la tarea y el formato de respuesta
- Incluir instrucciones de interacción (esperar respuesta, correcciones, /PISTA, /S para estadísticas)

## Skills para agents

### skill-nuevo-prompt
Útil cuando se pide crear un nuevo prompt para una asignatura. Seguir la plantilla de `template-prompts.md` manteniendo coherencia con los prompts existentes.

### skill-nueva-asignatura
Útil cuando se pide añadir una asignatura completa. Crear la carpeta, el archivo prompts.md con al menos 2 prompts, y actualizar README.md.

### skill-ampliar-existente
Útil cuando se pide añadir más prompts a una asignatura que ya existe. Leer el archivo existente, añadir nuevos prompts numerados y actualizar el índice.

## Stack técnico

- Markdown (.md) para todo el contenido
- Sin dependencias ni build system
- Despliegue: repositorio GitHub
