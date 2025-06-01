# Proyecto-Final-Cafeteria
Proyecto Final Cafeteria Practica08 Ebusiness Enero Junio
Este proyecto es una aplicación web simple desarrollada con Django para gestionar una tienda o cafetería con funcionalidades de catálogo, carrito de compras, registro de pedidos y administración básica.

Requisitos
Python 3.8 o superior

pip (administrador de paquetes de Python)

Virtualenv (opcional pero recomendado)

Git (para clonar el repositorio)

Base de datos SQLite (por defecto con Django, no requiere instalación adicional)

Instalación y configuración
Clonar el repositorio

bash
Copiar
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
Crear y activar un entorno virtual

En Windows:

nginx
Copiar
python -m venv venv
venv\Scripts\activate


bash
Copiar
python3 -m venv venv
source venv/bin/activate
Instalar dependencias

nginx
Copiar
pip install -r requirements.txt
Si no tienes el archivo requirements.txt, instala Django manualmente:

nginx
Copiar
pip install django
Realizar migraciones para crear las tablas de la base de datos

nginx
Copiar
python manage.py makemigrations
python manage.py migrate
Crear un superusuario para acceder al panel de administración

nginx
Copiar
python manage.py createsuperuser
Sigue las instrucciones para ingresar usuario, correo y contraseña.

Correr el servidor de desarrollo

nginx
Copiar
python manage.py runserver
