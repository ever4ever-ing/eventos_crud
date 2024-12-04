# Readme:


# Despliegue
# Paso 1. Crear repositorio
# Paso 2. Subir archivos
``` 
git init
git remote add origin https://github.com/ever4ever-ing/eventos_crud.git
git branch -M main
git push -u origin main
```
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