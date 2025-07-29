# ExcelComparadorXmlVsJsonRips
Archivo para comparar los datos de la factura electrónica en salud con los JSON de RIPS, según lo establecido en la Resolución 2275 de 2023

# Comparador de Factura Electrónica en Salud vs JSON RIPS (Resolución 2275 de 2023)

Este archivo de Excel contiene macros que permiten comparar los datos entre un archivo XML de factura electrónica del sector salud y
un archivo JSON estructurado conforme a la **Resolución 2275 de 2023** del Ministerio de Salud de Colombia.

## 📌 Funcionalidades

- 📥 Lectura de archivos XML de facturación electrónica.
- 📥 Lectura y conversión de archivos JSON RIPS a hojas de Excel para facilitar su visualización.
- 🔁 Posibilidad de convertir nuevamente el Excel en JSON.
- 💰 Comparación automatizada de valores monetarios entre los documentos XML y JSON.

## 🧰 Requisitos

- Microsoft Excel con macros habilitadas (Excel 2016 o superior recomendado).
- Permitir ejecución de macros (VBA).
- Archivos válidos XML y JSON conforme a los estándares de facturación electrónica y resolución 2275:2023.

## 📚 Librerías utilizadas

Este proyecto utiliza la librería de código abierto [VBA-JSON](https://github.com/VBA-tools/VBA-JSON) para la manipulación de archivos JSON en VBA.

### Licencia de `VBA-JSON` (MIT)

```text
The MIT License (MIT)

Copyright (c) 2016-2019 Tim Hall

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
