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

Diario de desarrollo:

 - 23/06/23: Descubro que la columna del EAN13 es inservible desde la fuente original, puesto que, en algún momento previo a la publicación del dataset en Kaggle, se puso esta columna en formato numérico y se adaptó a la notación científica, eliminando así el número identificativo. Por tanto, la desecho en la limpieza.

   
