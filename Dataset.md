1. Título: Vino de Calidad

2. Fuentes
   Creado por: Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos y José Reis (CVRVV) @ 2009
   
3. Uso Pasado:

  P. Cortés, A. Cerdeira, F. Almeida, T. y J. Matos Reis.
  Modelar las preferencias de vino por la minería de datos de las propiedades físico-químicas.
  En Decision Support Systems, Elsevier, 47 (4): 547-553. ISSN: 0167-9236.

  En la referencia anterior, se crearon dos conjuntos de datos, usando muestras de vinos tintos y blancos.
  Las entradas incluyen pruebas objetivas (por ejemplo, valores de pH) y la salida se basa en datos sensoriales
  (Mediana de al menos 3 evaluaciones realizadas por expertos del vino). Cada experto calificó la calidad del vino
  entre 0 (muy malo) a 10 (muy excelentes). Varios métodos de minería de datos se aplicaron para modelar
  estos conjuntos de datos bajo un enfoque de regresión. El modelo de máquina de vectores de soporte logra la
  mejores resultados. Varios indicadores se calcularon: MAD, matriz de confusión para una tolerancia de error fijo (T),
  etc. Además, representamos gráficamente las importancias relativas de las variables de entrada (medida por una sensibilidad
  Procedimiento de análisis).
 
4. Información pertinente:

   Los dos conjuntos de datos se relacionan con variantes rojas y blancas del vino portugués "Vinho Verde".
   Para más detalles, consultar: http://www.vinhoverde.pt/en/ o la referencia [Cortés et al., 2009].
   Debido a cuestiones de privacidad y logística, sólo físico-química (entradas) y sensorial (la salida) las variables
   están disponibles (por ejemplo, no hay datos acerca de los tipos de uva, vino de marca, precio de venta de vino, etc.).

   Estos conjuntos de datos se pueden ver como las tareas de clasificación o regresión.
   Las clases están ordenados y no equilibrada (por ejemplo, hay masque vinos más normal que
   excelente o los pobres). los algoritmos de detección de valores atípicos se podrían utilizar para detectar los pocos excelente
   o vinos pobres. Además, no estamos seguros de si todas las variables de entrada son relevantes. Asi que
   podría ser interesante para poner a prueba los métodos de selección de características.

5. Número de instancias: el vino tinto - 1599; Vino blanco - 4898.
6. Número de Atributos : 11 + salida de atributos
  
   Nota : varios de los atributos pueden correlacionarse , por lo tanto, tiene sentido aplicar algún tipo de
   selección de características.

7. La información de atributos :

   Para obtener más información, lea [ Cortés et al . , 2009] .

   Las variables de entrada ( sobre la base de las pruebas fisicoquímicas ):
   1 - acidez fija
   2 - acidez volátil
   3 - ácido cítrico
   4 - azúcar residual
   5 - cloruros
   6 - dióxido de azufre libre
   7 - dióxido de azufre total
   8 - Densidad
   9 - pH
   10 - sulfatos
   11 - alcohol
   Magnitud de salida ( basado en datos sensoriales ) :
   12 - calidad ( puntuación entre 0 y 10 )

8. Los valores de atributos ausentes : Ninguno
