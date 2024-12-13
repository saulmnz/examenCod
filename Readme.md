# Examen 1ª Evaluación :rocket: :rocket:

---

# Imágenes Ordinograma Apartado 1 =


![Primera Imagen Ordinograma](./foto1.png)
![Primera Imagen Ordinograma](./foto2.png)
![Primera Imagen Ordinograma](./foto3.png)

# Como es el tablero? Apartado 2 =
```java
int [] [] tablero = {0, 1, 0, 1, 0, 1, 0, 1},
{1, 0, 1, 0, 1, 0, 1, 0},
{0, 1, 0, 1, 0, 1, 0, 1},
{0, 0, 0, 0, 0, 0, 0, 0},
{0, 0, 0, 0, 0, 0, 0, 0},
{2, 0, 2, 0, 2, 0, 2, 0},
{0, 2, 0, 2, 0, 2, 0, 2}, 
{2, 0, 2, 0, 2, 0, 2, 0};

`tablero [i][j] = 1 (Fichas Negras)`
`tablero [i][j] = 2 (Fichas Blancas)` 
```

# Enumera funciones Apartado 3 =

- public static int [] recorrerTablero = Recorrerá el tablero e indicará la casilla ocupada por una pieza, indicará si es negra o blanca.
    Parámetros = (int [][] tablero) ("Hay que referenciarle en memoria el parámetro que hace referencia al tablero (array) bidimensional")
    Return = Que nos devuelva un nuevo array hecho del contador de fichas negras y blanca = return new int [] {contadorNegras, ContadorBlancas}
    
- public static void imprimirTablero = Imprimirá el estado del tablero para consultarlo ( está función no retornará nada, será void)
    Parámetros = (int [][] tablero) ("Hay que referenciarle en memoria el parámetro que hace referencia al tablero (array) bidimensional")

- public static void mostrarResultado = Muestra el resultado de el conteo de las piezas tanto negras como blancas, compara si contador de piezas negra o blanca es mayor o menor una que la otra y entonces imprime que color de piezas va ganando ( De ser el mismo  numero de piezas entonces la función devoltará que van empatados )
    Parámetros = Parámetros = (int [][] tablero) ("Hay que referenciarle en memoria el parámetro que hace referencia al tablero (array) bidimensional")

# Javadoc Apartado 4 =
```java

**recorrerTablero =**

/**  
*Función = Recorrerá el tablero e indicará la casilla ocupada por una pieza, indicará si es negra o blanca.  
*@param = int [][] tablero referenciarle en memoria el parámetro del tablero (array) bidimensional  
*@return = Nos devuelva un nuevo array hecho del contador de fichas negras y blanca = return new int [] {contadorNegras, ContadorBlancas}  
*/

**imprimirTablero =** 

/**  
*Función que Imprime el estado del tablero para consultarlo  
*@param = int [][] tablero referenciarle en memoria el parámetro del tablero (array) bidimensional  
*/

**mostrarResultado =** 

/**  
*Función que muestra el resultado de el conteo de las piezas tanto negras como blancas, compara si contador de piezas negra o blanca es mayor o menor una que la otra y entonces imprime que color de piezas va ganando ( De ser el mismo numero de piezas entonces la función devoltará que van empatados )  
*@param = int [][] tablero referenciarle en memoria el parámetro del tablero (array) bidimensional  
*/
```