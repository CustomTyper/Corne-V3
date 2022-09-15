# Corne Keyboard V3

<!-- wp:paragraph -->
<p>En esta guía de montaje, vamos a ver como montar el famoso teclado Corne (<a href="https://github.com/foostan/crkbd">crkbd</a>), en este caso se trata de la V3, la cual tiene pequeños cambios respecto a la original, pero en esencia el montaje es el mismo.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
## <p>Índice rápido</p>
<!-- /wp:paragraph -->

<!-- wp:columns {"verticalAlignment":"center"} -->
<div class="wp-block-columns are-vertically-aligned-center"><!-- wp:column {"verticalAlignment":"center","width":"100%"} -->
<div class="wp-block-column is-vertically-aligned-center" style="flex-basis:100%"><!-- wp:group -->
<div class="wp-block-group"><!-- wp:columns -->
<div class="wp-block-columns"><!-- wp:column {"width":"100%"} -->
<div class="wp-block-column" style="flex-basis:100%"><!-- wp:group -->
<div class="wp-block-group"><!-- wp:list -->
<ul><li>Placa base</li><li>Diodos</li><li>Socket Hot Swappable</li><li>Micro controladores</li></ul>
<!-- /wp:list --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->

<!-- wp:paragraph {"textColor":"foreground","fontSize":"large"} -->
## <p class="has-foreground-color has-text-color has-large-font-size">Preparacion del lugar de trabajo</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Se recomienda manipular los componentes en entornos ventilados, si bien, las soldaduras de estaño no producen casi humo, pero si calor; además, los componentes electrónicos, son especialmente delicados con la elctricidad electroestática, por lo que se recomienda el uso de tapetes de goma (link).</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
## <p class="has-large-font-size">Placa Base</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(imagen PCB)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>En total, son 2 placas, las cuales son aparentemente iguales, pero para saber cual es la de cada lado, las marcas blancas son hacia abajo. Tras comprobar el estado de las mismas, podemos lijar las pequeñas protuberancias del contorno de las placas sin presionar fuerte.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
 ## <p class="has-large-font-size">Diodos</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(imagen Diodos)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Este será el primer compoente SMD que vamos a soldar a la placa, por lo que podemos ir poniendo el soldador a calentar a 300º y esperar unos 5 minutos.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Hay que tener en cuenta que los diodos tienen polaridad y debemos saber en que sentido hay que ponerlo, se ve facilmente si observamos las lineas blancas del diodo, que se debe poner en el mismo sentido que las lineas blancas dibujadas en cada hueco donde se soldará el diodo.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(imagen lineas blancas)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>La tecnica para soldar estos componentes es la siguiente: se recomienda echar una gota de flux por cada diodo, una vez aplicado, procederemos a pre-estañear los pads, acercamos el soldador a cada pad junto al estaño, se calientará el hilo de estaño y aplicamos una pequeña cantidad de estaño, el solo se va a su sitio, por lo que te quedará algo así </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(foto pad con estaño)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>una vez pre-estañeado cada pad, con unas pinzas de punta fina, cogemos cada diodo teniendo en cuenta el sentido y lo sujetamos encima de cada pad, no hace falta ejercer presión, con el soldador, acercamos la punta nuevamente al estaño ya aplicado, y en cuanto se funda el diodo se coloca en un pad, y repetimos el proceso con el otro.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Esta tarea se repetirá por la totalidad de los diodos.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
 ## <p class="has-large-font-size">LEDs teclas</p>
<!-- /wp:paragraph -->
<!-- wp:paragraph -->
<p>(imagen leds teclas)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Los LED de las teclas son fáciles de soldar.&nbsp;Tienen un orificio en la PCB, por lo que son fáciles de colocar.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Al igual que los diodos, tienen posición, hay que situar la pata más corta y con un triángulo en la esquina de la silueta blanca dibujada en la PCB</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(imagen led soldado)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>El mayor problema que podemos tener es que los leds son sensibles al calor, y hay que tener cuidado, recomendamos bajar el soldador de potencia para no deteriorar la parte plástica y que se suelde en unos 5 segundos.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
## <p class="has-large-font-size">LEDs de iluminación inferior</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>De la misma forma que los LEDs de las teclas, estos tienen posición y se colocan de la misma manera.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Una cosa a tener en cuenta, es que en este caso las patas son más cortas por lo que aumenta el riesgo de sobrecalentar o quemar el propio LED. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(imagen led iluminacion)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
## <p class="has-large-font-size">Conectores Hotswap</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(imagen sockets)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>La soldadura de estos conectores es bastante más sencilla que los leds, dado que no tienen problemas de temperaturas ni patas cortas.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Para soldar estos, colocamos como en cada soldadura un poco de flux y ya solo hay que ponerlos en su posición y presionar con pinzas sobre la PCB, lo que se recomienda en este punto, es que se observe en todo momento que el conector queda perfectamente en su sitio para que luego no surjan problemas al colocar los switches.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
## <p class="has-large-font-size">Pro Micro</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Soldar esta parte es bastante más facil qeu soldar otras más pequeñas, pero hay que tener en cuenta las siguientes consideraciones:</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Tener clara la posición del Pro Micro, y saber que esta es la primera pieza que vamos a situar en el otro lado de la placa, es decir, hasta ahora hemos ido soldando en la parte inferior de la placa, pero el Pro Micro va situado en la otra cara de la PCB, teniendo esto claro, surgen dos opciones de soldar este componente.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Por un lado se puede soldar directamente a la PCB con estos conectores, los cuales los unen soldando las dos partes</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(foto conectores dobles)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>La otra opción es soldar por un lado zócalos en la PCB con una parte macho y otra hembra, y luego al Pro Micro se le suelda un conector macho a macho o patas de diodos</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(foto conectores macho-hembra)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Esta forma permite remplazar de manera más facil el Promicro ya que este se conecta a la placa en vez de soldarlo junto, pero el problema es por un lado, queda más elevado y tiene más relieve, y además se tarda más en soldar todas las partes.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
## <p class="has-large-font-size">Conector TTRs y botón de reset</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Estos componentes son muy sencillos de conectar, al igual que el Pro Micro, estos van situado en la misma cara que el anterior, simplementes colocamos el conector en su sitio, damos la vuelta a la placa y soldamos, repetimos esta operación con el botón de reset.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(foto conector y reset)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
## <p class="has-large-font-size">Pantalla LCD</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Al igual que el Pro Micor, podemos hacerlo de dos foramas:</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Con conector macho-macho, es decir, un extremo del conector a la PCB y el otro extremo a la pantalla, y la otra oción es conector macho-hembra a la PCB, y al pantalla un conector macho, las ventajas y desventajas son las mismas que las citadas con el Pro Micro.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(fotos de ambas posibilidades)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>En este punto, ya hemos terminado de soldar todos los componentes necesarios a la PCB, y pasamos a la parte final que es la comprobación y montaje final.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
## <p class="has-large-font-size">Comprobacion del funcionamiento básico</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>En este punto, ya podemos comprobar el funcionamiento de nuestro teclado para poder finalizar el montaje.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Mediante la siguiente guía vamos a aprendemos a instalar el firmware por defecto del corne.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(link Guia firmaware corne)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>También existe la opción de hacer a tu gusto el firmware y poder personalizar las teclas, luces, pantallas etc.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>En la siguiente guía se muestra como hacerlo.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(link guia firmware custom)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Para poder hacer la comprobación básica, instalamos el fimware por defecto.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>A continuacion, podemos fijarnos si los LEDs lucen correctamente, y si las teclas al pulsarlas marca el caracter correcto, de ser así podemos seguir con el montaje.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
## <p class="has-large-font-size">Protector pantalla LCD y Pro Micro</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Para empezar con la parte final del montaje, vamos a colocar el protector de la pantalla y Pro Micro.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Este va colocado con los espaciadores M2 de 9 mm y tornillos M2, es necesario atornillarlo por ambas caras de la PCB.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(foto protector montado)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"large"} -->
## <p class="has-large-font-size">Plate y switches</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Para colocar bien el plate, se recomienda hacer de la siguiente forma:</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>(foto plate con switches en las esquinas)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Posicionamos el plate encima de la PCB y ponemos un switch en cada punta, para segurarnos de que queda centrado y además facilitar la colocación de los Switches, atornillamos el plate a la PCB con el espaciador M2 de 7,5 mm y los tornillos M2 en la placa superior y dando la vuelta a la placa, podemos atornillar el plate inferior y "cerrar" el sandwich.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Terminamos de introduccior los switches restantes.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Y ya podemos dar por concluido el montaje del teclado Corne Keyboard V3.</p>
<!-- /wp:paragraph -->