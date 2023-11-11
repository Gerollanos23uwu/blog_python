# API de Blog en Python... blog_boookface
Esta API proporciona un servicio de blogs donde los usuarios pueden realizar las siguientes acciones:

Crear un nuevo post
Obtener una lista de todos los posts
Obtener detalles de un post específico
Comentar en un post existente

# Instalación

Clona este repositorio:
git clone https://github.com/tu-usuario/blog_boookface
cd blog_boookface

Crea un entorno virtual (se recomienda, pero opcional)
python -m venv venv
source venv/bin/activate  


Instala las dependencias:
pip install -r requirements.txt

Configuración
# Abre el archivo config.py y configura las variables según tus necesidades:

# config.py
DATABASE_URI = 'sqlite:///blog.db'  # Cambia esto según tu base de datos
SECRET_KEY = 'tu_clave_secreta'