# 📸 PDF Media & Screenshot Extractor

Un pipeline automatizado en Python para la extracción, filtrado dimensional y estructuración de recursos multimedia (capturas, diagramas, imágenes) desde informes técnicos en formato PDF.

## 🚀 Características
- **Filtrado Inteligente:** Elimina automáticamente elementos decorativos, firmas y logos de bajo tamaño mediante restricciones de dimensiones (`--min-width`).
- **Integración con CLI/System Utilities:** Utiliza `poppler-utils` (`pdfimages`) para un rendimiento eficiente en entornos Linux/Google Colab.
- **Estructuración Automática:** Organiza las capturas por número de página en carpetas listas para ser integradas en documentación o portafolios en Markdown.

## 🛠️ Tecnologías
- Python 3.x
- Poppler Utilities (`pdfimages`)
- Google Colab / Linux Environment