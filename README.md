# Proyecto de Evaluación - Módulo 2: Big Data Analyst

Este proyecto recoge el trabajo práctico correspondiente a la evaluación del Módulo 2, estructurado en dos bloques principales de ingeniería y análisis de datos utilizando Python (Pandas y SQLAlchemy) y MySQL.

## 🛠️ Estructura del Proyecto

El desarrollo se encuentra unificado en un cuaderno de Jupyter Notebook:
* `ejercicioFINAL_MODULO_2.ipynb`: Contiene todo el código fuente documentado, la extracción de datos y las consultas relacionales secuenciales.

---

## 🚀 Cómo arrancar el proyecto

Para ejecutar este proyecto en tu entorno local, sigue estos pasos:

### 1. Requisitos Previos
Es necesario tener instalado:
* **Python 3.x**
* **MySQL Server** (con los esquemas correspondientes activos en local)
* **Visual Studio Code** (con las extensiones de *Jupyter* habilitadas)

### 2. Instalación de Dependencias
Abre la terminal en la raíz del proyecto e instala las librerías necesarias ejecutando:
```bash
pip install pandas sqlalchemy mysql-connector-python
```

### 3. Configuración de la Base de Datos
1. Asegúrate de que tu servidor MySQL local esté corriendo.
2. Verifica que dispones del esquema `sakila` cargado en tu entorno local.
3. El motor de conexión en el cuaderno está parametrizado por defecto mediante SQLAlchemy con la siguiente estructura de URI:
   `mysql+mysqlconnector://root:Linda@localhost/sakila`


### 4. Ejecución
Abre el archivo `ejercicioFINAL_MODULO_2.ipynb` en VS Code y ejecuta las celdas secuencialmente de arriba a abajo utilizando `Shift + Enter`.