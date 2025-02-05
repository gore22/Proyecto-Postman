
# 📌 Proyecto de Automatización de Pruebas en Postman 

Este repositorio contiene un conjunto de pruebas automatizadas realizadas en Postman para validar una API. Se incluye la colección de pruebas, entorno y reporte generado con Newman.

Este proyecto tiene como objetivo automatizar pruebas en Postman para verificar la funcionalidad de la API DummyJSON. Se incluyen:

- 📂 Colección de pruebas (`.DummyJSON API Tests.postman_collection.json`).
- 📊 Reportes de ejecución generados con Newman.


## 🚀 Instalación y Configuración

### 1️⃣ Instalar Newman y el reporter HTML  
Para ejecutar las pruebas desde la terminal, instala Newman y el reporte en HTML:  
```bash
npm install -g newman newman-reporter-html


### 2️⃣ Ejecutar pruebas con Newman  
Ejecuta el siguiente comando en la terminal para correr las pruebas y generar un reporte en HTML:  
```bash
newman run "collections/DummyJSON API Tests.postman_collection.json" -r html --reporter-html-export newman/report.html

3️⃣ Ver el reporte generado

Informe: newman/report.html
Summary Report: newman/DummyJSON API Tests-2025-02-04-15-49-13-417-0.html


## 🛠 Uso del Proyecto

1. Clonar este repositorio:  
   ```bash
   git clone https://github.com/gore22/Proyecto-Postman.git


2. Instalar Newman y el reporter HTML.
3. Ejecutar las pruebas con Newman.
4. Revisar el reporte generado en newman/report.html.


##  🤝 Contribuir

Si deseas contribuir a este proyecto, sigue estos pasos:
1. Realiza un fork del repositorio.
2. Crea una rama (`git checkout -b nueva-rama`).
3. Realiza cambios y confirma (`git commit -m "Descripción del cambio"`).
4. Sube tus cambios (`git push origin nueva-rama`).
5. Abre un Pull Request.



