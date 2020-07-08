# cloud-flask-app-template
## Configuración del entorno de desarrollo
- Crear una nueva carpeta
- Navegar hacia la nueva carpeta desde terminal o línea de comandos
- Instalar un entorno virtual de Python utilizando el siguiente comando:
    - (Linux/MacOS) `python3 -m venv .`
    - (Windows) `python -m venv .`
- Activar el entorno virtual ejecutando el siguiente comando:
    - (Linux/MacOS) `source bin/activate`
    - (Windows) `Scripts\activate.bat`
- Instalar Flask dentro del entorno virtual activado mediante el siguiente comando:
    - (Linux/MacOS) `python3 -m pip install flask`
    - (Windows) `python -m pip install flask`
- Definir las variables de entorno para definir el punto de arranque de la aplicación mediante el siguiente comando:
    - (Linux/MacOS) `export FLASK_APP=app.py`
    - (Windows) `set FLASK_APP=app.py`
- Ejecutar el servidor de flask para iniciar la aplicación mediante el siguiente comando:
    - (Cualquier SO) `flask run`
- (Opcional) Habilitar el modo de depuración para que la apliación cargue los cambios de manera automática mediante el siguiente comando (antes de ejecutar el servidor de flask):
    - (Linux/MacOS) `export FLASK_ENV=development`
    - (Windows) `set FLASK_ENV=development`
