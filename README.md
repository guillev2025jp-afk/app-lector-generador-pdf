# App Multiplataforma - Lector y Generador de PDF

Aplicación profesional con arquitectura simétrica, optimizada para su uso en computadoras (PC) y dispositivos móviles (Celular) sin necesidad de descargas externas.

---

## 🛠️ Funcionalidades Clave

### 1. Panel de Edición y Generación Multimedia
* **Inserción de Imágenes:** Zona activa para cargar fotos locales (`PNG`, `JPG`, `WebP`) mediante arrastre o selección, procesadas de manera nativa en formato Base64.
* **Gráficos Estadísticos:** Motor vectorial integrado que transforma datos numéricos simples en gráficos de barras o tortas con nitidez absoluta y sin pixelado.
* **Compilación Local:** Generación del archivo binario directamente en el dispositivo para garantizar la privacidad y un rendimiento instantáneo.

### 2. Panel de Lectura y Visualización
* **Visor Interactivo:** Renderizado fluido de documentos en una hoja de previsualización que simula el formato físico de impresión.
* **Extracción de Contenido:** Estructura preparada para interactuar con el texto y los elementos del archivo cargado.

### 3. Conectividad y Exportación
* **Descarga Inmediata:** Almacenamiento nativo y privado del archivo `.pdf` compilado en la carpeta local del sistema.
* **Compartición Directa:** Integración con la API Web Share para enviar el documento generado de manera directa a través de aplicaciones del celular como WhatsApp, Telegram o Gmail.

---

## 💻 Arquitectura Tecnológica
* **Estructura Base:** PWA (Progressive Web App) ejecutable mediante entorno web responsivo.
* **Procesamiento de Archivos:** Compilación de binarios ejecutada 100% en el cliente (lado del navegador).
