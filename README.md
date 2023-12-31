# **Proyecto de EDA, limpieza e inserción de datos**
## **Los 100.000 libros más leídos en Goodreads**
### **Lidya Descals**

---

Inicio del proyecto el 21/06/23.

Plan:
 - Realizar un EDA profundo del conjunto de datos.
 - Ejecutar una limpieza completa de los datos.
 - Insertar los datos en una BBDD en MySQL
 - Realizar con los datos depurados una serie de visualizaciones (¿Tableau o PowerBI?) mostrando los patrones subyacentes.

Notas:
 - El dataset original no he podido meterlo en este repositorio por su tamaño. Lo tengo guardado en local y lo llamo desde el primer notebook. A continuación, después de procesarlo, sí que reduce su tamaño lo suficiente como para poder guardar una copia del csv ya limpio, que se encuentra en la carpeta "data".

Diario de desarrollo:

 - 23/06/23: Descubro que la columna del EAN13 es inservible desde la fuente original, puesto que, en algún momento previo a la publicación del dataset en Kaggle, se puso esta columna en formato numérico y se adaptó a la notación científica, eliminando así el número identificativo. Por tanto, la desecho en la limpieza.

 - 26/06/23: Prosigo la transformación de los datos, eliminando otras columnas que no son de interés e imputando los nulos.

 - 02/07/23: Guardo el csv con el dataframe procesado y limpio. 

   
