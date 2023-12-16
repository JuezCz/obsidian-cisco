

IP consta de tres características básicas que son:

+ **Sin conexión**: No hay conexión establecido con destino antes de enviar los paquetes.
+ **Mejor esfuerzo**(poco confiable): la IP es poco confiable, no garantiza la entrega de paquetes.
+ **Medios independientes**: La operación no depende del medio utilizado para la transmisión (cobre, fibra, aire).


**Sin conexión**: Para enviar un paquete no es necesario que haya comunicación previa entre las partes interesadas (origen y destino). 

**Mejor esfuerzo**: La IP no requiere campos adicionales en el encabezado para mantener una conexión. Esto reduce la sobrecarga del protocolo IP.  Pero al no tener una conexión completa preestablecida, los remitentes (origen) no saben si los dispositivos de destino están o no en funcionamiento o presentes cuando se envían los paquetes. Tampoco sabe si los paquetes llegan con éxito o no.

El protocolo IP no garantiza la entrega de todos los paquetes enviados.

**Independiente de los medios**: Que sea poco confiable significa que no tiene funciones para administrar ni recuperar paquetes. Las capas superiores son quienes deben ocuparse de como se envían y ordenar los paquetes.

De la confiabilidad se encargara el protocolo TCP en la capa 4(transporte).

IP funciona de forma independiente a la capa 1 y 2. Un datagrama no cambia aun que el medio si lo haga.






