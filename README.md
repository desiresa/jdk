[[_TOC_]]
## jdk

## Instalación de JDK en el SO



# 1. Instalación desde repositorios

# 2. Instalar una versión específica de Java

# 3. Configurar las variables de entorno



Actualizamos desde el terminal con:
- ```sudo apt-get update```

[![]()] imagen

Luego de actualizarlo, instalamos Java con:
- `sudo apt-get install default-jdk`

![]()

Comprobamos la versión que tenemos actualmente en nuestro SO con:

- `java -version`


![]()

Y como se ve en la captura se nos instalo la última versión disponible de OpenJDK

##2. Instalar una versión específica de Java

Para instalar las versiones de Java OpenJDK utilizaremos los siguientes comandos:
- `sudo apt install openjdk-11-jdk`

![]()

- `sudo apt install openjdk-9-jdk`

![]()

- `sudo apt install openjdk-8-jdk`

![]()

La versión que usaremos este año será la 8. Ahora volveremos a comprobar que versión tenemos instalada.
- `java -version`

![]()

Si no nos aparece como última versión la 8, deberemos configurar las variables de entorno.

## 3. Configurar las variables de entorno.

Deberemos configurar estas variables para que Linux sepa donde se encuentra ubicado el OpenJDK para ejecutarlo, y que versión usar de forma predeterminada.
Primero listamos klas versiones que tenfamos instaladas de OpenJDK, con el siguiente comando:

- ``
