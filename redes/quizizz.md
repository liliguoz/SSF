# INTRODUCCIÓN A LOS SISTEMAS EN RED + CAPA 1 (FÍSICA)
1. ¿Qué es CIERTO en un sistema de comunicación?

a) Los transcriptores adaptan las señales al canal <br> b) **La fuente emite el mensaje y el destino lo recibe** <br> c) El transmisor convierte la comunicación recibida del canal a señal eléctrica <br> d) El canal siempre se aisla para evitar interferencias

2. Según el canal, las comunicaciones pueden ser (elegir la FALSA)

a) simplex <br> b) **full-simplex** <br> c) half-duplex <br> d) duplex

3. ¿Qué NO es una ventaja en una red de equipos?

a) Compartir información y recursos <br> b) Permite trabajar en grupo o colaborativamente <br> c) **Aumenta la seguridad y la privacidad** <br> d) Permiten una mejor comunicación: emails, videollamadas, etc.

4. ¿Cuál de las siguientes redes por extención es correcta?

a) A nivel personal: MAN o WMAN <br> b) **En un edificio: LAN o WLAN** <br> c) En una ciudad: WAN o WWAN <br> d) En una región amplia, como un estado: PAN o WPAN

5. ¿Cuál es FALSA sonbre la Normalización de Redes?

a) Existen organismos reguladores a nivel internacional, continental, estatal, etc. <br> b) Estándares y protocolos rigen los diferentes componentes y procedimientos <br> c) Las normas pueden ser "de iure" o "de facto" <br> d) **La gran mayoria de normas son opcionales y dependen de la región**

6. ¿Qué organismos de estandarización son correctos en cada ámbito geográfico?

a) EEUU: ITU, ISO, IEEE, IEC <br> b) Internacional: CEN, CENELEC, ETSI <br> c) Europa: ANSI y TIA <br> d) **España: CTN, AENOR**

7. ¿Cuál es la caracteristica VERDADERA del modelo de interconexión de sistemas abiertos (Modelo OSI)?

a) Tiene 5 capas <br> b) Cada capa establece una comunicación virtual con cualquier otra capa <br> c) **En general, cada capa es independiente de las demás y las ve como "cajas negras"** <br> d) En el modelo OSI es una simplificación del modelo TCP/IP, que es mucho más complejo <br> e) La primera capa (inferior) es la más cercana al usuario y la última (superior) a la red física

8. ¿Qué es FALSO sobre los PDU?

a) Se refiere al encapsulamiento de datos (Protocol Data Unit) <br> b) **La encapsulación es realizada por el ordenador destino** <br> c) Establece comunicación de datos en capas homólogas <br> d) Depende fe ela capa se llaman tramas, segmentos, paquetes, datos,...

9. ¿Qué medios de transmición son correctos?

a) **GUIADOS (par trenzado, coaxial, fibra ópt.) y NO GUIADOS (radiofreq, microondas,...)** <br> b) MODULADOS (FM, AM) y NO MODULADOS (PM) <br> c) MULTIPLEXADOS y DEMULTIPLEXADOS <br> d) Por PULSOS o por IMPULSOS

10. ¿Por qué se trenzan los cables en el par trenzado?

a) Para dar mayor robuztez al cable según indica el AWG <br> b) **Para reducir las interferencias entre los propios hilos internos** <br> c) Para eleminar totalmente el efecto de inducción de las antenas <br> d) Para poder superar la distancia máxima estándar de 500 metros <br> e) Para que queden más bonitos. También hay pares ondulados y pares tirabuzón

11. ¿Qué es FALSO sobre los cables de par trenzado?

a) UTP: no tiene blindaje <br> b) FTP: cable apantallado (blindaje que engloba todos los pares) <br> c) **MTP: cable con apantallamiento medio (se blindan los hilos positivos)** <br> d) STP: blindado individual (cada par está apantallado)

12. En redes locales y o LAN, en en condiciones "normales", se usa principalmente par tenzado UTP porque...

a) **El par trenzado UTP es más barato, más flexible y más fino** <br> b) En general con par trenzado UTP permite distancias más largas <br> c) El par trenzado UTP tiene mejor aislamiento que el coaxial <br> d) Es justo lo contrario, se usa más coaxial que par trenzado <br> e) El UTP es el único que permite PoE

13. En un cable trenzado UTP, ¿cuál es la CORRECTA?

a) Se utiliza el conector RJ11 <br> b) Se usa sólo 1 par (2 hilos) para 10BASE-T y 10-BASE-TX <br> c) Se usan los 8 pares para Gigabit Ethernet <br> d) El cable directo se usa para conectar 2 equipos directos <br> e) **La velocidad y distancia máxima depende de la categoría del cable**

14. A dia de hoy, ¿cuál es la categoria más recomendable para realizar una nueva instalación de cable por trenzado?

a) Cat 4 <br> b) Cat 5 <br> c) Cat 5e <br> d) **Cat 6** <br> e) Cat 7

15. ¿Cuál NO es una ventaja de la fibra óptica?

a) Altas velocidades <br> b) Alta inmunidad frente interferencias electromagnéticas <br> c) Alta distancias <br> d) **Alta sencillez en los conectores**

16. En una red de área local que utiliza un HUB, ¿cuál seía la topología?

a) Física: anillo, Lógica: bus <br> b) Física: bus, Lógica: malla <br> c) **Física: estrella, Lógica: bus** <br> d) Física: malla, Lógica: árbol

17. En el nivel 1, ¿Cuál es el dispositivo que, en general, no sería correcto?

a) Un hub activo <br> b) Un concentrador pasivo <br> c) **Un repetidor pasivo** <br> d) Un repetidor activo


# CAPA 4 (TRANSPORTE) + CAPAS 5, 6 Y 7 (SESIÓN, PRESENTACIÓN Y APLICACIÓN) + ADMINISTRACIÓN DE SISTEMAS OPERATIVOS EN RED

1) ¿Qué es FALSO sobre una dirección IP(IPv4)?

a) **En todo el mundo no hay 2 equipos con la misma dirección IP** <br>
b) Tienen 32 bits (4 bytes), siendo el total de más de 4.200 billones <br>
c) Se suelen representar en decimal separando cada número con un punto: 1.2.3.4 <br>
d) No todas las IPs son iguales, hay clases, públicas, privadas, reservadas, etc. <br>

2) ¿Qué dispositivo son de la capa 3 (y 4)?

a) router <br>
b) **switch** <br>
c) AP <br>
d) **firewall** <br>
e) hub

3) ¿Qué protocolo es CORRECTO?

a) ICMP: Difunde las tablas de routeo a routers próximos. <br>
b) BGP: Envia mensajes de control para determinar el estado de la conexión <br>
c) ARP: Obtiene la dirección MAC a partir de la IP <br>
d) RIP: Traduce las direcciones de red en el router 

4) Mi organización tiene 1000 equipos en la intranet y quiero que tengan conexión a Internet, pero NO se vean desde el exterior, ¿Qué tipo de IPs debo tener?

a) Debo usar IPs estáticas en equipos y dinamica en router <br>
b) Debo usar IPs dinamicas en equipos y router. <br>
c) Debo usar IPs públicas en los quipos y router con IP privada <br>
d) Debo usar IPs privadas y estar detrás de un router con IP pública

5) No todas las IPs de una red son útiles. Hay algunas con significado especial. Elige la afirmación FALSA

a) En todas las redes hay 2 direcciones reservadas, la primera y la última. <br>
b) La ID de red junto a la mascara sirven para representar a todas las IPs de esa red <br>
c) Si mando un mensaje a la ultima IP de una red, le llegará a todos los equipos de la red. <br>
d) **La ID de red tiene todos los bits de red a 1 y los de broadcasing a 0**

6) En general, ¿se produce fragmetnacion y reesamblaje de paquetes en la capa 3?

a) No, la capa 3 no soporta esto, es la capa 4 la que se encarga <br>
b) El router se encarga de realizar la fragmentacion y reensamblaje. <br>
c) La fragmentacion se haria en rputers y el reensamblaje en el host del destino<br>
d) Fragmentación y reensamblaje es gestionado por los swithes

7) Elige la afirmacion falsa sobre los puertos

a) El uso de cada puerto la asigna IUANA y no se pueden cambiar

8) Viendo solo dos IPs, piuedo saber si pertenece o no a la misma red

a) necesitas la mascara

9) Para configurar una IP estatica, hay que indicar al menos tres paramentro.

a) MAC

10) En un servidor web que quiero que se peuda acceder desde cualquier parte del mundo, en general, que tipo de IP nos interesa.

a) estatica y publica

11) ¿cual de las siguientes ip podria ser valida apra un servidor web accesible desde cualquier situo de internet?

a) 172.57.25.31

12) Cuando indico el CIDR por ejemplo /27, ¿que quiero decir?

a) bits de la mascara de 1 a 27

13) que no forma parte de un socket?

a) mascara

14) que es falso sobre NAT


