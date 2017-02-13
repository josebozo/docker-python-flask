# docker-python-flask
Contenedor para despliegues rápidos de app flask 

Facil de usar, un rapido contenedor que puede ser utilizado para empaquetar una codigo Python Flask o usar con un volumen donde este el codigo

ejemplo:

docker run -v /home/user/flask_app:/app -p 5000:50000 flask python /app/app.py
