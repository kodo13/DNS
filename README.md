# Descripción de las opciones del archivo docker-compose.yml

El archivo docker-compose.yml contiene las *siguientes opciones de configuración* para el contenedor con la imagen oficial de bind9:

- `version`: indica la versión de la especificación de Compose que se está utilizando.
- `services`: define los servicios que se ejecutarán dentro del contenedor.
- `bind9`: es el nombre del servicio al que se le aplican las opciones de configuración.
- `image`: define la imagen que se utilizará para crear el contenedor.
- `container_name`: especifica el nombre que se le dará al contenedor.
- `restart`: determina si el contenedor se reiniciará automáticamente en caso de que falle o se detenga.
- `ports`: mapea los puertos del contenedor a los puertos del host. 
- `volumes`: define los volúmenes que se utilizarán para la configuración de bind9. En este caso, se utilizan los archivos `named.conf`, `named.conf.options` y `named.conf.local`.

