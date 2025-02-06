# 📌 Proyecto de Automatización de Pruebas en Postman 

Este repositorio contiene un conjunto de pruebas automatizadas realizadas en Postman para validar una API. Se incluye la colección de pruebas, entorno y reporte generado con Newman.

Este proyecto tiene como objetivo automatizar pruebas en Postman para verificar la funcionalidad de la API DummyJSON. Se incluyen:

- 📂 Colección de pruebas (`.DummyJSON API Tests.postman_collection.json`).
- 📊 Reportes de ejecución generados con Newman.

## 🚀 Instalación y Configuración

1. **Clonar el repositorio**  
   Primero, clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/gore22/Proyecto-Postman.git
   ```

2. **Instalar Node.js y npm**  
   Si no tienes Node.js y npm instalados, descárgalos e instálalos desde nodejs.org. Luego, verifica la instalación:
   ```bash
   node -v
   npm -v
   ```
   Nota: Para descargar la última versión de npm, en la línea de comandos, ejecuta el siguiente comando:
   ```bash
   npm install -g npm
   ```

3. **Instalar Newman y el reporter HTML**  
   Para ejecutar las pruebas desde la terminal, instala Newman y el reporter en HTML globalmente:  
   ```bash
   npm install -g newman newman-reporter-html
   ```

4. **Ejecutar pruebas con Newman**  
   Ejecuta el siguiente comando en la terminal para correr las pruebas y generar un reporte en HTML:  
   ```bash
   newman run "collections/DummyJSON API Tests.postman_collection.json" -r html --reporter-html-export newman/report.html
   ```

5. **Ver reporte generado**  
   Después de ejecutar las pruebas, puedes ver el reporte generado en la carpeta newman. Los archivos de reporte incluyen:
   - reportTest: newman/report.html
   - summaryReport: newman/DummyJSON API Tests-2025-02-04-15-49-13-417-0.html

## 🛠 Uso del Proyecto

1. Clonar repositorio.  
2. Instalar Node.js y npm.
3. Instalar Newman y el reporter HTML.
4. Ejecutar las pruebas con Newman.
5. Revisar el reporte generado en newman/report.html.

## 🤝 Contribuir

Si deseas contribuir a este proyecto, sigue estos pasos:

1. Realiza un fork del repositorio.
2. Crea una rama (`git checkout -b nueva-rama`).
3. Realiza cambios y confirma (`git commit -m "Descripción del cambio"`).
4. Sube tus cambios (`git push origin nueva-rama`).
5. Abre un Pull Request.
