


**• Marginal P(A):**  
Cuando obtienes una probabilidad sencilla. Puede obtenerse a partir de una probabilidad conjunta.  **Ejemplos típicios:**  
Probabilidad de obtener cara en una moneda  
Probabilidad de obtener “2” en un dado  
Probabilidad de que el día este soleado  
Probabilidad de ganar la lotería.


Primero: La probabilidad marginal **ES** una probabilidad tradicional. Esto es, en un entorno en que el evento es independiente, seguirá la forma  
Probabilidad marginal = Número de eventos exitosos / Número de eventos posibles

Dicho esto, veamos qué pasa cuando la probabilidad marginal **depende** de otro eventos o factores y esos factores son mutuamente excluyentes:

Cuando la probabilidad marginal depende de eventos mutuamente excluyentes, construiremos esta probabilidad marginal a partir de sumar todos los posibles eventos mutuamente excluyentes hasta haber contemplado nuevamente la totalidad de mi Espacio Muestral (O Universo).

Es decir, si tengo una población de 100 personas en un país y un político quiere saber cuánta gente votará por él, deberá considerar dos poblaciones diferentes: la población de gente que está afiliada a su partido (supongamos que son 30/100) y la población de gente que NO está afiliada a su partido (supongamos que es 70/100).

Sólo si toma en cuenta estas dos poblaciones este político obtendrá datos sobre el 100% de su población (70/100 + 30/100) y podrá obtener la probabilidad GLOBAL de que la gente que vote por él **INDEPENDIENTEMENTE** de si son de su partido o no.

Pongamos que de su partido (que son 30 personas), 30 votarán por él. Pero de fuera de su partido (que son 70 personas), 35 votarán por él.  
El cálculo para obtener la probabilidad marginal (independiente de eventos externos) de que la gente en su país vote por él se hará de la siguiente forma:  
P(A) = P(A|B1) P(B1) + P(A|B2) P(B2)  
Que se lee> Probabilidad de que la gente vote por el político es igual a: (La probabilidad de que la gente vote por él siendo de su partido, multiplicado por la probabilidad de que una persona sea de su partido) + (La probabilidad de que la gente vote por él NO siendo de su partido, multiplicado por la probabilidad de que una persona NO sea de su partido)

Sustituyendo los valores del problema:  
P(A) = (30/30)(30/100) + P(35/70)(70/100) = (1)(0.3) + (0.5)(0.7) =0.3 + 0.35 = 0.65  
Esto es: La probabilidad de que una persona vote por este político, ahora **INDEPENDIENTEMENTE** de que sea de su partido o no es de 0.65 (65%). Tomando en cuenta que esto fue calculado  **A PARTIR DE DATOS QUE ERAN DEPENDIENTES**  de la afiliación política de los pobladores.

Esto mismo puede ser aplicado a calcular la probabilidad de que el dado A salga par, sumando el supuesto de que el dado B sea par con el supuesto de que el dado B sea impar. El resultado final será la probabilidad de que el dado A salga par en general, sin importar si el dado B es par o impar.

**• Conjunta P(A,B):**  
Es la unión de sucesos. (En inglés: joint)  
$$P(A,B)=P(A\& B) = P(A\cap B)$$
**Ejemplos típicos**  
Probabilidad de obtener un número par y un número impar al lanzar dos dados.  
Probabilidad de que el día este soleado y el cielo despejado.  
Probabilidad de que el día este soleado con algo de nubes.  
Probabilidad de sacar un dulce rojo y otro azul.

**• Condicional P(A|B):**  
Que suceda un evento dado que ocurre otro previamente. 
$$P(A| B)$$ 
**Ejemplos típicos**  
Probabilidad de obtener en un dado “3”, dado que primero se obtuvo un "4"  
Probabilidad de que llueva hoy, dado que ayer estuvo muy nublado.  
Probabilidad de que llueva hoy, dado que el cielo está soleado (hoy).  
Probabilidad de que llueva mañana, por que en la ciudad vecina llovió ayer.  
Probabilidad de tener una enfermedad mental, después del abuso de sustancias.

**Regla del producto**  
$P(A,B) = P(A|B) P (B)$
