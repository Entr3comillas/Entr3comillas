Escáner de Malware por Hash

Este script en Python permite escanear una carpeta en busca de archivos maliciosos utilizando hashes de archivos conocidos de malware. Funciona calculando el hash de cada archivo en la carpeta especificada y comparándolo con una lista de hashes de malware conocidos. Si se encuentra una coincidencia, se indica que el archivo podría ser malicioso.

Funcionalidades:

    Calcula el hash de un archivo utilizando el algoritmo especificado (predeterminado: SHA256).
    Escanea una carpeta en busca de archivos maliciosos comparando sus hashes con una lista de hashes conocidos de malware.
    Proporciona retroalimentación sobre la maliciosidad de cada archivo escaneado.

Uso:

    Define una lista de hashes conocidos de malware en la variable malware_hashes. Esta lista debería ser mucho más grande y actualizada en la realidad.
    Especifica la ruta de la carpeta que deseas escanear en la variable carpeta_a_escanear.
    Ejecuta el script para iniciar el escaneo de la carpeta.

Nota: Es importante mantener la lista de hashes de malware actualizada para garantizar la eficacia del escaneo.
