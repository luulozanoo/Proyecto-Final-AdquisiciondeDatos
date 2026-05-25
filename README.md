# 🕸️ Data Engineering & Web Scraping: Construyendo Datasets desde Cero

En el mundo real, los datos que necesitas para un proyecto rara vez están empaquetados en un archivo limpio y listo para usar. La mayoría de las veces, tienes que salir a buscarlos.

Este repositorio es una demostración de **autonomía en la obtención y gestión de datos**. Aquí recopilo las herramientas, *scripts* y *crawlers* que he desarrollado desde cero para extraer información directamente de internet, limpiarla, y construir mis propios datasets cuando estos no existen.

## 🚀 El valor de este código

En lugar de depender de datos preexistentes, he construido automatizaciones capaces de:

* **Web Scraping y Crawling Avanzado:** Uso de `Scrapy` para la navegación dinámica por sitios web complejos. Por ejemplo, he desarrollado *spiders* que recorren Wikipedia de forma autónoma extrayendo resultados históricos de Fórmula 1 (2012-2024), identificando y parseando tablas HTML específicas y transformándolas en DataFrames limpios de Pandas.
* **Extracción de Catálogos:** *Crawlers* programados para rastrear páginas web enteras siguiendo enlaces de paginación y categorías, extrayendo metadatos específicos (como títulos o identificadores únicos) y exportando la información a formatos estructurados como JSON.
* **Ingesta y Orquestación Multimodelo:** Una vez obtenidos los datos mediante *scraping*, estos scripts se encargan de su procesamiento e inserción masiva. He programado *pipelines* que distribuyen los datos extraídos hacia arquitecturas multimodelo: MySQL (datos relacionales), MongoDB (documentos y textos) y Neo4j (grafos y relaciones).

## 🛠️ Stack Tecnológico

* **Extracción y Manipulación:** Python, Scrapy, Pandas.
* **Orquestación de Bases de Datos:** `pymysql`, `pymongo`, `neo4j`.
* **Optimización:** Procesamiento por lotes (*batch processing*) y lectura optimizada para manejar grandes volúmenes de datos recién scrapeados sin saturar la memoria RAM.
