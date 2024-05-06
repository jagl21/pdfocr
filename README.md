Mediante la herramienta de Python ocrmypdf hacer una llamada:
ocrmypdf input.pdf output.pdf

El output muestra la metadata correctamente pese a hacer el OCR en inglés. En caso de que no lo lea bien, habría que descargar el paquete de Tesseract en castellano y la llamada sería:

ocrmypdf -l spa input.pdf output.pdf