

**Switching de almacenamiento y envío** (Store-and-forward): Se recibe la trama completa. El switch analiza el CRC y hace el calculo correspondiente para la comprobación de errores. Si todo es correcto, reenviara la trama.

Descartar las tramas con errores reducen el ancho de banda necesario. aun que también aumentara la latencia al tener que esperar a las tramas completas por parte del switch y su posterior procesado del CRC.




**Switching por método de corte** (Cut-Trought): Con este método la trama se reenvía antes de recibirla completamente. El switch leera la dirección de destino y lo enviara. 

Este método mejora la latencia en la comunicación pero el ancho de banda necesario aumentara debido a que se enviaran todas las tramas indistintamente de si tienen errores o no.


Este método tiene dos variantes que son:
**Switching de Reenvio rapido** (fast-forward):  Ofrece la latencia mas baja, pero no se verifican las tramas.


**Switching libre de fragmentos** (fragment-free switching):  Metodo intermedio entre el store-and-forward y el fast-forward.
Almacena los primeros 64 bytes de la trama. Estos son donde se detecta la mayoria de errores en las tramas.