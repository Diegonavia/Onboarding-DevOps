# Onboarding-DevOps 💥
Repositorio creado para el entrenamiento y Onboarding de nuevos DevOps que se integren al equipo 😎 

## Resumen 📃
Este proyecto está orientado a todos los DevOps que se integren al equipo de Concrete, con la finalidad de adaptarse a las tecnologías utilizadas en el proyecto, así como también herramientas esenciales para cualquier DevOps.

## Prerrequisitos :exclamation:

- Tener conocimientos previos en algunas de las herramientas utilizadas en este Onboarding. 
- Necesitarás crear una cuenta de AWS (Amazon Web Services) para realizar algunos laboratorios de AWS.
- Familiarizarse con la Infraestructura del proyecto 
- Editor de código fuente donde almacenar las carpetas y el código, utilizaremos Visual Studio Code versión 1.36.31 (Recomendación) :nerd_face:

## Primeros pasos :walking:

- Familiarizarse con la Infraestructura del proyecto [Infraestructura](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Infraestructura) y todos sus componentes.
- Conocer los componentes que integran el proyecto y las herramientas utilizadas para la realización de las actividades diarias [Presentación](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Presentaci%C3%B3n). 
- Leer este [Artículo](https://medium.com/@devfire/how-to-become-a-devops-engineer-in-six-months-or-less-366097df7737) aquellos DevOps que están iniciando en la posición, para que se tenga claro hacia que apunta esta cultura, y como integrar las distintas herramientas.

## Herramientas utilizadas en el Proyecto 	💻

- ### GIT 🔱

En el proyecto utilizamos GIT como Sistema De Control de Versiones, el cual es un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo de tal manera que sea posible recuperar versiones especificas más adelante.

Git fue creado pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un gran número de archivos de código fuente, es decir Git nos proporciona las herramientas para desarrollar un trabajo en equipo de manera inteligente y rápida y por trabajo nos referimos a algún software o página que implique código el cual necesitemos hacerlo con un grupo de personas.

Algunas de las características más importantes de Git son:

- Rapidez en la gestión de ramas, debido a que Git nos dice que un cambio será fusionado mucho más frecuentemente de lo que se escribe originalmente.

- Gestión distribuida; Los cambios se importan como ramas adicionales y pueden ser fusionados de la misma manera como se hace en la rama local.

- Gestión eficiente de proyectos grandes.

- Realmacenamiento periódico en paquetes.


![git](https://user-images.githubusercontent.com/45079819/77668248-ed2ece80-6f61-11ea-9aed-205fe5137a97.png)


Para tener una mejor idea de como funciona GIT puede realizar este [Curso](https://codigofacilito.com/cursos/git) gratis en cualquier momento si así lo desea. 🤓

Para mayor dominio de la herramienta, se han creado una serie de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/GIT) con diferente nivel de dificultad para dominlarla.


- ### Jenkins 🚀

Jenkins es un herramienta open source que cubre algunas de las fases del ciclo de vida de integración continua de tu aplicación. Permite a los equipos de desarrollo compilar, probar y desplegar los desarrollos. Gestionando las entregas continuas desde el código hasta el despliegue en un solo flujo de trabajo, más conocido como “Job” en entorno Jenkins.

La base de Jenkins son las tareas Jobs, desde donde podrás indicar todo el proceso hasta llegar a un **build** final estable. Vamos con un ejemplo: 📎

Puedes programar un Job que se ejecute cada vez que subimos una nueva versión a Git, que este se **compile** y se ejecuten las **pruebas**.

Si el resultado no es el esperado o hay algún error, Jenkins notificará al desarrollador o a quien definas, por email u otros medios. Si la compilación es correcta, podremos indicar a Jenkins que integre el código en una rama ‘master’ del propio repositorio del control de versiones.

Una vez tenemos el código compilado, podrás indicar que se ejecuten las **pruebas**, con métricas de calidad y visualizar los resultados y para finalizar, podrás **desplegar** una versión estable del software al entorno de pruebas para ser **testeado**, en pre-producción o producción. Con el desarrollo disponible, solo queda esperar nuevos reportes de mejora.


<img width="1042" alt="Screen Shot 2020-03-26 at 16 25 07" src="https://user-images.githubusercontent.com/45079819/77688175-62100180-6f7e-11ea-850f-1578849684e7.png">


#### ¿Qué son la integración/distribución continuas (CI/CD)? ✔️

La CI/CD es un método para distribuir aplicaciones a los clientes con frecuencia mediante el uso de la automatización en las etapas del desarrollo de aplicaciones. Los principales conceptos que se atribuyen a la CI/CD son la integración continua, la distribución continua y la implementación continua. La CI/CD es una solución para los problemas que puede generar la integración del código nuevo a los equipos de desarrollo y de operaciones


En el desarrollo de una aplicación, la integración continua se organiza en las siguientes fases: 📄

- **Desarrollar** nuevas integraciones o mejoras en nuestra aplicación.
- **Compilación** del código fuente, obteniendo el ‘build’.
- **Pruebas**, realizando análisis y test unitarios, con métricas de calidad para la detección preventiva de errores
- **Despliegue** y aprovisionamiento de la aplicación en el entorno que definamos, como por ejemplo test o producción.
- **Tests** funcionales y de integración, automatizados o manuales.
- **Reportes** de nuestros usuarios o automatizados con por ejemplo Sentry, New relic, etc.


<img width="1412" alt="Screen Shot 2020-03-26 at 16 45 34" src="https://user-images.githubusercontent.com/45079819/77689928-478b5780-6f81-11ea-8ee7-c30fdb337e44.png">


Para mas información acerca de Jenkins pueden dirigirse a su [Página-Oficial](https://jenkins.io/) o pueden realizar este [Curso](https://www.youtube.com/watch?v=FX322RVNGj4) completo totalmente gratis. 

Para mayor dominio de la herramienta, se han dispuesto de un conjunto de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Jenkins) de Jenkins para mejorar el dominio de la misma.

Adicional a estos recursos, disponemos de un entrenamiento en la herramienta realizado por uno de nuestros colaboradores, lo puedes encontrar [Aquí](https://github.com/vitorsalgado/ci-cd-training-proposal) lo cual te ayudará en la adopción de CI/CD. 



- ### Docker 🐳

Docker es una plataforma de software que le permite crear, probar e implementar aplicaciones rápidamente. Docker empaqueta software en unidades estandarizadas llamadas contenedores que incluyen todo lo necesario para que el software se ejecute, incluidas bibliotecas, herramientas de sistema, código y tiempo de ejecución. Con Docker, puede implementar y ajustar la escala de aplicaciones rápidamente en cualquier entorno con la certeza de saber que su código se ejecutará.

A primera vista se piensa en Docker como una especie de máquina virtual “liviana”, pero la verdad no lo es. En Docker no existe un hypervisor que virtualice hardware sobre el cual corra un sistema operativo completo. En Docker lo que se hace es usar las funcionalidades del Kernel para encapsular un sistema, de esta forma el proyecto que corre dentro de el no tendrá conocimiento que está en un contenedor. Los contenedores se encuentran aislados entre sí y se comportaran como máquinas independientes.

Iniciar un contenedor no tiene un gran impacto a diferencia de iniciar una máquina virtual ya que no tiene que iniciar un sistema operativo completo (desde cero). Gracias al uso de contenedores la demanda de recursos baja limitándose sólo al consumo de la aplicación que contenga. Un contenedor inicia en milisegundos.



<img width="914" alt="Screen Shot 2020-03-26 at 18 13 49" src="https://user-images.githubusercontent.com/45079819/77697409-93dc9480-6f8d-11ea-8eb7-cd49b2e5d1f9.png">


#### ¿Qué son los Contenedores? ✔️

Un contenedor es una unidad de software estándar que empaqueta el código y todas sus dependencias para que la aplicación se ejecute de manera rápida y confiable. Una imagen de contenedor de Docker es un paquete de software ligero, independiente y ejecutable que incluye todo lo necesario para ejecutar una aplicación: código, tiempo de ejecución, herramientas del sistema, bibliotecas y configuraciones del sistema.

Contenedores Docker que se ejecutan en Docker Engine: 🚢

- **Estándar:** Docker creó el estándar de la industria para contenedores, por lo que podrían ser portátiles en cualquier lugar
- **Ligero:** los contenedores comparten el núcleo del sistema operativo de la máquina y, por lo tanto, no requieren un sistema operativo por aplicación, lo que aumenta la eficiencia del servidor y reduce los costos de servidor y licencias
- **Seguro:** las aplicaciones son más seguras en contenedores y Docker proporciona las capacidades de aislamiento predeterminadas más sólidas de la industria

![docker](https://user-images.githubusercontent.com/45079819/77698192-f84c2380-6f8e-11ea-9466-887b11dad91e.jpg)


Para mas información acerca de Docker pueden dirigirse a su [Página-Oficial](https://www.docker.com/) o pueden realizar este [Curso](https://codigofacilito.com/cursos/docker) completamente **Gratis** para afianzar los conocimientos en la herramienta. 🤓

Además de esto, se han dispuesto una serie de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Docker) para mejorar el dominio en Docker. 🐳


- ### Bash Scripting 📓

Bash es un intérprete de comandos que ejecuta, una por una, las instrucciones introducidas por el usuario o contenidas en un script y devuelve los resultados. En otras palabras, actúa como interfaz entre el kernel Linux y los usuarios o programas del modo texto. Además, incorpora numerosas utilidades de programación y mejoras sobre sh, su shell predecesora. Debido a que es una herramienta desarrollada por GNU, suele ser utilizada por defecto en las distros actuales.

El uso de bash scripting permite:

- Automatizar acciones repetitivas, gracias al uso de expresiones matemáticas, como condiciones, bucles puertas lógicas, etc.
- Como consecuencia de lo anterior, nos permite mejorar la experiencia del usuario.
- También ofrece las herramientas necesarias a un administrador para que su sistema operativo sea más automático, más ágil y más capaz de procesar datos.

<img width="287" alt="Screen Shot 2020-03-30 at 15 23 47" src="https://user-images.githubusercontent.com/45079819/77947568-80397280-729a-11ea-93e0-982db6e63628.png">


Para tener una mejor idea de como utilizar Bash Scripting puede realizar este [Curso](https://www.youtube.com/watch?v=e7BufAVwDiM) gratis en cualquier momento si así lo desea. 🤓

Además del curso, puede encontrar esta [Guía](https://devhints.io/bash) con los principales comandos utilizados en Bash. 

Adicionalmente, se han dispuesto una serie de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Bash) para mejorar el dominio en Docker.

- ### Ansible :spades:

Ansible es un software que automatiza el aprovisionamiento de software , la gestión de configuraciones y el despliegue de aplicaciones. Está categorizado como una herramienta de orquestación , muy útil para los administradores de sistema y DevOps.

En otras palabras, Ansible permite a los DevOps gestionar sus servidores, configuraciones y aplicaciones de forma sencilla, robusta y paralela

Ansible gestiona sus diferentes nodos a través de SSH y únicamente requiere Python en el servidor remoto en el que se vaya a ejecutar para poder utilizarlo. Usa YAML para describir acciones a realizar y las configuraciones que se deben propagar a los diferentes nodos.

#### Compatibilidad de Ansible ✔️

Ansible se distribuye en Fedora, Red Hat enterprise Linux, CentOS y Scientific Linux mediante los paquetes EPEL, además está disponible para diferentes distribuciones Linux aparte de las anteriores mencionadas puedes verlo en este enlace y descargar la que necesites.

También está disponible para MAC, pero no para Windows, aunque podemos usarlo en máquinas virtuales.

#### ¿Qué es un playbook de Ansible? ✔️

Los playbooks nos proporcionan una manera totalmente diferente de utilizar Ansible . Los comandos ad-hoc hacen de Ansible una herramienta muy potente, pero los playbooks la convierten en “la herramienta”. Mientras que podemos ejecutar comandos ad-hoc con Ansible, los playbooks podemos tenerlos en un control de versiones como Git . Además, pueden ejecutar tareas tal y como nosotros queramos haciendo uso de los inventarios, tags, roles, etc. 

#### Arquitectura de Ansible ✔️

En Ansible existen dos tipos de servidores:

- **Controlador:** La máquina desde la que comienza la orquestación
- **Nodo:** Es manejado por el controlador a través de SSH.

<img width="586" alt="Screen Shot 2020-03-30 at 15 50 53" src="https://user-images.githubusercontent.com/45079819/77950008-49655b80-729e-11ea-9074-74e274b9674e.png">


Para mas información acerca de Ansible pueden dirigirse a su [Página-Oficial](https://www.ansible.com/) o pueden realizar este [Curso](https://www.youtube.com/watch?v=wf_Ax0PpZxI) completamente **Gratis** para afianzar los conocimientos en la herramienta. 🤓

Adicionalmente, se han dispuesto una serie de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Ansible) para mejorar el dominio en Ansible.

- ### Kubernetes 🌀

Kubernetes es una plataforma portable y extensible de código abierto para administrar cargas de trabajo y servicios. Kubernetes facilita la automatización y la configuración declarativa. Tiene un ecosistema grande y en rápido crecimiento. El soporte, las herramientas y los servicios para Kubernetes están ampliamente disponibles.

Kubernetes actua como un **orquestador** de contenedores. Un orquestador es el encargado de gestionar el ciclo de vida de los contenedores de una aplicación. Kubernetes, como orquestrador ofrece las siguientes caracteristicas:

- Manejo del clúster (permitir añadir o quitar nodos al clúster)
- Gestión del ciclo de vida de los contenedores (p. ej. reiniciar contenedores que fallen)
- Service Discovery (que un contenedor pueda encontrar las rutas IP/DNS de otro contenedor)
- Servicios de red y load-balancing (repartir la carga entre las distintas máquinas del clúster)
- Servicios de monitorización
- Servicios de chequeo de estado de salud (del clúster y de cada uno de los contenedores)

#### ¿Cómo funciona Kubernetes? ✔️

Kubernetes es un sistema de orquestación de contenedores, lo que significa que el software no se encarga de crearlos, sino de administrarlos. Para ello, Kubernetes aplica la automatización de procesos, lo que vuelve más fácil para los desarrolladores comprobar, mantener o publicar aplicaciones. La arquitectura de Kubernetes consta de una clara jerarquía, compuesta por los siguientes elementos:

- **Contenedor:** incluye las aplicaciones y entornos de software.
- **Pod:** este elemento de la arquitectura de Kubernetes se encarga de agrupar aquellos contenedores que necesitan trabajar juntos para el funcionamiento de una aplicación.
- **Nodo:** uno o varios pods se ejecutan en un nodo, que puede ser tanto una máquina virtual como física.
- **Clúster:** en Kubernetes, los nodos se agrupan en clústeres

![Figura1](https://user-images.githubusercontent.com/45079819/77954436-fc38b800-72a4-11ea-8490-c533fd2b1543.png)


Para mas información acerca de Kubernetes pueden dirigirse a su [Página-Oficial](https://kubernetes.io/) o pueden realizar este [Curso](https://www.youtube.com/watch?v=5ovqsvqwtZM&feature=youtu.be) completamente **Gratis** para afianzar los conocimientos en la herramienta. 🤓

Adicionalmente, se han dispuesto una serie de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Kubernetes) para mejorar el dominio en Kubernetes.

- ### Terraform 🔧

Terraform es una herramienta para construir, combinar y poner en marcha de manera segura y eficiente la infraestructura. Desde servidores físicos a contenedores hasta productos SaaS (Software como un Servicio), Terraform es capaz de crear y componer todos los componentes necesarios para ejecutar cualquier servicio o aplicación.

Se define la infraestructura completa como código, incluso si se extiende a múltiples proveedores de servicios. Por ejemplo los servidores pueden estar de Openstack, el DNS en AWS, terraform construirá todos los recursos a través de estos proveedores en paralelo, con esto se proporciona un flujo de trabajo y se usa como herramientas para cambiar y actualizar la infraestructura con seguridad.

Las principales características de Terraform son:

- **Infraestructura como código:** La infraestructura se describe utilizando una sintaxis de alto nivel. Esto permite que un blueprint sea versionado y tratado como lo haría con cualquier otro código. Estos archivos que describen la infraestructura pueden ser compartidos y reutilizados.

- **Planes de Ejecución:** Terraform tiene un paso de “planificación” donde genera un plan de ejecución. El plan de ejecución muestra lo que hará Terraform cuando se ejecute. Esto permite evitar sorpresas.

- **Gráfico de recursos:** Terraform crea un gráfico de todos los recursos y paraleliza la creación y modificación de cualquier recurso. Con esto los operadores obtienen información sobre las dependencias en la infraestructura.

- **Automatización de cambios:** Los conjuntos de cambios complejos se pueden aplicar a su infraestructura con una mínima interacción humana. Con el plan de ejecución y el gráfico de recursos mencionados anteriormente, se sabe exactamente qué cambiará Terraform y en qué orden, evitando muchos posibles errores humanos.

#### ¿Qué es Infraestructura cómo código? ✔️

Infraestructura como código hace referencia a la práctica de utilizar scripts para configurar la infraestructura de una aplicación como máquinas virtuales, en lugar de configurar estas máquinas de forma manual.

La infraestructura como código permite a las máquinas virtuales gestionarse de manera programada, lo que elimina la necesidad de realizar configuraciones manuales (y actualizaciones) de componentes individuales. Esto es una construcción de infraestructura más consistente y de mayor calidad con mejores capacidades de administración, maximizando la eficiencia y evitando el error humano.

El resultado es una infraestructura muy elástica, escalable y replicable gracias a la capacidad de modificar, configurar y apagar cientos de máquinas en cuestión de minutos con solo presionar un botón.

<img width="588" alt="Screen Shot 2020-03-30 at 17 18 09" src="https://user-images.githubusercontent.com/45079819/77957806-7455ac80-72aa-11ea-89d6-399e31407f45.png">


Para mas información acerca de Terraform pueden dirigirse a su [Página-Oficial](https://www.terraform.io/) o pueden realizar este [Curso](https://www.youtube.com/watch?v=ec4qHgJQM7c&list=PLfW3im2fiA7XDjPgS9uzgv5Zeyhi_QE9Y) completamente **Gratis** para afianzar los conocimientos en la herramienta. 🤓

Adicionalmente, se han dispuesto una serie de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Terraform) para mejorar el dominio en Terraform.


- ### Splunk ✅

Splunk es la solución es un software que permite monitorizar y analizar todo el big data de la empresa (en aplicaciones, sistemas e infraestructuras) a través de una interfaz web. Toda esa información se interpreta y se plasma en un repositorio mediante gráficos, alertas y paneles con información clara y útil para la toma de decisiones.

Es una herramienta muy importante en el proyecto ya que permite monitorear la aplicación a todos los niveles y todas las capas, proporcionando información detallada de cada uno de los componentes, separandolos en distintos **Dashboards** los cuales contienen toda la información relevante de cada componente.

<img width="476" alt="Screen Shot 2020-03-30 at 17 48 23" src="https://user-images.githubusercontent.com/45079819/77960448-b385fc80-72ae-11ea-8aec-53c3c90c1353.png">


El machine data (los datos de las máquinas) son la información que genera cualquier dispositivo o sistema conectado: GPS, etiquetas RFID, servidores, aplicaciones, teléfonos, ordenadores, centros de datos, dispositivos etc. Para darle valor a toda esa información, Splunk se apoya en cinco funciones principales:

- **Índex:** La parte que recoge los datos de todas las fuentes y los procesa, manteniendo constante la identificación de todos los eventos y almacenándolos para su posterior búsqueda.
- **Search & Investigate:** El buscador de Splunk que permite encontrar eventos permitiendo analizar y ejecutar estadísticas.
- **Add knowledge:** Con esta función se pueden agregar datos manualmente que ayuden a la interpretación de los mismos, permitiendo clasificarlos, normalizarlos y guardar informes.
- **Monitor & Alert:** La sección de monitorización que permite identificar problemas y aplicar soluciones antes de que un ataque impacte sobre los clientes y servicios. En esta funcionalidad se pueden configurar alertas para configurar respuestas automáticas a ciertos eventos.
- **Report & Analyze** Creación de informes y visualizaciones para la toma de decisiones.

![SplunkArq](https://user-images.githubusercontent.com/45079819/77961024-9a318000-72af-11ea-863c-ac6920d367dd.png)

Para mas información acerca de Splunk pueden dirigirse a su [Página-Oficial](https://www.splunk.com/) o pueden realizar este [Curso](https://www.youtube.com/watch?v=DJ6tXTsjX_A) completamente **Gratis** para afianzar los conocimientos en la herramienta. 🤓

Adicionalmente, se han dispuesto una serie de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Splunk) para mejorar el dominio en Splunk.


- ### AWS (Amazon Web Services) 🔸

Amazon Web Services con sus siglas abreviadas **AWS**, es una plataforma de nube muy popular y completa debido a sus múltiples servicios que ofrece. Muchas empresas crecen a una velocidad fugaz y esto nos lleva a responder con el funcionamiento de sus infraestructuras, el aumento de su productividad y reducción de costos.

La tendencia general para las plataformas en la nube es la de ofrecer la mayor cantidad posible de herramientas y servicios, para que así se pueda crear todo un entorno de computación en una misma nube. Al igual que otras plataformas como Microsoft Azure, Amazon dispone de una gran cantidad de herramientas para la gestión de diferentes elementos dentro de la empresa. 

#### ¿Para qué sirve Amazon Web Services? ✔️

Amazon web services nos provee una gigante cantidad de servicios para poder dar solución a distintas variables que tenemos en una infraestructura de TI, estas variables pueden ser desde almacenamiento en la nube, gestión de instancias, hosting web hasta desarrollo de aplicaciones móviles, y esto solo nombrando algunas de ellas.

AWS nos garantiza una plataforma más segura y confiable , tanto así que un arquitecto de TI puede encontrar con Amazon todos los recursos necesarios para montar su arquitectura completa, segura y tolerante a fallos. Todo lo que necesita una compañía para entrar a competir en el mercado.

<img width="563" alt="Screen Shot 2020-03-30 at 18 16 58" src="https://user-images.githubusercontent.com/45079819/77962806-abc85700-72b2-11ea-8ac6-8ad653a09a36.png">

#### Principales Herramientas/servicios en AWS ✔️

- **Amazon EC2:** Cloud Computing, provee todo lo necesario para la gestión y administración de instancias y escalado de ellas.

- **Amazon VPC:** Redes virtuales, proporciona el servicio de creación de redes y subredes a través de su servicio llamado Amazon VPC.

- **Amazon RDS:** Bases de datos, provee el servicio de bases de datos y entre ellos, podemos elegir los motores de bases de datos más comunes como MYSQL, PosgreSQL, SQL SERVER, Oracle, Amazon Aurora y NoSQL.

- **Amazon S3:** Almacenamiento de archivos, como su nombre lo dice, nos permite almacenar toda clase de objetos con un tipo de acceso clasificado en: acceso regular, poco frecuente, o muy frecuente. Aquí podemos respaldar nuestros archivos de backup, fotografías, videos. Lo que quiera guardar en la nube.

- **IAM** Seguridad y control de acceso, es sobre autenticación de usuarios, básicamente nos ayuda a gestionar el acceso a nuestros recursos.

- **Amazon Cloudwatch:** Es una herramienta de monitoreo que permite el rastreo de métricas y logs sobre nuestros servicios.

- **Amazon CloudFormation:** Brinda el servicio de crear y administrar una colección de recursos, aprovisionándolos y actualizándolos mediante plantillas escritas en Json.

- **Amazon CloudTrail:** Brinda una auditoria de Api’s mediante un servicio web.

![aws-josemariagonzalez](https://user-images.githubusercontent.com/45079819/77963471-c949f080-72b3-11ea-9fa5-4b467ea8f1f1.jpg)

Para mas información acerca de AWS pueden dirigirse a su [Página-Oficial](https://aws.amazon.com/) o pueden realizar este [Curso](https://www.youtube.com/watch?v=Ik0powELqDY&list=PLfW3im2fiA7Wp6H7FWNK8Mm53U2BqxjX4) completamente **Gratis** para afianzar los conocimientos en AWS. 🤓

Adicionalmente, se han dispuesto una serie de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/AWS) para conocer un poco AWS y familiarizarse con los servicios principales.



