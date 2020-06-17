ESTRUCTURA DEL C�DIGO FUENTE:
- Listado de paquetes a instalar y librer�as a importar
- Clases para la carga de datos y representaci�n de ejemplos (DataSet y Canvas)
- Clases del dominio del problema (Point y Circunference)
- Clases de resoluci�n y tratamiento de la soluci�n (ClusteringSolver y Solution)
- Clases de la interfaz de usuario (ClusteringUI)
- Generaci�n y resoluci�n de ejemplos utilizando el c�digo fuente
- Carga y resoluci�n de ejemplos utilizando el c�digo fuente
- Interfaz de usuario para generaci�n y resoluci�n de ejemplos
- Interfaz de usuario para carga y resoluci�n de ejemplos
- C�digo descartado (Versi�n iterativa del algoritmo y B�squeda de puntos para el Circuncentro)

USO DEL C�DIGO FUENTE:
- En el c�digo fuente existe una secci�n con llamada Ejemplos donde se detalla como utilizar el c�digo para la generaci�n, carga y resoluci�n de ejemplos.

USO DE LA INTERFAZ DE USUARIO:
Por cada punto hay que ejecutar esa secci�n d�ndole a "Run Interact".

Generaci�n y resoluci�n:
1. Se seleccionan el n�mero de circunferencias, el rango del radio de estas y n�mero de puntos de cada una. Si el n�mero de circunferencias es mayor que 6, al mostrarse la soluci�n, puntos pertenecientes a mismas circunferencias pueden aparecer del mismo color. Tras ejecutarlo se mostrar� el ejemplo generado.
2. Se introduce la ruta donde se guardar� el archivo .csv con el ejemplo, el porcentaje de puntos eliminados y la cantidad de ruido. Importante que la ruta incluya la extensi�n del fichero ".csv". Tras ejecutarlo se mostrar� el ejemplo modificado
3. Se seleccionan el n�mero de generaciones, n�mero de clusters, la precisi�n, el m�ximo n�mero de iteraciones, el m�todo para calcular las circunferencias (c = Circuncentro, b = Baricentro) y el m�nimo grado de pertenencia que no consideramos ruido. Tras ejecutarlo se mostrar� la soluci�n.

Carga y resoluci�n:
1. Se introduce la ruta donde se encuentra guardado el archivo .csv con el ejemplo. Tras ejecutarlo se mostrar� el ejemplo cargado.
2. Se seleccionan el n�mero de generaciones, n�mero de clusters, la precisi�n, el m�ximo n�mero de iteraciones, el m�todo para calcular el las circunferencias (c = Circuncentro, b = Baricentro) y el m�nimo grado de pertenencia que no consideramos ruido. Tras ejecutarlo se mostrar� la soluci�n.

FORMATO DE LOS ARCHIVOS .CSV:
- Archivos .csv generados: Poseen una �nica columna. La primera fila corresponde con las cabeceras, concretamente, "Coord X,Coord Y,Circulo". El resto de filas son las coordenadas X e Y de cada punto y el c�rculo al que pertenecen de los generados aleatoriamente. Un ejemplo de una de estas filas ser�a: "29.521215663645105,65.8654626993763,Circulo5".
- Archivos .csv que pueden ser cargados: Archivos con el formato mencionado anteriormente y aquellos eliminando la cabecera "Circulo". La primera fila corresponde con las cabeceras, concretamente, "Coord X,Coord Y". El resto de filas son las coordenadas X e Y de cada punto. Un ejemplo de una de estas filas ser�a: "29.521215663645105,65.8654626993763".

REPRODUCCI�N DE EXPERIMENTOS:
Se recomienda utilizar la interfaz de usuario de carga y resoluci�n. Habr�a que utilizar los archivos .csv que se aportan y seleccionar los par�metros presentes en las tablas de cada ejemplo en la documentaci�n; as� como en el pie de foto de las capturas de los resultados.
