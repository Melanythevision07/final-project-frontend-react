#  Educa Academic Platform — Prototipo UI

Prototipo de maquetación web para una plataforma educativa interactiva. Este proyecto representa la fase inicial de diseño y maquetación de la interfaz de usuario, orientado a la construcción de un ecosistema académico digital.

>  **Nota del proyecto:** Actualmente nos encontramos en la **fase de maquetación estática en HTML5 y Tailwind CSS** (exportada y estructurada desde Stitch/Figma). La interfaz utiliza un enfoque de clases de utilidad para garantizar un diseño moderno, responsivo y ágil. La arquitectura de carpetas y la nomenclatura de archivos han sido organizadas siguiendo buenas prácticas para facilitar su próxima migración a componentes en **React**.

---

## Estructura del Repositorio

El proyecto cuenta con una estructura limpia y desacoplada para separar el punto de entrada principal, los módulos de usuario, las hojas de estilo de Tailwind y los recursos gráficos:

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
├── css/                         # Configuración y estilos del proyecto
│   └── tailwind.css             # Archivo base de Tailwind CSS / Estilos globales
└── assets/                      # Recursos multimedia y evidencias visuales
    └── screenshots/             # Capturas de pantalla de los prototipos
```

---

## 🚀 Visualización e Interactividad del Prototipo

Para explorar la interfaz de la plataforma y probar la navegación entre los diferentes módulos, sigue estas indicaciones:

1. **Punto de Entrada Unificado:** Toda la experiencia del usuario se encuentra centralizada. Para iniciar el prototipo, **debes abrir directamente el archivo `index.html`** ubicado en la raíz del proyecto desde tu navegador web preferido (Google Chrome, Microsoft Edge, Mozilla Firefox, etc.).
2. **Navegación Interconectada:** Al arrancar desde `index.html`, los menús laterales y superiores quedarán completamente activos. Podrás hacer clic en las opciones principales (Dashboard, Mis Cursos, Tareas, Mensajes y Perfil) para desplazarte de forma fluida entre las interfaces sin necesidad de abrir los archivos de la carpeta `pages/` individualmente.
