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
