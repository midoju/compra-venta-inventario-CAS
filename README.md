# Gesti贸n de compras, ventas e inventarios

_El siguiente proyecto se realiza en respuesta a la creaci贸n de una soluci贸n informatica para la gestion de procesos de operaci贸n de compras, ventas e inventario del centro de acopio Sabanilla_

## Comenzando 馃殌

_Para empezar a usar el proyecto configurar un virtualenv y activar._
## Obtener el codigo
```
git clone https://github.com/midoju/compra-venta-inventario-CAS.git
cd compra-venta-inventario-CAS
```

### Pre-requisitos 馃搵

_Instalaci贸n de los requerimientos necesarios para la ejecucion_

```
pip install -r requirements.txt
```

### Ejecutar el codigo 馃敡

_Ejecutar el codigo en un entorno de desarrollo_

```
cd gentelella
python manage.py runserver
```
## Despliegue 馃摝

_Para el despliegue en local del proyecto debe ir_

```
http://localhost:8000/
```
![2021-08-20 16_41_41-Window](https://user-images.githubusercontent.com/13515624/130297038-93ce96af-8be9-4035-84b3-7baef97c45d2.png)



## Construido con 馃洜锔?

_La plantilla de adimistraci贸n usada para crear ese proyecto es_

* [Gentelella Admin](https://github.com/GiriB/django-gentelella) - Plantilla Admin usado.
* [Python](https://www.python.org) - Lenguaje de programacion basica.
* [Django](https://www.djangoproject.com) - Framework de Python para la contruccion de aplicaciones web de alto nivel.

## Flujo de archivos 馃搵
* [app](https://github.com/midoju/compra-venta-inventario-CAS/tree/main/gentelella/app) - Aplicativo web
    * [static](https://github.com/midoju/compra-venta-inventario-CAS/tree/main/gentelella/app/static) - Carpeta con los plugins instalados 
    * [templates](https://github.com/midoju/compra-venta-inventario-CAS/tree/main/gentelella/app/templates) - Carpeta con los plantillas del fronted
    * [forms.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/app/forms.py) - Formularios de creaci贸n y edici贸n
    * [models.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/app/models.py) - Modelado de base de datos
    * [urls.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/app/urls.py) - Direcciones url del aplicativo web
    * [views.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/app/views.py) - Control de funcionamiento del las funciones y clases del aplicativo
* [gentelella](https://github.com/midoju/compra-venta-inventario-CAS/tree/main/gentelella/gentelella) - Configuraciones de la plantilla Admin
    * [settings.py](https://github.com/midoju/compra-venta-inventario-CAS/blob/main/gentelella/gentelella/settings.py) - Configuraciones general de la Aplicaci贸n web

---
鈱笍 Construido por [LuisMiguelJumbo](https://github.com/midoju) 馃槉
Gestion de compras, ventas e inventarios del Centro de Acopio Sabanilla

