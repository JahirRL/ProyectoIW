# Proyecto de Ingeniería Web #

## Descripción ##
El proyecto consiste en la creación de una aplicación web que en su diseño contemple a tres tipos de usuario:
* Administrador
* Proveedor de servicio (Dentista en este caso)
* Usuario
Y crear los modelos correspondientes, para más detalles consultar el archivo del proyecto en: 
> ../ProyectoIW/docs/Proyecto.pdf

## Base de datos ##

![](/img/capturas/DB.png)

## Capturas de pantalla ##

![](/img/capturas/Inicio.png)
![](/img/capturas/1.png)
![](/img/capturas/2.png)
![](/img/capturas/3.png)

## Notas ##

* Para ejecutar el programa es necesario contar con:
    * Apache
    * MySQL
    * PHP
    
## Instalación ##
Al cumplir con los requisitos anteriores es necesario:
1. Pasar el archivo a la carpeta localhost correspondiente de Apache
2. Cargar la base de datos
    1. `mysql -u username -p`
    2. `create database proyectoiw;`
    3. `\q`
    4. `mysql -u root -p proyectoiw < proyectoiw.sql`
    ![](/img/capturas/IBD.png)
