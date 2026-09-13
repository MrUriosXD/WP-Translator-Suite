# WP-Translator-Suite

![HTML5](https://img.shields.io/badge/HTML5-Static-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-6.x-528DD7?style=flat-square&logo=fontawesome&logoColor=white)

Herramienta web **single-page** para trabajar con la localización de temas y plugins de WordPress directamente desde el navegador.

Permite cargar archivos `.PO` y `.POT`, traducir cadenas, gestionar una memoria de traducción y generar archivos `.POT`, sin necesidad de instalar software ni dependencias en el servidor.

## ✨ Características

- 🌐 Traducción de archivos `.PO` y `.POT`.
- 🧩 Generación de archivos `.POT` para proyectos de WordPress.
- 💾 Memoria de traducción gestionada desde el navegador.
- 🔄 Intercambio rápido entre idioma de origen y destino.
- 🤖 Diferentes motores de traducción gratuitos sin API Key.
- ⏱️ Configuración del retraso entre solicitudes para reducir problemas de rate limiting.
- 📊 Resumen del archivo con cadenas totales, traducidas, pendientes y advertencias.
- 🌓 Modo claro y oscuro.
- 📱 Interfaz adaptable para escritorio y dispositivos móviles.
- 🖱️ Carga de archivos mediante selección o arrastrar y soltar.
- 🔒 Procesamiento orientado al navegador, sin backend propio.

## 🌍 Motores de traducción

Actualmente incluye opciones gratuitas que no requieren una API Key:

- Google Translate (Web)
- MyMemory Translate
- Lingva Translate
- Apertium

> La disponibilidad y las limitaciones de los servicios externos pueden variar con el tiempo.

## 📁 Estructura

```text
wp-translator-suite/
├── index.html    # Aplicación web completa
└── README.md     # Documentación del proyecto
```

La aplicación está contenida en `index.html`, incluyendo la interfaz, estilos y lógica necesaria para su funcionamiento.

## 🚀 Uso

No requiere instalación ni configuración de un servidor PHP, Node.js u otro backend.

1. Descarga o clona el repositorio.
2. Abre `index.html` en un navegador moderno.
3. Selecciona **Traductor .PO** o **Generador .POT**.
4. Carga el archivo `.PO` o `.POT` cuando corresponda.
5. Configura los idiomas y el motor de traducción.
6. Procesa y descarga el resultado desde la propia aplicación.

## 🛠️ Tecnologías

- HTML5
- JavaScript
- Tailwind CSS
- Font Awesome
- APIs/servicios de traducción externos según el motor seleccionado

## ⚠️ Consideraciones

WP-Translator-Suite depende de servicios externos para determinadas funciones de traducción. Un cambio, límite, bloqueo o caída de uno de estos servicios puede afectar al funcionamiento del motor correspondiente.

Antes de procesar archivos importantes, se recomienda conservar una copia del archivo original.

## 📄 Licencia

Consulta los archivos y avisos incluidos en el repositorio para conocer las condiciones de uso del proyecto.

---

**WP-Translator-Suite** · Herramientas de localización para WordPress desde el navegador.
