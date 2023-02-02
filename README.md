# AREP Laboratorio 1

Api que consulta la informacion de Peliculas atravez de una servidor que se conecta con una Api de www.omdbapi.com que consulta la informacion
y la transmite al un cliente que corre el navegador, mostrando su información en una tabla hmtl.

## Iniciando

### Prerequisites

- Java - Ambiente de desarrollo
- Maven - Administrador de dependencias
-  Git - Sistema de control de versiones y descarga del repositorio

### Instalando el entorno

Descargamos el archivo .zip o lo clonamos con el comando:
```
git clone https://github.com/Derjasai/AREP_Lab01.git
```

Una vez descargado nos dirigimos al directorio raiz del proyecto ye ejecutamos el comando:

```
mvn clean package exec:java -D "exec.mainClass"="edu.escuelaing.arem.ASE.app.HttpServer"
```

Finalmente ingrese al navegador de su preferencia y usamos el link:
http://localhost:35000


## Corriendo Tests unitatios

Nos ubicamos en la carpeta principal del proyecto y ejecutamos el comando:

```
mvn test
```

## Despliegue

Add additional notes about how to deploy this on a live system

## Construido con

* [Maven](https://maven.apache.org/) - Dependency Management

## Versonamiento

Versión 1.0

## Autores

* Yesid Camilo Mora Barbosa

## Explicaciones