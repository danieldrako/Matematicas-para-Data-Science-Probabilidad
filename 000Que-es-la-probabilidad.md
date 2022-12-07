# **¿Qué es probabilidad?**

La probabilidad siempre se usa en situaciones donde hay incertidumbre. La incertidumbre es la toma de decisiones con información incompleta, como por ejemplo los juegos de azar.

>*"El azar no es más que la medida de  nuestra ignorancia. Los fenómenos fortuitos son, por definición, aquellos cuyas leyes ignoramos"*- Henri Poincaré	 							

El azar en este contexto, representa la ausencia del conocimiento de todas las variables que componen un sistema.

La probabilidad es una creencia que tenemos sobre la ocurrencia de eventos elementales. **Es un lenguaje que nos da herramientas para cuantificar la incertidumbre.**

#### ¿En qué casos usamos la probabilidad?

Intuitivamente, hacemos estimaciones de la probabilidad de que algo ocurra o no, al desconocimiento  que tenemos sobre la información relevante de un evento lo llamamos incertidumbre.

### AXIOMAS:  
Es un conjunto de sentencias que no son derivables de algo más fundamental. Las damos por verdad  
y no requieren demostración.

-   “A veces se compara a los axiomas con semillas, porque de ellas surge toda la teoría”

----------

### AXIOMAS DE PROBABILIDAD :

La probabilidad está dada por el número de casos de éxito sobre la cantidad total(teórica) de casos.

-  $$ P = \frac{\text{Casos de éxito}} {\text{Casos totales}}$$
    
-   **Suceso elemental**: Es una única ocurrencia, *“El resultado de lanzar el dado es 4”*
    
-   **Sucesos**: Son las posibilidades que tenemos en el sistema. Está compuesto de sucesos elementales,   por ejemplo, *“El resultado de lanzar un dado es par”*, hay tres sucesos (2,4,6) que componen este enunciado.

-   **Espacios muestral**: Un conjunto donde están incluidas todas las posibles ocurrencias de un evento aleatorio .
    

----------

-   De la interpretación del axioma anterior divergen dos escuelas de pensamiento.  **Frecuentista y Bayesiana**
    
-   Ejemplo: *“Solo tengo dos posibles resultados al lanzar una moneda, 50% de probabilidad para cada cara , $(1/2 , 1/2)$, si lanzo la moneda $n$ veces, la moneda no cae la mitad de las veces en una cara, y luego la otra”*
    

-   Esta equiprobabilidad de ocurrencia en un espacio muestral ocurre bajo el supuesto de que  
    la proporción de exitos/totales tiende a un valor $P$. En otras palabras, solo lanzando la moneda  
    infinitas veces podemos advertir que el valor de la probabilidad es cercano a $1/2$ o $50%$.

----------

**Escuela frecuentista**

*“Toda variable aleatoria viene descrita por el espacio muestral que contiene todos los posibles sucesos de ese problema aleatorio.”*

La probabilidad que se asigna como un valor a cada posible suceso tiene varias propiedades por cumplirse

#### PROPIEDADES AXIOMAS:

-   $0 \leq P \leq 1$
-   $Certeza: P = 1$
-   $Imposibilidad:P = 0$
-   $\text{Disyunción:} P(A\cup B) = P(A) +P(B)$