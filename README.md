![Banner](./carpeta_fotos/banner1.png)

# Documentación Proyecto

Aquí realizaremos la documentación del proyecto, actualmente estamos realizando `SEGUNDO PROYECTO`.

</div>

<details>
  <summary>
   PRIMER PROYECTO🛠️
  </summary>
  
## ÍNDICE

1. IDEA DEL PROYECTO Y OBJETIVO DEL TRABAJO
2. OBLIGATORIO A APLICAR
3. LOGO DEL EQUIPO
4. PALETA DEL EQUIPO
5. TAREAS DE LOS INTEGRANTES
6. MOCKUP Y ARBOL DE NAVEGACIÓN
7. ARQUITECTURA DEL SISTEMA Y FUNCIONALIDADES
8. DIAGRAMA DE LA BASE DE DATOS
9. ESQUEMA DE RED
10. CONFIGURACIÓN DE PROXMOX
11. CONFIGURACIÓN DE DNS
12. CONFIGURACIÓN DE DHCP
13. CONFIGURACIÓN DE NGINX
14. BASE DE DATOS
15. CAMBIOS EN LA WEB
16. FUNCIONALIDADES
17. NUESTO FURTURO
18. VALORACIONES DEL PROYECTO
19. INCIDENCIAS TÉCNICAS
20. BIBLIOGRAFIA

    
## 1.IDEA DEL PROYECTO Y OBJETIVO DEL TRABAJO

Nuestra idea del proyecto se basa en diseñar una aplicación web inspirada en el popular juego de Fantasy Football. El fantasy es un juego donde los usuarios crean su propio equipo, y la finalidad de este juego es obtener los máximos puntos posibles, estos puntos se consiguen mediante tus jugadores, los jugadores en la vida real dependiendo de como juega un partido, puede obtener muchos puntos o muy pocos puntos. Como ejemplo de puntuacion, si un jugador no tiene minutos de juego entonces tendra 0 puntos, y si otro jugador marca 4 goles, possiblemente tendra una puntuación de 25 puntos. 

Entonces nuestra idea es crear una página relacionada con esta idea. Hemos elegido esta idea porque ambos integrantes del equipo sabemos más o menos cómo funciona el futbol fantasy, y por eso creemos que es una gran opción escoger este tema, ya que nos parece muy interesante.

Nuestro objetivo será aplicar todas las tecnologías necesarias para aspirar a la máxima nota posible y poner en práctica los conocimientos aprendidos en el primer año, así como lo que aprenderemos en este segundo año, para hacerlo lo mejor posible. También el año pasado un grupo escogio la misma idea y viendo como lo hicieron, vimos sus errores y pensamos que lo podemos hacer mucho mejor.

Con el trello y el github mostraremos todo nuestro trabajo realizado para mostrar nuestros avanzes semanales y diarios

## OBLIGATORIO A APLICAR

__-Node.js & MySQL:__

Node.js es un entorno de ejecución para JavaScript en el servidor, ideal para construir aplicaciones web rápidas y escalables. 

MySQL es un sistema de gestión de bases de datos relacional que almacena y organiza datos de manera eficiente, facilitando consultas rápidas.

__-NGINX o Apache:__ 

Ambos son servidores web populares. NGINX es conocido por su rendimiento y capacidad para manejar múltiples conexiones simultáneas, 
mientras que Apache es altamente configurable y tiene una gran cantidad de módulos disponibles.

__-DNS + DHCP:__ 

DNS (Sistema de Nombres de Dominio) traduce nombres de dominio en direcciones IP, facilitando la navegación web. 

DHCP (Protocolo de Configuración Dinámica de Host) asigna automáticamente direcciones IP a dispositivos en una red, simplificando la gestión de redes.


## 2.LOGO DEL EQUIPO

Nuestro logo lo hemos creado basándonos en el nombre de nuestro trabajo, Team Tactics. En él, se pueden ver dos "T" que hacen referencia al nombre del equipo. Tambien, hemos pensado este logo ya que con la forma y sus colores tiene mucha relación con el mundo del futbol.

El color negro y blanco creemos que queda muy estetico, que es eso lo que buscamos y lo que nos interesa.

![Logo del equipo](carpeta_fotos/logo_teamtactics_negro.png)

## 3.PALETA DEL EQUIPO

Los colores con los que vamos a trabajar son los siguientes, hemos considerado que esta paleta de colores puede cuadrar muy bien con la funcionalidad de la web y puede atraer visualmente a nuestro público objetivo
ya que son colores muy visuales y relacionados con el mundo de los videojuegos.

__-000000__

__-00FF00__

__-FFFFFF__


![Paleta de la web](carpeta_fotos/tabladecolores.png)


## 4.TAREAS DE LOS INTEGRANTES

Ambos integrantes tocaremos de todo un poco. La idea es que los dos programemos, hagamos la base de datos, etc. Ahora estamos los dos trabajando juntos, y empezaremos cada uno a hacer sus 3 funcionalidades.

## 5.NUESTRO MOCKUP Y ARBOL DE NAVEGACIÓN

Hemos diseñado un mockup de la aplicación a través de Canva, basándonos principalmente en nuestra paleta de colores. Además, hemos realizado un diseño lo más visual posible para atraer la atención del público que creemos podría estar interesado en nuestra aplicación. Nuestro público objetivo son hombres entre 13 y 40 años.

Aquí explicaremos el arbol de navegación de nuestra página web.
Para empezar tendremos una página principal, donde a la parte superior derecha se vera los siguentes botones:
 - Inicio
 - Plantillas
 - Estadísticas
 - Contacto
 - Login

El boton de inicio es para que cuando accedas a otro boton te lleve a la pagina principal.

El boton de plantillas te llevara al apartado de tu plantilla/equipo

El boton de estadísticas te llevara a la parte de estadisticas globales

EL boton de contacto es para que el usuario acceda a la pagina con su usuario creado. En ese apartado podrà iniciar sección.

Abajo de todo esto, se veràn los 20 escudos de la liga, donde si hacemos click a un escudo te llevara a ver información de ese equipo como: Plantilla, sitio en la clasificación etc..

Entonces abajo de esto mostraremos el mensaje de Juega a teamtactics, esto es para que el usuario vea de una forma un esquema de lo que va la web

![Logo del equipo](carpeta_fotos/INICIO.png)

Abajo de esto, veremos un apartado de pròximos partidos y lideres de la liga, ambas son como una mínima información. En cada apartado tendrá abajo derecha un boton que pondra como: Ver todos los partidos/Estadísticas, que te llevara a otro sitio, para ver toda la información.

![Logo del equipo](carpeta_fotos/proximospartidos.png)

Entonces, si le damos al botón de arriba derecha de estadísticas, te llevará a una página donde salgan todas las estadísticas, donde podremos ver:

 -Máximos goleadores
 

 -Máximos asistententes
 
 
 -Jugador con más disparos
 
 
 -Jugador con más pases.
 

 -Portero con más paradas.
 

 -Jugador con más tarjetas amarillas y rojas.

 Cada jugador que salga, si por ejemplo el jugador que es el máximo goleador es Lewandowski, saldrá el escudo del equipo y los minutos jugados.

Esta página de estadísticas también se podrá llegar a parte del botón arriba derecha en la parte que he comentado donde decía: Ver todas las estadísticas
Y si le damos al botón de ver todos los partidos, que se encuentra a abajo del todo de la página principal, nos llevará a otra página donde veremos todos los partidos jugados, y los puntos que todo el equipo ha conseguido, esto servirá para que el usuario mire los puntos que ha hecho cada jugador.

![Logo del equipo](carpeta_fotos/estadisiticas.png)

![Logo del equipo](carpeta_fotos/proximospartidos2.png)

Ahora, en la página principal, si le damos a Crea tu equipo, te llevará a la página donde el usuario podrá crear el equipo. En esta página, se verá de fondo como un campo de fútbol negro, para que el usuario ponga sus jugadores a cada posición que corresponde.
Arriba, dentro de la misma página, se verá un balance. El balance principal empieza con 100.000.000, luego si el usuario hace incorporaciones, entonces el balance bajará. 
Abajo de esto, se verá un apartado de puntos, donde el usuario verá la suma total que ha realizado su equipo.
Y arriba derecha se verá el número de jugadores que tiene puestos en el campo de fútbol, normalmente esto será simple 11/11.

![Logo del equipo](carpeta_fotos/creatuequipo.png)

La opción de número de jugadores funcionará como un botón, donde, si hacemos click a esto, veremos nuestros jugadores, nombre, club, media puntos, puntos que ha hecho en una jornada y el valor de mercado.
La media de puntos se hará haciendo una media de los 37 partidos jugados.

![Logo del equipo](carpeta_fotos/tusjugadores.png)

También se verá un botón de mercado, para que el usuario pueda comprar jugadores en el mercado.
Todos los jugadores que el usuario ha comprado también pueden ser vendidos.

Luego, en el botón contacto pondremos un poco de información de nosotros para explicar un poco dentro de la página web el proceso del proyecto.

Y en el botón de inicio de sección, el usuario podrá hacer registro para poder acceder con su cuenta a la página, claro que si no tiene cuenta, tendrá que darle a crear cuenta, y luego de crear cuenta le tendrá que dar a iniciar sección.
![Logo del equipo](carpeta_fotos/arboldenavegacion.png)

El mockup y nuestra idea del trabajo creo que lo hemos entendido perfectamente. Sabemos que el árbol de navegación no será el mejor de la historia, pero para nosotros nos sirve cómo una buena guía de cómo funcionará la página.


## 6.ARQUITECTURA DEL SISTEMA Y FUNCIONALIDADES

![Logo del equipo](carpeta_fotos/arquitectura.png)

Nuestros objetos serán:
- Registro de usuarios
- Una zona de comentarios para todos los usuarios que se hayan agregado como amigos
- Una zona donde el usuario podrá modificar su perfil.
- Poner notificaciones para los usuarios
- Búsqueda de usuarios y poder agregarlos como amigos
- Y hacer obligatorio el uso de contraseña para cuando se entra a la aplicación.

  El día de la fecha de entrega puede variar

Ahora mostramos la arquitectura de nuestro trabajo.
  ![Logo del equipo](carpeta_fotos/arquitectura2.png)

## 7.DIAGRAMA DE LA BASE DE DATOS

Los usuarios crean sus propios equipos, que consisten en jugadores de equipos reales, organizados en plantillas. 

Los usuarios pueden participar en ligas, competir entre sí y realizar transacciones de compra y venta de jugadores. Para calcular las puntuaciones, 
Se registran los partidos reales y las puntuaciones obtenidas por cada jugador en esos encuentros. 

Además, hemos incluido un sistema de Amigos, así como Roles para gestionar diferentes tipos de usuarios en la plataforma.


![Logo del equipo](carpeta_fotos/basededatos_final.png)


## 8.ESQUEMA DE RED

Por el momento tenemos hecho este prototipo de mapa de red, aunque aun lo tenemos que hablar con Alina ya que no es el definitivo y queremos que nos aclare algunos conceptos que quizas no han quedado tan claros.

![Logo del equipo](carpeta_fotos/mapa_de_red.JPG)

## 9.PROXMOX Y SU CONFIGURACIÓN

Por el momento, ya tenemos instalado el ProxMox en el PC de clase asignado de los que están atrás del todo. Una vez tengamos más claro el esquema de red definitivo, procederemos a empezar a configurarlo y documentarlo.

__Proxmox__ es una plataforma de virtualización de código abierto que permite gestionar máquinas virtuales y contenedores. Está basada en Debian y combina tecnologías como KVM (para la virtualización completa) y LXC (para la virtualización basada en contenedores).

Se utiliza principalmente en entornos de servidores para crear, administrar y orquestar múltiples VMs y contenedores de forma eficiente. También incluye herramientas para gestionar almacenamiento, redes y copias de seguridad. Además, soporta la creación de clusters para alta disponibilidad y migraciones en vivo, lo que lo hace ideal para centros de datos y servidores corporativos.

Es especialmente útil para:

-Consolidación de servidores: Ejecutar múltiples sistemas operativos en un solo servidor físico.

-Gestión de recursos: Controlar y distribuir recursos de hardware como CPU, memoria y almacenamiento.

-Automatización y alta disponibilidad: Ofrecer soluciones escalables y resistentes a fallos.

[Ver archivo](M11UF4A2-QuimFernandez_PolCamarena.docx.pdf)

Creamos ROUTER con vmbr0 y vmbr1 para que todo el proyecto funcione de manera correcta.

![image](https://github.com/user-attachments/assets/3dd03ffe-1fb9-4995-8ce8-77cdfb792f1e)

Ahora creamos Cliente con vmbr1 

![image](https://github.com/user-attachments/assets/a9b6528e-5400-4da7-a68b-a23a08da9600)

Creamos DNS  con vmbr1

![image](https://github.com/user-attachments/assets/59b69707-28b5-4a25-9e1d-3a029bd5748b)



## 11.DNS Y SU CONFIGURACIÓN 

¿Qué es el DNS?

El DNS es  un servicio distribuido a nivel global que permite convertir los nombres de los sitios en las direcciones IP que les corresponde.
Cuando un usuario registra un dominio, se crea una entrada WHOIS en el registro correspondiente y queda almacenada en el DNS como un
resource record.
La base de datos de un servidor DNS se convierte en la compilación de todos los registros de la zona del espacio de nombres de dominio que gestiona.

Registros del DNS:

A (Address Record): Mapea un nombre de dominio a una dirección IPv4.

AAAA (IPv6 Address Record): Mapea un nombre de dominio a una dirección IPv6.

MX (Mail Exchange): Define qué servidor gestiona el correo electrónico para el dominio.

CNAME (Canonical Name): Apunta un dominio a otro dominio.

NS (Name Server): Especifica qué servidores DNS son responsables de un dominio.

PTR (Pointer Record): Utilizado en la búsqueda inversa de DNS, mapea una IP a un nombre de dominio.

Información del DNS

El servicio de DNS se encuentra en la capa de aplicación del modelo OSI.

La capa más cercana al usuario y contiene todos los protocolos de alto nivel como SMTP, DNS y HTTP.

Este protocolo de red emplea la capa de transporte TCP, UDP y utiliza el puerto 53.

Tipos de Consultas:

Consulta recursiva: Si el servidor DNS local no sabe la respuesta, realiza consultas a otros servidores DNS.

Resolución iterativa: Si un servidor DNS no tiene la respuesta directa, le da al cliente la dirección de otro servidor que puede tenerla. 

VENTAJAS DEL DNS

Una ventaja es que resuelve el problema de las colisiones o nombres duplicados porque garantiza que todos los nombres hermanos o hijos de un mismo nodo tengan etiquetas o nombres diferentes.

Elimina los problemas del sistema basados en el fichero HOSTS.TX

Y tambiém permite "particionar" y gestionar los diferentes subdominios de modo independiente.


CONFIGURACIÓN DEL DNS EN PROYECTO


Para empezar la configuracióm, actualizamos los repositorios de nuestro sistema:

sudo apt update

Y ahora instalamos el paquete bind9:

sudo apt install bind9

![image](https://github.com/user-attachments/assets/d1dc8dc2-0ce6-46a3-9c21-92cfd6a7b8b6)


Editamos el netplan, lo ponemos con DHCP y lo editamos para poder avanzar de forma correcta


![image](https://github.com/user-attachments/assets/5a148d65-8ba3-46a5-8dc1-fa04f57cb2b9)

Ahora si ponemos ip a, veremos que mediante DHCP, tenemos asignada la IP 10.20.30.4

![image](https://github.com/user-attachments/assets/c1268273-0e87-47e4-a158-c9d55fc7c9fa)

Entonces ahora vamos al archivo que se llama named.conf.local , que bàsicamente es donde haremos la configuración DNS de la zona inversa y directa

El named.conf.local lo utiliza por el servidor DNS BIND para configurar zonas específicas y personalizadas, como dominios locales o zonas reversas. 

Permite definir configuraciones locales que el servidor manejará, como:

Zonas directas: Traduce nombres de dominio a direcciones IP.

Zonas inversas: Traduce direcciones IP a nombres de dominio.

![image](https://github.com/user-attachments/assets/698eab22-3c6f-41ad-9a3f-f2b6e7828c11)

Para comprobar que la configuración ha sido correcta y que no hemos tenido ningun problema ponemos:

named-checkconf

Ahora creamos los dos archivos de la zona directa y inversa

![image](https://github.com/user-attachments/assets/ea0ca40b-a449-4ef2-a788-3e54fd966750)

Ahora, accedemos al archivo de la zona directa y lo configuramos para comprobar que funcione de forma correcta

La zona directa de DNS es una configuración que mapea nombres de dominio a direcciones IP.

En nuestro caso el servidor DNS manejará el dominio quimpol.local  y usará el archivo db.quimpol.local para almacenar.

![image](https://github.com/user-attachments/assets/13a11569-e7f1-4d9a-aba1-63da8068c6b0)

Y ahora haremos lo mismo pero para la zona inversa

Lo que hace la zona inversa es que  está buscando el nombre de dominio asociado con una dirección IP determinada.

En nuestro caso la IP  es la 10.20.30.4,

Entonces nuestra dirección IP, que es la 10.20.30.4, nos  permitirá resolver esa IP al nombre de nuestro dominio, el quimpol

Y tambien ya lo ponemos para la configuración con la MV de cliente

![image](https://github.com/user-attachments/assets/2a8c4855-e765-45e1-87d0-8fcde3150868)

Ahora para comprobar que toda la configuración de los ficheros de zonas se ha realizado correctamente, hacemos lo siguiente:

![image](https://github.com/user-attachments/assets/afe5a924-e594-42eb-a3f1-cf78db086c3b)

![image](https://github.com/user-attachments/assets/9204d77d-c49c-4d64-b5b6-d4a5bce35c60)

Ahora nos tocaría editar el fichero 
/etc/bind/named.conf.options

Esto lo que hace es configurar parámetros globales y opciones predeterminadas que se aplican a todas las zonas y consultas DNS gestionadas por el servidor.

Modificamos el archivo y en listen ponemos la 10.20.30.4 que es para que servidor DNS escuchará consultas.

 
![image](https://github.com/user-attachments/assets/10fba1a7-6320-46e1-96bd-8c527a266608)

Ahora, vamos al archivo
/etc/default/named 

El archivo /etc/default/named controla cómo se inicia el servicio BIND

Que es donde especificaremos la opción -4 como argumento para el usuario bind, que  se crea automáticamente durante la instalación del servicio bind9. 

La opción -4 , nos sirve para forzar el uso de IPv4 siempre y evitar  mensajes de error de red inalcanzable por direccionamiento IPv6.

![image](https://github.com/user-attachments/assets/35beebba-441a-4400-80e9-f9f877005fe8)

Ahora reiniciamos el servicio bind9 y ver si todo esta correcto

![image](https://github.com/user-attachments/assets/d041f362-1301-4ab1-9ab2-8b52c5389859)

Ahora mediante el nslookup, comprobamos si el servidor DNS está resolviendo correctamente los nombres y las direcciones IP

![image](https://github.com/user-attachments/assets/29f10803-5094-4337-a681-789bf41a54a0)


## 12.CONFIGURACIÓN DE DHCP


Primero lo que hacemos es instalar el servicio DHCP:

Actualizamos: sudo apt update

sudo apt-get install isc-dhcp-server




Hacemos la configuración del archivo DHCP:


El archivo de configuración principal se encuentra en /etc/dhcp/dhcpd.conf. En este archivo, lo que hay que hacer es definir los parámetros de red, como el rango de direcciones IP, la puerta de enlace predeterminada, DNS y duración de la concesión. 

![image](https://github.com/user-attachments/assets/cdd31d80-568d-4635-abe8-0af37b193f6b)

   
Esta es nuestra configuración en el netplan:

![image](https://github.com/user-attachments/assets/a8cf1adb-abcb-4c2d-aac0-f47b7dc92b6a)



Configurar las interfaces de red:

Ahora  para comprobar y asegurarnos que la interfaz de red correcta esté configurada para proporcionar el servicio DHCP definimos  la interfaz en el archivo de configuración de red o directamente en /etc/default/isc-dhcp-server:


Reiniciar el servicio DHCP:

Una vez configurado, hay que reiniciar el servicio para aplicar los cambios:


sudo systemctl restart isc-dhcp-server
Comprobación:

 Y para verifica si el servidor DHCP está funcionando correctamente:


sudo systemctl status isc-dhcp-server




## 13.CONFIGURACIÓN DE NGINX

Para empezar, instalamos el nginx con el comando:

sudo apt-get install nginx

Entramos al netplan y configuramos para que funcione de forma correcta

![image](https://github.com/user-attachments/assets/b9dba283-7f6d-4336-9ac2-6986d0f7c8df)

Vemos con el ip a que nos da la IP mediante DHCP, la 10.20.30.5

![image](https://github.com/user-attachments/assets/0063e93c-20d3-491c-967e-1965c49805d0)

Ahora tenemos que editar el archivo nginx.conf que se encuentra en /etc/nginx

![image](https://github.com/user-attachments/assets/f54260e8-7625-45e1-be91-1d5da4098f22)

Eel archivo de configuración global es: 

/etc/nginx/nginx.conf

Entonces ahora, con el  el directorio  /etc/nginx/sites-enabled/ , lo que haremos será almacenar los  los enlaces simbólicos a los archivos de configuración de sitios web creados en 
/etc/nginx/sites-available/  para que puedan ser habilitados los sitios


Ahora editamos el archivo /sites-available/default, que en este caso sería el bloque predeterminado del servidor de Nginx

Php:

¿Qué es php?

PHP es un lenguaje de programación de propósito general ampliamente utilizado para el desarrollo de aplicaciones web del lado del servidor

Características principales:

Dinámico y orientado a la web:

PHP se usa principalmente para generar contenido dinámico en páginas web.
Puede interactuar con bases de datos, manejar formularios y autenticar usuarios.

Integración con HTML:

PHP se incrusta directamente en archivos HTML, lo que facilita la creación de páginas web dinámicas.

Compatibilidad multiplataforma:

PHP funciona en varios sistemas operativos, como Windows, Linux y macOS.
Es compatible con la mayoría de los servidores web, como Apache, NGINX.

Para instalar el php ponemos:

sudo apt install php-fpm

Para verificar si tenemos instalado PHP ponemos:


php -version

Para comprobar si tenemos php-fpm ponemos:


php-fpm7.4 -v



## ACTIVIDAD ENTREGADA EN LA MEMÓRIA (ALINA)

¿Qué es un servidor web?

Un servidor web es un software que forma parte del servidor y tiene como misión principal devolver información (páginas) cuando recibe peticiones por parte de los usuarios.

En otras palabras, es el software que permite que los usuarios que quieren ver una página web en su navegador puedan hacerlo.


¿Qué es un hosting?

Un hosting es un servicio de alojamiento web que te permite publicar un sitio web o aplicación en Internet. Cuando contratas un servicio de hosting, básicamente alquilas un espacio en un servidor físico donde puedes almacenar todos los archivos y datos necesarios para que tu sitio web funcione correctamente.

¿Qué es Nginx?

Nginx, pronunciado como “engine-ex”, es un servidor web de código abierto que, desde su éxito inicial como servidor web, ahora también es usado como proxy inverso, cache de HTTP, y balanceador de carga.

Algunas compañías de alto perfil que utilizan Nginx incluyen Autodesk, Atlassian, Intuit, T-Mobile, GitLab, DuckDuckGo, Microsoft, IBM, Google, Adobe, Salesforce, VMWare, Xerox, LinkedIn, Cisco, Facebook, Target, Citrix Systems, Twitter, Apple , Intel, y muchos más


Haz una comparativa entre Nginx y Apache.

Nginx:

Usa una arquitectura basada en eventos y asincrónica, lo que le permite manejar múltiples conexiones simultáneamente con menos recursos.
Es ideal para cargas altas y servidores con tráfico masivo.
Excelente para servir contenido estático (imágenes, archivos HTML, etc.) rápidamente.


Apache:

Emplea un modelo de procesos/hilos, donde cada conexión consume un hilo o proceso. Esto puede ser ineficiente bajo cargas pesadas.
Ofrece más flexibilidad para manejar configuraciones complejas gracias a sus módulos dinámicos.





## 14.BASE DE DATOS

Aquí mostramos el esquema final de la base de datos, donde hemos añadido algunas conexiones que no habíamos tomado en cuenta. Hemos creado la base con MySQL WorkBench a través de SQL y una vez ejecutado el código, gracias a la función de la creación de diagramas, hemos podido ver las tablas y sus conexiones.

![Logo del equipo](carpeta_fotos/esquema_basededatos.png)


## 15.NOVEDADES/CAMBIOS DE LA WEB

Para empezar, hemos hecho nuchos cambios respectivamente a la idea que decimos hacer al principio de la web, la idea que me estoy refiriendo, es toda esa explicación que hicimos al principio del github, que es donde esta esa explicación con capturas que nosotros mismo hicimos del canva del boceto de la idea principal del proyecto.

Como página principal, seguimos teniendo lo mismo, una página donde el usuario pueda ver arriba derecha los botones de estadísticas, plantilla y login, etc..
Y que si va bajanda podrá ver la zona de estadísticas y resultados, que esta linkeado a otra página, ya que se podrá ver y entender mucho mejor  bajo nuestro punto de vista

Entonces, creemos que lo mas importamte que llevamos hecho es la parte de  plantilla, ya que lo que hicimos fue crear en nuestra bbdd, todos los jugadores de todas las plantillas de laliga.

Eso lo hicimos poniendo a cada equipo un numero, del 1 al 20, ya que son 20 equipos, entonces lo siguiente era poner a cada posicion del campo, del 1 al 5, osea 1 es portero 2 es defensa, 3 es mediocampista, 4 delantero y 5 que sea la posicion del banquillo, entonces ahora abria que poner 11 jugadores con 1,2,3 y 4 osea, 1 jugador con 1, 4 jugadores con el numero 2, 3 jugadores con el numero 3 y 3 jugadores con el numero 4, esto suma a 11. Y  los otros jugadores, da igual que sean 10 o 20, todos estaran con el numero 5, que será en la posicion de banquillo. Entonces despues de poner todo en la bbdd lo que hicimos fue conectarlo para nuestra pagina web, entonces si ahora por ejemplo le doy click al escudo del getafe, me saldriá el 11 de jugadores, y el banquillo, también tengo que decir que cada equipo tiene también puesto la imagen y nombre del entrenador

Entonces lo que hicimos en estadisticasm fue ponerlas de forma manualmente, ya que con el tiempo que quedaba para entregar el trabajo era imposible acabarlo

## 16.FUNCIONALIDADES

Aquí como funcionalidades, tenemos:

1. Register: El usuario se puede registrar a nuestra página, esto con la bbdd entre medio, haciendo que cuando el usuario se registra se pueda ver en nuestra bbdd como usuario
2. Login: El usuario después de registrase puede acceder a nuestra página ya como usuario

3. Plantilla: Esta funcionalidad es la de plantillas, es decir todo lo que he explicado antes, hay que decir que para hacer esto tardamos mucho tiempo, pusimos manualmente unos 1000 links en la bbdd entre imagenes de jugadores, entrenadores y escudos.

4. Contactarnos: Esta función esta en procedimiento, y basicamente es para que los usuarios nos puedan enviar un mensaje para dudas/críticas/valoraciones etc..

Creemos que las 4 funcionalidades para nuestro trabajo son muy buenas ideeas, ya que conjuntan perfectamente a nuestra idea prinpial

## 17.NUESTRO FUTURO

Creemos que para la siguente UF, podemos seguir con nuestro proyecto, ya que tenemos aún muchas buenas ideas para seguir mejorando y aprendiendo. Esto lo defenderemos en la exposición del proyecto hasta la muerte
Algunas ideas serián:
- API de resultados
- Poder básicamente hacer el FANTASY, con que cada persona pueda hacer su equipo, y competir con otros jugadores

## 18.VALORACIONES DEL PROYECTO

Creemos que en el proyecto hemos aprendido muchisimo, con las instalaciones de las diferentes máquinas virtuales, con el nuevo conocimiento como nginx, o php. O también con el constante trabajo diario y semanal sobre una idea que poco a poco hemos ido creando y mejorando.

Y personalmente a los dos intregantes del equipo nos parece por ahora seguir con nuestro trabajo en la próxima UF


## 19.INCIDENCIAS TÉCNICAS

Mala configuración en el DNS, por falta de no haber reiniciado el servicio despues de modificarlo

![image](https://github.com/user-attachments/assets/b6244674-e807-4ece-85bb-f70eb73dd330)

Otro fail....

![image](https://github.com/user-attachments/assets/da6ec4d0-d5c3-4dce-a58a-2327ed2720b5)

En incidencias durante las instalaciones de las MV no tuvimos muchos errores, y los únicos que tuvimos eran por equivocaciones de escritura y palabras.
Pero donde si tuvimos muchos errores fue durante la creación de la bbdd, ya que al crear plantilla , donde pusimos muchos datos, nos equivocamos mucho, pero poco a poco esos errores se fueron arreglando hasta el dia de hoy que nuestra bbdd funciona perfectamente
</details>

<details>
  <summary>SEGUNDO PROYECTO💻</summary>


## ÍNDICE

## 1.IDEAS PARA EL SEGUNDO PROYECTO

### NUEVAS FUNCIONALIDADES

#### PENDIENTES
- Opción de cambio de contraseña
- Formulario de Contacto

#### NUEVAS EN LA WEB
- Implementación de una API: recrear la web a partir de la API que nos permitirá añadir la función de las estadísticas actualizadas de los jugadores.

- Agregar como amigos a los usuarios

- Implementación del juego:

    Está para nosotros es la parte mas importante, aquí pondremos de novedades:
    
    Los jugadores se puedan agregar como si fueran amigos
  
    Una página donde los usuarios puedan crear sus equipos, saldrá su 11 inicial, y también habrá un apartado para ver todos sus jugadores ( a parte del 11 inicial)
  
    Una página donde los usuarios podrán comprar los jugadores, hará la misma función que un mercado, allí apareceran todos los jugadores de futbol disponibles para ser comprados
  
    Una página que funcionará como si fuera una clasificación donde los jugadores con más puntos conseguidos apareceran, así será más competitivo y hará el juego más interesante para los usuarios




#### OBLIGATORIAS
- Docker
- FireWall
- Backups (script)
- Seguridad:
  - MySQL (crear más de un usuario, securizar la DB, triggers)
  - Protección de código fuente
 
## FUNCIONALIDADES

![image](https://github.com/user-attachments/assets/ecd8f3c9-cd94-4e7b-a4e9-cfcbcfb238fd)

Los dos, Quim y Pol haremos la funcionalidad del juego Fantasy, ya que es una funcionalidad muy larga y compleja, y necesitamos que los dos lo hagamos para poder acabar

La funcionalidad de la API la hará Pol

La funcionalidad de cambio de contraseña la hará Quim

La funcionalidad de agregar amigos la haremos cuando acabemos la del Juego Fantasy, ya que preferimos insistir con el tiempo en terminar la funcionalidad del juego fantasy por su gran importancia y valor en nuestro proyecto, ya que es en lo que se basa nuestra idea de proyecto

## ARQUITECTURA DEL SISTEMA

Esta será mas o menos nuestra arquitectura, no es definitivo pero por ahora es lo que tenemos como idea

![image](https://github.com/user-attachments/assets/19bd263b-e789-4cd1-b4b9-a880a6ba2c8e)

![image](carpeta_fotos/esquema_red_2.png)

## DIAGRAMA DE LA BASE DE DATOS

Esta es nuetra base de datos, es la misma que la del primer proyecto pero con pequeñas variaciones ya que como comentamos seguimos con el mismo proyecto entonces la infraestructura de la base de datos por narices tiene que ser muy parecida ya que mas o menos ya esta de alguna manera terminada

Si tenemos más tiempo alomejor podemos añadir alguna tabla más a la base de datos, pero por ahora es lo que tenemos

![image](https://github.com/user-attachments/assets/c77022c7-f9fa-4e4f-b08c-578abd2a24fb)

## TAREAS

Ahora mismo por problemas no podimos empezar en la creación de la infraestructura de la Ubuntu o Alpine.
El 29/01 empezamos con docker y los containers, y desde una MV de ubuntu server, ya que desde Alpine hubo algunos problemas y preferimos utilizar la ubuntu por la razón de que ya la hemos usado mucho, entonces empezamos a crear la estrucura y importamos el sitio web en docker, luego dentro de nginx configurmos el default.conf, luego en mysql lo tenemos vació por ahora y ahora estamos con el docker compose. 
Creo que para el proximo miercoles 5/02 ya lo tendremos terminado ya que Alina y algunos compañeros nos han dado explicaciones para entenderlo mejor y asi hacerlo de alguna forma un poco mas rapido para asi aprovechar el tiempo al maximo para llegar al ritmo de la clase

## FUNCIONALIDADES HECHAS

Por ahora durante estas 3 semanas hemos realizado la funcionalidad de canvio contraseña, y también la funcionalidad de que el usuario no pueda inpeccionar nuestro código, aplicando un poco de seguridad para nuestra página web
## Docker Basic

¿Qué es Docker y cuál es su principal función en el ámbito de la virtualización de aplicaciones?

Docker es una plataforma de contenerización que permite empaquetar aplicaciones y sus dependencias en contenedores ligeros y portables. Su principal función es facilitar la virtualización a nivel de sistema operativo, lo que permite ejecutar múltiples aplicaciones de manera aislada en el mismo host, asegurando consistencia, eficiencia y portabilidad entre entornos

¿Cuáles son las principales ventajas de utilizar contenedores Docker en comparación con otras formas de virtualización?

Ligereza:
Los contenedores comparten el núcleo del sistema operativo, reduciendo el consumo de recursos en comparación con las VMs, que requieren un sistema operativo completo para cada instancia.
Velocidad:
Los contenedores se inician en segundos, mientras que las VMs pueden tardar minutos debido al proceso de arranque completo del sistema operativo.
Portabilidad:
Los contenedores son altamente portables, ya que encapsulan todo lo necesario para ejecutar una aplicación (código, dependencias, configuraciones), asegurando consistencia entre entornos.
Escalabilidad:
Docker permite escalar aplicaciones fácilmente, ejecutando múltiples instancias de un contenedor de forma rápida y eficiente.
Aislamiento:
Proporcionan un aislamiento efectivo entre aplicaciones, evitando conflictos entre dependencias o configuraciones.

¿Cómo se crea un contenedor en Docker y cuáles son los elementos clave en la definición de su entorno y configuración?

¿Cuál es la diferencia entre una imagen y un contenedor en Docker, y cómo se relacionan entre sí?

Una imagen en Docker es una plantilla estática que contiene todo lo necesario para ejecutar una aplicación. Un contenedor es una instancia activa de esa imagen, ejecutándose en un entorno aislado.


Lista las principales funciones de gestión de imágenes y explica brevemente que hace cada una de ellas. 
Lista las principales funciones de gestión de contenedores y explica brevemente que hace cada una de ellas. 

Ejecuta los siguientes comandos y explica qué es lo que hace, qué información te muestra:
docker info

Muestra información detallada sobre el estado de Docker, incluyendo configuración del sistema, número de contenedores, imágenes, redes y más.

![image](https://github.com/user-attachments/assets/bb106249-9b69-41b6-80a9-443a07662ef0)

docker version

Muestra la versión de Docker instalada, incluyendo información del cliente y del servidor.

![image](https://github.com/user-attachments/assets/fece4bc1-5eb0-47be-b52f-f21b5c610d98)

docker run debian /bin/echo "Hola Mundo"
 Corre el comando /bin/echo "Hola Mundo" 

![image](https://github.com/user-attachments/assets/ff226922-77f9-4dc8-9042-7f9e31f0d4b9)
docker –help   
Muestra la ayuda general de Docker

![image](https://github.com/user-attachments/assets/5fee144e-23b1-475a-abfb-bb4929c8dbd8)


docker inspect id

Proporciona información detallada en formato JSON sobre un contenedor o una imagen especificada por su ID o nombre.

docker rmi debian 

Elimina la imagen debian del sistema si no tiene contenedores asociados. 

docker ps (-a  -l)

 Lista los contenedores en ejecución. Luego con el -a, lista todos los contenedores, incluyendo los detenidos, y el -l, lo que hace es que muestra solo el último contenedor creado 

Ejecuta el siguiente comando: y responde
docker run -d -p 83:80 nginx 
¿Qué es la exposición de puertos?

La exposición de puertos es el mapeo entre un puerto del sistema anfitrión (físico) y un puerto del contenedor. Permite acceder desde el equipo anfitrión (o red externa) a los servicios ejecutándose dentro del contenedor.

¿Qué puerto corresponde a tu equipo (físico) y cuál al contenedor?

Puerto del equipo (físico): 83
Puerto del contenedor: 80


¿Qué ejecuta este comando? Explica

-d: Ejecuta el contenedor en segundo plano (modo desapegado).
-p 83:80: Mapea el puerto 83 del equipo anfitrión al puerto 80 del contenedor.
nginx: Usa la imagen oficial de Nginx para levantar un servidor web en el contenedor.
En resumen, lanza un servidor web Nginx accesible en el puerto 83 del equipo anfitrión.

Ve al navegador y verifica que el servidor web del container. ¿Qué puerto utilizas para visualizar la web?

Usarías el puerto 83 en el navegador,

Ejecuta los siguientes comandos y explica:

docker logs id

Muestra los registros (logs) generados por el contenedor identificado por <id>
Aqui podremos ver Los logs dependen de la aplicación que se ejecuta dentro del contenedor. Por ejemplo, si estás ejecutando un servidor Nginx, podrías ver mensajes de inicio del servidor y cualquier solicitud HTTP procesada por él.

docker inspect id

Proporciona información detallada en formato JSON sobre un contenedor o una imagen, según el ID o nombre especificado.

docker ps

Lista todos los contenedores que están en ejecución.


docker stop id

Detiene el contenedor especificado por <id> o su nombre.

¿Qué hace el comando: docker volume create portainer_data? Investiga y explica 

Es para crear el volumen que Portainer Server usará para almacenar su base de datos.

![image](https://github.com/user-attachments/assets/dd073f48-4937-4339-8b75-50885da2e8e3)

docker inspect portainer_data

Aqui lo verificamos


![image](https://github.com/user-attachments/assets/517cbc02-e9fe-4919-9c34-0378e9a9dd61)

¿Cuál es el puerto del equipo físico y cuál del contenedor en el siguiente comando:


docker run -d -p 8000:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest

Puerto del contenedor: 8000 es el puerto dentro del contenedor al que está expuesto el servicio
Puerto del contenedor: 9443 el puerto dentro del contenedor

Mas capturas del proceso:

![image](https://github.com/user-attachments/assets/7860ed7f-3bb3-4eac-a9b8-17627939b851)

![image](https://github.com/user-attachments/assets/e39df1f0-021a-4717-8ef1-50786f3690b9)

![image](https://github.com/user-attachments/assets/b5ee1335-2d74-446e-b3cc-605162baa0bd)

Aqui es el primer momento que accedemos a los container, luego abajo hay una foto donde se ven todos los contenedores que se estan ejecutando






## Docker Compose

## Docker Compose - M08UF2A6-DC-final

El default.conf para que Nginx funcione correctamente como servidor web y define cómo manejar las solicitudes, redirigir tráfico y procesar archivos PHP. 

./teamtactics/nginx/default.conf

![image](https://github.com/user-attachments/assets/69f60272-7c05-44b5-b477-c0e89d5964fe)

./teamtactics/docker-compose.yml

![image](https://github.com/user-attachments/assets/1e85f092-505d-4477-84af-9f765b440a24)

Containers

![image](https://github.com/user-attachments/assets/4a164909-a9ee-4f5f-baa7-1fe14bf196d4)

Visualizar la Web

Accedemos al nginx mediante el puerto 8082

![image](https://github.com/user-attachments/assets/52ec569c-64e2-44ab-b2c5-47879e7f4a53)

![image](https://github.com/user-attachments/assets/365c1b08-8353-4b0f-a684-5e532ed0c0f5)


- ¿Qué son los contenedores de docker?

  Los contenedores de Docker son entornos aislados y ligeros que permiten ejecutar aplicaciones con sus dependencias en cualquier sistema con Docker.
- ¿Qué diferencias hay entre los contenedores de docker y los lxc?

  Docker es más simple y centrado en aplicaciones, mientras que LXC proporciona contenedores más similares a máquinas virtuales, con un sistema operativo completo.
- ¿Cuál es la diferencia entre una imagen y un contenedor en Docker?

  Una imagen es una plantilla inmutable con el software y sus dependencias; un contenedor es una instancia en ejecución de una imagen.
- ¿Qué sucede con los datos cuando un contenedor se elimina?

  Los datos cuando un contenedor se elimina se pierden si no están en volúmenes o montajes persistentes.
- ¿Cuáles son las ventajas de utilizar contenedores de docker?

  Portabilidad, eficiencia, escalabilidad, rapidez en despliegues y aislamiento.
- ¿Qué tipo de aplicaciones y servicios se pueden desplegar con docker?

  Web apps, bases de datos, microservicios, entornos de desarrollo, CI/CD, entre otros.
- ¿Qué otros tipos de contenedores existen además de docker?

  LXC, Podman, Kubernetes (orquestación), OpenVZ y rkt.                                                         
- Guía de Usuario con los pasos claves para desplegar una aplicación web en contenedores.


</details>

## BIBLIOGRAFIA

https://punkymo.gitbook.io/miwiki

