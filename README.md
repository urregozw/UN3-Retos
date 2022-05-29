# UN3-Retos

## Reto 1
Los pasos del desarrollo y la documentación de la actividad esta en el documento PDF [GuiaReto1](https://github.com/urregozw/UN3-Retos/blob/main/GuiaReto1.pdf).

En este principalmente creamos un cluster de EMR en AWS, seguimos el paso a paso y con este creamos el cluster dentro de AWS, logramos realizar:
- Crear el cluster de EMR para su utilización
- Habilitar los puertos dentro del EMR
- Habilitar los puertos dentro de los security groups
- Hacer la conexión via ssh al EMR
- Crear un usuario en la consola de HUE, que nos ayudara a concentrarnos en toda la parte de hadoop

## Reto 2
Los pasos del desarrollo y la documentación de la actividad esta en el documento PDF [GuiaReto2](https://github.com/urregozw/UN3-Retos/blob/main/GuiaReto2.pdf).


En esta guia exploramos un poco mas del EMR que creamos en el reto anterior y retomamos desde este, aqui lo que principalmente hacemos es:
- Manejar los archivos HDFS via ssh y HUE
- Manejar los archivos S3 via ssh y HUE
- Administrar la visibilidad publica del S3

## S3 public URLs

Se crearon dos carpetas para mostrar la utilización de las herramientas de HUE y ssh, la ruta de archivos de estas carpetas es igual a la que se nos compartio en la carpeta de los datasets a la hora de realizar este laboratorio, para navegar en los archivos cambie el endpoint del archivo añadiendo por ejemplo "url.txt":

**datasets_hue:** [https://mybucketemrtelematica.s3.amazonaws.com/datasets_hue/](https://mybucketemrtelematica.s3.amazonaws.com/datasets_hue/)

**datasets_ssh:** [https://mybucketemrtelematica.s3.amazonaws.com/datasets_ssh/](https://mybucketemrtelematica.s3.amazonaws.com/datasets_ssh/)

---
**Ejemplo:** [https://mybucketemrtelematica.s3.amazonaws.com/datasets_hue/url.txt](https://mybucketemrtelematica.s3.amazonaws.com/datasets_hue/url.txt)
