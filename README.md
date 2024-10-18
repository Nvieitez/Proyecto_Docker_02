# Proyecto_Docker_02
Este proyecto va a tratar los diferentes usos y servicios que ofrece Apache a través de Docker, para ello seguiremos los diferentes apartados:

    1. Instalación
      1.1 Descarga de la imagen de Apache
      1.2 Creación de un nuevo contenedor llamado "dam_web1"

    2. Conexión con la web
      2.1 Acceso al contenedor desde el navegador
      2.2 Creación un "Hola Mundo" en HTML y accede desde el navegador
      2.3 Creación de un segundo contenedor "dam_web2" con puerto 9080
      2.4 Comprobación de los puertos con localhost
      2.5 Realización de modificaciones en la página web

# 1. Instalación
> [!NOTE]
> Este apartado tratará la instalación de la imagen "Apache" en Docker, junto a la creación de su respectivo contenedor.

## 1.1 Descarga de la imagen de Apache
Para descargar e instalar la imagen de Apache utilizamos los siguientes comandos:

**docker pull httpd:2.4**

> [!IMPORTANT]
> Este comando se encarga de buscar la imagen de Apache en la base de datos de Docker

**docker images**

> [!IMPORTANT]
> Este comando se encarga de mostrar todas las imágenes instaladas en Docker

Resultado:
