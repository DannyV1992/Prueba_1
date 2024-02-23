# Paquetes necesarios 

numpy==1.26.4

pandas==2.2.0

python-dateutil==2.8.2

pytz==2024.1

six==1.16.0

tzdata==2024.1

# Instalacion de paquetes

Crear archivo txt llamado requirements para instalar los paquetes anteriores con el codigo proporcionado abajo

pip install -r requirements.txt para instalar todo

# Excluir archivos de ser subidos a GitHub

En el archivo .gitignore se puede especificar los archivos que no se desean subir.

Por ejemplo en este proyecto podras encontrar al inicio de ese archivo este codigo:

---
My selected files

Proyecto_1/

---

Con esto se excluyen todos los archivos de la carpeta Proyecto_1

# Comandos para hacer commits

`git add .` = para agregar todos los archivo

`git commit -m "Cambios"` = agregar un titulo a los cambios

`git push origin main` = subir cambios a GitHub

# Para crear branches
`git branch staging main` = para crear una rama apartir de main

`git branch -v` = para ver branches

`git checkout staging` = para cambiar de branch