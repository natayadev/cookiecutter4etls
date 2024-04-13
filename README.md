# CookieCutter4ETLs Template
Una plantilla de [CookieCutter](https://cookiecutter.readthedocs.io/en/1.7.3/index.html) para ETLs en Python.

        ├── config             <- Acá va el archivo .env y otros archivos
        │                         de configuración.
        │
        ├── data               <- Almacena los datos procesados y los datos crudos
        │   │                     organizados en carpetas.
        │   ├── processed
        │   └── raw
        │
        ├── docs               <- Acá va la documentación del proyecto en
        │                         formatos .md, .pdf, etc.
        │
        ├── log                <- Contiene los archivos de registro.
        │
        ├── models             <- Almacena los modelos necesarios para ML o DBs.
        │
        ├── notebooks          <- Acá van los archivos de Jupyter notebooks.
        │
        ├── scripts            <- Almacena los archivos principales del ETL.
        │
        ├── test               <- Contiene los tests automatizados.
        │
        ├── utils              <- Acá van los módulos auxiliares y las bibliotecas
        │                         que se reutilizan en el proyecto.
        │
        ├── .gitignore         <- Ficheros que Git ignorará.
        │
        ├── environment.yml    <- Manifiesto utilizado por Conda.
        │
        ├── requirements.txt   <- Enlista todas las librerías de Python necesarias
        │                         y sus versiones para que el proyecto funcione.
        │
        └── README.md          <- El README principal.

## Paso a paso

### 1. Crear entorno virtual
```python -m venv env```

### 2. Activar entorno virtual
- En Windows:

  ```env\Scripts\activate```

- En Unix o MacOS:

  ```source env/bin/activate```

### 3. Instalar CookieCutter
```pip install cookiecutter```

### 3. Descargar plantilla cookiecutter4etls
```cookiecutter https://github.com/natayadev/cookiecutter4etls.git```

*Hecho por Nataya Flores (@natayadev), espero que te sea útil.*
