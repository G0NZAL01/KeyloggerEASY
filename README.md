# ⌨️ KeyloggerEASY

![Python](https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

Este proyecto es una Prueba de Concepto (PoC) de un registrador de pulsaciones de teclado (Keylogger) desarrollado en Python y compilado a un archivo ejecutable (`.exe`). Su propósito es puramente educativo y demostrativo, ilustrando cómo los scripts de automatización pueden interactuar con los eventos del sistema operativo y registrar la entrada de datos en un archivo de texto local.

> ⚠️ **Aviso de Uso Seguro:** Este software se proporciona exclusivamente con fines educativos, de auditoría de seguridad y aprendizaje. El uso de esta herramienta en sistemas sin la autorización explícita del propietario es estrictamente ilegal.

---

## ⚙️ Funcionamiento y Características

* **Registro Local:** Captura las pulsaciones de teclado del sistema operativo y las almacena de forma estructurada en un archivo de texto plano (`.txt`).
* **Portabilidad:** Desarrollado originalmente en Python y congelado a un binario `.exe` independiente para ejecutarse sin necesidad de tener el intérprete de Python instalado en la máquina objetivo.
* **Diseño Ligero:** Ejecución en segundo plano con un consumo mínimo de recursos del sistema.

---

## 📂 Estructura del Repositorio y Uso

El repositorio incluye una estructura optimizada para pruebas rápidas en entornos controlados:

1.  **Carpeta `copiarAusb`:** Contiene los archivos necesarios ya listos y configurados.
2.  **Preparación:** Copia todo el contenido que se encuentra dentro de la carpeta `copiarAusb` directamente al directorio raíz de una unidad de almacenamiento USB.
3.  **Ejecución:** Ejecuta el archivo `.exe` directamente desde la unidad para iniciar la captura en el entorno de pruebas. El archivo `.txt` con los registros se generará en la misma ruta de ejecución.

---

## 🛠️ Detalles Técnicos (Desarrollo)

* **Lenguaje:** Python 3.x
* **Librerías principales:** Utiliza manejadores de eventos del sistema (como `pynput` o `keyboard`) para la escucha nativa del teclado.
* **Compilación:** El archivo ejecutable fue generado utilizando herramientas de empaquetado como `PyInstaller` o `auto-py-to-exe`.

