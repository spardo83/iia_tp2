# IIA - TP2

#### Integrantes

- Gimenez, Pablo Eduardo
- Pardo, Sebastián
- González, Martín
- Brazón, Josmar
- Losada, Ricardo
- Meoli, Lucas Pablo

#### Consigna
Se requiere construir un modelo de regresión que permita predecir el valor medio de las casas en distintos distritos de California, EE. UU. (medido en cientos de miles de dólares, es decir, $100,000). Este conjunto de datos proviene del censo de EE. UU. de 1990, donde cada observación corresponde a un bloque. Un bloque es la unidad geográfica más pequeña para la cual la Oficina del Censo de EE. UU. publica datos de muestra, y típicamente tiene una población de entre 600 y 3.000 personas.

Los atributos, en el orden en que se presentan en el conjunto de datos, son:

- __MedInc:__ Ingreso medio en el bloque
- __HouseAge:__ Edad mediana de las casas en el bloque
- __AveRooms:__ Número promedio de habitaciones por hogar
- __AveBedrms:__ Número promedio de dormitorios por hogar
- __Population:__ Población del bloque
- __AveOccup:__ Número promedio de personas por hogar
- __Latitude:__ Latitud del bloque
- __Longitude:__ Longitud del bloque

El target es:

__MedHouseVal:__ Mediana del valor de las casas en el bloque (en unidades de $100,000)
#### Tareas y preguntas a resolver:

Obtener la correlación entre los atributos y entre los atributos y el target.
* ¿Qué atributo tiene mayor correlación lineal con el target? 
* ¿Cuáles atributos parecen estar más correlacionados entre sí? Se pueden calcular los coeficientes de correlación o representarlos gráficamente mediante un mapa de calor.
* Graficar los histogramas de los distintos atributos y del target. 
* ¿Qué forma presentan los histogramas?
* ¿Alguno muestra una distribución similar a una campana que sugiera una distribución gaussiana, sin necesidad de realizar pruebas de hipótesis?
* Calcular una regresión lineal utilizando todos los atributos. 
* Con el conjunto de entrenamiento, calcular la varianza total de los datos y la varianza explicada por el modelo.
* ¿Está el modelo capturando adecuadamente el comportamiento del target? Fundamente su respuesta.
* Calcular las métricas de MSE, MAE y R² sobre el conjunto de evaluación.
* Crear una regresión de Ridge. 
* Usar validación cruzada de 5 folds y tomar como métrica el MSE.
* Buscar el mejor valor de α en el rango [0, 12.5].
* Graficar el MSE en función de α.
* Comparar los resultados obtenidos entre la regresión lineal y la mejor regresión de Ridge, evaluando el conjunto de prueba.
* ¿Cuál de los dos modelos obtiene mejores resultados en términos de MSE y MAE? ¿Poseen suficiente diferencia como para indicar si uno es mejor que el otro?
* ¿Qué tipo de error podría haberse reducido?