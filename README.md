# Manual de Ajedrez

## Descripción

Este proyecto es un manual interactivo de ajedrez desarrollado con MkDocs y Material for MkDocs. Está diseñado como una guía completa para principiantes y jugadores intermedios que desean aprender o mejorar sus habilidades en el ajedrez.

El manual combina contenido educativo estructurado con elementos interactivos modernos, incluyendo secciones desplegables, cuestionarios, advertencias contextuales y una navegación intuitiva. Todo el contenido está en español y se presenta de manera clara y accesible.

## Contenido del Manual

El manual está organizado en las siguientes secciones:

- **Introducción al Ajedrez**: Conceptos básicos, objetivo del juego y preparación del tablero
- **Movimiento de las Fichas**: Guía detallada de cómo se mueve cada pieza (peón, torre, caballo, alfil, dama y rey), incluyendo valores relativos y consejos tácticos
- **Reglas del Juego**: Normativa oficial, movimientos especiales (enroque, captura al paso, promoción) y condiciones de victoria
- **Historia del Ajedrez**: Evolución del juego desde sus orígenes hasta la era moderna
- **Partidas Legendarias**: Análisis de las partidas más famosas de la historia del ajedrez
- **Enlaces de Interés**: Recursos externos para practicar, aprender y profundizar en el ajedrez

## Características Técnicas

- Desarrollado con **MkDocs** y el tema **Material for MkDocs**
- Diseño responsive y moderno
- Búsqueda integrada en el sitio
- Elementos interactivos: pestañas, acordeones y cuestionarios
- Navegación estructurada por secciones
- Optimizado para lectura en diferentes dispositivos

## Visualizar el Manual

Puedes acceder al manual en línea a través de GitHub Pages:

**[Ver Manual de Ajedrez](https://jlcape02.github.io/Manual_Ajedrez/)**

## Instalación Local

Si deseas ejecutar el manual localmente en tu equipo:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/JLCaPe02/Manual_Ajedrez.git
   cd Manual_Ajedrez
   ```

2. Instala las dependencias (requiere Python y pip):
   ```bash
   pip install mkdocs-material
   ```

3. Inicia el servidor de desarrollo:
   ```bash
   mkdocs serve
   ```

4. Abre tu navegador en `http://127.0.0.1:8000/`

## Estructura del Proyecto

```
Manual_Ajedrez_Mkdocs/
├── docs/               # Archivos de contenido en Markdown
│   ├── index.md       # Página principal
│   ├── fichas.md      # Movimiento de las fichas
│   ├── reglas.md      # Reglas del juego
│   ├── historia.md    # Historia del ajedrez
│   ├── famosas.md     # Partidas legendarias
│   ├── enlaces.md     # Enlaces de interés
│   └── img/           # Imágenes y recursos visuales
├── mkdocs.yml         # Configuración de MkDocs
└── README.md          # Este archivo

```

## Autor

Desarrollado por José Luis como proyecto educativo para aprender MkDocs y crear un recurso útil para la comunidad ajedrecística.

## Licencia

Este proyecto es de código abierto y está disponible para uso educativo.