TU TELEFONO TIENE QUE ESTAR ROOTEADO

Android V 1.0

*Instalar Andronix APP, seguir los pasos del video subido en youtube:

*Instalar Termux *Instalar dependencia en modo consola :   

                                                           ***pkg install root-repo***

                                                           ***pkg install x11-repo***

                                                           ***pkg install python***

                                                           ***pkg install tsu***

                                                           ***pkg upgrade***

                                                           ***pip install scapy***

*Lanzamos comando ***env** Copiamos linea PATH=xxxxxxxxxxxxxxxxxxxx  en editor de texto y la modificamos para añadirla mas tarde al PATH de 
modo root, la linea tiene que quedar algo así ***export PATH=$PATH:/xxx/xxxx/xxx/xx/xxxx/xxx/xx/ tienes que ser dos linea distintas como las instrucciones del video.

*Nos logueamos como root con el comando ***su*** y añadimos las linea PATH comentadas anteriormente.

Nos vamos al directorio de descargas del telefono donde previamente nos hemos descargado este repositorio, el directorio donde nos deja 
el acceso root no es el correcto para ejecutar el programa que necesitamos , podemos tambien incluir nuestro programa en otra linea PATH la line a implementar seria la siguiente :
***export PATH=$PATH:/storage/emulated/0/Download/XxXxcarpeta_descarga_aulauniversal_archivo_start_android.pyXxx/***

Directorio de descarga : /storage/emulated/0/Download/

****************************************************************

Ejecutamos por fin el archivo ***python start_android.py***
                                                          -


***ACTUALIZACIÓN***
-ACTUALIZADO STAGE2.BIN 11.00 LOADER STABLE
-ACTUALIZADO RECOPILACION PAYLOADS 11.00

***ACTUALIZACIÓN***
Sustituir la carga util "stage2.bin" por el requerido por el usuario , ya se encuentra disponible  tanto
LoaderUSB como modo DebugSystem para version 11.00
La ubicación a sustituir es     /PS4_stage_bin_all/XxXVersion/stage2/

Eliminar el archivo existente stage2.bin y sustituir por el seleccionado, renombrar este como el archivo de origen "stage2.bin"

Valido para todas las versiones dese 9.00 hasta 11.00 
Payload inyectable solo con versión 9.00 y 11.00 de momento, incluye payload y GoldHen(la instalacion es sencilla , copiar el GoldHen.bin y copiar en raiza de USb
formateado en fat32 , renombrarlo a payload.bin, ejecutar Start.exe y seguir las instarucciones.
Todo esto no sería posible sin la ayuda de nuestro amigo
TheFlow y la vulneravilidad encontrada https://hackerone.com/reports/2177925 ( CVE-2006-4304)

https://github.com/TheOfficialFloW/PPPwn
