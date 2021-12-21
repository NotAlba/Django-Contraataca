# Django Contrataca: Mysite
## _El tutorial inicial de Django vuelve a la carga_



## El proyecto

Repositorio hecho para seguir el tutorial inicial de DJANGO


## Requerimientos

Es recomendable disponer de un instalador PIP y de Virtualenv para instalar las librerias requeridas, de esta forma no tendrás problemas con las de tu sistema operativo:
``` 
sudo apt install python3-pip
pip install virtualenv
``` 


## Instalación

Para empezar clonamos este repositorio
``` git clone https://github.com/NotAlba/Django-Contraataca```

Para no tener problemas con las librerias del nuestro sistema operativo y aislar esta prueba creamos un virtualenv y lo ponemos en marcha:
``` 
virtualenv venv 
source venv/bin/activate
```
Entramos en la carpeta de nuestro proyecto,creamos nuestras variables de entorno e instalamos las dependencias.
```cp .env.example .env
pip3 install -r requirements
python3 manage.py migrate
python3 manage.py runserver
``` 

Para comprobar que nuestra aplicación funciona correctamente accedemos a localhost en el puerto 8000:
```sh
127.0.0.1:8000
```
