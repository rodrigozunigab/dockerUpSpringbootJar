# dockerUpSpringbootJar
Esta aplicación corre en el puerto 8081.

Paso 1: construir imagen
docker build -t my-java-grupo1 .

Paso 2: ejecutar contenedor
docker run --name app_grupo1_container -d -p 8081:8081 my-java-grupo1

Paso 3: verificar funcionamiento
docker exec -it app_grupo1_container bash