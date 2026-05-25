# 🕸️ Data Engineering & Web Scraping: Construyendo Datasets desde Cero

En el mundo del análisis de datos, la información que necesitas rara vez viene empaquetada en un archivo limpio y listo para usar. La mayoría de las veces, tienes que salir a buscarla.

Este repositorio es una demostración de **autonomía en la obtención de datos**. Aquí recopilo las herramientas, *scripts* y *crawlers* que he desarrollado para extraer información directamente de internet, limpiarla, y construir mis propios datasets estructurados cuando estos no existen de antemano.

## 🚀 El valor de este código

En lugar de depender de datos preexistentes o APIs limitadas, he construido automatizaciones capaces de:

* **Web Scraping y Crawling Avanzado:** Uso de la librería `Scrapy` para la navegación dinámica por sitios web. Por ejemplo, he desarrollado *spiders* que recorren Wikipedia de forma autónoma extrayendo resultados históricos de Fórmula 1 (2012-2024), identificando enlaces anidados de "Reportes de Carrera".
* **Parseo y Limpieza en Memoria:** Extracción de tablas HTML crudas y su transformación directa en DataFrames de Pandas, limpiando filas innecesarias en el proceso para asegurar la calidad del dato.
* **Generación de Datasets Estructurados:** Diseño de sistemas de guardado automático que organizan la información extraída de forma lógica. Creación de estructuras de carpetas dinámicas (`/data/{año}/`) para exportar la información limpia a archivos **CSV** listos para ser consumidos por herramientas de visualización o modelos de Machine Learning, así como volcados de catálogos completos en formato **JSON**.

## 🛠️ Stack Tecnológico

* **Lenguaje:** Python
* **Extracción y Navegación Web:** Scrapy
* **Procesamiento de Datos:** Pandas, io
* **Gestión de Archivos:** os (Exportación estructurada a CSV y JSON)

## 📩 Contacto
Si tienes alguna duda sobre el proyecto, el despliegue en local o quieres conectar conmigo, puedes encontrarme a través de los siguientes canales oficiales:

* 📧 **Email:** lucia.lozano110@gmail.com
* 💼 **LinkedIn:** [linkedin.com/in/tu-perfil](https://linkedin.com/in/tu-perfil)
* 🐙 **GitHub:** [github.com/luulozanoo](https://github.com/luulozanoo)
