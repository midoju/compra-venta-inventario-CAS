# Gestión de compras, ventas e inventarios

_El siguiente proyecto se realiza en respuesta a la creación de una solución informatica para la gestion de procesos de operación de compras, ventas e inventario del centro de acopio Sabanilla_

## Comenzando 🚀

_Para empezar a usar el proyecto configurar un virtualenv y activar._
## Obtener el codigo
```
git clone https://github.com/midoju/compra-venta-inventario-CAS.git
cd compra-venta-inventario-CAS
```

### Pre-requisitos 📋

_Instalación de los requerimientos necesarios para la ejecucion_

```
pip install -r requirements.txt
```

### Ejecutar el codigo 🔧

_Ejecutar el codigo en un entorno de desarrollo_

```
cd gentelella
python manage.py runserver
```
## Despliegue 📦

_Para el despliegue en local del proyecto debe ir_

```
http://localhost:8000/
```
![2021-06-12 10_10_32-Window](https://user-images.githubusercontent.com/13515624/123519080-c680ab80-d66e-11eb-8dc9-803a22c1f0dd.png)

## Construido con 🛠️

_La plantilla de adimistración usada para crear ese proyecto es_

* [Gentelella Admin](https://github.com/GiriB/django-gentelella) - Plantilla Admin usado.
* [Python](https://www.python.org) - Lenguaje de programacion basica.
* [Django](https://www.djangoproject.com) - Framework de Python para la contruccion de aplicaciones web de alto nivel.

## Flujo de archivos 📋
* [app](https://github.com/midoju/compra-venta-inventario-CAS/tree/main/gentelella/app) - Aplicativo web
    * [static](https://github.com/midoju/compra-venta-inventario-CAS/tree/main/gentelella/app/static) - Carpeta con los plugins instalados 
    * [templates](https://github.com/midoju/compra-venta-inventario-CAS/tree/main/gentelella/app/templates) - Carpeta con los plantillas del fronted
    * [forms.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/app/forms.py) - Formularios de creación y edición
    * [models.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/app/models.py) - Modelado de base de datos
    * [urls.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/app/urls.py) - Direcciones url del aplicativo web
    * [views.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/app/views.py) - Control de funcionamiento del las funciones y clases del aplicativo
* [gentelella](https://github.com/midoju/compra-venta-inventario-CAS/tree/main/gentelella/gentelella) - Configuraciones de la plantilla Admin
    * [settings.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/gentelella/settings.py) - Configuraciones general de la Aplicación web

---
⌨️ Construido por [LuisMiguelJumbo](https://github.com/midoju) 😊
Gestion de compras, ventas e inventarios del Centro de Acopio Sabanilla

