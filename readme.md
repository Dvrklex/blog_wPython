# EpicBlogSpot

## Instalar Requerimientos - Comando para instalar Flask, SQLAlchemy, Flask-Migrate.
- pip install -r requirements.txt

## XAMPP - Crear base de datos
Primero debes crear tu base de datos local en XAMPP, en este caso el nombre de la base de datos es blog_python
El nombre es importante al momento de queres obtener o agregar datos a las diferentes tablas
Ejemplo de como llamar la base de datos en tu código:
<!-- app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+pymysql://root@localhost/nombredelabasededatos' -->
- app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+pymysql://root@localhost/blog_python'

## FLASK MIGRATE - Comando para generar los modelados de las tablas.
Iniciar Migraciones
- flask db init

Generar la migracion
- flask db migrate -m "Descripcion del cambio."

Migrar los cambios a la db
- flask db upgrade


## FLASK - Comando para ejecutar la Aplicacion
- flask run

### Finalmente abre tu navegador para visualizar la aplicación.
![Alt text](../../../../../c:/Users/lobod/Desktop/Captura%20de%20pantalla%202022-11-21%20015807.png)