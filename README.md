# Aplicacion To Do List

Crear una carpeta en el escritorio
```
C:\> mkdir projects\todo_list
C:\> cd projects\todo_list
```
Comprobar que la version de python sea 3.6 o superior
, crear y activar el entorno virtual con los siguientes comandos:
```
C:\> python -m venv venv
C:\> venv\Scripts\activate.bat
```
Instalar la biblioteca Django y sus dependencias:
```
python -m pip install django=="3.2.9"
```
Clonar el contenido de este repositorio: 
```
git clone https://github.com/erika-romero/AplicacionToDoList
```
Revisar el archivo requirements.txt para verificar las versiones de las dependencias a utilizar.

Ejecutar este comando dentro del entorno virtual en caso de no tener las dependencias:
```
pip install -r requirements.txt
```
Finalmente, ejecutar el servidor de desarrollo Django:

```
(venv) C:\> python manage.py runserver
```
