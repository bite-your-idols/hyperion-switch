# hyperion-switch
Toggle on/off hyperion in OpenELEC with an addon.


DESCRIPCIÓN
Sistema para apagar los Leds controlados por Hyperion en una Raspberry Pi desde el menu de Kodi y desde el mando a distancia de tu TV.
El sistema ha sido probado en OpeneELEC 4, 5 y 6.

INSTRUCCIONES:
Instalar el addon desde el zip.
Podemos modificar el archivo "remote.xml" para añadir un acceso directo al encendido/apagado desde tu propio mando a distancia. Elegis el boton y le asignais el codigo:
XBMC.System.Exec("/storage/.kodi/addons/script.hyperion.switch/bin/switch.sh")

+ información: http://www.elotrolado.net/hilo_hilo-oficial-movimiento-ambilight-eol_1036973
