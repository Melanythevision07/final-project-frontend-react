#  Educa Academic Platform — Prototipo UI

Prototipo de maquetación web para una plataforma educativa interactiva. Este proyecto representa la fase inicial de diseño y maquetación de la interfaz de usuario, orientado a la construcción de un ecosistema académico digital.

>  **Nota del proyecto:** Actualmente nos encontramos en la **fase de maquetación estática en HTML5 y CSS3** (exportada y estructurada desde Stitch/Figma). La arquitectura de carpetas y la nomenclatura de archivos han sido organizadas siguiendo buenas prácticas para facilitar su próxima migración a componentes en **React**.

---

## Estructura del Repositorio

El proyecto cuenta con una estructura limpia y desacoplada para separar el punto de entrada principal, los módulos de usuario y los recursos gráficos:

```text
educa-academic-platform/
├── index.html                   # Página de inicio / Dashboard principal
├── pages/                       # Módulos y vistas individuales de la plataforma
│   ├── dashboard.html
│   ├── cursos.html
│   ├── tareas.html
│   ├── mensajes.html
│   ├── aula-virtual.html
│   ├── foros.html
│   ├── certificaciones.html
│   └── perfil.html
└── assets/                      # Recursos multimedia y evidencias visuales
    └── screenshots/             # Capturas de pantalla de los prototipos
