# CONSUMOS.

![Consumos.PNG](/imgs/Consumos.PNG)

Como podras observar, he modificado sensiblemente la tabla de consumos. Es posible que le eches un vistazo para asegurar que no hay errores con las potencias de los elementos?? 
Tambien podras ver que hay una linea naranja para herramientas potentes. Mi intención por el momento es arrancar esos equipos con el generador de soporte que ya tenemos intencion de comprar. Es posible programar el sistema para que cuando detecte el pico de arranque de estas herramientas, directamente se arranque el generador?? Si mas adelante disponemos de medios para ampliar la instalacion de baterias, quizas lo haremos para prescindir del generador y utilizarlo unicamente como soporte.

# FACTOR DE SIMULTANEIDAD Y POTENCIA PICO.

Con los cambios incorporados, la suma de todos los consumos ha cambiado. El nuevo valor es **4990W** (Resultado columna verde). Por lo tanto, el factor de simultaneidad tambien se ve modificado:

> Fs = (700 + 1000) / 4990 = 0,34
> La potencia del inversor no deberia ser inferior a: 4990 * 0,34 = 1697W

En definitiva no parace un gran cambio por el momento. 

# CONSUMO FINAL CALCULADO.

Aqui me gustaria incorporar dos cambios:

1. Nuevo valor de consumo obtenido del total de la columna amarilla. **5800Wh/dia**.
2. La potencia puntual de un motor electrico me gustaria eliminarla. Como he dicho antes, las herramientas me gustaria que arrancaran con el generador y de esa manera reducir el total de energia consumida de la casilla **010**. Mis calculos con el rendimiento del 95% me dan un total de **6106Wh/dia**.

# PRODUCCION ENERGETICA.

## DATOS FOTOVOLTAICA.

Aqui, si es posible me gustaria modificar el valor de la casilla **019**, para ponernos en el caso mas desfaforable. En lugar de **2,33**, me gustaria introducir **2,00**.

Por lo demas estoy de acuerdo en sobredimensionar el 30% de la casilla **026**. Y tambien estoy de acuerdo en la casilla **027**.

De esa manera solamente seria necesario modificar la casilla **028** con el nuevo valor obtenido previamente de **6106Wh/dia**.
Supongo que quizas podemos reducir el numero de paneles a 6, con un total de potencia instalada de **2370Wp**?? Aunque esto realmente no se si nos interesa porque el precio de los paneles es asequible y disponemos de espacio en el tejado para instalar 8 sin problema. Ademas si disponemos de mas potencia instalada entiendo que tenemos mayor posibilidad de almacenamiento en baterias. No se si es correcto mi plamteamiento.

Tambien entiendo que si fueramos con 8 paneles, seguiriamos haciendo el mismo tipo de conexion (5 en serie + 3 en serie, ambos conjuntos conectados en paralelo), con el objetivo de mantener la tension del campo fotovoltaico en **207Vcc**. A no ser que me digas que seria mejor aumentar la tension del campo FV.

En cuanto a la corriente en el campo, porque la intensidad es la de una placa?? Si pones dos conjuntos en paralelo (uno de 5 panels en serie y otro de 2 en serie), el resultado de la casilla **035** no deberia ser **19A**?? Tambien tenia entendido que lo mejor seria conectarlos todos en serie o quizas esto aumenta demasiado el voltaje??

La distancia entre las placas y el regulador-inversor no sera mas de **20m** (Casilla **038**).

Sin problema en cuanto a las secciones de los cables.

# CAPACIDAD DE LA BATERIA.

Teniendo en cuenta el nuevo valor de **6106Wh/dia**, tengo un nuevo valor para la casilla **050**. A mi me sale **4580Wh** de energia a acumular.

Pero en cualquier caso, el tema baterias necesito investigarlo mas en detalle porque son carisimas y quiero hacerlo bien.

# INVERSOR DE RED.

Aqui estoy de acuerdo en elegir inversor de fabricacion EU aunque sea mas caro. La potencia seleccionada de **5000W** me parece bien aunque ahora pueda estar algo sobredimensionada, creo que puede estar bien para ampliacion furura con turbina o mas paneles. En cuanto a la opcion Inversor creo nos decidiremos por el de red mixto. Necesito darle una vuelta en funcion de las baterias.

Esto es todo para la parte electrica de la casa. Te parece bien recalcularlo todo con los nuevos datos que te he facilitado y valoramos los resultados? Por mi parte me pongo a tope con las baterias.

# FOTOTERMIA.

Aqui entiendo que lo que propones es una instalacion independiente y estoy totalmente de acuerdo y decidido a realizarlo de esta manera con el soporte de una calentador de agua ACS especifico. Por el momento no queremos depender de una caldera de gas para calentar radiadores porque tenemos otras opciones para calentar la casa.

Aqui te dejo una opcion o similar, que he estado valorando y que parece economica y permite utilizar propano en lugar de butano. Ademas parece compatible con la fototermia? Cual es tu opinion??

![CalentadorGas.PNG](/imgs/CalentadorGas.PNG)

Inicialmente hemos pensado que lo queremos hacer sencillo pero con posibilidad de ampliacion. Asi que te explico mi idea:

1. Instalacion independiente en el alero trasero de la casa. (En el delantero estarian los 8 del sistema FV). 

![Orientacion.PNG](/imgs/Orientacion.PNG)

Crees que puede haber problemas en ese lado del tejado?

2. Como te dije, solamente tengo 4 paneles por el momento. Asi que los paneles para la fototermia pueden ser diferentes y podria mirar otras opciones a los Atersa. Tu me recomendarias alguno en especial?
   
3. A partir de aqui, el objetivo seria instalar la opcion 1 de tu pagina web. Es decir el sistema Vcc. Creo que es un buen comienzo para valorar el gasto junto con el calentador de gas. Y por el momento no gastamos en mas baterias e inversor. Si en el futuro queremos ampliar, entiendo que podemos instalar otro termo para resistencia Vca y baterias e inversor para gestionar excedente.

4. El kit de fototermia que ofreces en tu web me parece interesante y ademas no dispongo de termo y prefiero que venga todo calibrado de tu parte. La capacidad deberia estar entorno a los 200l segun tus calculos. Dispones de esa capacidad? 

Con estos datos crees que me podrias pasar precio de la fototermia?

Muchas gracias por tu tiempo Jacint!




























