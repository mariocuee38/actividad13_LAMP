# Creación de un LAMP en una instancia EC2 de AWS
`LAMP es un conjunto de software usado en desarrollo de aplicaciones web. Es acrónimo de Linux, Apache, MariaDB (en mi caso) y PHP`

### Sobre una instancia EC2 de Ubuntu(Linux):
## Instalación de Apache:
![paso1](img/c1.PNG)

![paso2](img/c2.PNG)

### Creo y añado el index.php al conf de Apache:
(mostraré mas adelante el resultado)

![indexphp](img/cindexphp.PNG)

![indexphp2](img/cindexphp2.PNG)

![paso3](img/c3.PNG)


### Creo también info.php en `/var/www/html`:
![paso4](img/c4.PNG)


## Instalación de MariaDB:
![paso6](img/c6.PNG)

### Creo el usuario...
![paso7](img/c7.PNG)

## Instalación de PHP:
![paso8](img/c8.PNG)

![paso9](img/c9.PNG)

## Accedo al PHPmyAdmin:
![paso10](img/c10.PNG)



# Adminer:

## Instalación:
![adminer1](img/adminerinstall.PNG)

### Accedo desde el navegador a la base de datos:
![accederAdminer](img/adminer.PNG)



# Pruebas de acceso a los sitios creados en el servidor LAMP:

## Pagina por defecto Apache:
![defaultA](img/resultado1.PNG)

## Pagina de info.php:
![infophp](img/resultadoInfo.PNG)

## Pagina de index.php:
![indexphp](img/resultadoIndex.PNG)

