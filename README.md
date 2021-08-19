# Sitio Web desarrollado en el Informatorio 2021 

_Proyecto Web Chaco del modulo de desarollo web_

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

```
git init

git clone https://github.com/sanfosx/Webchaco.git
```

### Pre-requisitos 📋

_Instalar las dependendencias del proyecto (ir a la carpeta de requirements)_

```
pip install -r base.txt
```

_Crear settings local.py_

from .base import *
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql', # Conector de DB
        'NAME': 'NombreBaseDeDatos',
        'USER': 'UsuarioBaseDeDatos',
        'PASSWORD': 'ContraseñaBaseDeDatos',
        'HOST': 'localhost',
        'PORT': '5432'
    }
}
```

## Construido con 🛠️

* [Django]Framework web
* [PostgreSQL]Base de datos


## Autores ✒️

* **Santiago Foschiatti** - *Student* - [sanfosx]
* **Lucas Ibañez** - *Developer* - [lucasibaniez]


---

