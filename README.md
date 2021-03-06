# Lab-Circuitos-
Informes y videos del laboratorio de circuitos

Objetivos
Generales:

•	Explicar y demostrar teórica y practicamos las leyes de Kirchhoff

•	Comprender e experimentar el uso de los diferentes instrumentos de medición 

•	Mostrar prácticamente la función del circuito en un simulador

Específicos:

•	Utilizar correctamente los instrumentos de medición tomando en cuenta las recomendaciones explicadas en clase 

•	Mostrar la relación de que existe entre la teoría y la práctica de cada una de las leyes de Kirchhoff 

•	Entender la funcionalidad de cada uno de los componentes (resistencias, protoboars, multímetro, etc)

Requisitos previos
•	Análisis correcto de circuitos 

•	Verificación de la teoría para la aplicación en la practica 

•	Tener un conocimiento previo de la utilización de la instrumentación 


Marco Teórico 
Leyes de Kirchhoff
Son dos y junto con la ley de Ohm, definen el conjunto de ecuaciones que permiten resolver un circuito eléctrico más o menos complejo. Ambas leyes se basan en principios superiores como el principio de conservación de la carga eléctrica y el principio de conservación de la energía. Previamente al desarrollo de ambas leyes, será necesario definir algunos conceptos previos sobre lo que se llama topología de los circuitos.

•	Circuito o red eléctrica: Es todo conjunto de componentes dispuestos de distinta forma y por los cuales puede establecerse una corriente eléctrica

•	Concepto de nodo: Es todo punto de un circuito o red eléctrica donde confluyen dos o más corrientes. Si las corrientes son de tres en adelante se lo suele llamar nodo principal

•	Concepto de rama: Es todo componente de un circuito eléctrico, que se extiende entre dos nodos.

•	Concepto de malla: Es todo camino cerrado dentro de una red eléctrica.


Primera ley de Kirchhoff o ley de los nodos o de las corrientes

En el nodo A, se deberá cumplir, en la medida que la carga debe conservarse que la carga por unidad de tiempo, que llega a él debe ser igual a la carga por unidad de tiempo que sale del mismo nodo. En términos matemáticos escribiremos  i1  i2  i3  i4  0 donde la suma es algebraica, es decir, considerando su signo, positivo si ingre- san y negativo si salen. Desde un punto de vista más formal podemos introducir la simbología de sumatoria, es 
decir:	N ij  0, donde la letra sigma mayúscula representa a la suma algebraica de todas las corrientes desde la primera hasta la n-ésima. Insisto en que deben ser tomadas con su signo. Por lo tanto, esta primera ley permite, conociendo todas las corrientes menos una, determinar aquélla.

![Ley 1](https://user-images.githubusercontent.com/75337022/102905811-afec6400-4441-11eb-87ea-299f6c8689f1.jpg) 


Segunda ley de Kirchhoff o ley de las mallas o de las tensiones.
 
Como las diferencias de potencial están asociadas a energías, como vimos cuando estudiamos el tema, y como la energía debe conservarse, entonces se cumplirá que la suma algebraica de todas las diferencias de potencial, debe ser nula. Hay que definir cuándo las tomamos como positivas y cuándo, como negativas.
Una vez elegido el sentido de giro, consideraremos positiva a toda tensión que aparezca sobre un componente, fuente o resistencia, si con el recorrido elegido, pasamos de un potencial más bajo a otro más elevado. La consideraremos negativa si se da el caso contrario.
Analicemos el caso planteado en el dibujo, en el cual se ve un trozo de circuito eléctrico, dentro de una red eléctrica más grande. Antes de continuar, conviene observar que siempre, por donde ingresa la corriente en un elemento pasivo (resistencia), es el polo positivo y por donde sale es el negativo. Al revés sucede con un elemento activo o fuente, por donde sale es el positivo, ya que se requiere un mayor potencial para que al corriente salga de la batería. Lo anterior se observa en el diagrama siguiente:

![Ley 2](https://user-images.githubusercontent.com/75337022/102907174-a6fc9200-4443-11eb-80fa-03e8041a97f5.png) 

Como la fuente y la resistencia están en paralelo, deben conservar la polaridad

Dicho esto, podemos encarar el análisis de la malla anterior.
Supongamos partir de V1, con el sentido de recorrido adoptado C, pasamos de un punto de menor potencial a otro de mayor potencial, es decir, de - a +, por lo que deberá ser tomada como positiva. Siguiendo con el recorrido, pasamos ahora de un punto de mayor potencial sobre R2 a otro de menor potencial, es decir de + a -, por lo cual deberá ser adoptada como 
negativa, pues es una caída de tensión. Al llegar a V2, pasamos de + a -, por lo tanto, a pesar de tratarse de una fuente, deberá ser tomada como una caída de tensión. Con R1 ocurre algo análogo. Luego seguimos aplicando al resto de los componentes el mismo criterio, de manera que resultará la expresión siguiente: V1  I1R2  V2  I2R1  V3  I3R4  V4  I4R3  0 Debe quedar claro que si adoptáramos un sentido contrario de recorrido que el C, todos los signos serían contrarios, pero nada cambiaría, es sólo adoptar una “referencia” dis- tinta.
También se puede expresar en forma general mediante el símbolo de sumatoria, es decir:	         NVj  0 donde el
1
subíndice “j”varía entre 1 y N.


Material o equipo requerido

![Material](https://user-images.githubusercontent.com/75337022/102907299-da3f2100-4443-11eb-9736-be6072bcf91e.png) 

Diagramas

![Diagrama](https://user-images.githubusercontent.com/75337022/102907895-ad3f3e00-4444-11eb-89f5-78b8574cf2ea.png) 

 
Procedimiento 
•	Realice el circuito previamente visto en el diagrama a utilizar en este caso Tinkercad 

•	Con el multímetro procedemos a medir el voltaje en cada uno de las resistencias y tomamos nota de los resultadas en la tabla correspondiente.


•	El mismo multímetro lo usaremos para medir corriente, procedemos a medir la corriente en cada uno de las resistencias y coloque los resultados en la tabla correspondiente.

•	Luego con los valores obtenidos vamos a proceder a realizar los cálculos aplicando la teoría de las leyes de Kirchhoff


•	Con los valores obtenidos analizamos cada uno de los valores obtenidos y los valores medidos con lo cual realizamos una comparación 

![Diagrama_1](https://user-images.githubusercontent.com/75337022/102907971-c9db7600-4444-11eb-94ce-76cafd58084e.png) 


Tabulación de datos

![Tabla 1](https://user-images.githubusercontent.com/75337022/102908105-fbecd800-4444-11eb-90b9-5d701d33bf6e.png) 
![Tabla 2](https://user-images.githubusercontent.com/75337022/102908146-0a3af400-4445-11eb-8f7e-5339c2236476.png) 
![tabla 3](https://user-images.githubusercontent.com/75337022/102908192-1de65a80-4445-11eb-8a87-1418b1bf9b46.png) 

Cálculos

![calculos](https://user-images.githubusercontent.com/75337022/102908243-2ccd0d00-4445-11eb-9b18-8f28da56af3b.jpg) 
![calculos de error](https://user-images.githubusercontent.com/75337022/102908284-39e9fc00-4445-11eb-84f7-f4bb6afea926.jpg) 



Conclusiones

•	Utilizando un simulador es más fácil de comprender la funcionalidad del circuito asi mismo la comprensión de la teoría para poder plasmarla en los cálculos que realizamos con los datos obtenidos

•	Aprendimos a manejar es simulador Tinkercad con más variantes ahora ajustamos el voltaje la resistencia, etc a nuestro gusto pudiendo asi realizar los cálculos

•	Verificar y medir correctamente utilizando los instrumentos tomando en cuenta las indicaciones que previamente nos dio la persona encargada 


Recomendaciones 

•	Como sabemos Tinkercad tiene muchos valores ideales al momento de realizar la medición debemos procurar utilizar un simulador que nos de valores lo más acercado posible a la realidad para entender mejor la compresión 

•	Realizar el mismo circuito en un protoboard físicamente asi vamos a tener una mejor comprensión de lo que hicimos y también podremos apreciar el funcionamiento del mismo


Bibliografia 

Adrian Rosa A,2015, Leyes de Kirchhoff : http://www.adrosa.net/PDF/Electrotecnia/Leyes%20de%20Kirchhoff.pdf
Lifeder, 2020, Leyes de Kirchhoff: Primera y Segunda Ley (Con Ejemplos): https://www.lifeder.com/leyes-kirchhoff/

