# Introducción a los Sistemas de Comunicación<br>

## 1. Defina los tres modos de transmisión.

<p>
  Simplex: Es unidireccional. La televisión o la radio.<br>
  Half-duplex: es bidireccional pero no pueden fluir datos en sentidos opuestos de forma simultanea.<br>
  Full-duplex: Las comunicaciónes pueden ir en ambos sentidos de forma simultanea<br>
</p>

## 2. Indique las ventajas de cada tipo de topología de red. <br>

| Topología | Punto de vista físico | Punto de vista lógico|
| ------------- | ------------- | -------------------------|
|    Bus    | Se pueden comunicar entre sí directo. |Comparten información |
|    Anillo  | Los dispositivos están conectados entre sí mediante cadena.| No colisiones|
| Anillo doble| Confiabilidad y flexibilidad de la red. | 2 anillos independientes, de los cuáles sólo de usa uno en un momento dado|
|  Estrella |   Los nodos se comunican entre si conveniente.| Seguridad y acceso restringido.|
|  Estrella extendida| Cableado más corto limita la cantidad de dispositivos que se deben interconectar al nodo central.| Es muy jerárquica; busca que la info se mantenga local|
|    Árbol o jerárquica | El enlace troncal es un cable con varias capas de ramificaciones.| Flujo de información jerárquico|
|    Malla completa | Cada nodo se conecta física con los demás nodos. Redundancia de info que puede circular por distintas vías.| Depende mucho de los dispositivos utilizados|
|    Red celular | No hay enlaces físicos -> ondas e.m.| Las tecnologías celulares se pueden comunicar entre sí directa o solo con celdas adyacentes. Se suelen integrar con otras topologías| <br>

## 3. ¿Cuáles son los factores que determinan que un sistema de comunicación sea una LAN, MAN o WAN?

<p> MAN: Usa tecnologías similares a las de las redes LAN pero en escalas geográficas más grandes. Típicamente abarcan ciudades enteras. <br>
  WAN: Es una red que intercomunica equipos en un área geográfica muy amplia (países, continentes). Las líneas de transmisión que utilizan son normalmente propiedad de las compañías telefónicas. Baja velocidad, mayor tasa de error.<br>
  LAN: Son redes que interconectan un área privada y restringida.<br>

  ## 4. Enumere las cinco topologías básicas de red. <br>
  <ul>
    <li>Topología: Malla completa</li>
    <li>Topología: Anillo</li>
    <li>Topología: Estrella</li>
    <li>Topología: Bus</li>
    <li>Topología: Árbol</li>
  </ul> <br>  

  ## 5. Indique una desventaja de cada tipo de topología de red.<br>

  |Topología|Punto de vista físico|Punto de vista lógico|
  |---------|---------------------|---------------------|
  |Bus      |Si se rompe el cable -> todos hosts desconectados|Problemas de tráfico y colisiones||
  |Anillo   |Los dispositivos están conectados entre sí mediante cadena|
  |Anillo doble||2 anillos independientes, de los cuáles sólo se usa uno en un momento dado
  |Estrella|Si nodo central falla -> falla todo <br> Según dispositivo que hace de nodo central -> colisiones|Colisiones|
  |Estrella extendida|||
  |Árbol o jerárquica|||
  |Malla completa|Solo para pocos nº de nodos|Depende de los dispositivos utilizados||
  |Red celular|Disturbios y violaciones de seguridad||<br>

  ## 6. Para una red con n dispositivos, ¿cuál es el número de enlaces de cable necesarios para una malla, un anillo, un bus y una topología en estrella?
Malla: n(n-1)/2

Anillo: # dispositivos =  # enlaces

Bus: n dispositivos = n+1 enlaces

Estrella: el concentrador, tiene que tener n puertos por n dispositivos.<br>

## 7. Para cada tipo de topología de red, indique las implicaciones de que exista un fallo de un único cable

Malla: si falla un cable se reencamina por los otros.

Estrella: si falla un enlace, solamente ese enlace se ve afectado, los demás permanecen activos.

Árbol: si falla el primer cable, se interrumpe toda la transmición, si no, seguira la red.

Bus: un fallo o ruptura de cualquier cable, interrumpe todas las transmisiones del bus.

Anillo: una ruptura del anillo en cualquier enlace, inhabilita toda la red.

## 8. ¿Qué es una intranet? ¿Qué es Internet?

intranet: es una serie de redes interconectadas.

Internet: es un red de ámbito mundial (World Wide Web)

## 9. ¿Qué topología necesita un controlador central o un concentrador?

Una topología estrella

## 10. La comunicación entre una computadora y un teclado implica una transmisión *simplex*

## 11. En una red con 25 computadoras, ¿qué topología necesitaría el cableado más extenso? 

Una topología malla

## 12. Una topología en árbol es una variación de una topología en *estrella*

## 13. Una conexión *punto a punto* proporciona un enlace dedicado entre dos dispositivos.

## 14. En la transmisión *full-duplex*, la capacidad del canal es siempre compartida por los dos dispositivos que se comunican.

## 15. Una rotura de cable en una topología en *bus* detiene toda la transmisión.

## 16. Una red que contiene múltiples concentradores está configurada muy probablemente como una topología en *árbol*

## 17. Defina el tipo de topología de las siguientes figuras:

Figura 1: Topología bus

Figura 2: Topología bus

Figura 3: Topología estrella estentida 

Figura 4: Topología árbol 

Figura 5: Topología anillo

## 18. Relacione los conceptos siguientes con una topología de red (cada uno se puede aplicar a más de una topología):

a) Topologia de bus, estrella y árbol

b) Topología de estrella y árbol

c) Topología de anillo y bus 

## 19. Cuando alguien hace una llamada telefónica local a otra persona, ¿está usando una configuración de línea punto a punto o multipunto? Explique su respuesta.

En una configuración de línea punto a punto, dos, y únicamente dos, dispositivos se conectan a través de un enlace dedicado.

Sería una de punto a punto ya que la llamada solo se realizó a través de un dispositivo

## 20. ¿Qué modo de transmisión (símplex, semidúplex o full-dúplex) se puede comparar a los siguientes?

a) Semidúplex

b) Full-Dúplex

c) Simplex 
