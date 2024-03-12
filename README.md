# Estado_ubnt
Código para verificar el correcto funcionamiento de APs de la red libre y actuar en caso de falla de forma autónoma.

El código cuenta de 4 bloques: Escaneo, detección de caida, operación y aviso.
**Escaneo: Verifica el correcto funcionamiento del AP basado en el parámetro "remote" que se obtiene mediante SSH.
**Detección de caida: Algoritmo encargado de encontrar fallas de operación de forma confiable.
**Operación: Bloque que es llamado para actuar sobre el AP, generalmente generando un reinicio.
**Aviso: Este bloque avisa al usuario de la acciones mediente un mensaje de Telegram.
