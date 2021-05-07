# Reto 1 - Máster: Conceptos de la Nube

## Generales

  - **Nube:** Es un paradigma que permite ofrecer servicios de computación a través de una red, que usualmente es internet.

  - **Disponibilidad:** Dependiendo del acuerdo de nivel de servicio que se elija, las aplicaciones basadas en la nube pueden proveer una experiencia de usuario continua, sin caídas aparentes, incluso cuando algo haya salido mal.

  - **Escalabilidad:** Es la propiedad deseable de un sistema, una red o un proceso, que indica su habilidad para reaccionar y adaptarse sin perder calidad, o bien manejar el crecimiento continuo de trabajo de manera fluida, o bien para estar preparado para hacerse más grande sin perder calidad en los servicios ofrecidos. Las aplicaciones en la nube pueden escalarse tanto vertical como horizontalmente.

  - **Escalamiento vertical:** Implica el incremento en las capacidades de cómputo, como la adición de procesadores o de memoria RAM.

  - **Escalamiento horizontal:** Implica el incremento de las capacidades paralelas, por ejemplo, añadiendo más máquinas virtuales.

  - **Eslasticidad:** Es posible configurar a las aplicaciones de manera auto-escalable, así, éstas serán capaces de configurarse para adaptarse a sus necesidades.

  - **Agilidad:** Es el despliegue y configuración ágil de nuevos recursos, a la misma velocidad que cambian los requerimientos de las aplicaciones.

  - **Geo-distribución:** Se pueden desplegar datos y aplicaciones a centros de datos regionales alrededor del planeta, así se asegura que los clientes siempre obtengan el mejor rendimiento en su región.

## Modelos de Servicio en la Nube

  - **Iaas:** Infraestructuras como Servicio, un proveedor proporciona a los usuarios acceso a recursos informáticos, tales como: servidores, almacenamiento  y redes.

  - **Paas:** Plataformas como Servicio, un proveedor proporciona a los usuarios acceso a un entorno en la que pueden alojar sus propias aplicaciones.

  - **Saas:** Software como Servicio, proporciona a los usuarios acceso a software que ya está instalado en el servidor. Por ejemplo Microsoft Office Online.

  - **Informática sin servidor:** Permite a los desarrolladores crear aplicaciones rápidamente sin la necesidad de administrar la infraestructura. Las arquitecturas sin servidor son muy escalables y controladas por eventos y solo usan reursos cuando se produce una función.

## Modelos de Despliegue en la Nube

  - **Nube Privada:** Los recursos computacionales son utilizados de forma exclusiva por un negocio u organización. Una nube privada puede estar ubicada físicamente en centros de datos de una organización, pero también pueden ser hospedadas por un proveedor de servicio ajeno a la organización.

  - **Nube Pública:** Los servicios son ofrecidos a todo el público de internet que quiera comprarlos. Los recursos de la nube, como lo son los servidores y el almacenamiento, son administrados y operados por un proveedor de servicios de terceros, y entregado a través de internet.

  - **Nube Híbrida:** Este entorno de cómputo combina la nube privada y la nube pública, de modo que es posible compartir datos y aplicaciones entre ambas.

## Gastos

  - **Gastos de Capital (CapEx):** Hacen referencia a la inversión previa de dinero en infraestructura física, que se podrá deducir a lo largo del tiempo. El costo previo de CapEx tiene un valor que disminuye con el tiempo.

  - **Gastos Operativos (OpEx):** Son dinero que se invierte en servicios o productos y se factura al instante. Este gasto se puede deducir el mismo año que se produce. No hay ningún costo previo, ya que se paga por un servicio o producto a medida que se usa.

## Microsoft Azure

  - **Hipervisor:** Emula todas las funciones de un equipo real y su cpu en una maquina virtual.

  - **Orquestador:** El orquestador es el responsable de administrar los recursos de la nube, tambien administra las respuestas a las solicitudes de los usuarios.

  - **Espacio aislado:** Es una suscripción temporal que permite crear recursos en Azure para la duración de un módulo de Learn.

  - **Recursos:** Los recursos son instancias de los servicios que se pueden crear, por ejemplo, maquinas virtuales.

  - **Grupos de recursos:** Son una combinación de recursos que actúan como un contenedor logico en el que se implementan recursos.

  - **Suscripciones:** Agrupa las cuentas de usuario y los recursos que se han creado. En las suscripciones existen limites en los recursos que se pueden crear y usar.

  - **Grupos de administración:** Ayudan a administrar el acceso, las directivas y el cumplimiento de varias suscripciones. Todas las suscripciones de un grupo de administración heredan automáticamente las condiciones que se aplican al grupo de administración. 

  - **Ciclo de vida:**
  La organización de los recursos por ciclo de vida puede ser util en entornos que no sean de producción, en los que puede probar un experimento y despues descartarlo. 

  - **Azure Resource Managaer:** Es un servicio de implementación y administración para Azure. Proporciona una capa de administración que le permite crear, actualizar y eliminar los recursos de la cuenta de Azure. 
  
  - **Zona de disponibilidad:** Son centros de datos separados fisicamente dentro de una region de Azure. Cada zona de disponibilidad tiene uno o varios centros de datos equipados con refrigeración, alimentación y redes independientes. Están conectadas con redes de fibra optica.

  - **Servicios de zona:** El recurso está anclado a una zona específica

  - **Servicios de redundancia de zona:** La plataforma se replica automáticamente entre zonas.
  