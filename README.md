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


#### ¿Qué son la integración/distribución continuas (CI/CD)? ✏️

La CI/CD es un método para distribuir aplicaciones a los clientes con frecuencia mediante el uso de la automatización en las etapas del desarrollo de aplicaciones. Los principales conceptos que se atribuyen a la CI/CD son la integración continua, la distribución continua y la implementación continua. La CI/CD es una solución para los problemas que puede generar la integración del código nuevo a los equipos de desarrollo y de operaciones


En el desarrollo de una aplicación, la integración continua se organiza en las siguientes fases: 📄

- **Desarrollar** nuevas integraciones o mejoras en nuestra aplicación.
- **Compilación** del código fuente, obteniendo el ‘build’.
- **Pruebas**, realizando análisis y test unitarios, con métricas de calidad para la detección preventiva de errores
- **Despliegue** y aprovisionamiento de la aplicación en el entorno que definamos, como por ejemplo test o producción.
- **Tests** funcionales y de integración, automatizados o manuales.
- **Reportes** de nuestros usuarios o automatizados con por ejemplo Sentry, New relic, etc.


<img width="1412" alt="Screen Shot 2020-03-26 at 16 45 34" src="https://user-images.githubusercontent.com/45079819/77689928-478b5780-6f81-11ea-8ee7-c30fdb337e44.png">


Para mas información acerca de Jenkins pueden dirigirse a su [Página-Oficial](https://jenkins.io/) o pueden realizar este [Curso](https://www.youtube.com/watch?v=FX322RVNGj4) completo totalmente gratis. 📚

Para mayor dominio de la herramienta, se han dispuesto de un conjunto de [Ejercicios](https://github.com/Diegonavia/Onboarding-DevOps/tree/master/Jenkins) de Jenkins para mejorar el dominio de la misma.

Adicional a estos recursos, disponemos de un entrenamiento en la herramienta realizado por uno de nuestros colaboradores, lo puedes encontrar [Aquí](https://github.com/vitorsalgado/ci-cd-training-proposal) lo cual te ayudará en la adopción de CI/CD. 



- ### Docker 🐋

Docker es una plataforma de software que le permite crear, probar e implementar aplicaciones rápidamente. Docker empaqueta software en unidades estandarizadas llamadas contenedores que incluyen todo lo necesario para que el software se ejecute, incluidas bibliotecas, herramientas de sistema, código y tiempo de ejecución. Con Docker, puede implementar y ajustar la escala de aplicaciones rápidamente en cualquier entorno con la certeza de saber que su código se ejecutará.

A primera vista se piensa en Docker como una especie de máquina virtual “liviana”, pero la verdad no lo es. En Docker no existe un hypervisor que virtualice hardware sobre el cual corra un sistema operativo completo. En Docker lo que se hace es usar las funcionalidades del Kernel para encapsular un sistema, de esta forma el proyecto que corre dentro de el no tendrá conocimiento que está en un contenedor. Los contenedores se encuentran aislados entre sí y se comportaran como máquinas independientes.

Iniciar un contenedor no tiene un gran impacto a diferencia de iniciar una máquina virtual ya que no tiene que iniciar un sistema operativo completo (desde cero). Gracias al uso de contenedores la demanda de recursos baja limitándose sólo al consumo de la aplicación que contenga. Un contenedor inicia en milisegundos.



<img width="914" alt="Screen Shot 2020-03-26 at 18 13 49" src="https://user-images.githubusercontent.com/45079819/77697409-93dc9480-6f8d-11ea-8eb7-cd49b2e5d1f9.png">


#### ¿Qué son los Contenedores?

Un contenedor es una unidad de software estándar que empaqueta el código y todas sus dependencias para que la aplicación se ejecute de manera rápida y confiable. Una imagen de contenedor de Docker es un paquete de software ligero, independiente y ejecutable que incluye todo lo necesario para ejecutar una aplicación: código, tiempo de ejecución, herramientas del sistema, bibliotecas y configuraciones del sistema.

Contenedores Docker que se ejecutan en Docker Engine: 🚢

- **Estándar:** Docker creó el estándar de la industria para contenedores, por lo que podrían ser portátiles en cualquier lugar
- **Ligero:** los contenedores comparten el núcleo del sistema operativo de la máquina y, por lo tanto, no requieren un sistema operativo por aplicación, lo que aumenta la eficiencia del servidor y reduce los costos de servidor y licencias
- **Seguro:** las aplicaciones son más seguras en contenedores y Docker proporciona las capacidades de aislamiento predeterminadas más sólidas de la industria

![docker](https://user-images.githubusercontent.com/45079819/77698192-f84c2380-6f8e-11ea-9466-887b11dad91e.jpg)