# Readme:


# Despliegue
### Paso 1. Crear repositorio
### Paso 2. Subir archivos
Para configurar repositorio:
``` 
git init
git remote add origin https://github.com/ever4ever-ing/eventos_crud.git
git branch -M main
git push -u origin main
```
Para subir archivos:
```
git add .
git commit -m "primer commit"
git push -u origin main
```


## Instalación

 pip install -r requirements.txt

## Estructura del proyecto

Friendship-Flask/ 

    ├── flask_app/  
    │   ├── \_\_init\_\_.py  
    │   ├── config/ 
    │   │   └── mysqlconnection.py  
    │   ├── controllers/  
    │   │   └── usuarios.py  
    │   ├── models/  
    │   │   ├── usuario.py  
    │   ├── static/  
    │   │   ├── css/  
    │   │   │   └── style.css  
    │   │   └── js/  
    │   │       └── script.js  
    │   ├── templates/  
    │   │   └── index.html  
    │   └── bd/  
    │       └── bd.sql  
    │  
    ├── .gitignore  
    ├── requirements.txt  
    ├── server.py  
    └── README.md


## Explicación

- `flask_app/`: Contiene la aplicación Flask.
- `__init__.py`: Inicializa la aplicación Flask.
- `config/`: Archivos de configuración, como la conexión a la base de datos.
- `controllers/`: Controladores que manejan las rutas y la lógica de la aplicación.
- `models/`: Modelos que representan las entidades de la base de datos.
- `static/`: Archivos estáticos como CSS y JavaScript.
- `templates/`: Plantillas HTML para la aplicación.
- `bd/`: Archivos relacionados con la base de datos, como scripts SQL.
- `.gitignore`: Archivos y directorios que Git debe ignorar.
- `requirements.txt`: Lista de dependencias de Python necesarias para el proyecto.
- `server.py`: Archivo principal para ejecutar la aplicación Flask.
- `Readme.md`: Documentación del proyecto.



## Comandos en aws
    1  ls
    2  ifconfig
    3  https://github.com/ever4ever-ing/eventos_crud.git
    4  git clone https://github.com/ever4ever-ing/eventos_crud.git
    5  ls
    6  cd eventos_crud/
    7  ls
    8  pipenv install flask
    9  pip install -r requirements.txt 
   10  sudo apt-get update
   11  sudo apt-get install python3-pip nginx git -y
   12  sudo apt-get update
   13  }
   14  sudo apt-get update
   15  sudo apt-get install python3-venv
   16  ls
   17  sudo apt-get install mysql-server
   18  sudo apt-get update
   19  sudo mysql -uroot -p
   20  ls
   21  python3 -m venv venv  
   22  history