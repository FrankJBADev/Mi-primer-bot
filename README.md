# Bot de Automatización de Precios (Selenium & Python)

Este proyecto es una herramienta de automatización RPA (Robotic Process Automation) diseñada para realizar **Web Scraping** de resultados de búsqueda en tiempo real.

El bot navega automáticamente en Google, busca productos específicos (como "Lenovo Legion") y extrae los títulos y datos relevantes para exportarlos a un reporte estructurado en Excel.

## Tecnologías Utilizadas
* **Python 3.12**: Lenguaje principal.
* **Selenium WebDriver**: Para la automatización del navegador y control de DOM.
* **Pandas**: Para la estructuración de datos y generación de archivos Excel (.xlsx).
* **Git & GitHub**: Control de versiones.

## Funcionalidades
1.  **Navegación Autónoma**: Abre un navegador Chrome controlado por software.
2.  **Interacción Humana**: Simula escritura y pulsaciones de teclas (Enter).
3.  **Extracción de Datos**: Identifica elementos HTML (etiquetas `<h3>`) dinámicamente.
4.  **Exportación**: Genera automáticamente un archivo `reporte_precios.xlsx`.

## Cómo usarlo
1.  Clonar el repositorio.
2.  Instalar las dependencias:
    ```bash
    pip install pandas selenium webdriver-manager openpyxl
    ```
3.  Ejecutar el script principal.

---
**Desarrollado por:** [FrankJBADev](https://github.com/FrankJBADev) 👨‍💻
*Estudiante de Ingeniería de Software | Especialista en Python & Datos*