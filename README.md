Carpetas Front-End

Este repositorio presenta una estructura de carpetas sugerida para proyectos de front‐end. Ayuda a mantener un orden común, facilita el trabajo en equipo y mejora la mantenibilidad del código.

🧩 ¿Por qué una estructura estándar?

Hace que cualquier desarrolladore que entre al proyecto comprenda rápidamente dónde está cada cosa.

Facilita separar responsabilidades (vista, estilos, scripts, assets, etc.).

Mejora la escalabilidad cuando el proyecto crece.

Evita “carpetas misceláneas” que con el tiempo se vuelven inmanejables.

Ideal si colaboras o quieres que tu código quede bien organizado para ti misma/e.

✅ Estructura sugerida

Aquí tienes el árbol de carpetas más habitual, con explicación de su propósito:
/
├─ index.html           ← Punto de entrada principal del sitio
├─ static/              ← Carpeta principal para activos estáticos
│   ├─ css/             ← Hojas de estilo (o preprocesadores)
│   ├─ js/              ← Código JavaScript o TypeScript (y bundles)
│   ├─ img/             ← Imágenes (.png, .jpg, .svg, etc.)
│   ├─ fonts/           ← Tipografías externas o personalizadas
│   └─ libs/            ← Librerías externas que no se instalan vía paquete
└─ .gitignore           ← Define qué no subir al control de versiones

Descripción breve

index.html: Archivo HTML principal, punto de arranque visible para el navegadore.

static/: Contenedor de todos los recursos estáticos.

css/: Aquí se ubican los estilos del proyecto. Si usas un preprocesador (Sass, Less) puedes tener aquí la versión compilada o la fuente.

js/: Aquí va la lógica del front-end: módulos, scripts, bundles generados.

img/: Todas las imágenes usadas en el UI (íconos, ilustraciones, fondo).

fonts/: Tipografías personalizadas o de terceros que incluyes manualmente.

libs/: Si existieran librerías que no manejas vía npm/yarn o no quieres empaquetar, puedes colocarlas aquí.

.gitignore: Define qué archivos/carpetas no subir al repositorio (por ejemplo node_modules/, dist/, carpetas de build, archivos temporales).
