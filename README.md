# examen1_fc1
Examen primer corte

## Examen A (Exoplantas)

- Ejercicio 1:
1. Lea el archivo de datos *sunspots.txt* que se encuentra 
   ubicado en el directorio: data/. Este archivo contienen
   la el número de manchas observadas en el sol desde 
   enero de 1979. La estructura de este archivos es: 
   columna 1, número del mes; columna 2, número de manchas 
   solares.

2. Haga una gráfica del número de manchas solares como
   función del tiempo. 

3. Haga una nueva gráfica pero esta vez mostrando los
   primeros 1000 datos.

4. Calcule el promedio de manchas solares de la siguiente
   forma:
   Y_k = \frac{1}{2r+1} \sum^{r}_{m=-r}{y_{k+m}}

   donde r=5; y_k corresponde al número de manchas solares.

5. Haga una nueva gráfica donde muestre los datos del punto
   3, y en la misma figura muestre los datos obtenidos en 4.

- Ejercicio 2:

1. El coeficiente binomial (n,k) = \frac{n!}{k!(n-k)!}.
   Donde k>=1, o (n,0)=1 para k=0. Escriba una función en
   python que calcule el éste coeficiente, recibiendo como 
   argumentos n y k. Asegure que el valor que retorna la
   función sea un entero y que para k=0 retorne 1.

2. La probabilidad que una moneda, lanzada n veces al aire,
   caiga con el símbolo cara hacia arriba es (n,k)/2^n.
Escriba un programa que calcule: (a) la probabilidad que una
moneda lanzada 100 veces caiga con el símbolo cara
exactamente 60 veces, y (b) la probabilidad que caiga 60 
veces o más con este mismo símbolo.


## Examen B (Difracción)

Ejercicio único:

El principio de Huygens establece que cada punto no 
obstruido en un frente de onda actuará como fuente de una
onda esférica secundaria. Teniendo en cuenta el principio de 
Superposición, la amplitud de la onda en cualquier punto más 
allá del frente de onda inicial es la superposición de las 
amplitudes de todas las ondas secundarias. 

1. Escriba un programa que calcule el patrón de difracción
   que se forma en una pantalla, ubicada a una distancia D=1
m, debido a la interacción de un frente de onda plana que 
llega una pared con dos agujeros separadas una distancia d=1
cm (ver figura difraccion.png). Asuma que la amplitud de la
onda es igual 1, la frecuencia (omega) 1 y la longitud de
onda (lambda) 1 cm. (E = A cos(kz)).

2. Realice una gráfica que presente la amplitud de la onda
   en la pantalla como función de la distancia.

3. Compare sus valores con los calculados analíticamente.
