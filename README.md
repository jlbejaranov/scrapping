# 🧾 Automatización de consultas masivas al SISBÉN

Este proyecto utiliza **Python, Selenium y Excel** para automatizar la consulta de información en el portal público del SISBÉN, permitiendo procesar múltiples documentos de forma automática desde un archivo Excel.

## 🚀 Funcionalidades

- Rellena automáticamente el formulario del SISBÉN usando datos de un archivo Excel (.xlsx).
- Extrae los nombres, apellidos y el grupo asignado desde la respuesta del portal.
- Guarda los resultados en un nuevo archivo Excel.
- Incluye manejo básico de errores y navegación controlada.

## 📦 Tecnologías utilizadas

- Python 3
- Selenium
- Pandas
- openpyxl
- webdriver-manager

## 🖥️ Requisitos

Instalar dependencias:

```bash
pip install selenium pandas openpyxl webdriver-manager
