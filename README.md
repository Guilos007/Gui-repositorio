"# Gui-repositorio" 
##proyecto Django

Haremos un proyecto con el framwork Django para certificar el curso
comando usados
git log --oneline ve los cambios
git push sube a la nube
git branch dev : crea una nueva rama
git checkout dev : 
git

## Entornos virtuales

Un entorno virtual en Python es una herramienta 
que te permite crear un espacio aislado donde puedes instalar 
y manejar las dependencias (bibliotecas y versiones de Python) 
específicas para un proyecto en particular, sin afectar al sistema global de Python.

'pip list' muestra las bibliotecas instaladas en el entorno virtual o global
Como crear un entorno virtual? entorno aislado del global
'python -m venv .venv'

.\.venv\Scripts\activate : (windows powershell)
seguramente aparece un error y se debe ejecutar powershell e ingresar el siguiente comando que activa el modo virtual
Set-ExecutionPolicy -ExecutionPolicy unrestricted

## Instalacion Django

'pip install django' comando para instalar django

## comandos
creo una carpeta que se llame project
cd project

django-admin startproject config . (es un comando de django)

python manage.py runserver
con ctrl+c detengo el servidor
git add . (agrega todo de una)

django-admin startapp core (para crear aplicaciones)




