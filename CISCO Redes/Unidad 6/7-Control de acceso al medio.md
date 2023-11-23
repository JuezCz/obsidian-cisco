
Hay dos métodos por los que los dispositivos pueden acceder al medio. 

+ Acceso por contienda
+ Acceso controlado

**Contienda**
Como su nombre indica, hay una contienda entre los dispositivos. Todos compiten por acceder al medio. Los dispositivos operan en semi dúplex. Hay un protocolo por si dos dispositivos transmiten a la vez en el medio. Lo cual provocara una colisión.

+ Acceso múltiple con detección de colisiones (CSMA/CD)
+ Acceso múltiple con Detección de colisiones (CSMA/CA), empleado en LAN inalámbricas.


**Acceso controlado**
Los nodos tienen un tiempo para poder utilizar el medio. Si su turno pasa, tendrán que esperar a que su turno llegue de nuevo.


Redes que emplean el sistema de acceso por contienda.
- **LAN inalámbrica (utiliza CSMA/CA)**
- LAN Ethernet de topología de bus heredada (utiliza CSMA/CD)
- LAN Ethernet heredada con un hub (utiliza CSMA/CD)

Las redes WLAN funcionan  en modo semidúplex por la propiedad física del medio (el aire).


**Acceso por contienda CSMA/CD**
Si dos dispositivos transmiten al mismo tiempo, se produce una colisión. 
Para las LAN Ethernet heredadas, ambos dispositivos detectarán la colisión en la red. Esta es la parte de detección de colisiones (CD) de CSMA/CD. 
La NIC compara los datos transmitidos con los datos recibidos, o al reconocer que la amplitud de la señal es más alta de lo normal en los medios. Los datos enviados por ambos dispositivos se dañarán y deberán enviarse nuevamente.

**Acceso por contienda CSMA/CA**
CSMA/CA utiliza un método similar a CSMA/CD para detectar si el medio está libre. CSMA/CA usa técnicas adicionales. 
En entornos inalámbricos, es posible que un dispositivo no detecte una colisión. CSMA/CA no detecta colisiones pero intenta evitarlas ya que espera antes de transmitir. 
Cada dispositivo que transmite incluye la duración que necesita para la transmisión. Todos los demás dispositivos inalámbricos reciben esta información y saben durante cuánto tiempo  no estará disponible el medio.

Después de enviar una trama 802.11, el receptor devuelve un ACK para que el emisor sepa que la trama fue recibida.

>**Nota**
>Las redes LAN Ethernet con switches no utilizan sistemas por contención porque el switch y la NIC de host operan en el modo de dúplex completo.