Usando [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) añadimos una capa de texto OCR a archivos PDF que son imágenes escaneadas, para poder buscar en su texto.

La llamada sería:
`ocrmypdf input.pdf output.pdf`

En caso de que no lo lea bien, habría que descargar el paquete de Tesseract en castellano y la llamada sería:

`ocrmypdf -l spa input.pdf output.pdf`

## Instalación

Antes de poder usar ocrmypdf  se tendría que instalar [Tesseract](https://github.com/tesseract-ocr/tesseract) y [GhostScript](https://www.ghostscript.com/releases/index.html). Aunque los paquetes de Python esten disponibles en `requirements.txt`, se recomienda seguir el proceso de instalación disponible en la [documentación de OCRmyPDF](https://ocrmypdf.readthedocs.io/en/latest/installation.html#installing-on-windows)
