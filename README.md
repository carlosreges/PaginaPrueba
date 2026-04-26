# Landing Page - Marketing para Odontólogos (Córdoba)

Este proyecto es una landing page profesional diseñada específicamente para servicios de Social Media y Community Management enfocados en el sector odontológico en Córdoba, Argentina. La página está optimizada para la conversión de clientes mediante un diseño moderno, responsivo y llamadas a la acción (CTA) claras.

## 🚀 Tecnologías Utilizadas

*   **HTML5 & JavaScript:** Estructura y lógica de interactividad.
*   **Tailwind CSS:** Framework de CSS para un diseño rápido y personalizado.
*   **FontAwesome:** Iconografía profesional.
*   **Vercel:** Plataforma de despliegue y hosting.

## 🛠️ Características Principales

*   **Diseño Responsivo:** Adaptado al 100% para móviles, tablets y computadoras.
*   **Sistema de Acordeón FAQ:** Preguntas frecuentes interactivas para mejorar la experiencia de usuario.
*   **Smooth Scroll:** Navegación suave entre secciones.
*   **Integración con WhatsApp:** Botón flotante y enlaces directos con mensajes preconfigurados.
*   **Optimización de Rendimiento:** Compilación de CSS mediante Tailwind CLI para producción.

## 📦 Instalación y Desarrollo Local

Si deseas realizar cambios y verlos en tiempo real, asegúrate de tener [Node.js](https://nodejs.org/) instalado y sigue estos pasos:

1.  **Instalar dependencias:**
    ```bash
    npm install
    ```

2.  **Compilar CSS:**
    Para generar el archivo `main.css` optimizado:
    ```bash
    npm run build
    ```

3.  **Desarrollo:**
    Si quieres trabajar con el modo "watch" de Tailwind (para que compile automáticamente al guardar):
    ```bash
    npx tailwindcss -i ./style.css -o ./main.css --watch
    ```

## 🌐 Despliegue en Vercel

El proyecto está configurado para desplegarse automáticamente al subir cambios a la rama principal de GitHub.
*   **Archivo de configuración:** `vercel.json` define el directorio de salida en la raíz (`.`).
*   **Comando de construcción:** `npm run build`.

## 📝 Notas de Versión

*   **v1.0.0:** Lanzamiento inicial con sección de Mes de Prueba, Planes, FAQ y Botón de WhatsApp.
*   **v1.1.0:** Migración a Tailwind CLI y configuración profesional de despliegue.