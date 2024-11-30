desafio M6S3-CREACIÓN DE UN PROYECTO DJANGO

1. Crear dos entornos virtuales
python -m venv django_development
python -m venv django_development_1

2. Activar y desactivar los entornos virtuales
django_development\Scripts\activate
deactivate (DESACTIVAR 1 ENTORNO A LA VEZ)

3. Eliminar el entorno virtual django_development_1
Remove-Item -Recurse -Force django_development_1

4. Instalar Django versión 4.0.5 en django_development
django_development\Scripts\activate 

- Instalar Django versión 4.0.5
pip install django==4.0.5 --> instalar 
django-admin --version --> version

5. site_django
cd C:\Users\danmi\Desktop\M6S2_Django1\M6S2_practica-django
python manage.py runserver
http://127.0.0.1:8000
