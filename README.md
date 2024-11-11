# Proyecto: Creación y Actualización de Base de Datos con Web Scraping

Este proyecto tiene como objetivo crear y mantener actualizada una base de datos MySQL en la nube utilizando datos obtenidos mediante técnicas de web scraping. Los datos recopilados se almacenan en una base de datos alojada en CleverCloud, permitiendo centralizar y gestionar información de productos de una página web específica.

## Tecnologías Utilizadas

- **Python**: para el desarrollo del código de web scraping y la conexión a la base de datos.
- **BeautifulSoup** y **Requests**: para la extracción de datos de la web.
- **MySQL (CleverCloud)**: como base de datos en la nube para almacenar los datos obtenidos.
- **Git** y **GitHub**: para el control de versiones y almacenamiento del código.

## Estructura del Proyecto

- **`web_scraping.py`**: contiene el código para realizar el web scraping, extrayendo información de productos desde una URL específica.
- **`.env`**: archivo de configuración con las credenciales de acceso a la base de datos en CleverCloud. **Nota**: este archivo está excluido del repositorio por motivos de seguridad.
- **`database_setup.py`**: script para configurar y conectar la base de datos MySQL en CleverCloud.
- **`README.md`**: descripción del proyecto y guía de uso.
