# Pec4-Jerley-Andres-Mejia
PEC4 proyecto programacion para la ciencia de datos

#  Programación para la Ciencia de Datos - PEC4

Este proyecto corresponde a la PEC4 de la asignatura Programación para la Ciencia de Datos. Como objetivo se busca realizar una serie de transformaciones, análisis y visualizaciones a partir de un conjunto de datos sobre embalses en Cataluña.

El proyecto está dividido en varios ejercicios, cada uno con funciones específicas que se pueden ejecutar todas juntas o paso a paso desde `main.py`.

---

##  Requisitos del sistema

- Python 3.8 o superior
- pip (instalador de paquetes)

---

##  Instalación del proyecto

### 1. Abrir la consola (cmd o PowerShell)  
Presiona `Win + R`, escribe `cmd` o `powershell` y presiona Enter.

### 2. Acceder a la carpeta del proyecto  
Ejemplo:

```bash
cd "C:\Users\jerle\OneDrive\Documents\Master\Programacion Para la ciencia de datos\proyect"

### 3. Para realizar la instalacion de requisitos desde la carpeta que contiene el proyecto

Asegúrate de estar dentro de la carpeta del proyecto (donde está el archivo requirements.txt) y ejecuta:

pip install -r requirements.txt

### 4. Ejecutar todo el proyecto completo
Desde la raíz del proyecto, ejecuta:
python main.py

### 4.1. Ejecutar el proyecto paso a paso ejecutando la siguiente linea deltro de la carpeta que contiene el proyecto

Se puede ejecutar cada ejercicio por separado (en orden, ya que dependen unos de otros). Usa el parámetro -ex seguido del número de ejercicio:

python main.py -ex 1
python main.py -ex 2
python main.py -ex 3
python main.py -ex 4
python main.py -ex 5


### 5. Ejecutar los tests

Ubícate dentro de la carpeta tests y ejecuta individualmente cada archivo de pruebas:

cd tests

python test_ejercicio1.py 
python test_ejercicio2.py 
python test_ejercicio3.py 
python test_ejercicio4.py 
python test_ejercicio5.py 

## Licencia 
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

## Para generar archivos html

pip install sphinx
se generan archivos .rst de la carpeta src con el siguiente comando:
sphinx-apidoc -o docs/source src

generar documentacion en formato html con el siguiente comando

sphinx-build -b html docs/source docs/build

visualizar la documentacion 

docs/build/index.html o abrelo desde el explorador de archivos 

## Captura de documentación generada

Captura de documentación (img/documentacion_JerleyAndresMejia index HTML)


## Instalacion como paquete 

en la raiz del programa ejecuta el siguiente comando:

pip install -e  .

#para descargar de github copia el siguiente enlace

https://github.com/Andresmejia11/pec4_JerleyMejia.git





Autor
Jerley Andres Mejia Gallo
Maestría en Ciencia de Datos – UOC
