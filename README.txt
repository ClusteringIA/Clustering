ESTRUCTURA DEL CÓDIGO FUENTE:
- Listado de paquetes a instalar y librerías a importar
- Clases para la carga de datos y representación de ejemplos (DataSet y Canvas)
- Clases del dominio del problema (Point y Circunference)
- Clases de resolución y tratamiento de la solución (ClusteringSolver y Solution)
- Clases de la interfaz de usuario (ClusteringUI)
- Generación y resolución de ejemplos utilizando el código fuente
- Carga y resolución de ejemplos utilizando el código fuente
- Interfaz de usuario para generación y resolución de ejemplos
- Interfaz de usuario para carga y resolución de ejemplos
- Código descartado (Versión iterativa del algoritmo y Búsqueda de puntos para el Circuncentro)

USO DEL CÓDIGO FUENTE:
- En el código fuente existe una sección con llamada Ejemplos donde se detalla como utilizar el código para la generación, carga y resolución de ejemplos.

USO DE LA INTERFAZ DE USUARIO:
Por cada punto hay que ejecutar esa sección dándole a "Run Interact".

Generación y resolución:
1. Se seleccionan el número de circunferencias, el rango del radio de estas y número de puntos de cada una. Si el número de circunferencias es mayor que 6, al mostrarse la solución, puntos pertenecientes a mismas circunferencias pueden aparecer del mismo color. Tras ejecutarlo se mostrará el ejemplo generado.
2. Se introduce la ruta donde se guardará el archivo .csv con el ejemplo, el porcentaje de puntos eliminados y la cantidad de ruido. Importante que la ruta incluya la extensión del fichero ".csv". Tras ejecutarlo se mostrará el ejemplo modificado
3. Se seleccionan el número de generaciones, número de clusters, la precisión, el máximo número de iteraciones, el método para calcular las circunferencias (c = Circuncentro, b = Baricentro) y el mínimo grado de pertenencia que no consideramos ruido. Tras ejecutarlo se mostrará la solución.

Carga y resolución:
1. Se introduce la ruta donde se encuentra guardado el archivo .csv con el ejemplo. Tras ejecutarlo se mostrará el ejemplo cargado.
2. Se seleccionan el número de generaciones, número de clusters, la precisión, el máximo número de iteraciones, el método para calcular el las circunferencias (c = Circuncentro, b = Baricentro) y el mínimo grado de pertenencia que no consideramos ruido. Tras ejecutarlo se mostrará la solución.

FORMATO DE LOS ARCHIVOS .CSV:
- Archivos .csv generados: Poseen una única columna. La primera fila corresponde con las cabeceras, concretamente, "Coord X,Coord Y,Circulo". El resto de filas son las coordenadas X e Y de cada punto y el círculo al que pertenecen de los generados aleatoriamente. Un ejemplo de una de estas filas sería: "29.521215663645105,65.8654626993763,Circulo5".
- Archivos .csv que pueden ser cargados: Archivos con el formato mencionado anteriormente y aquellos eliminando la cabecera "Circulo". La primera fila corresponde con las cabeceras, concretamente, "Coord X,Coord Y". El resto de filas son las coordenadas X e Y de cada punto. Un ejemplo de una de estas filas sería: "29.521215663645105,65.8654626993763".

REPRODUCCIÓN DE EXPERIMENTOS:
Se recomienda utilizar la interfaz de usuario de carga y resolución. Habría que utilizar los archivos .csv que se aportan y seleccionar los parámetros presentes en las tablas de cada ejemplo en la documentación; así como en el pie de foto de las capturas de los resultados.
