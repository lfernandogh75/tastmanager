1) crear entorno virtual
python -m venv myenv
2) activarlo 
myenv\Scripts\activate
3) instalar dependencias
pip install -r requirements.txt
4) aplicar la migración
python manage.py migrate
5) ejecutar proyecto
python manage.py runserver