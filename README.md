![](logo.png)
# Actividad 01 - Estadística Univariada

* Para poder realizar esta actividad debes haber revisado la lectura correspondiente a la semana.
* Crea una carpeta de trabajo y guarda todos los archivos correspondientes (notebook y csv).
* Una vez terminada la actividad, comprime la carpeta y sube el `.zip` a la sección correspondiente.

## Ejercicio 1: Hola Mundo

* Utilice el método `print` para retornar la siguiente línea:

> Hola Mundo, esta es mi primera incursión en Python

## Ejercicio 2: Ingreso de variables
* Ahora ingrese una serie de datos respecto a su información personal. Esta información debe estar ingresada en variables para su posterior uso. Ingrese los siguientes datos:
    - Su nombre
    - Edad
    - Una lista con sus 3 actividades favoritas.
    - ¿Tiene mascotas?

## Ejercicio 3: Imprimiendo Variables
* Imprima cada variable creada
    - Acceda al segundo elemento de su lista
* Pida los tipo de datos asociados
* Interpole los datos en un método print para generar una presentación sobre usted.

## Ejercicio 4: A continuación se presenta una serie de códigos que generan errores. Corrígalos y comente cuáles fueron las fallas


```python
print('Estaba la pájara pinta sentada en el verde limón)
```


```python
print('Mi nombre es' name 'y tengo' edad, 'años')
```


```python
import padnas as pd
import nunnpy as np
```


```python
"Ornitorrinco" + 45
```

## Ejercicio 5: Utilizando `pandas` y `numpy`

* Importe `pandas` y `numpy` siguiendo la nomenclatura enseñada.
* Posteriormente importe el archivo `flights.csv` y guardelo en un objeto llamado `df`.
* Solicite las primeras y últimas 5 observaciones del objeto `df` creado.
* Utilice `describe` para obtener las medidas univariadas de la columna `year`.
* Utilice `value_counts` para obtener la frecuencia de meses y años de la tabla.
* Guarde en variables las primeras y últimas 15 observaciones de la tabla.
* Solicite la media, mediana y desviación estandar de la cantidad de pasajeros utilizando los métodos de `numpy`. Replique el procedimiento para las últimas y primeras 15 observaciones. Comente brevemente los resultados.

