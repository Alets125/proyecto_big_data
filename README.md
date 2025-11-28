# ♻️ Sistema de Inventario de Reciclaje con IA

Este proyecto es una aplicación web de visión por computadora diseñada para la identificación y conteo automático de materiales de reciclaje en entornos industriales. Utiliza inteligencia artificial (**TensorFlow.js**) para funcionar directamente en el navegador, permitiendo una gestión de inventario ágil y moderna.

---

## 🚀 Acceso a la Aplicación

No es necesario instalar código ni configurar servidores. Puedes ejecutar el sistema directamente desde el siguiente enlace:

### [🔗 CLIC AQUÍ PARA ABRIR EL ESCÁNER](https://alets125.github.io/proyecto_big_data/)

> **Nota:** El sistema requiere acceso a la cámara web para funcionar. Asegúrate de ejecutarlo en un dispositivo con cámara (Laptop, PC o Celular) y permitir los permisos en el navegador.

---

## 🌟 Características Principales

* **Detección en Tiempo Real:** Uso de modelos de *Teachable Machine* para clasificar objetos e identificar materiales al instante.
* **Modo "Snap & Count":** Sistema de captura manual que congela la imagen para asegurar el conteo preciso de unidades sin duplicados accidentales.
* **Gestión de Inventario:** Tabla dinámica en pantalla que suma cantidades por categoría automáticamente.
* **Exportación de Datos:** Descarga directa del inventario actual en formato **.csv**, totalmente compatible con Excel.
* **Privacidad:** Todo el procesamiento de imágenes ocurre localmente en el navegador del usuario; no se envían imágenes a la nube ni servidores externos.
* **Interfaz Industrial:** Diseño responsivo (adaptable a móviles y PC) creado con Bootstrap 5, utilizando un tema oscuro y visuales de entorno industrial.

## 📖 Guía Rápida de Uso

1.  **Ingresa al enlace** proporcionado arriba.
2.  Lee el aviso de privacidad y haz clic en el botón azul **"✅ Activar Sistema de Escaneo"**.
3.  Tu navegador te pedirá permiso para usar la cámara. Haz clic en **"Permitir"**.
4.  Coloca el material frente a la cámara.
5.  Cuando el sistema detecte el objeto, presiona el botón verde **"📸 Capturar y Registrar"** para sumarlo al inventario.
6.  Al finalizar tu sesión, puedes descargar el reporte haciendo clic en el botón negro **"📊 Exportar Reporte (.csv)"**.

## 📦 Tecnologías Utilizadas

Este proyecto fue construido utilizando tecnologías web estándar y librerías de Machine Learning:

* **HTML5 / CSS3 / JavaScript**: Estructura, estilo y lógica del sistema.
* **Bootstrap 5**: Framework utilizado para el diseño responsivo, sistema de rejillas (grids) y componentes de interfaz (modales, tablas, botones).
* **TensorFlow.js**: Motor de inteligencia artificial que permite ejecutar modelos de aprendizaje automático en el navegador.
* **Teachable Machine Library**: Librería especializada de Google para la carga y gestión eficiente de modelos de reconocimiento de imágenes.

## 📄 Licencia y Créditos

Este proyecto es de uso académico y libre distribución.

**Desarrollado por:** Jesus Alexis Garnica Mendoza  
**Universidad:** Universidad Autónoma de Baja California (UABC)  
**Carrera:** Inteligencia de Negocios
