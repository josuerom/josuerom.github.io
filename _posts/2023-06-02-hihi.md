### RAMANUJAN TOTAL: 1 + 2 + 3 + ⋯ + ∞ = -1/12?
#### Marcos Dodds
=========
> “¿De qué diablos estás hablando? ¡Esto no puede estar bien!" - Mi madre

Lo dijo cuando le hablé de esta extraña ecuación matemática. Y simplemente, es una ecuación irregular. Realmente, convirtió la lógica básica en una farsa. ¿Cómo es que cuando sumamos números enteros positivos, obtenemos no solo un número negativo, sino también una fracción negativa? ¿Cuál es esa fracción?
Antes de continuar: Cuando me hablaron de esto, se dijo que en ese momento la palabra 'total' ya no tenía sentido común. Como todas las series de números con las que me encuentro no suelen converger en un número concreto, hablaremos de otro tipo de suma, la Suma de Cesàro. Además para cualquier interesado en las matemáticas, la suma de Cesàro asignará valores a algunas series de números que no convergen en el sentido habitual. "La suma de Cesàro se define como el límite de la media aritmética de las primeras n sumas parciales de una serie cuando n tiende a infinito" — Wikipedia. También me gustaría decir que a lo largo de este artículo solo usaré el concepto de infinito contable, que es un tipo de infinito que involucra un conjunto infinito de números finitos que, dado el tiempo suficiente, podrías contar hasta cualquier número en ese conjunto. . Esto me permite usar algunas de las propiedades habituales de las matemáticas en mis ecuaciones, como la conmutatividad (que usaré a lo largo del artículo).
Si eres nuevo en la serie de números llamada Ramanujan Sum, lleva el nombre de un famoso matemático indio, Srinivasa Ramanujan. Esta suma muestra que si sumamos todos los números naturales, 1, 2, 3, 4, etc., hasta el infinito, obtenemos -1/12. Halo, -0.083333333333 ahí.
> (-1) = 1 + 2 + 3 + 4 + ..... = -1/12

¿No me crees? Sigue leyendo para ver cómo lo hago, probaré dos proposiciones igualmente locas:
> 1. 1 – 1 + 1 – 1 + 1 – 1 = 1/2

> 2. 1 – 2 + 3 – 4 + 5 – 6 = 1/4

Primero, tienes que estar preparado. El verdadero milagro está por suceder, de hecho no podemos probar las otras dos proposiciones sin este párrafo.
Comenzaré con una secuencia de números A, igual a 1 – 1 + 1 – 1 + 1 – 1 repetido un número infinito de veces. Lo escribo como:
> UN = 1 – 1 + 1 – 1 + 1 – 1⋯

Y haz un poco de técnica. Tomemos 1 menos A
> 1 – A = 1 - (1 – 1 + 1 – 1 + 1 – 1⋯)

Todo salió muy bien, ¿no? Y aquí está el clímax. Si reduzco el lado derecho de la ecuación, obtengo algo realmente genial:
> 1 – UN = 1 – 1 + 1 – 1 + 1 – 1 + 1⋯

¿Te parece familiar? Si ya lo has olvidado, esa es la A. Bueno, el lado derecho de la ecuación es la serie de números que teníamos inicialmente. Así que puedo reemplazar el lado derecho con A y hacer un poco de álgebra de secundaria simple y luego ¡bum!
> 1 - A = A

> 1 – A + A = A + A

> 1 = 2A

> 1/2 = A

Esta bonita ecuación es la serie Grandi, llamada así por el matemático, filósofo y sacerdote italiano Guido Grandi. Ese es todo el contenido de esta serie, me encanta, aunque no hay una historia genial o historias interesantes detrás. Sin embargo, nos abrió la puerta para probar muchas otras cosas fascinantes, incluida una ecuación importante en la mecánica cuántica e incluso en la teoría de cuerdas. Pero eso es para más adelante. Ahora bien, demostremos 2 más: 1 – 2 + 3 – 4 + 5 – 6⋯ = 1/4.
Comenzando como arriba de mí, he establecido la serie B = 1 – 2 + 3 – 4 + 5 – 6⋯. Y ahora podemos empezar a jugar un poco. Esta vez, en lugar de restar B de 1, restaremos A menos B y obtendremos:
> A - B = (1 – 1 + 1 – 1 + 1 – 1⋯) — (1 – 2 + 3 – 4 + 5 – 6 )

> A - B = (1 – 1 + 1 – 1 + 1 – 1⋯) — 1 + 2 – 3 + 4 – 5 + 6⋯

Cambiaremos un poco los términos y veremos surgir muchas reglas interesantes.
> A - B = (1 – 1) + (–1 + 2) + (1 – 3) + (–1 + 4) + (1 – 5) + (–1 + 6)⋯

> A - B = 0 + 1 – 2 + 3 – 4 + 5⋯

Y de nuevo, tenemos la secuencia con la que empezamos, y encima de eso, hemos probado A = 1/2, así que usamos un poco más de álgebra básica y obtenemos la paridad Esta segunda sorpresa.
> A - B = B

> A = 2B

> 1/2 = 2B

> 1/4 = SOBRE

¡Oh, no! Esta ecuación no tiene un nombre elegante, como muchos matemáticos han demostrado a lo largo de los años, siempre se ha considerado una paradoja matemática. Hubo un acalorado debate académico en ese momento con respecto a esta ecuación, aunque contribuyó a la extensión del trabajo de Euler sobre el problema de Basilea y la creación de funciones importantes como la función Zeta Reimann.
Ahora llega la sublimación que estabas esperando. Volvemos a poner la serie C = 1 + 2 + 3 + 4 + 5 + 6⋯ y, como puedes adivinar, le restamos C a B.
> segundo - do = (1 – 2 + 3 – 4 + 5 – 6⋯) - (1 + 2 + 3 + 4 + 5 + 6⋯)

Y las matemáticas aún no han terminado, vamos a reorganizar algunos términos para crear algo familiar, pero tal vez no sea lo que espera.
> segundo - do = (1 - 2 + 3 - 4 + 5 - 6⋯) - 1 - 2 - 3 - 4 - 5 - 6⋯

> B - C = (1 - 1) + (-2 - 2) + (3 - 3) + (-4 - 4) + (5 - 5) + (-6 - 6)

> B - C = 0 - 4 + 0 - 8 +