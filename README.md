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

1. IDEAS PARA EL SEGUNDO PROYECTO
2. FUNCIONALIDADES
3. ARQUITECTURA
4. DIAGRAMA DE RED
5. DIAGRAMA DE LA BASE DE DATOS
6. TECNOLOGÍAS
7. HARDWARE
8. SISTEMA OPERATIVO
9. TAREAS
10. FUNCIONALIDADES HECHAS
11. DOCKER COMPLETO
12. DOCKER COMPOSE
13. SERVIDOR DE CORREO  (POSTFIX)
14. Firewall

    
## 1.IDEAS PARA EL SEGUNDO PROYECTO🧠

<details>
  <summary>
   Propuestas de Proyecto💡 
  </summary>

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

</details> 
 
## 2.FUNCIONALIDADES⚙️

<details>
  <summary>
   Opciones y Características🔧
  </summary>

![image](https://github.com/user-attachments/assets/ae76384b-944e-404a-8210-133f7ed628f9)


Los dos, Quim y Pol haremos la funcionalidad del juego Fantasy, ya que es una funcionalidad muy larga y compleja, y necesitamos que los dos lo hagamos para poder acabar

La funcionalidad de la API la hará Pol

La funcionalidad de cambio de contraseña la hará Quim

La funcionalidad de agregar amigos la haremos cuando acabemos la del Juego Fantasy, ya que preferimos insistir con el tiempo en terminar la funcionalidad del juego fantasy por su gran importancia y valor en nuestro proyecto, ya que es en lo que se basa nuestra idea de proyecto
</details> 

## 3.ARQUITECTURA DEL SISTEMA🏛️

<details>
  <summary>
   Estructura del Sistema🏗️
  </summary>

Esta será mas o menos nuestra arquitectura, no es definitivo pero por ahora es lo que tenemos como idea

![image](https://github.com/user-attachments/assets/19bd263b-e789-4cd1-b4b9-a880a6ba2c8e)
</details> 

## 4.DIAGRAMA DE RED🌐

<details>
  <summary>
   Esquema de Conexiones🖧
  </summary>

![image](https://github.com/user-attachments/assets/fe1754c7-bb9f-49b0-aad5-28bc79a0d82a)

</details> 




## 5.DIAGRAMA DE LA BASE DE DATOS🗄️

<details>
  <summary>
   Modelo de BBDD🛢️
  </summary>

Esta es nuetra base de datos, es la misma que la del primer proyecto pero con pequeñas variaciones ya que como comentamos seguimos con el mismo proyecto entonces la infraestructura de la base de datos por narices tiene que ser muy parecida ya que mas o menos ya esta de alguna manera terminada

Si tenemos más tiempo alomejor podemos añadir alguna tabla más a la base de datos, pero por ahora es lo que tenemos

![image](https://github.com/user-attachments/assets/ebfed1b1-f2a8-4a6b-af22-dba2dc718b2d)

</details> 





 ## 6.TECNOLOGÍAS🚀

<details>
  <summary>
   Herramientas Utilizadas🖥️
  </summary>

En este segundo proyecto tenemos la intención de agregar ciertas tecnologías a nuestra web que nos permitirán aumentar la seguridad y eficiencia a la hora de funcionar y monitorizar la. Anteriormente ya habíamos trabajado con algunas como Proxmox, Ubuntu, Html/Css, JavaScript, NGinx, MySQL, PHPMyAdmin, bibliotecas, frameworks, etc.
Aparte de estas tecnologías, agregaremos algunas como; Docker, Portainer, alguna API, Pi-Hole, aplicaremos FireWall, y algunas que iremos añadiendo según las necesidades que encontremos a la hora realizar el proyecto.
</details> 




## 7.HARDWARE🖨️

<details>
  <summary>
   Componentes Físicos🛠️ 
  </summary>


Para este segundo proyecto seguiremos usando el ordenador de clase asignado a nuestro grupo específicamente, en nuestro caso usaremos uno nuevo ya que no sabemos como a pasado pero nuestro antiguo ordenador con toda la infraestructura de Proxmox a desaparecido y ahora no nos queda otra que volver a montarlo todo pero esta vez utilizando los contenedores de Docker con los que trabajaremos en este segundo proyecto.

</details> 




## 8.SISTEMA OPERATIVO💾

<details>
  <summary>
   Plataforma y Software Base🖥️
  </summary>


Principalmente íbamos a usar Alpine Linux ya que nos ofrece mucha eficiencia en cuanto a recursos, ya que es conocida por su tamaño reducido, lo que la hace muy popular en entornos donde se necesita un sistema ligero, como en contenedores Docker. 

Pero trás varias pruebas con el, nos dió ciertos problemas que finalmente nos hizo decantarnos por utilizar un Ubuntu Server ya que ya habíamos trabajado anteriormente con ese sistema. Este nos ofrece ventajas como:

Familiaridad y eficiencia: Ya teníamos experiencia con Ubuntu, lo que facilitó la gestión y configuración de los contenedores sin perder tiempo en aprender un nuevo sistema.

Soporte y estabilidad: Ubuntu Server ofrece un soporte robusto y actualizaciones regulares, lo que garantiza seguridad y estabilidad a largo plazo, vital para producción.

</details>  




## 9.TAREAS📋

<details>
  <summary>
   Actividades✅
  </summary>

Ahora mismo por problemas no podimos empezar en la creación de la infraestructura de la Ubuntu o Alpine.
El 29/01 empezamos con docker y los containers, y desde una MV de ubuntu server, ya que desde Alpine hubo algunos problemas y preferimos utilizar la ubuntu por la razón de que ya la hemos usado mucho, entonces empezamos a crear la estrucura y importamos el sitio web en docker, luego dentro de nginx configurmos el default.conf, luego en mysql lo tenemos vació por ahora y ahora estamos con el docker compose. 
Creo que para el proximo miercoles 5/02 ya lo tendremos terminado ya que Alina y algunos compañeros nos han dado explicaciones para entenderlo mejor y asi hacerlo de alguna forma un poco mas rapido para asi aprovechar el tiempo al maximo para llegar al ritmo de la clase

</details>  



## 10.FUNCIONALIDADES HECHAS🎯

<details>
  <summary>
   Funciones Implementadas✔️
  </summary>

Por ahora hemos realizado la funcionalidad de canvio contraseña, y también la funcionalidad de que el usuario no pueda inpeccionar nuestro código, aplicando un poco de seguridad para nuestra página web
</details>  
 
## 11.DOCKER🐳 

<details>
  <summary>
   ▶Introducción a Docker📦
  </summary>
  
Bueno para empezar, un poco sobre que es Docker, Docker es una plataforma de contenedorización que permite a los desarrolladores empaquetar aplicaciones y sus dependencias en contenedores ligeros y portátiles. 
Estos contenedores pueden ejecutarse de manera consistente en cualquier entorno, ya sea en una computadora local, en servidores o en la nube.

Nosotros en nuestro caso usamos Docker ya que aparte de que es obligatorio, es mucho más rápido que iniciar o detener máquinas virtuales y también Docker es mas eficaz ya que las MV


Ahora mostraremos algunos comandos, ya que creemos que es importante dentro de la introducción, y asi mostramos alguna información de Docker 

docker version:   	Muestra la versión instalada de Docker.


docker info:  Muestra información detallada sobre Docker y su configuración.


docker help: Muestra ayuda sobre los comandos de Docker


docker run <imagen>	Ejecuta un contenedor basado en una imagen.


docker run -d -p 8080:80 <imagen>	Ejecuta un contenedor en segundo plano y expone un puerto.


docker ps	Lista los contenedores en ejecución.


docker ps -a	Lista todos los contenedores (ejecutándose o detenidos).


docker stop <id>	Detiene un contenedor en ejecución.


docker rm <id>	Elimina un contenedor detenido.


Ahora explicaremos algunas ventajas de Docker


Tenemos que los contenedores Docker pueden ejecutarse en cualquier entorno sin cambios, ya sea en Windows, Linux, MacOS, servidores o en la nube y también evita problemas de dependencias, configuraciones o versiones de software diferentes en cada entorno.
Los contenedores comparten el mismo sistema operativo, lo que reduce el consumo de recursos y con Docker Compose, puedes definir y ejecutar múltiples contenedores con un solo archivo YAML


NUDO (DOCKER) GUIA DE USUARIO DE COMO INSTALAR / UTLIZAR DOCKER


Ahora lo que haremos será dentro del NUDO de Docker, como una mini guia sobre DOCKER, aquí intentaremos explicar sobre como instalar y utilizar DOCKER
Aqui ya decimos que lo montaremos dentro de una MV ubuntu server

Entonces para empezar, primero de todo lo que tendriamos que realizar sería actualizar los paquetes de ubuntu

sudo apt update

![image](https://github.com/user-attachments/assets/3c989c29-7705-463b-a4cd-0eb8627f6da4)


Entonces ahora lo que tendríamos que hacer seria instalar paquetes que permitan a APT descargar a través de HTTPS, ya que Docker se descarga desde un repositorio HTTPS, y es necesario instalar algunos paquetes para que lo habiliten

sudo apt install -y apt-transport-https ca-certificates curl software-properties-common

![image](https://github.com/user-attachments/assets/edd77fe6-b72b-4245-b22b-571ab40f15a3)


Ahora lo que tendriamos que hacer es importar la clave GPG para verificar que los paquetes que descargues desde el repositorio oficial de Docker 
Entonces podremos este comando:

sudo mkdir -m 0755 -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg

![image](https://github.com/user-attachments/assets/2d929a93-0f20-405b-bec8-9615005eb984)



Y ahora para poder instalar Docker, es necesario agregar su repositorio oficial a la lista de repositorios de tu sistema
Entonces pondremos este comando:

sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"

![image](https://github.com/user-attachments/assets/d5049960-317b-4626-8cce-a61b1a5dfbea)



Ahora después de esto esto, tendremos que actualizar nuevamente los paquetes del sistema:

![image](https://github.com/user-attachments/assets/ec61ad41-9f71-4848-84cc-d4790427d064)


Y ya luego de hacer todo esto procedimiento, ya podremos instalar el docker. 
Para eso pondremos este comando:

sudo apt install docker-ce

![image](https://github.com/user-attachments/assets/b884cfb1-9e07-4fbe-a499-c3745fccd13b)+


Y ya si queremos comprobar si el funcionamiento esta correcto, pondremos el siguiente comando para asegurarnos

sudo systemctl status docker

![image](https://github.com/user-attachments/assets/1a7d2297-d143-41fd-ba89-f71c3110110f)


Vale, ahora para seguir con el procedimento, tenemos que tocar portainer

Portainer es una herramienta de administración para Docker con una interfaz gráfica fácil de usar. Permite gestionar contenedores, imágenes, redes y volúmenes sin necesidad de usar la línea de comandos.

Para empezar, nosotros hemos creado  un volumen de Docker llamado portainer_data para almacenar la base de datos de Portainer


docker volume create portainer_data

![image](https://github.com/user-attachments/assets/adaed8b5-bfcb-4897-99ab-3f2207643689)

Ahora, comprobaremos si  el volumen se haya creado correctamente usando el comando:

docker volume inspect portainer_data

![image](https://github.com/user-attachments/assets/e5f2e4fc-cd5b-4895-a0c0-0f0260eb61e2)


Ahora si ya podremos  instalar el contenedor de Portainer:

docker run -d -p 8000:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest

![image](https://github.com/user-attachments/assets/485c77c8-5e63-4661-a904-0cf373604f62)


Ahora para comprobar si el contenedor está corriendo

docker ps

![image](https://github.com/user-attachments/assets/9e455002-e5d8-48a1-934b-5d4427b5f0a5)


Y ya ahora si vamos al navegador y ponemos una IP con el puerto 9443

https://192.168.1.79:9443

Ya podriamos acceder al portainer donde se encontraran todos los contenedores DOCKERS


Bueno y en la foto de abajo, se ven todos los contenedores que tenemos montados, hay q decir q para poder tener todo eso tenemos que configurar diferentes archivos de configuración:


![image](https://github.com/user-attachments/assets/60136b7d-26c2-4ccb-b183-5b735b91f971)


Tenemos estos dos archivos para poder realizar la configuración:

default.conf

docker-compose.yml

El  default.conf para que Nginx funcione correctamente como servidor web y define cómo manejar las solicitudes, redirigir tráfico y procesar archivos PHP. 

./teamtactics/nginx/default.conf

![image](https://github.com/user-attachments/assets/b50f36eb-d6be-41ec-8440-bbca1c0fdfc1)


Bueno, el servidor escucha el puerto 80 y tenemos el nombre del servidor como localhost.

Luego, la definimos la carpeta donde se encuntra el contenido del sitio web:
root /var/www/teamtactics/TeamTactics/html

Primero busca index.htm, luego el index.html y luego el index.php
index index.htm index.html index.php;


Luego tenemos los registros de acceso y el de los errores, ya que guarda las solicitudes que recibe el servidor y también registra los errores

access_log /var/log/nginx/access.log;
error_log /var/log/nginx/error.log;

Esto ahora sería la configuracion de nuestros archivos que son PHP

    location ~ \.php$ {
        include fastcgi_params;
        fastcgi_pass php:9000;
        fastcgi_index index.php;
        fastcgi_param SCRIPT_FILENAME $document_root$fastcgi_script_name;
    }

Y ahora definimos las rutas para los archivos CSS, JAVASCRIPT, las imagenes y también todos los archivos subidos.
Todo estos archivos se sirven de:

/var/www/teamtactics/TeamTactics/

Estos creemos que son los mas importantes de explicar





El archivo docker-compose.yml es un archivo de configuración en formato YAML que se usa con Docker Compose para definir y ejecutar múltiples contenedores de Docker de manera organizada.

./teamtactics/docker-compose.yml

![image](https://github.com/user-attachments/assets/5b88f50a-abb6-4ff3-bd46-f796a59be8d8)


Dentro de este archivo tenemos la configuracion de 4 servicios de docker

phpfpm:
  image: php:8-fpm-alpine
  container_name: phpfpm
  working_dir: /var/www/teamtactics
  ports:
    - "9000:9000"
  volumes:
    - './web:/var/www/teamtactics'
  restart: always
  networks:
    - netweb

Este sería la configuración del PHP 
Donde se define el directorio de trabajo dentro del contenedor, en nuestro caso en teamtactics:

working_dir: /var/www/teamtactics

nginx:
  image: nginx:alpine
  container_name: nginx
  ports:
    - 8082:80
  working_dir: /etc/nginx
  volumes:
    - './web:/var/www/teamtactics'
    - './nginx/default.conf:/etc/nginx/conf.d/default.conf'
    - './nginx:/var/log/nginx/'
  restart: always
  networks:
    - netweb

Este sería la configuracion del nginx, y expone el puerto 80 del contenedor en el 8082 del host.
Comparte archivos del host con el contenedor:

./web:/var/www/teamtactics

Y también carga los archivos de la configuración de Nginx:

./nginx/default.conf:/etc/nginx/conf.d/default.conf

db:
  image: mysql
  container_name: miDB
  ports:
    - "3307:3306"
  environment:
    MYSQL_ROOT_PASSWORD: 1234
  volumes:
    - './mysql:/var/lib/mysql'
    - './db:/db'
  networks:
    - netweb

Este seria el servicio del MYSQL, y por ahora no hemos hecho nada y lo mismo con el phpMyAdmin

Estos 2 archivos, el docker-compose-yml y el default.comf, lo que hacen es trabajar juntos para configurar y ejecutar un entorno web basado en Docker, bueno y como he dicho antes, estara compuesto por Nginx, PHP-FPM, MySQL y phpMyadmin

docker-compose.yml levanta y configura los contenedores
default.conf define cómo Nginx maneja las peticiones


Containers

Aqui se ven todos los containers que tenemos, y si clickamos en teamtactics se veran todos los que son para teamtactics

![image](https://github.com/user-attachments/assets/4a164909-a9ee-4f5f-baa7-1fe14bf196d4)

Visualizar la Web

Una vez ya teniendo todas las configuraciones y ponemos la IP en el navegador ya podremos tener acceso al nginx mediante el puerto 8082

![image](https://github.com/user-attachments/assets/52ec569c-64e2-44ab-b2c5-47879e7f4a53)

![image](https://github.com/user-attachments/assets/365c1b08-8353-4b0f-a684-5e532ed0c0f5

</details>

<details>
  <summary>
   Docker Compose⚓
  </summary>
  
- ¿Qué son los contenedores de docker?

  Los contenedores de Docker son entornos ligeros, portátiles y aislados que encapsulan una aplicación junto con todas sus dependencias (bibliotecas, código, configuraciones y archivos necesarios) en un solo paquete. Esto permite que la aplicación se ejecute de manera 
  consistente en cualquier sistema que tenga Docker instalado, independientemente del sistema operativo subyacente.

  Los contenedores eliminan los problemas de compatibilidad entre entornos de desarrollo, prueba y producción, optimizando el uso de recursos en comparación con las máquinas virtuales tradicionales.
- ¿Qué diferencias hay entre los contenedores de docker y los lxc?

  - Docker:

     - Diseñado principalmente para la ejecución de aplicaciones en contenedores individuales.
     - Utiliza una arquitectura basada en imágenes y capas para facilitar la reutilización y distribución de aplicaciones.
     - Tiene una mayor integración con herramientas de orquestación como Kubernetes.
     - Ofrece una interfaz más amigable y centrada en el desarrollo de aplicaciones.
  - LXC (Linux Containers):

    - Proporciona un sistema de contenedores más cercano a una máquina virtual, permitiendo ejecutar múltiples procesos en un solo contenedor.
    - Usa un enfoque más tradicional de virtualización basada en el sistema operativo.
    - No impone restricciones en cómo se deben construir o empaquetar las aplicaciones.
- ¿Cuál es la diferencia entre una imagen y un contenedor en Docker?

  - Imagen: Es un archivo inmutable que contiene el sistema base y las dependencias necesarias para ejecutar una aplicación. Es como una plantilla que permite la creación de múltiples contenedores con la misma configuración.
 
  - Contenedor: Es una instancia en ejecución de una imagen. Puede crearse, iniciarse, detenerse y eliminarse sin afectar la imagen original. Es el entorno donde realmente corre la aplicación.
- ¿Qué sucede con los datos cuando un contenedor se elimina?

     Cuando un contenedor se elimina, todos los datos almacenados dentro del sistema de archivos del contenedor desaparecen. Sin embargo, si los datos se almacenan en:

       - Volúmenes de Docker (docker volume create) → Son persistentes y pueden ser reutilizados por otros contenedores.
       - Montajes de Bind (-v /ruta/local:/ruta/contenedor) → Los datos quedan almacenados en el sistema de archivos del host.
     Si no se usa ninguna de estas opciones, los datos desaparecerán cuando el contenedor sea eliminado.
- ¿Cuáles son las ventajas de utilizar contenedores de docker?

     - Portabilidad: Se pueden ejecutar en cualquier sistema con Docker instalado sin preocuparse por dependencias.
     - Eficiencia: Utilizan menos recursos que las máquinas virtuales porque comparten el kernel del sistema operativo.
     - Escalabilidad: Permiten el despliegue de múltiples instancias fácilmente.
     - Rapidez en despliegues: Facilitan la automatización y configuración rápida en CI/CD.
     - Aislamiento: Cada contenedor tiene su propio entorno sin interferir con otros.
- ¿Qué tipo de aplicaciones y servicios se pueden desplegar con docker?

  Docker se puede usar para desplegar una amplia variedad de aplicaciones, incluyendo:

     - Aplicaciones web (Node.js, PHP, Python, Java, .NET, etc.).
     - Bases de datos (MySQL, PostgreSQL, MongoDB).
     - Microservicios y APIs.
     - Servidores proxy y balanceadores de carga (Nginx, HAProxy).
     - Entornos de desarrollo y testing.
     - Pipelines de CI/CD (Jenkins, GitLab CI/CD).
- ¿Qué otros tipos de contenedores existen además de docker?

    - LXC (Linux Containers): Contenedores de bajo nivel que ofrecen un entorno más similar a una máquina virtual.
    - Podman: Alternativa a Docker sin necesidad de daemon central.
    - Kubernetes: No es un contenedor en sí, pero es una plataforma de orquestación de contenedores.
    - OpenVZ: Tecnología de virtualización a nivel de sistema operativo para Linux.
    - rkt (Rocket): Solución de contenedores más enfocada en seguridad.

</details>



  
## 12.SERVIDOR DE CORREO  (POSTFIX)📬

<details>
  <summary>
   Gestión de Correos✉️
  </summary>

PARTE TEORICA

¿Qué es un servidor de correo?
Un servidor de correo es quien se encarga de gestionar el envío, la recepción y el almacenamiento de correos electrónicos entre los usuarios.
¿Cómo es el funcionamiento del servicio de correos?
Funcionamiento:
Creación del correo 
Envío del correo (SMTP)
Transporte del correo
Recepción del correo (POP3 o IMAP)
Lectura del correo

Explica, en una tabla:
Las características principales de los protocolos SMTP, IMAP, POP3

![image](https://github.com/user-attachments/assets/e9b7a139-24b8-4fc9-9787-5becc707f038)

Los puertos seguros e inseguros

![image](https://github.com/user-attachments/assets/b7972c13-1d49-4b5a-8233-5138e183412c)

¿Qué es SSL / TLS y STARTTLS? Haz una comparativa entre ellos.

![image](https://github.com/user-attachments/assets/7cdf58e3-e155-4638-bb10-ab4a1a3f4aca)

¿Qué es …

Postfix

Postfix es un servidor de correo electrónico de código abierto que se usa para el envío y la recepción de correos electrónicos.
Es una de las opciones para gestionar servidores de correo en entornos de servidores debido a su eficiencia, seguridad y facilidad de configuración.

Instalar Postfix:

![image](https://github.com/user-attachments/assets/5335e5b7-f68d-4b3d-9a3f-73934e824a95)


Dovecot

Dovecot es un servidor de correo electrónico que se usa para la recepción de correos. 

Se encarga de gestionar el acceso a los mensajes almacenados en un servidor de correo y de proporcionar acceso a los correos electrónicos a los usuarios a través de los protocolos:

 IMAP (Internet Message Access Protocol)  
POP3 (Post Office Protocol). 

Instalar dovecot:

![image](https://github.com/user-attachments/assets/c92bef24-049c-470c-b024-b733d329a384)

Mailutils


Mailutils es para gestionar el correo electrónico en sistemas Unix y Linux. 

Permite enviar, recibir, y manipular mensajes de correo electrónico de manera eficiente.
El paquete Mailutils incluye implementaciones de protocolos de correo, como IMAP, POP3, SMTP, y otros, permitiendo interactuar con servidores de correo de diversas maneras.

Instalar mailutils:

![image](https://github.com/user-attachments/assets/fdbb4a89-44a7-4330-9dfd-20780eed21da)

¿Qué es mbox y maildir? 	

mbox y Maildir son utilizados para almacenar los correos electrónicos en los servidores de correo. 
mbox:

Descripción:

mbox es un formato tradicional que almacena todos los correos electrónicos en un solo archivo. En este formato, los mensajes están concatenados uno tras otro en un archivo de texto plano.
Cada mensaje de correo es precedido por un encabezado específico, que marca el comienzo de un nuevo correo.

Características:
Almacenamiento en un solo archivo: Todos los correos electrónicos de una carpeta (como la bandeja de entrada) se guardan juntos en un único archivo.
Formato texto: Los correos se almacenan como texto plano, lo que hace que se puedan leer muchos correos a la vez, ya que todos están en el mismo archivo.


maildir

Descripción
Maildir es un formato más moderno que organiza los correos electrónicos en archivos individuales, en lugar de almacenarlos todos en un único archivo. Cada mensaje se guarda en un archivo separado dentro de un directorio.
Maildir utiliza tres carpetas principales: new (nuevos correos), cur (correos leídos), y tmp (mensajes temporales en proceso de ser entregados).
Características:
Almacenamiento de correos en archivos individuales: Cada correo se guarda en su propio archivo, lo que permite un acceso más rápido y seguro.
Mayor fiabilidad: Debido a la organización de los correos en archivos independientes, si un archivo se corrompe, solo se perderá un correo en lugar de todos los mensajes almacenados en el archivo mbox.
Mejor rendimiento: Al estar los correos almacenados en archivos individuales, las operaciones de lectura y escritura son más rápidas y eficientes, especialmente cuando el número de correos es alto.


Investiga y explica qué es MIME. ¿Cuál es su importancia?


MIME (Multipurpose Internet Mail Extensions) es un estándar que extiende las capacidades del correo electrónico para permitir el envío de contenido más allá del texto simple, como imágenes, videos, audio y archivos adjuntos.

Importancia de MIME:

Permite contenido multimedia → Los correos pueden incluir imágenes, audio, video y archivos de diferentes formatos.
Soporta múltiples tipos de contenido → Un solo correo puede tener texto en distintos formatos 


Qué es Webmail? 

Webmail es un servicio de correo electrónico que permite a los usuarios acceder y gestionar sus cuentas de correo electrónico a través de un navegador web

¿En qué casos se utilizaría? 

Acceso remoto a correo electrónico
Usuarios sin clientes de correo instalados
Sincronización entre dispositivos



¿Qué otros ejemplos de webmail hay?

Gmail (de Google)
Outlook.com (de Microsoft)
Yahoo Mail (de Yahoo)
ProtonMail (enfocado en la privacidad)
Zoho Mail (orientado a negocios)





PARTE PRÁCTICA

Lo primero que hicimos es instalar el Postfix con el comando apt-get install postfix, como podemos observar nos dice que ya está instalado.

![image](https://github.com/user-attachments/assets/74f99917-ed6f-40eb-9edd-77ad6560bb2f)


![image](https://github.com/user-attachments/assets/0627b92a-73a1-4595-a5e1-5700f7a285c3)

Ahora editamos el fichero main.cf agregando al final de todo la línea home_mailbox = Maildir/. Lo que hacemos con esto es cambiar la configuración y usar Maildir, ya que por defecto de Postfix y Mailutils se utiliza el formato Mbox, pero como que ambos soportan  Maildir lo pondremos así.

![image](https://github.com/user-attachments/assets/3ff8ea78-4b48-442f-bd75-d2a2f9aee3ea)

Ahora toca instalar Dovecot, esta vez utilizaremos el comando sudo apt install dovecot-core dovecot-imapd dovecot-pop3d. Como anteriormente lo hemos instalado sin hacer capturas si volvemos a ejecutar el comando podemos ver que ya está instalado.

![image](https://github.com/user-attachments/assets/f8bc62cd-563f-4e12-bf86-1ab43bd34f8e)


![image](https://github.com/user-attachments/assets/013d8397-6917-425e-8459-d2b29c8f8f26)

En este caso editamos el archivo /etc/dovecot/conf.d/10-mail.conf, lo que haremos es descomentar la línea mail_location = maildir:~/Maildir. Como he explicado antes, lo que hacemos con esto es cambiar la configuración y usar Maildir, ya que por defecto de Postfix y Mailutils se utiliza el formato Mbox, pero como que ambos soportan Maildir lo pondremos así.

![image](https://github.com/user-attachments/assets/70dd2405-e67b-401c-bcc5-4107141d7c15)

Ahora toca instalar 	Mailutils, esta vez utilizaremos el comando sudo apt-get install mailutils. Como anteriormente lo hemos instalado sin hacer capturas si volvemos a ejecutar el comando podemos ver que ya está instalado.

![image](https://github.com/user-attachments/assets/a645c374-7873-4d6c-aa28-2e7f25016511)

ACTIVIDAD

Ahora ejecutaremos el echo "Este es el body del email" | mail -s "Este el asunto" pepe@soterasdns. Anteriormente hemos creado el usuario Pepe con sudo adduser pepe, y como podemos observar en el directorio /Maildir podemos encontrar el contenido de echo realizado anteriormente.

El contenido del directorio /Maildir encontramos; /maildir/new/: contiene los correos electrónicos nuevos. También /maildir/cur/:correos que ya han sido leídos. Y /maildir/tmp/: contiene los correos temporales.

![image](https://github.com/user-attachments/assets/d298d171-f295-48b6-a28c-59b6fd25b2c7)

ACTIVIDAD

Utiliza Telnet para testear el servicio, por cada uno de los puertos de comunicación correspondientes a POP3, IMAP, SMTP.

![image](https://github.com/user-attachments/assets/ffcc3e04-b393-4915-bfdf-6080fb950300)


![image](https://github.com/user-attachments/assets/fa161a9e-96af-4a6b-b8d0-49c5700dd352)

Con el comando telnet 192.168.6.100 25, lo que hace el servidor es que responde con un banner de Postfix, indicando que el servicio SMTP está funcionando correctamente.
Ahora con el comando  192.168.6.100 110 , el servidor responde con +OK Dovecot (Ubuntu) ready., lo que indica que el servicio POP3 está funcionando.
Y en la última captura, con el comando 192.168.6.100 143, elservidor responde con un mensaje que muestra que el servicio IMAP está disponible


Aquí ahora usamos Telnet para verificar la conexión con el servicio POP3 en el servidor local a través del puerto 110.
![image](https://github.com/user-attachments/assets/e29bbbd2-f29d-4b5b-893d-d33a6a12660c)

Esto es una conexión a un servidor IMAP en el puerto 143 mediante Telnet, mostrando que el servicio Dovecot está en ejecución.

![image](https://github.com/user-attachments/assets/b464d423-a88c-4bf2-84ee-19ebb7c85f25)

Y aqui mostramos  una conexión a un servidor SMTP en el puerto 25 mediante Telnet, mostrando que el servicio Postfix está en ejecución.

![image](https://github.com/user-attachments/assets/6e3f20d0-af7f-4980-b1f4-69ad9f418c7a)

THUNDERBIRD


Bueno, aqui instalamos y configuramos thunderbird que es un cliente para  gestionar correos electrónicos y es compatible con protocolos como IMAP, POP3 y SMTP

Hemos creado el usuario quim como correo.

![image](https://github.com/user-attachments/assets/560df44c-9345-476d-bc8d-17cf3e32e25b)

Desde el cliente nos hemos conectado al usuario quim , es decir, configuramos nuestro usuario para que podamos empezar a enviar mensajes.

![image](https://github.com/user-attachments/assets/df6410f4-1b60-44da-afb0-40226b5798e2)


Bueno aqui mostramos que nuestra cuenta ha sido creada de forma correcta para que ya nosotros podamos empezar a enviar correos. 

![image](https://github.com/user-attachments/assets/9549fd0a-0ef2-4b7a-927f-ab8c2e62db74)

Enviamos un mensaje, desde dentro de thunderbird, como usuario quim para que el receptor sea pepe.

![image](https://github.com/user-attachments/assets/80f418cc-4140-4947-b629-8f19cee17bbf)

Comprobamos que en el servidor se puede ver el mensaje para verificar que el procedimiento de la instalación y montaje ha funcionado de forma correcta.


![image](https://github.com/user-attachments/assets/1a1eba61-320f-4a34-86f2-d4f410c93da2)

</details>


## 13.FIREWALL🔥 - pfSense
<details>
  <summary>
   Seguridad y Reglas de Red🛡️
  </summary>

### **Teórica**

La primera interfaz se conectará a la WAN (salida hacia Internet), mientras que la segunda se destinará a la LAN (conexión con otras máquinas virtuales del laboratorio):

Adaptador puente para la WAN: Se conecta a la red física del host, permitiendo que pfSense obtenga una dirección IP del router de Internet. Esto es crucial para que pfSense actúe como firewall y router, gestionando el tráfico entre la red interna (LAN) y la externa (Internet).

Red NAT para la LAN: Se utiliza para permitir la conexión entre las máquinas virtuales dentro de la red interna. La tecnología NAT traduce direcciones IP privadas a públicas, lo que es esencial para conservar las direcciones IPv4.

Abajo de esto se vera las capturas de las IPs de las 2 interfaces

**Que es pfSense?**


**pfSense** es un firewall y router basado en FreeBSD, ampliamente utilizado en entornos empresariales y redes domésticas avanzadas. Se destaca por su flexibilidad, seguridad y facilidad de configuración. Algunas de sus principales características incluyen:

Firewall y NAT: Reglas avanzadas de filtrado y traducción de direcciones.
VPN: Soporte para OpenVPN e IPsec, permitiendo conexiones seguras desde el exterior.
QoS y Traffic Shaping: Control del tráfico para priorizar servicios. Soporte que permite establecer límites de ancho de banda por IP o red.
Sistema de detección de intrusos (IDS/IPS) con Snort o Suricata.Integración con Snort o Suricata como sistemas de detección y prevención de intrusiones.
Permitiendo monitorear y bloquear tráfico malicioso en tiempo real
Portal Cautivo: Control de acceso a la red con autenticación.</br></br>


#### **Instalación del Firewall**

Una vez que pfSense esté instalado, se te pedirá que configures las interfaces de red, como WAN y LAN.

- 100.77.20.74 como red WAN, que es la red donde podremos acceder en el navegador
- 192.168.1.2 como red LAN, que es la red interna de la máquina


![image](https://github.com/user-attachments/assets/ae8774f5-dc22-45b1-8e69-39255aa3630e)

Para acceder a la interfaz web de administración de pfSense desde cualquier navegador, primero debemos deshabilitar temporalmente el firewall. Para ello, dentro de pfSense, seleccionamos la opción 8 (Shell) y ejecutamos el siguiente comando:

pfctl -d: Este comando desactiva el firewall de pfSense de forma temporal, permitiendo el acceso a la GUI sin restricciones.

![image](https://github.com/user-attachments/assets/775212c2-cbd8-4107-a3c8-86cb75470a8a)

Ahora podemos acceder a la interfaz web de pfSense aunque el navegador pueda mostrar una advertencia 

![image](https://github.com/user-attachments/assets/1b827a79-12af-4d7d-b7da-7117464aee55)


Una vez ya hemos configurado todo, si vamos al navegador y ponemos la IP que he dicho antes, osea la 100.77.20.74 ya podremos ver la página de pfsense para asi nosotros poder acceder

![image](https://github.com/user-attachments/assets/94e0f486-0f0b-4ed3-be72-698a9bd73715)

Ahora podemos iniciar sesión en la interfaz web de pfSense utilizando las credenciales predeterminadas:

Usuario: admin
Contraseña: pol

Accederemos a la interfaz web introduciendo https://http://100.77.20.74/ en el navegador, usando "admin" como usuario y "pol"

Esta es la página principal de pfsense como se ve osea la pagina de bienvenida

![image](https://github.com/user-attachments/assets/3b5407a1-0afa-4ae9-9216-9b3b691f3bd4)

Aquí configuramos el hostname (nombre del equipo), el dominio y los servidores DNS.

Hostname: Nombre que identificará a pfSense en la red. Debe comenzar con una letra y solo puede contener letras, números o guiones

Domain: Dominio al que pertenece el firewall (opcional, útil en redes empresariales).

Servidores DNS: Direcciones de los servidores DNS que pfSense utilizará para resolver nombres de dominio. 



![image](https://github.com/user-attachments/assets/7b18463d-0466-4a46-bb6c-40434ea937b5)

En esta sección, se configuran el Time Server Hostname y la Zona Horaria (Time Zone).
Por defecto, pfSense selecciona un servidor de tiempo adecuado y la zona horaria predeterminada.

![image](https://github.com/user-attachments/assets/4b05de62-059a-414c-93e1-40338e089e53)

hacemos clic en "Next" para continuar con la configuración.
Si no es necesario realizar ajustes en la configuración puedes simplemente avanzar al siguiente paso sin hacer cambios

![image](https://github.com/user-attachments/assets/30dccf02-3241-4982-8c6d-03d8e1948f79)

Ahora configuramos la interfaz LAN, donde definimos la dirección IP que tendrá pfSense dentro de la red interna.

Aquí podemos establecer una IP estática para el firewall, que servirá como puerta de enlace para los dispositivos de la red local.

![image](https://github.com/user-attachments/assets/cb4ce82e-d3a1-4836-8c8c-a29a49b9c8f4)

En este paso, podemos cambiar la contraseña de acceso a la interfaz web de pfSense.

Una vez realizados los cambios, avanzamos para completar la configuración.

-pol
-pol

![image](https://github.com/user-attachments/assets/eade089a-c756-44f8-8abd-92e05612c9f7)

Hacemos clic en "Reload" para que pfSense reinicie con la nueva configuración. Después de este paso, ya estaremos listos para acceder a la interfaz web y seguir con la configuración avanzada.

![image](https://github.com/user-attachments/assets/98e24467-d93b-433c-a19e-cc16dfda5a06)

Ya tenemos pfense configurado

![image](https://github.com/user-attachments/assets/9530651c-8a38-4515-bfc1-05d9a226525a)

La pantalla principal o dashboard de pfSense muestra un resumen general del estado del sistema y proporciona acceso rápido a las configuraciones más importantes.

1. Barra de Navegación Superior
En la parte superior de la página, encontrarás una barra de navegación con las opciones principales:

System: Configuración del sistema, incluyendo reinicios y actualizaciones.
Interfaces: Configuración de las interfaces de red, como WAN y LAN.
Firewall: Reglas de firewall, NAT y configuraciones relacionadas.
Services: Servicios adicionales como VPN, DHCP, DNS, etc.
Diagnostics: Herramientas de diagnóstico y logs.

2. Resumen del Estado del Sistema
Debajo de la barra de navegación, se muestra una vista general del estado del sistema:

Estado de las interfaces: Información sobre las interfaces WAN y LAN, incluyendo si están activas y su dirección IP asignada.
Uso de CPU y memoria: Un gráfico que muestra el uso actual de CPU y memoria del sistema.
Estado del Firewall: Si el firewall está activo o si hay alguna alerta relevante.

3. Notificaciones y Alertas
En la parte superior o inferior de la página, puede haber un área para notificaciones y alertas. Aquí se muestran advertencias de seguridad, actualizaciones disponibles, o problemas de configuración.

4. Accesos Rápidos a Funciones Comunes
En el centro o en el lateral, encontrarás accesos rápidos a tareas comunes, como:

Reiniciar el sistema.
Ver los logs del sistema.
Ver las conexiones activas o estadísticas de tráfico.

5. Estadísticas de Tráfico y Conexiones
También suele haber un área con gráficos o tablas que muestran el tráfico de la red, las conexiones activas, la velocidad de descarga y carga, etc.


![image](https://github.com/user-attachments/assets/2a01815e-a5a3-4502-bbd8-e86d30d97846)







Instalar el plugin OpenVPN client

Hemos empezando descargando el paquete que se llama openvpn-client-export que se encuentra en System-Package

![image](https://github.com/user-attachments/assets/f7a2dd07-ce0b-4dc5-93b7-a1fc5a9a004f)

![image](https://github.com/user-attachments/assets/8f5073bd-8a82-4d82-97ab-f38bcef14d7b)

Crear la CA (Autoridad de Certificación) 

Ahora creamos la CA, que es una entidad confiable responsable de emitir y revocar certificados digitales utilizados para transacciones y firmas electrónicas, entonces vamos a System - Certificate Manager y le damos a agregar


![image](https://github.com/user-attachments/assets/40590d84-a8ae-4bd4-a9fc-947e5621aa7b)

![image](https://github.com/user-attachments/assets/10abd077-9dc7-42db-97f7-3e3212b1172a)

Luego iriamos a crear el certificado del servidor OpenVPN, que eso se encuentra en System - Certificates y lo que haremos serà agregar un certificado
Y luego lo que haremos será configurar el servidor de OpenVPN, que se encuentra en Servers, y hacemos la misma configuración que nos comento Alina en el punkymo para poder hacerlo de la forma correcta</br></br>

### PARTE PRÁCTICA

#### 1. Las dos VM se conectan a la DMZ y comprueba que el firewall está brindando servicio de DHCP a los equipos.

Hemos creado las dos VM que en nuestro caso son Ubuntu Cliente, ambas con adaptador de red Solo Anfitrión (DMZ).

![image](https://github.com/user-attachments/assets/bedd76f6-30ad-4bea-b5dd-f6d9ed723854)

Aquí podemos ver como ambas Ubuntu Cliente conectan perfectamente con la máquina PfSense, es mas tienen la IP 192.168.10.100 y 101 del rango que le hemos configurado a PfSense, y nos deja entrar en Admin poniendo la IP 192.168.1.186 que es la IP WAN de la VM PfSense. 

![image](https://github.com/user-attachments/assets/a3418d96-da53-435c-9711-d0dc70ce992b)


![image](https://github.com/user-attachments/assets/8a02b50d-998b-492b-bab8-052448f5ed50)

   
#### 2. El equipo anfitrión se conecta a la LAN
   
#### 3. Configura el port forward para acceder por SSH a la VM de la DMZ

![image](https://github.com/user-attachments/assets/1bca5198-38e9-4c0a-a491-e74fcd14dabb)

![image](https://github.com/user-attachments/assets/83d2df3e-3321-4f23-80f5-5ff3aa0cef86)
   
#### 4. Configura el port forward para visualizar la página web de la VM de la DMZ

![image](https://github.com/user-attachments/assets/e3b34164-a974-47b8-b73b-75376963e499)

 
#### 5. Realiza pruebas de conexión entre los dispositivos.
 
#### 6. Configuración de un servidor FTP en la VM de la DMZ

![image](https://github.com/user-attachments/assets/3daf55f4-c710-4566-8160-f43b69953a22)

![image](https://github.com/user-attachments/assets/a96f76b3-72bf-44d0-a389-14b408da8b65)

![image](https://github.com/user-attachments/assets/970f7086-826c-4092-9b49-ec8c508a2a12)



</details>

## 14.BACKUP🏦
<details>
  <summary>
   Copias de Seguridad🛡️
  </summary>

  #### Introducción
  
  Las copias de seguridad (backups) son esenciales para garantizar la continuidad del negocio, la integridad de los datos y el cumplimiento normativo, asegurando la disponibilidad de los datos incluso en situaciones de fallos técnicos o incidentes como ransomware.
  Este script de backup se encarga de realizar copias de seguridad completas (full) o incrementales de los sistemas de información, garantizando la recuperación de los datos.
  Hemos intentado hacer lo del correo pero no nos ha salido, esperamos que dentro de poco lo tengamos para que también lo podamos tener implementado.

  ####  Objetivos
  
  Garantizar la disponibilidad y recuperabilidad de los datos críticos.
  Minimizar el impacto de incidentes como ransomware o fallos técnicos.
  Cumplir con los requisitos legales y regulatorios en materia de protección de datos y resiliencia operativa.
  
  #### Alcance
  
  Aplica a todos los sistemas de información que gestionen:
  Registros internos: Logs de actividad, configuración de sistemas, etc.
  Archivos de usuarios: Documentos, imágenes o bases de datos alojadas en los servidores.

  <details>
    <summary>
      
  ### Script de Backup
  </summary>
  
          #!/bin/bash
          
          # Configuración principal
          BACKUP_DIR="/var/backups"
          PARTICION_DIR="/mnt/backup_particion"
          LOG_FILE="/var/log/backup.log"
          ARCHIVO_HASH="/var/backups/backup.hash"
          REMOTE_SERVER="quim@192.168.1.195" # Dirección del servidor remoto de mi casa
          REMOTE_PATH="/home/quim" # Ruta de destino en el servidor remoto
          
          # Esto lo que hace es crear los directorios si no existen
          mkdir -p "$BACKUP_DIR" "$PARTICION_DIR"
          
          # Verificamos si el tipo de backup que queremos hacer es full o incremental
          if [ "$1" == "full" ]; then
              TAR_FILE="$BACKUP_DIR/full_$(date +%F).tar.gz"
              tar -czf "$TAR_FILE" /home /etc /var
          elif [ "$1" == "incremental" ]; then
              TAR_FILE="$BACKUP_DIR/incremental_$(date +%F).tar.gz"
              tar -czf "$TAR_FILE" --newer-mtime="$(date -d 'yesterday' +%F)" /home /etc /var
          else
              echo "Uso: $0 [full|incremental]"
              exit 1
          fi
          
          # Esto copia el backup a la partición local
          cp "$TAR_FILE" "$PARTICION_DIR/"
          
          # Generar hash
          sha256sum "$TAR_FILE" > "$ARCHIVO_HASH"
          
          # Registrar en log
          echo "[$(date)] Backup $1 realizado: $TAR_FILE" >> "$LOG_FILE"
          
          # Esto sirve para copiar el archivo al servidor remoto usando rsync
          rsync -avz "$TAR_FILE" "$REMOTE_SERVER:$REMOTE_PATH"
          
          # Esto registra en log que se copió al servidor remoto
          echo "[$(date)] Backup copiado al servidor remoto: $TAR_FILE" >> "$LOG_FILE"
          
          echo "Backup completado y copiado al servidor remoto."
          
          # Envía un correo de reporte (no nos funcionó al final)
          cat "$LOG_FILE" | mail -s "Reporte de Backup" qfernandez2004@gmail.com
  </details>
          
 <details>
    <summary>
      
  ### Script de Restauración
  </summary>
  
          #!/bin/bash
          
          # Restauración del backup
          BACKUP_DIR="/var/backups"
          PARTICION_DIR="/mnt/backup_particion"
          LOG_FILE="/var/log/restore.log"
          
          # Verificar si existe el archivo
          if [ -z "$1" ]; then
          echo "Uso: $0 <archivo_backup>"
          exit 1
          fi
          BACKUP_FILE="$BACKUP_DIR/$1"
          if [ ! -f "$BACKUP_FILE" ]; then
          echo "Error: Archivo de backup no encontrado: $BACKUP_FILE"
          exit 1
          fi
          
          # Restaurar el archivo
          tar -xzf "$BACKUP_FILE" -C /
          
          # Registrarlo en log
          echo "[$(date)] Restauración realizada: $BACKUP_FILE" >> "$LOG_FILE"
          echo "Restauración completada."
  </details>



#### Preparación de la máquina

Para comprobar que los scripts funcionan correctamente lo que haremos es preparar la máquina Ubuntu Desktop para así poder hacer uso de los scripts. (Estamos en CMD conectados por SSH a la máquina para comodidad mía).

Creamos dos ubicaciones para almacenar los backups: un directorio local (/var/backups)
y una partición montada (/mnt/backup_particion)

sudo mkdir -p /var/backups
sudo mkdir -p /mnt/backup_particion

En  /home/quim creamos los dos scripts.

nano backup.sh
nano restore.sh

Y les damos permisos.

chmod +x backup.sh restore.sh


Prueba de Backup

Ejecutamos el backup de forma full y incremental, y si nos vamos a /var/backups podemos observar que se han realizado correctamente.

![image](https://github.com/user-attachments/assets/f7ab86fc-3f88-4447-8cb7-f494d5f3b692)

![image](https://github.com/user-attachments/assets/5a61aab2-552d-4121-a022-64f85eb25193)

![image](https://github.com/user-attachments/assets/ed352017-9475-4a3e-afcf-30fe3538222f)

También revisamos el log.

![image](https://github.com/user-attachments/assets/2b6e0869-6ad2-4314-a7ef-5287ae27f5c1)


Restaurar el Backup

Usamos ./restore.sh full_2025-02-24.tar.gz para restaurar el backup que hemos hecho.

![image](https://github.com/user-attachments/assets/271a19fd-490b-4d4f-aa9b-5008ce5ba837)


Y también revisamos el log.

![image](https://github.com/user-attachments/assets/523132ae-0669-4ad3-9970-62b0ecb0176f)


Automatización del Proceso de Backup

Ahora con el crontab, lo que haremos será ajustar  a nuestro gusto la automatización del backup, agregando esta línea generamos un backup diario a las 2 AM y otro incremental a las 3 AM. 
Sabemos que no es la mejor distribución de días para hacer backups pero hemos puesto este como ejemplo rápido para no darle muchas vueltas.

0 2 * * * /usr/bin/rsync -avz /datos/ /backup/completo/
0 3 * * * /usr/bin/rsync -avz --ignore-existing /datos/ /backup/incremental/

![image](https://github.com/user-attachments/assets/edc8cdf3-81a8-46c0-85a7-72a05c5b0291)


Copia al Servidor Remoto

Este es nuestro Ubuntu Server Servidor Externo que usaremos para enviar el backup.

![image](https://github.com/user-attachments/assets/21debb94-912f-4b01-bfec-5d45a4563750)

A través de rsync podemos crear esa copia manualmente ahora a través de este comando, pero hemos añadido en el script el código para que pueda hacerlo automáticamente cada vez que se ejecute grácias al Crontab.

![image](https://github.com/user-attachments/assets/d79739eb-b594-4df0-b26f-95665b929dbd)

Ya tenemos el backup en el Servidor de Ubuntu

![image](https://github.com/user-attachments/assets/d64f7071-fb2b-441f-bef3-310321932746)










</details>

## 15.Ejabberd🐍
<details>

  ### Ejabberd📘

Ejabberd es una plataforma en tiempo real de código abierto, robusta, escalable y extensible creada con Erlang/OTP, que incluye un servidor XMPP, un agente MQTT y un servicio SIP.

 ### ¿Qué es el protocolo xmpp?

El XMPP (Extensible Messaging and Presence Protocol) es un protocolo de comunicación utilizado principalmente para la mensajería instantánea, también permite que las personas se envíen mensajes en tiempo real y compartan su estado de disponibilidad, como "en línea" o "ocupado". 
xmpp és abierto y flexible, lo que significa que se puede adaptar y utilizar en diferentes aplicaciones de mensajería.

### Pidgin 

Pidgin es un programa de mensajería instantánea que permite chatear con amigos a través de diferentes servicios y soporta múltiples redes al mismo tiempo.

### Alternativas mensajería instantánea


### Uso de los puertos:  5222, 5223, 5280, 5443, 5269

  -5222:  Usado para la comunicación de cliente a servidor en XMPP. Es el puerto estándar para que los clientes XMPP

  -5223:  Usado para comunicación de cliente a servidor en XMPP, pero con conexiones cifradas mediante SSL

  -5280:  Este puerto es usado para conexiones HTTP a través de la interfaz de administración del servidor XMPP, o en algunos casos, para servicios de mensajería web 

  -5443:  Usado para la comunicación de clientes con servidores XMPP mediante conexiones seguras a través de WebSockets. 

  -5269:  Usado para la comunicación entre servidores XMPP y es el puerto es estándar para la conexión de servidores XMPP que se utilizan para intercambiar información y mensajes entre diferentes servidores

### INSTALACIÓN

Primero de todo instalamos el ejabber con:

sudo apt install ejabberd -y

Ahora vamos a entrar a : sudo nano /etc/ejabberd/ejabberd.yml
Y añadimos el dominio del servidor al host, que el nuestro es soterasdns.soterasdns.local
El dominio es este, ya que gerard nos presto su maquina de DNS

 ![image](https://github.com/user-attachments/assets/6836f18a-a386-4490-9b71-489f69b8840c)

Y ahora  vamos a dar permisos de administrador al usuario admin, que es el nombre de nuestro administrador

 ![image](https://github.com/user-attachments/assets/ed9b6cf5-f704-40a4-aaba-3d585419d222)

Ahora creamos un usuario administrador del sistema: con el nombre admind, luego el dominio, que es soterasdns.soterasdns.local y la contraseña que es admin

![image](https://github.com/user-attachments/assets/8bcace50-e54e-454e-893f-919596100afa)

Y aqui vemos todos los nuestros usuarios a parte del admin , que son Quim y Pol

![image](https://github.com/user-attachments/assets/2807c1ec-ca2a-4ba3-a5cd-55589d9fb88b)

Ahora dentro de las ubuntus hemos de instalar pidgin 
Ponemos: sudo apt install pidgin

![image](https://github.com/user-attachments/assets/bd54147e-c61d-43d3-9ae8-fd2adf88f15f)

Y accedemos dentro de las 2 ubuntus a /etc/hosts.
Y ponemos la IP de la MV DNS y el dominio de antes, que es el soterasdns.soterasdns.local

![image](https://github.com/user-attachments/assets/db92587c-71c9-4260-bb35-2a082ad40755)

Ahor despues de esto si ponemos si ponemos la IP la 192.168.6.100 y vamos al navegador ya podremos acceder a ejabberd

![image](https://github.com/user-attachments/assets/a4addc0f-7fe9-404c-b301-6ca9a1469a35)

Entonces si vamos a Virtual Hosts y vamos Users, se veran los usuarios que hemos creado antes y que se puede ver en la captura de antes

Que son:
-admin: Como administrador
-users:  Quim y Pol

![image](https://github.com/user-attachments/assets/b73c32db-d965-466a-9f1b-111ee448baa0)

![image](https://github.com/user-attachments/assets/07d4cc1c-5bce-4e1f-82f6-889a0be785f3)

Ahora accedemos a pidgin en las 2 Ubuntus y primero de todo vamos añadir las cuentas para poder enviar mensajes entre quim y pol, entonces una vez hecho esto y poner el dominio , le damos añadir.

![image](https://github.com/user-attachments/assets/6d8bea69-a946-4312-ab08-993a00b7b0c2)

Ahora una vez hecho todo, aqui mostramos una captura de en las 2 ubuntus que los 2 usuarios se pueden enviar mensajes y comunicar de forma correcta, como se puede ver en la captura de abajo

![image](https://github.com/user-attachments/assets/6d337f5f-480c-4828-9a42-ae86ae176982)




![image](https://github.com/user-attachments/assets/4f1d87d9-525f-4560-a0b8-75b7138a4ebe)


</details> 

## 16.FFMPEG 📹

<details>
  <summary>
   Teoria y Instalación🎆 
  </summary>

### TEORIA 

Busca información acerca de los siguientes protocolos en cuanto a: funcionalidades principales, latencia, red, seguridad y compatibilidad?

RTMP 

El Protocolo de Mensajería en Tiempo Real (RTMP) es un estándar desarrollado por Adobe para la transmisión en vivo de audio, video y datos a través de Internet. A continuación, se analizan sus características clave en términos de funcionalidades principales, latencia, red, seguridad y compatibilidad:
1. Funcionalidades principales:
Transmisión en vivo: RTMP permite la entrega en tiempo real de contenido multimedia desde el emisor hasta el receptor, facilitando interacciones en directo.


Control de flujo: Ofrece comandos como play, pause y seek, brindando un control detallado sobre la reproducción del contenido.


Soporte para códecs: Es compatible con códecs de video como H.264 y de audio como AAC, garantizando una calidad adecuada en las transmisiones.


2. Latencia:
   
RTMP proporciona una latencia baja, generalmente entre 3 y 5 segundos, lo que lo hace adecuado para aplicaciones que requieren interactividad en tiempo real

4. Red:
   
Protocolo de transporte: Funciona sobre TCP (Protocolo de Control de Transmisión), asegurando la entrega confiable de los datos.


Ancho de banda: Aunque eficiente, el uso de RTMP puede ser intensivo en ancho de banda, especialmente al transmitir contenido en alta definición.


4. Seguridad:
   
Cifrado: RTMP en su forma básica no incorpora cifrado, lo que puede exponer el contenido a interceptaciones. Sin embargo, variantes como RTMPS implementan cifrado SSL/TLS para proteger las transmisiones.


Autenticación: Ofrece mecanismos básicos de autenticación, pero no cuenta con características avanzadas de seguridad integradas.


5. Compatibilidad:
   
Plataformas y dispositivos: Aunque ampliamente soportado en plataformas y software de streaming, la compatibilidad con dispositivos modernos ha disminuido debido al desuso del reproductor Flash, originalmente asociado con RTMP.


Software y hardware: Muchos servidores y aplicaciones de streaming aún admiten RTMP, pero su uso ha disminuido en favor de protocolos más recientes y adaptativos.

2. HLS (HTTP Live Streaming)

   
Funcionalidades principales:

Transmisión adaptativa: HLS es un protocolo de transmisión de video basado en HTTP desarrollado por Apple. Utiliza segmentación en pequeños archivos de video (por lo general, en segmentos de 10 segundos) y un archivo de lista de reproducción (M3U8) para gestionar las solicitudes de video.


Adaptación de calidad: Permite la transmisión de video con diferentes calidades, adaptándose a la capacidad de ancho de banda disponible del usuario.


Latencia:

Alta latencia: La latencia en HLS es generalmente más alta debido a la segmentación de video y el buffering en el cliente. Puede estar entre 10 a 30 segundos o más, dependiendo de los segmentos y la red.


Red:

Basado en HTTP: HLS se adapta bien a redes basadas en HTTP/HTTPS, lo que lo hace compatible con las infraestructuras web comunes y redes de entrega de contenido (CDNs).


Escalabilidad: 

Funciona bien con redes de distribución de contenido (CDNs), lo que facilita la escalabilidad global.


Seguridad:

Cifrado: HLS puede ser protegido mediante cifrado AES para asegurar la transmisión de video. Además, puede integrar autenticación y control de acceso, como el uso de tokens para restringir el acceso.


Compatibilidad:

Compatibilidad amplia: Es compatible con una gran cantidad de dispositivos y plataformas, como iOS, Android, navegadores web, Smart TVs, etc.


Limitaciones: La latencia más alta es una de sus principales limitaciones, lo que no lo hace ideal para transmisiones en vivo que requieren interacción en tiempo real.


3. RTSP (Real-Time Streaming Protocol)
   
Funcionalidades principales:

Control de transmisión en tiempo real: RTSP es un protocolo de control que permite la transmisión de medios en tiempo real, como video y audio. Utiliza comandos como PLAY, PAUSE, STOP, SEEK, etc., para controlar la reproducción de medios.


Orientado a transmisión en vivo: Aunque no es un protocolo de transporte en sí mismo, suele emplearse en combinación con otros protocolos como RTP para la transmisión de contenido en tiempo real.


Latencia:

Baja latencia: RTSP tiene menor latencia en comparación con HLS. Dependiendo de la red y la configuración, la latencia puede ser de solo unos pocos segundos (1-3 segundos), lo que lo hace adecuado para transmisiones en vivo interactivas.


Red:

Redes TCP/UDP: RTSP puede funcionar tanto sobre TCP como sobre UDP. Cuando se utiliza sobre UDP (a través de RTP), la latencia es más baja, pero puede haber problemas de calidad de transmisión en redes inestables.


No tan escalable: Aunque RTSP funciona bien para transmisiones en tiempo real, no es tan fácil de escalar en comparación con HLS, especialmente para una gran cantidad de usuarios simultáneos.


Seguridad:

Limitada seguridad: RTSP en su versión básica no tiene características de seguridad integradas como el cifrado. Sin embargo, puede usarse sobre protocolos seguros como HTTPS o utilizar transporte mediante TLS/SSL para proteger la transmisión.


Compatibilidad:

Compatibilidad moderada: Si bien RTSP es soportado por muchas cámaras IP y dispositivos de videovigilancia, su compatibilidad en dispositivos móviles y navegadores web es limitada.


Requiere software especial: Para reproducir flujos RTSP en navegadores, generalmente se necesita un complemento o reproductor especial, como VLC o un cliente RTSP específico.



4. SRT (Secure Reliable Transport)
   
Funcionalidades principales:

Transporte confiable y seguro: SRT es un protocolo de transmisión de video en tiempo real que ofrece una capa de transporte segura y confiable, incluso en redes no confiables como internet público. Utiliza corrección de errores y reintentos para garantizar la entrega de paquetes.


Optimización de la red: Se adapta a condiciones de red cambiantes, como la latencia y el jitter, lo que lo hace ideal para situaciones de transmisión en vivo en condiciones de red inestables.


Latencia:

Baja latencia: SRT está diseñado para ofrecer latencia baja, comparable a la de RTSP, pero con la ventaja de ser más robusto en condiciones de red inestables. La latencia puede ser de 1-2 segundos, aunque varía dependiendo de la red.


Red:

Optimización en redes inestables: SRT es especialmente útil en redes con alta latencia, pérdidas de paquetes o conexiones inestables, ya que incluye mecanismos de corrección de errores y ajuste dinámico de la tasa de transmisión.


Mayor resistencia: En comparación con HLS y RTSP, SRT es más resistente a la fluctuación de la red y la pérdida de paquetes.


Seguridad:

Cifrado y autenticación: SRT incluye cifrado AES de 128 bits para asegurar las transmisiones y mecanismos de autenticación para verificar las conexiones, lo que lo hace más seguro que RTSP y HLS por defecto.


Compatibilidad:

Compatibilidad creciente: SRT está ganando soporte en una variedad de plataformas y dispositivos de transmisión en vivo. Muchos servicios de CDN y plataformas de transmisión (como Wowza, Haivision, etc.) lo soportan, pero su adopción no es tan universal como HLS.


Nuevas soluciones: Aunque SRT está creciendo rápidamente, todavía no es tan compatible con dispositivos y plataformas de consumo como HLS.




¿Qué es ffmpeg? 


FFmpeg es una herramienta de software de código abierto que se utiliza para procesar archivos multimedia, como video y audio. Es muy popular debido a su capacidad para convertir, grabar, editar y transmitir archivos en casi cualquier formato.
Algunas de las funciones más comunes de FFmpeg incluyen:
Conversión de formatos: Puedes cambiar un archivo de video o audio de un formato a otro (por ejemplo, de .mp4 a .avi, o de .mp3 a .ogg).


Extracción de audio: Extraer el audio de un archivo de video.


Edición de video: Realizar tareas como recortar videos, cambiar su resolución, añadir filtros, y más.
Transmisión en vivo: FFmpeg puede ser utilizado para hacer streaming en tiempo real de video y audio.


Grabación de pantalla: Permite grabar el contenido de tu pantalla y guardarlo en diferentes formatos.

¿Cuál es su página oficial? 

https://ffmpeg.org/


¿Cuáles son sus características fundamentales? 

FFmpeg es una herramienta de código abierto y línea de comandos utilizada para procesar archivos multimedia (video y audio). Sus características fundamentales incluyen:
Conversión de formatos: Cambia entre diferentes formatos de audio y video (por ejemplo, de MP4 a AVI o MP3).


Codificación y decodificación: Soporta una amplia gama de códecs de audio y video.


Streaming en vivo: Permite la transmisión en tiempo real a través de diversos protocolos.


Edición de medios: Recorta, une y aplica efectos a archivos de video y audio.


Grabación de pantalla: Graba la pantalla o dispositivos de captura como cámaras.


Multiplexación y demultiplexación: Combina o separa pistas de audio, video y subtítulos.


Rendimiento eficiente: Optimizado para realizar conversiones rápidas y con soporte para aceleración de hardware.


Multiplataforma: Funciona en Windows, Linux y macOS.


Código abierto: Licenciado bajo GPL, permitiendo modificaciones y redistribución.


API: Puede ser integrado en aplicaciones para automatizar procesos de medios.

¿Es posible cambiar de contenedor sin tocar el contenido del vídeo. Por ejemplo, pasar de mp4 a mkv? Explica
Es posible cambiar el contenedor de un archivo sin modificar su contenido mediante "remuxing" o "multiplexado". Esto implica colocar el video y audio (sin recodificarlos) en un nuevo contenedor, como pasar de MP4 a MKV.
Cómo hacerlo con FFmpeg:
Usa este comando:
bash
Copiar
ffmpeg -i archivo.mp4 -c copy archivo.mkv

-i archivo.mp4: Especifica el archivo de entrada (MP4).


-c copy: Copia los flujos de video y audio sin recodificarlos.


archivo.mkv: Especifica el archivo de salida (MKV).


Ventajas:

Sin pérdida de calidad: No se recodifica, por lo que no hay cambios en el contenido ni pérdida de calidad.


Rápido: El proceso es mucho más rápido que la conversión tradicional.


Limitación:
Compatibilidad: No todos los dispositivos o reproductores soportan MKV tan ampliamente como MP4.



¿Qué características tienen los MP4 y los MKV?

MP4 (MPEG-4 Part 14)
Compatibilidad:


Muy compatible con una amplia gama de dispositivos y plataformas (reproductores de medios, teléfonos, consolas, etc.).


Ampliamente utilizado en servicios de streaming (YouTube, Netflix, etc.).


Códecs soportados:


Video: H.264, H.265 (HEVC), y otros.


Audio: AAC, MP3, y otros.


Características:


Formato más comprimido: Generalmente, los archivos MP4 tienen un buen equilibrio entre calidad y tamaño, lo que lo hace ideal para almacenamiento y transmisión.


Metadatos: Admite metadatos como títulos, subtítulos, portadas y capítulos.


Limitado en flexibilidad: Aunque puede manejar video, audio, subtítulos y algunos otros datos, tiene menos flexibilidad que MKV en términos de características adicionales.


Uso común:


Ideal para reproducción en dispositivos portátiles, servicios de streaming y para compartir en línea.


Es el formato de contenedor más utilizado para contenido comprimido.


MKV (Matroska Video)


Códecs soportados:


Video: H.264, H.265 (HEVC), VP8, VP9, AV1, etc.


Audio: AAC, MP3, FLAC, DTS, y más.


Subtítulos: Soporta varios tipos de subtítulos (como SRT, VobSub) y múltiples pistas de subtítulos.


Características:


Extremadamente flexible: Puede contener múltiples pistas de video, audio, subtítulos y otros datos como capítulos, menús y metadatos avanzados.


No tan comprimido como MP4: Los archivos MKV tienden a ser más grandes debido a la flexibilidad y las características adicionales.


Soporta más tipos de contenido: A diferencia de MP4, MKV puede manejar muchos tipos de contenido, como múltiples audios y subtítulos en un solo archivo, lo que lo hace perfecto para videos con múltiples idiomas o versiones.


Uso común:


Ideal para archivos de video de alta calidad, almacenamiento de películas y producción de videos donde la flexibilidad es clave.


Usado frecuentemente para archivos de cine en alta definición.

### PRACTICA 

sudo apt update && sudo apt upgrade
sudo apt-get install ffmpeg

![image](https://github.com/user-attachments/assets/98e01353-1607-45e2-bcb0-a84a720162d8)

![image](https://github.com/user-attachments/assets/1de6f560-430c-4c8f-8436-ff46ac124421)


YT-DLP es un fork de youtube-dl, que permite la descarga de contenido multimedia desde diversas fuentes en línea de un modo sencillo y eficiente.

Descargamos la aplicación desde github y lo ubicará en  /usr/local/bin/ haciéndolo accesible desde  cualquier directorio del sistema.

sudo wget https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -O /usr/local/bin/yt-dlp

![image](https://github.com/user-attachments/assets/e4668eee-87ae-4df0-89b5-3e7fbf40825f)

Para hacer que yt-dlp sea ejecutable, tenemos que darle permisos de ejecución:

sudo chmod a+rx /usr/local/bin/yt-dlp

![image](https://github.com/user-attachments/assets/6627e515-6f62-46a8-ad71-fe9dd7c53d15)

Descarga de videos 

Si queremos ver los formatos disponibles para el vídeo podemos usar la opción «-F»

sudo yt-dlp -F https://www.youtube.com/watch?v=zrnCBt2q-dY 

![image](https://github.com/user-attachments/assets/b4ab7e04-1dbe-4efd-a4b0-eef09c364f0b)

Para descargar uno de los formatos posibles:

sudo yt-dlp -f ID https://www.youtube.com/watch?v=zrnCBt2q-dY 

![image](https://github.com/user-attachments/assets/48d88215-d27c-4c2f-85cd-ff5922038461)

Si quieres descargar el video con la mejor resolución:

yt-dlp -f bv*+ba  https://www.youtube.com/watch?v=bH3NFlkui4Y 

![image](https://github.com/user-attachments/assets/0f384836-57fb-459d-9d6e-5812038dea8a)

![image](https://github.com/user-attachments/assets/b92d8a40-a357-4972-ac0d-06b248fc7af6)

Convierte el video .mp4 en .mkv pero con las opciones siguentes:

ffmpeg -i video_original.mp4 -vcodec libx264 video_264.mkv

![image](https://github.com/user-attachments/assets/7667888b-80f8-491b-ad33-488936263664)

![image](https://github.com/user-attachments/assets/c9cd149c-0ead-41e7-a962-910d1f7a5a99)

ffmpeg -i video_original.mp4 -vcodec libx265 video_265.mkv

![image](https://github.com/user-attachments/assets/c921ee62-badb-42f4-9d10-1644bca7b8d7)

![image](https://github.com/user-attachments/assets/e2bc6a7a-e98e-4cf0-b9bc-588684070297)

¿Qué diferencias hay?

h264 - codec de video que usa la librería libx264

h265 - codec de video que usa la librería libx265

H.264 (libx264) es ideal para la compatibilidad general y la calidad estable, especialmente en resoluciones 1080p o inferiores.

H.265 (libx265) es mejor para la compresión y la calidad en resoluciones más altas (como 4K) y en situaciones donde el ahorro de espacio es crucial sin perder demasiada calidad.


</details> 


## 17.RTMP🛢️

<details>
  <summary>
   RTMP🎙️
  </summary>

### TEORIA

¿Cuáles son las ventajas y desventajas del uso del protocolo RTMP?

Ventajas:

Baja latencia en la transmisión.


Soporte para transmisión en vivo y VOD (Video On Demand).


Compatible con plataformas como YouTube, Facebook y Twitch.


Permite la transmisión de video de alta calidad con compresión eficiente.

Desventajas:

Requiere un servidor compatible con RTMP.


No es compatible directamente con navegadores modernos sin un intermediario (como HLS o WebRTC).


Puede tener problemas con firewalls y restricciones de red.


¿Cómo funciona RTMP?
RTMP (Real-Time Messaging Protocol) es un protocolo de transmisión de datos en tiempo real que divide el contenido en "chunks" y los envía a un servidor de streaming. Luego, el servidor reenvía esos datos a los espectadores en un formato adecuado.
¿Qué son los "chunks"?
Son pequeños fragmentos de datos en los que RTMP divide la transmisión para optimizar la velocidad y reducir el buffering. Permiten un flujo más eficiente de audio y video.
¿Qué tipo de formato es AAC y H.264?
AAC (Advanced Audio Codec): Códec de compresión de audio que ofrece alta calidad con baja tasa de bits.


H.264: Códec de video eficiente que comprime el video sin perder demasiada calidad, utilizado en streaming, grabación y transmisión en vivo.

¿Qué tendríamos que hacer para que fuera multistreaming?

RTMP por sí solo no define cómo hacer multistreaming; se refiere a la conexión entre un punto A y un punto B. Para lograr multistreaming tienes varias opciones:
Usar un servicio de Multistreaming: Es la forma más común y sencilla. Envías un único stream RTMP desde tu codificador (como OBS) a un servicio de terceros (ej: Restream.io, Castr.io, StreamYard). Este servicio se encarga de replicar y reenviar tu stream a todas las plataformas que hayas configurado en su panel.
Usar Plugins o Software Específico: Algunos codificadores o plugins (como el plugin "Multiple RTMP outputs" para OBS) pueden permitir configurar varias salidas RTMP directamente desde el software. Sin embargo, esto consume muchos más recursos de tu CPU/GPU y requiere mucho más ancho de banda de subida, ya que tu ordenador está haciendo todo el trabajo de codificar y enviar múltiples streams.
Configuración del Lado del Servidor: Si tienes tu propio servidor de medios (como Nginx con el módulo RTMP), puedes configurarlo para que reciba un stream RTMP y lo retransmita (relay) a múltiples destinos RTMP. Esto requiere conocimientos técnicos de administración de servidores.


¿Qué otras alternativas a RTMP se recomiendan?
HLS (HTTP Live Streaming) – Mejor compatibilidad con navegadores.


WebRTC – Latencia ultrabaja para interactividad en tiempo real.


SRT (Secure Reliable Transport) – Mayor seguridad y estabilidad en conexiones inestables.

Haz un resumen de la configuración y uso de RTMP

### PRACTICA 

Comprobar Hostname :

	hostname
	hostnamectl set-hostname haven.local

![image](https://github.com/user-attachments/assets/2e9afeb7-25cc-4c19-a128-63eba198d20b)


Instalar Nginx-RTMP:


	 apt update
	apt install libnginx-mod-rtmp

Configurar Nginx-rtmp:


sudo nano /etc/nginx/nginx.conf
Ponemos esto:

rtmp {

    server {
    
	 listen 1935;
  
	 chunk_size 4096;
  
	 allow publish 127.0.0.1;
  
	 deny publish all;
  
	 application live {
  
	    live on;
     
	    record off;
     
	 }

  
 


![image](https://github.com/user-attachments/assets/d7db9e76-7e11-45ff-b5f5-5adb25b74d31)

Y ponemos esto:
	
 ffmpeg -re -i video.mp4 -c:v copy -c:a aac -ar 44100 -ac 1 -f flv 

Y vamos al multimedia y ponemos:

rtmp://100.77.20.67/live/haven.local, en nuetro caso:

![image](https://github.com/user-attachments/assets/5134f076-1ff6-4ce4-a3a5-21893c15c535)

Y ya se ve el video:


![image](https://github.com/user-attachments/assets/76116753-082a-4a4c-9d0a-8c3ab1750198)


Investiga el uso de la aplicación OBS Studio para la transmisión de un video en streaming


Uso para Streaming:


Configurar Escenas y Fuentes: Creas "Escenas" que representan lo que quieres mostrar. Dentro de cada escena, añades "Fuentes": tu cámara web, la captura de una pantalla, un juego, imágenes, texto, un navegador web, etc. Puedes organizar varias fuentes en una escena.

Configurar Audio: En el "Mezclador de Audio", ajustas los niveles de tus micrófonos, el audio del escritorio, etc. Puedes añadir filtros como supresión de ruido.

Configurar la Salida (Codificación): Vas a Archivo > Ajustes > Salida. En el modo "Sencillo" puedes elegir un bitrate de video y el codificador (x264 - software, o NVENC/AMF/QSV si tienes hardware compatible). En modo "Avanzado" tienes más control:

Pestaña Emisión: Seleccionas el Codificador de video (H.264 es lo estándar), Control de frecuencia (CBR es común para streaming), Tasa de bits (ej: 3000-6000 Kbps para 1080p, depende de tu subida), Intervalo de fotogramas clave (usualmente 2 s), y un Preajuste (calidad vs uso de CPU/GPU). Configuras también el Codificador de audio (AAC) y su Tasa de bits (ej: 128-160 Kbps).

Configurar el Destino (RTMP): Vas a Archivo > Ajustes > Emisión.

Seleccionas el Servicio (ej: Twitch, YouTube - RTMPS, Facebook Live). Si tu servicio está en la lista, a menudo solo necesitas conectar tu cuenta o pegar la Clave de transmisión. El servidor se suele configurar automáticamente.
Si no está en la lista o usas un servidor propio, seleccionas Personalizado.... Aquí introduces manualmente la URL del Servidor RTMP/RTMPS y la Clave de transmisión que te haya proporcionado tu plataforma.

Iniciar Transmisión: Una vez todo configurado, vuelves a la ventana principal de OBS y haces clic en el botón Iniciar transmisión. OBS se conectará al servidor RTMP y empezará a enviar tu video y audio. Para detenerla, usas el botón Detener transmisión.

Monitorizar: Durante la transmisión, OBS muestra información útil en la barra inferior, como el estado de la conexión, el uso de CPU, si hay fotogramas perdidos (por problemas de red o de rendimiento del PC), y la tasa de bits actual.
</details> 

## 18.JellyFinn🧩

<details>
  <summary>
   JellyFinn🎞️
  </summary>

### TEORIA

**🧊 ¿Qué es Jellyfin?**

Jellyfin es un servidor multimedia gratuito y de código abierto que te permite organizar, gestionar y transmitir tus películas, series, música y fotos en tu red local o de forma remota. Es una alternativa libre a Plex y Emby.

🔓 100% libre, sin coste ni funciones premium.

🖥️ Puedes usarlo en Windows, Linux, macOS, Docker y NAS.

📱 Clientes para navegador, Android, iOS, Smart TV, Roku, etc.<br><br><br>



**⚙️ Breve tutorial: Configuración y administración**

1. Instalación
	En Windows/Linux/macOS: Descárgalo desde https://jellyfin.org e instálalo.
		
	En Docker:
		
		bash
		Copiar
		Editar
		docker run -d \
		  --name jellyfin \
		  -v /ruta/config:/config \
		  -v /ruta/medios:/media \
		  -p 8096:8096 \
		  jellyfin/jellyfin


2. Primer inicio
	1. Abre el navegador y ve a: http://localhost:8096
		
	2. Sigue el asistente:
		
	-Crea un usuario administrador.
		
	-Define los idiomas.
		
	-Añade las rutas a tus carpetas multimedia (películas, series, música).
		
	-Configura el tipo de biblioteca (películas, TV, música, etc.).


3. Administración básica
		
	Desde el Panel de administración puedes:

	👥 Gestionar usuarios.

	📁 Agregar o editar bibliotecas multimedia.

	🔄 Configurar transcodificación.

	🧩 Instalar plugins (metadatos, subtítulos, etc.).

	🌐 Configurar acceso remoto (requiere redirección de puertos o VPN).<br><br><br>


**🤜 Jellyfin vs Plex**

| Característica              | Jellyfin                              | Plex                                 |
|----------------------------|----------------------------------------|--------------------------------------|
| Licencia                   | 100% libre y de código abierto         | Gratuito con funciones premium       |
| Precio                     | Gratis, sin versión de pago            | Plex Pass opcional                   |
| Acceso remoto              | Manual (puertos o VPN)                 | Automático (con cuenta Plex)         |
| Transcodificación HW       | Solo con configuración específica      | Incluida con Plex Pass               |
| Plugins y personalización  | Alta (open source)                     | Limitada en versión gratuita         |
| Facilidad de uso           | Algo más técnico                       | Muy amigable para principiantes      |
| Privacidad                 | Total (datos solo locales)             | Requiere cuenta, datos en la nube    |

<br>

### PRACTICA 

Primero de todo empezamos con un:

 sudo apt install apt-transport-https

 ![image](https://github.com/user-attachments/assets/caf44c29-31c3-4b82-a258-54611732febe)


Que basicamente instala el paquete apt-transport-https, que permite al gestor de paquetes APT para acceder a repositorios de software que usan el protocolo HTTPS 

Luego seguimos con:

echo "deb [arch=$(dpkg --print-architecture)] https://repo.jellyfin.org/ubuntu $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/jellyfin.list

Para  agregar el repositorio de Jellyfin

![image](https://github.com/user-attachments/assets/4889b8bd-6d4c-4c88-9348-f3e7aa59eb6a)

Hacemos un apt update y apt upgrade

![image](https://github.com/user-attachments/assets/8153af32-c4c6-46c4-b735-1c649cd1233d)



Luego descargamos e importamos la clave GPG de Jellyfin:

wget -O - https://repo.jellyfin.org/jellyfin_team.gpg.key | sudo apt-key add -

![image](https://github.com/user-attachments/assets/c24c0560-8184-4eb1-aa16-483adbb34a4c)


Ahora hacemos un mkdir -p para crear una carpeta que se  llama accion dentro de la ruta /home/series/

![image](https://github.com/user-attachments/assets/31dd9440-381f-4c07-9d3c-471001d60571)


Hacemos un systemctl status y vemos que jellyfin esta running

Y ahora configuramos permisos para el usuario jellyfin

con: setfacl -R -m u:jellyfin:rx /home/series/


Ahora una vez si ponemos todo esto, si ponemos la IP en el navegador ya podriamos acceder a Jellyfin, entonces una vez allí, si vamos a elegir ruta y ponemos la que hemos puesto antes, ya nos saldria la opcion de YA ESTA


![image](https://github.com/user-attachments/assets/e31344a0-ca66-4af0-8638-b1d0e7641b13)

![image](https://github.com/user-attachments/assets/70c764c9-a513-42d9-9aff-5ca27d876a53)

Luego de esto, una vez puesto todo esto y nuestro usuario, ya veremos que tenemos accesso y que la instalacion ha sido correcta

![image](https://github.com/user-attachments/assets/ad9d18f3-1c1b-48bc-9cd8-06399c6662fb)



</details> 


## 19.Suricata🌐

<details>
  <summary>
   Suricata🕵️‍♂️
  </summary>

### TEORIA

**¿Qué es Suricata?**

**Suricata** es un sistema de **detección y prevención de intrusiones (IDS/IPS)** de código abierto, diseñado para proteger las redes al **monitorizar el tráfico** y detectar actividades maliciosas. Su objetivo principal es detectar **intrusiones** y **prevenir ataques** en tiempo real, protegiendo así a los sistemas de posibles amenazas cibernéticas.<br><br>

**¿Para qué sirve Suricata?**

Suricata es útil para:

- **Detección de intrusiones** 🕵️‍♂️: Identifica y alerta sobre actividades sospechosas o maliciosas.
- **Prevención de ataques** 🚫: Bloquea tráfico peligroso antes de que llegue a los sistemas.
- **Análisis de tráfico de red** 🌐: Inspecciona los datos que pasan por la red para detectar vulnerabilidades.
- **Generación de alertas en tiempo real** ⏰: Informa al administrador de red sobre incidentes de seguridad.
<br><br>

**Ventajas y Desventajas de Suricata**


| **Ventajas**                       | **Descripción**                                                                                             |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------|
| **💻 Código abierto y gratuito**   | Suricata es **totalmente gratis** y accesible para todos. No necesitas pagar por licencias ni costos adicionales. |
| **⚡ Rendimiento y escalabilidad** | Está optimizado para redes **grandes** y con **alto volumen de tráfico**, sin sacrificar el rendimiento.       |
| **⏱️ Detección en tiempo real**   | Detecta intrusiones en **tiempo real**, lo que permite prevenir ataques antes de que causen daño.              |
| **🌐 Compatible con varios protocolos** | Es capaz de inspeccionar una amplia variedad de protocolos de red como **HTTP**, **DNS**, **FTP**, entre otros.  |
| **🔒 Integración con otras herramientas de seguridad** | Se puede integrar con sistemas de **gestión de eventos de seguridad (SIEM)**, facilitando la centralización de alertas. |

<br>

| **Desventajas**                    | **Descripción**                                                                                             |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------|
| **⚙️ Requiere configuración técnica** | Ofrece **gran flexibilidad**, pero su configuración es más **compleja** en comparación con soluciones comerciales más fáciles de implementar. |
| **🔋 Consumo de recursos**         | Puede consumir muchos **recursos** (CPU y RAM) si no se configura adecuadamente o si el tráfico es muy elevado. |
| **❌ Falsos positivos**            | **Genera alertas falsas** que pueden hacer perder tiempo investigando incidentes que no son reales.            |
| **🔧 Necesita intervención humana**| Aunque puede bloquear amenazas, **requiere ajustes manuales** y supervisión para enfrentar ataques más complejos. |
<br>


### PRACTICA 







sudo apt update

![image](https://github.com/user-attachments/assets/89cd8fbf-71b4-49a3-8c27-8932b6f86aaf)

AÑADIR SURICATA AL REPOSITORIO, para obtener la versión estable más reciente.

sudo add-apt-repository ppa:oisf/suricata-stable

![image](https://github.com/user-attachments/assets/c071abfc-670d-4733-b1f5-4abfa4624700)

sudo apt update  para que encuentre el repositorio

sudo apt install suricata jq

Se instala Suricata junto con jq que es una herramienta para procesar JSON en la terminal

![image](https://github.com/user-attachments/assets/60258766-4098-4d23-9243-05a4b6c24b32)

sudo suricata --build-info

verifica la versión instalada y las características soportadas por Suricata.
![image](https://github.com/user-attachments/assets/6d883c69-597b-4ee7-a9df-f2629870e6b3)


sudo systemctl status suricata

Accedemos al suricata.yaml y editamos el archivo de configuración principal de Suricata para ajustar parámetros como la interfaz de red (enp0s3) y el modo de operación (af-packet).

![image](https://github.com/user-attachments/assets/2c92fcdb-7499-49a1-b1ec-7f9068646ceb)
![image](https://github.com/user-attachments/assets/4807cfad-6d31-415e-9dad-7fd499e6a082)

 sudo systemctl restart suricata

 Se reinicia el servicio para aplicar los cambios realizados en la configuración
 
![image](https://github.com/user-attachments/assets/08b83324-0a8a-42c0-bae3-5e72a86e5cb5)

sudo tail -f /var/log/suricata/suricata.log

Se monitorean los registros en tiempo real para verificar que Suricata esté funcionando correctamente

![image](https://github.com/user-attachments/assets/74498d6a-6250-4347-8a8d-9cd0b7d6f03a)

curl http://testmynids.org/uid/index.html y el resultado en /var/log/suricata/fast.log.

Se realiza una prueba para verificar que Suricata detecte tráfico malicioso

wget https://rules.emergingthreats.net/open/suricata/emerging.rules.tar.gz

Se descargan reglas actualizadas para mejorar la detección de amenazas

![image](https://github.com/user-attachments/assets/a72314a9-95ff-4a69-be55-806d9cfe06a5)
![image](https://github.com/user-attachments/assets/371b4670-c551-441b-908d-10ffd4bcaab6)


PROMETHEUS

Prometheus es un sistema de monitoreo y alerta de código abierto diseñado para aplicaciones y servicios en entornos distribuidos. Recopila métricas en tiempo real, las almacena en una base de datos de series temporales y permite consultarlas mediante un lenguaje propio (PromQL).

Es ampliamente utilizado  para supervisar el rendimiento, detectar anomalías y generar alertas.


Características Principales

✅ Recolección de métricas:

Recopila datos mediante un modelo de "extracción" (pull) sobre HTTP.

Soporta múltiples formatos de exportación (client libraries para Python, Go, Java, etc.).

✅ Almacenamiento eficiente:

Usa una base de datos de series temporales optimizada para consultas rápidas.

✅ Alertas:

Integra Alertmanager para notificaciones (email, Slack, etc.) basadas en reglas predefinidas.

✅ Integración con Grafana:

Permite visualizar métricas en dashboards interactivos.

✅ Escalabilidad:

Soporta federación para entornos distribuidos.

sudo apt install prometheus

Instala Prometheus y configura automáticamente el servicio para iniciarse con systemd

![image](https://github.com/user-attachments/assets/4e3aded2-9b28-4876-a09c-947f75b406e4)

Tras la instalación, Prometheus escucha en el puerto 9090 (HTTP), y esto lo verificamos con:

sudo lsof -i -P -n 
Mediante la inspeccion de los puertos abiertos

![image](https://github.com/user-attachments/assets/adb17336-d620-487a-95c3-33990f6d6ea3)

http://100.77.20.41 :9090
Desde el navegador, permite ejecutar consultas en PromQL 

![image](https://github.com/user-attachments/assets/57f52021-ba5d-4ffb-a455-ebabb1bd4ecc)

GRAFANA

Grafana es una herramienta de visualización y monitoreo de código abierto que permite crear dashboards interactivos para métricas, logs y datos de series temporales. Es compatible con múltiples fuentes de datos, incluyendo Prometheus, bases de datos SQL, Elasticsearch

Características clave:
✅ Dashboards personalizables: Gráficos, tablas, mapas de calor, etc.
✅ Soporte para alertas: Notificaciones basadas en umbrales.
✅ Integración con Prometheus: Ideal para monitorizar Suricata y otros servicios.
✅ Multiplataforma: Funciona en Linux, Windows, Docker, y en la nube.

sudo apt-get install -y adduser libfontconfig1 musl

adduser: Para gestionar usuarios (necesario para el servicio de Grafana).

libfontconfig1: Librería para renderizar fuentes en los dashboards.

musl: Librería estándar ligera para C (requerida por Grafana)

Descargar e Instalar Grafana
Se descarga el paquete .deb desde el sitio oficial

wget https://dl.grafana.com/enterprise/release/grafana-enterprise_11.6.0_amd64.deb
sudo dpkg -i grafana-enterprise_11.6.0_amd64.deb

![image](https://github.com/user-attachments/assets/7eefebdd-0fd3-43d9-b481-f144fb910949)

Tras la instalación, grafana escucha en el puerto 3000 (HTTP), y esto lo verificamos con:

sudo lsof -i -P -n 
Mediante la inspeccion de los puertos abiertos

![image](https://github.com/user-attachments/assets/c4fe15ac-5640-4881-bef2-45672b479dac)

Acceder a la Interfaz Web con: http://100.77.20.41 :3000

![image](https://github.com/user-attachments/assets/a4181e35-c2c5-4f3c-a66a-ef4cba7eb845)

Tras iniciar sesión, vamos a Configuration (engranaje) > Data Sources.

Seleccionar Prometheus.

 Y configuramos la URL de Prometheus: http://100.77.20.41 :9090, luego guardamos y probamos la conexión
 
![image](https://github.com/user-attachments/assets/e5f070cc-5468-41e9-95ac-64ea3a22cb02)
![image](https://github.com/user-attachments/assets/f7379210-5dc1-4058-914d-bfb9cd3bb615)


QUE HARIAMOS CON SI TUVIERAMOS MAS TIEMPO

Podriamos Monitorización de Contenedores con  Grafana + Prometheus + cAdvisor y asi teamtactics tendria un sistema completo de monitorización para Docker, con gráficos en tiempo real, históricos y alertas proactivas y asi nos ayudaria a optimizar recursos, detectar problemas y mejorar la estabilidad de nuestros contenedores.

cAdvisor,  es una herramienta de monitorización de contenedores que proporciona métricas sobre CPU, memoria, red, disco y más y  expone las métricas en formato Prometheus para su integración con herramientas como Grafana

</details> 


## 20. FINAL DEL PROYECTO

<details>
  <summary>
   TODOS LOS CANVIOS
  </summary>



Ahora que estamos en la parte final del proyecto vamos a explicar de forma muy especifica todas las novedades que hemos realizado en comparación con la 1 UF de proyecto.

Para empezar, hablaremos sobre las funcionalidades que hemos aplicado  a nuestro proyecto, que han sido bastantes de verdad para ser un equipo de dos, y basicamente aqui tanto Quim y Pol no podemos decir que cada cosa ha hecho cada uno ya que hemos ido trabajado de forma conjunta como un equipo de verdad

### FUNCIONALIDADES

1. Una funcionalidad que hemos aplicado a sido la del canvio de contraseña para que los usuarios cuando se registran tengan esa opción de canvio de contraseña para así de una forma segurizar las contraseñas de los usuarios que se registran en nuestra web, este botón de canvio de contraseña se encuentra en la parte inferior de donde el usuario se registra con su correo y contraseña
   
2. Otra funcionalidad que hemos aplicado a sido la de que cuando un usuario accede a nuestra página web, no se le puede permitar inspeccionar, ya que de esta manera, aplicamos seguridad dentro de nuestra web y así de alguna forma proteger nuestro código para que no pueda ser reutilizado por otros usuarios a la vez que acceden a nuestra web

3. Otra funcionalidad que hemos realizado ha sido que dentro de nuestra web, arriba derecha hay un titulo de Contacto, y allí es donde el usuario puede poner algun comentario sobre nuestra web

4. Una funcionalidad que creemos que ha sido muy importante para la parte final, ha sido la parte de classificación, hace falta decir que en esta parte queriamos aplicar la API, pero por problemas económicos, ya que tener una API es bastante costosa la verdad, hemos decidido hacer esta parte de la web mediante codigo, donde el usuario  puede poner diferentes equipos como en un partido, para ver si el que pierda o gana como quedaría en la classificació, esta parte dentro de la web ha quedado bastante estética y es fundamental para poder mejorar nuestra web de teamtactics

5. Centro de soporte, esta es otra funcionalidad que hemos creado, esta, se basa que cuando accedemos a la página principal de nuestra web, abajo derecha aparece una opción de chat, como de centro de soporte


Ahora vamos a ampliar un poco de explicación de como lo hemos realizado, basicamente descubrimos por nuestra propia cuenta, que existe una web que se llama TIDIO, y basicamente, te da la opción de que dar un link para ponerlo en tu html y funciona como un chat, entonces, dentro de la web nuestra, existe está opción de chatear, y entonces dentro de tidio, tenemos una parte de donde a nuestro correo de usuario, es decir el de contacto, nos llegan todos los mensajes de los usuarios que han chateado con el chat de la web


6. BACKUP, otra funcionalidad ha sido la del backup, ya que basicamente aplicamos seguridad si por alguna razón perdemos algo, y así de paso hacemos otra funcionalidad y además es algo bastante importante para de una forma segurizar nuestro largo trabajo constante de estos últimos meses

7. CHATBOX, está ha sido la última que haremos, esta basicamente arriba y  te sale una opción de chatbox, donde un bot te pone unas respuestas establecidas estonces, tu puedes ir clickando sobre opciones y además si por ejemplo tienes alguna duda sobre algun sitio como estadisticas, te puede llevar allí directamente. 
   
### BASE DE DATOS

Basicamente, en nuestra base de datos, en este segundo trimestre no hemos tocado mucho ya que en el primer trimestre hicimos basicamente la gran mayoria de trabajo, sobretodo en la parte de equipos, en esta segunda UF lo hemos tocado para contacto y cambio de contraseña, para que así se guarden las personas que hos han enviado un mensaje de contacto y también esas contraseñas estas hasheada, mostramos imagen para verificar que es verdad y que no nos inventamos nada:

![image](https://github.com/user-attachments/assets/43d78bee-407d-4a2c-b1eb-605f9234fd8f)


### ESQUEMA DE RED


### CONCLUSIÓN

Bueno para hacer una conclusión sobre este trabajo, creemos tanto Quim y Pol hemos aprendido muchísimo durante estas 2 UF de proyecto con Alina, ya que nos ha enseñado todo tipo de nuevas tecnologias que possiblemente nunca habíamos escuchado anteriormente.
Hablando del trabajo, creemos que hemos ido trabajo semanalmente de forma correcta para que estos últimos días poder estar tranquilos por el trabjo diario y constante, nuestra web de teamtactics, ha ido mejorando paso a paso con todas las nuevas funcionalidades que hemos ido aplicando durante esta última UF, como por ejemplo el CHATBOX, que es brutal y también la zona de contacto que también siendo honesto es bantante interesante y possiblemente explicaremos en la presentación para que los possibles proyectos puedan tener esta función.

También, creo que hace falta decir, que en enero perdimos nuestro primer proxmox, es decir nuestro PC donde estaba montado todo nuestro proyecto de la UF 1 y lo que nos hizo perder todo lo trabajo y a la vez nos hizo perder mucho tiempo ya que confiamos que lo encontrariamos por alguna clase de IFP, pero no. Entonces nos obligo a Quim y Pol literalmente volar ya que sinó no llegariamos a donde estamos ahora ni de coña, y siendo honestos nunca me imagine tener el proyecto a los últimos dias de forma tan tranqula




 </details>

 
## BIBLIOGRAFIA

https://punkymo.gitbook.io/miwiki

