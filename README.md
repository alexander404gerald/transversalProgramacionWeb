Primero dentro e la carpeta Vacia
se crea el entorno virtual

1) Python -m venv "Nombre que le quieras dar a tu entorno"

luego activamos el entorno virtual de Python

2) "nombre del entorno\Scripts\activate"

Luego se instalan las dependencias que serian django y pip

3) pip install Django~=4.1.2

luego se instala pip con este comando se instala pip si no lo tienes y si lo tienes se actualiza 

4)python.exe -m pip install --upgrade pip

al terminar se crea la carpeta con el proyecto 

5) django-admin startproject "nombre que le quieras dar al proyecto"

al terminar haces la migración de los archivos

6)Python manage.py migrate

luego nos metemos a la carpeta del proyecto

7) cd "nombre de proyecto"

luego creamos la aplicación del proyecto

8) Python manage.py startapp "Nombre que quieras darle a la aplicación"
