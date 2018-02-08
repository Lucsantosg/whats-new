---

 

copyright:

  years: 2015, 2018

lastupdated: "2018-01-19" 

---


{:shortdesc: .shortdesc} 
{:new_window: target="_blank"}

# Novedades de {{site.data.keyword.Bluemix_notm}}
{: #whatsnew}

Consulte información actualizada sobre las nuevas características y servicios disponibles en {{site.data.keyword.Bluemix}} para sacar el máximo provecho de {{site.data.keyword.Bluemix_notm}}. Las actualizaciones están organizadas en las siguientes categorías: [plataforma de {{site.data.keyword.Bluemix_notm}}](index.html#platform_category), [{{site.data.keyword.Bluemix_local_notm}} y {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal), [Compute](index.html#compute_category), y [Servicios](index.html#services_category).
{:shortdesc}

## Plataforma {{site.data.keyword.Bluemix_notm}}
{: #platform_category}

### Ya está disponible el Servicio de {{site.data.keyword.Bluemix_notm}} Foundry de la región EE.UU. este
Novedad desde: 15 de diciembre de 2017

Ya está disponible un nuevo centro de datos de EE.UU. este en Washington, DC. Se puede llegar a esta nueva región mediante el punto final `us-east.bluemix.net`. Para obtener detalles sobre los servicios disponibles para su adquisición en esta nueva región, consulte [Servicios por región](/docs/services/services_region.html#services_region).

### Soporte para recursos en la Unión Europea
Novedad desde: 14 de diciembre de 2017

Si los servicios y los centros de datos están ubicados en Europa, {{site.data.keyword.Bluemix_notm}} ofrecerá ahora funciones adicionales para proteger los datos en la Unión Europea. Puede solicitar que los equipos de éxito de clientes ubicados en Europa proporcionen soporte. Este soporte está disponible 24 horas al día, 7 días por semana. Consulte [Habilitación de la opción Soporte en la UE](/docs/pricing/eusupported.html#bill_eusupported) y [Solicitud de soporte para recursos en la Unión Europea](/docs/support/index.html#eusupported) para obtener más información.

### Retirada de soporte para TLS 1.0 y 1.1
Novedad desde: 28 de noviembre de 2017

El 1 de marzo de 2018, {{site.data.keyword.Bluemix_notm}} retirará el soporte para TLS 1.0 y TLS 1.1 en muchos de nuestros productos y servicios en la nube como parte de nuestro compromiso para ofrecer una nube que sea completamente segura y acorde con las mejores prácticas de la industria para la seguridad y la privacidad de los datos. Para obtener más información sobre cómo afecta este cambio y qué acciones deberá tomar, consulte [Retirada de soporte para TLS 1.0 y 1.1](/docs/troubleshoot/appsectls.html).

### Una nueva forma de organizar los recursos en su cuenta
Novedad desde: 16 de noviembre de 2017

Los grupos de recursos son una nueva forma de crear agrupaciones personalizables de los recursos de la cuenta, y el acceso al grupo y a los recursos dentro del mismo se gestionan utilizando Identity and Access Management (IAM). Todos los usuarios inician con un grupo de recursos predeterminado. Puede renombrar este grupo de recursos y añadir nuevas instancias de servicio al mismo a medida que los cree desde el catálogo. 

Para los usuarios con una cuenta de Pago según uso o de Suscripción, puede crear grupos de recursos adicionales para hacer que la gestión de la cuota y la visualización del uso de facturación para un conjunto de recursos sean más sencillas. También puede agrupar recursos para facilitarle la asignación de acceso a los usuarios a más de un servicio a la vez. Para obtener más información sobre cómo trabajar con grupos de recursos para su cuenta, consulte [Gestionar grupos de recursos](/docs/admin/resourcegroups.html#rgs).

### Actualizaciones para {{site.data.keyword.Bluemix_notm}} IAM
Novedad desde: 16 de noviembre de 2017

La introducción de [grupos de recursos](/docs/overview/resource-groups.html#whatis) dentro de la cuenta de {{site.data.keyword.Bluemix_notm}} ha abierto una nueva forma de asignar acceso. Se puede asignar acceso a los usuarios y a los ID de servicio a todos los servicios de un grupo de recursos permitiéndole asignar rápidamente acceso a más de un recurso a la vez. También puede personalizar el acceso para cada usuario o ID de servicio asignando acceso a solo algunos servicios dentro de un grupo de recursos, o elija solo asignar acceso a recursos individuales hasta el nivel de instancia de servicio.
 
Para obtener más información sobre las características que puede aprovechar utilizando IAM, consulte [¿Qué características proporciona IAM?](/docs/iam/index.html#features)

### Personalice la vista de su panel de control 
Novedad desde: 16 de noviembre de 2017

Puede ver y gestionar todos los recursos de su cuenta desde el panel de control de la consola de {{site.data.keyword.Bluemix_notm}}. Y ahora, puede establecer filtros para personalizar la vista. Por ejemplo, puede filtrar por grupo de recursos para ver los recursos específicos de un grupo de recursos. También puede filtrar por región o por espacio de Cloud Foundry. Para obtener más detalles, consulte [Gestión de recursos en el panel de control](/docs/overview/ui.html#dashboardview).


### Centro de soporte
Novedad desde: 2 de noviembre de 2017

Ahora tenemos el nuevo Centro de soporte, donde puede buscar información, publicar preguntas en nuestra comunidad de desarrolladores, y gestionar incidencias. Vaya a **Soporte > Centro de soporte** en la barra de menús de la consola de {{site.data.keyword.Bluemix_notm}}. 

### Introducción a IBM Cloud
Novedad desde: 31 de octubre de 2017

Bluemix es ahora IBM Cloud. Aparte de nuestro nuevo nombre, nada cambia. Puede seguir construyendo y ejecutando fácilmente las apps y los servicios como siempre. Consulte el [Blog de IBM Cloud](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") para obtener más detalles.

### Cuenta Lite
Novedad desde: 31 de octubre de 2017

Una cuenta Lite es nuestro nuevo tipo de cuenta que le da acceso para intentar seleccionar servicios de forma gratuita sin restricciones de tiempo. Esta nueva cuenta también incluye las características de eficiencia y de seguimiento de uso para ayudarle a gestionar mejor sus recursos. Para obtener más información sobre lo que está disponible, consulte [Tipos de cuentas](/docs/pricing/index.html#liteaccount).

### Característica de autenticación de aplicación de Identity and Access Management
Novedad desde: 6 de octubre de 2017

Identity and Access Management (IAM) ahora proporciona la capacidad de crear un ID de servicio, que puede pensar que es una identidad que se puede utilizar para las apps para autenticarlas con sus servicios de {{site.data.keyword.Bluemix_notm}}. En lugar de utilizar las credenciales de usuario individual, un ID de servicio puede crearse con una clave de API asociada y los permisos de acceso en forma de una política de servicio que se asigna al ID de servicio para controlar el nivel de acceso para cualquier aplicación que se autentica con ese ID.

Para obtener más información sobre los beneficios de esta característica y cómo empezar, consulte la [Introducción a los ID de servicio y a las claves de API de IAM de IBM Cloud](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo"). 

### Catálogo global de {{site.data.keyword.Bluemix_notm}} 
Novedad desde: 27 de julio de 2017

Expandiéndose en la última actualización de consola para gestionar sus regiones públicas desde una ubicación única en la consola, {{site.data.keyword.Bluemix_notm}} ahora tiene un catálogo global que hace que el proceso de selección y de despliegue de elementos que selecciona desde el catálogo sea un proceso más ágil. Independientemente de la región que haya seleccionado en la consola, ahora puede ver todos los servicios que están disponibles en todas las regiones públicas desde el catálogo. Una vez que seleccione un mosaico del catálogo, puede ver en qué regiones está disponible el servicio, y seleccionar dónde desea desplegarlo.

Para obtener más información sobre las últimas actualizaciones del catálogo, consulte [Un catálogo global de {{site.data.keyword.Bluemix_notm}} facilita la creación de cosas](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

### Actualizaciones de consola de {{site.data.keyword.Bluemix_notm}}
Novedad desde: 23 de mayo de 2017

Ahora puede gestionar sus regiones públicas desde una sola ubicación mediante la consola actualizada de {{site.data.keyword.Bluemix_notm}}. El selector de regiones ofrece acceso ágil a sus recursos, y entre otras mejoras se incluye una mayor disponibilidad y un rendimiento mejorado.

Para obtener más información sobre esta actualización, consulte [Nueva IU de Bluemix global para mayor disponibilidad y más](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

### Gestión de accesos e identidades
Novedad desde: 1 de mayo de 2017

Con las últimas actualizaciones y mejoras, los propietarios o los administradores de la cuenta de {{site.data.keyword.Bluemix_notm}} ahora pueden utilizar una nueva IU de control de acceso unificada para aprovechar las siguientes funciones:
 * Gestionar el acceso preciso de los usuarios a los servicios de Kubernetes y otros servicios a medida que adopten las nuevas características de control de acceso
 * Asignar políticas de servicio y roles de Cloud Foundry a usuarios dentro de sus organizaciones

Además, los usuarios de la plataforma de {{site.data.keyword.Bluemix_notm}} pueden crear, suprimir y listar claves de API asociadas con sus ID de usuario. Y los usuarios de la plataforma pueden utilizar dichas claves de API para autenticarse al utilizar API o CLI.

Por último, hemos mejorado nuestra capacidad de gestión de usuarios unificada para garantizar que en una cuenta IaaS-PaaS enlazada, los usuarios se gestionen de forma unificada sin necesidad de añadir usuarios por separado en el Portal de cliente de SoftLayer o en la consola de {{site.data.keyword.Bluemix_notm}}.

Para obtener más información sobre la actualización reciente, consulte la publicación de blog [Introducción a Identity and Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

### Cambios de diseño de navegación para documentos de {{site.data.keyword.Bluemix_notm}}
Novedad desde: 13 de abril de 2017

Con esta actualización de navegación, pensamos que comprenderá mejor cómo se organiza el contenido en nuestra documentación, y que podrá encontrar contenido relevante de forma más eficiente. Con menos capas anidadas de contenido, no tendrá que buscar demasiado para encontrar la documentación que necesita para tener éxito con {{site.data.keyword.Bluemix_notm}}.


## {{site.data.keyword.Bluemix_local_notm}} y {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### Actualizaciones de diciembre para la consola de administración
{: #decemberadminconsole}
Novedad desde: 14 de diciembre de 2017

Con las últimas actualizaciones y mejoras de diciembre, puede utilizar las siguientes nuevas características:

#### Suscribirse a notificaciones para el umbral de uso de CPU promedio

La CPU promedio se ha añadido como un tipo de umbral en las suscripciones de notificaciones. Ahora puede recibir notificaciones cuando el uso de la CPU (promedio en todos los DEA y Células de Diego) esté por encima o por debajo de un umbral determinado.

#### Control de acceso a los sistemas en nube en la Unión Europea 

Combinada con la nueva funcionalidad de la Unión Europea para dar soporte a los recursos de nube (a partir de Frankfurt), la consola de administración ahora tiene la capacidad de definir políticas para que el personal de IBM controle el acceso. Puede gestionar las políticas de control de acceso, ver solicitudes de acceso, realizar acciones en las solicitudes, y rastrear el historial.
  
#### Información ampliada en los informes de seguridad

Los informes de seguridad ahora incluyen nombres fáciles, además de los ID exclusivos para usuarios y organizaciones.

### Actualizaciones de agosto de la consola de administración
{: #augustadminconsole}
Novedad desde: 31 de agosto de 2017

Con las últimas actualizaciones y mejoras de agosto, puede utilizar las siguientes nuevas características:

#### Actualizaciones en las métricas de uso de servicio de {{site.data.keyword.cloudant_short_notm}}

  * El cálculo de las métricas de uso de {{site.data.keyword.cloudant_short_notm}} se ha actualizado para reflejar la cantidad total de GB utilizados y disponibles en todos los nodos en un clúster de {{site.data.keyword.cloudant_short_notm}}. Normalmente, un clúster de {{site.data.keyword.cloudant_short_notm}} contiene 3 nodos, y un documento de la base de datos se replica en todos los nodos en el clúster la obtener alta disponibilidad y recuperación tras desastre. Con las actualizaciones de agosto, la métrica de capacidad en el marcador de {{site.data.keyword.cloudant_short_notm}} (disponible en la vista _Uso de recursos > Servicios_) indica el espacio en todos los nodos del clúster. Por ejemplo, si un único clúster de {{site.data.keyword.cloudant_short_notm}} contiene 3 nodos, cada uno de ellos con 1000 GB de capacidad, el límite de capacidad será de 3000 GB. Si se han utilizado 1500 GB de dicha capacidad, la métrica de uso de {{site.data.keyword.cloudant_short_notm}} será 50%.

#### Actualizaciones en la planificación de actualizaciones de mantenimiento
  
  * En {{site.data.keyword.Bluemix_dedicated_notm}}, los clientes pueden gestionar las fechas y las horas en que están disponibles sus entornos dedicados para el despliegue de actualizaciones del sistema. Los clientes pueden definir períodos de disponibilidad que representan fechas y horas en que las actualizaciones de mantenimiento pueden y no pueden desplegarse en su entorno Dedicado. En la actualización de agosto, _Períodos de actualización disponibles_ ha cambiado su nombre a _Períodos de actualización_, y _Períodos de actualización no disponibles_ ha cambiado su nombre a _Períodos de no disponibilidad_. Más allá de los cambios en la terminología, los clientes ahora tienen más flexibilidad y margen para definir fechas de no disponibilidad (no disponibles). Una vez solicitadas, las fechas de no disponibilidad necesitarán la aprobación de IBM, y el tiempo que se tarda en obtener la aprobación puede variar. Al aprobarse las fechas de no disponibilidad solicitadas, IBM cancelará todas las actualizaciones existentes que actualmente estén planificadas durante el período de no disponibilidad. IBM también creará nuevos registros para estas actualizaciones y las planificará fuera de las fechas de no disponibilidad aprobadas.
  
Consulte el [vídeo de demostración](https://bit.ly/2eCQNvu){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") para obtener más información.

### Actualizaciones de julio para la consola de administración
{: #julyadminconsole}
Novedad desde: 31 de julio de 2017

Con las últimas actualizaciones y mejoras de julio, puede utilizar las siguientes nuevas características:

#### Actualizaciones de las prestaciones del historial del uso de recursos

  * En la actualización anterior (junio), la vista Historial para el uso de la memoria y de disco ha introducido la visualización de los datos de uso de las últimas 48 horas, 30 días y 5 meses. En esta última actualización de julio, la funcionalidad del historial de uso de recursos se ha ampliado para permitir la personalización del intervalo de tiempo para el que se muestran los datos de uso de recursos. Permanecerán las vistas de las horas, los días y los meses, pero los usuarios ahora pueden especificar un día/hora de inicio y la duración para la que se mostrarán las métricas de uso de memoria y de disco (por ejemplo, mostrando el uso de memoria para 15 días, a partir del 1 de julio de 2017).
  * Se ha introducido un nuevo mandato de CLI para visualizar el historial de métricas de recursos en la CLI. Los parámetros del mandato, así como los ejemplos de uso, se pueden encontrar escribiendo lo siguiente: `_cf ba resource-metrics-history -help_`
 
Consulte el [vídeo de demostración](https://youtu.be/QBij0jB5qAk){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") para obtener más información.

### Actualizaciones de junio para la consola de administración
{: #mayadminconsole}
Novedad desde: 26 de junio de 2017

Con las últimas actualizaciones y mejoras de junio, puede utilizar las siguientes nuevas características:

#### Actualizaciones de la Página de uso de recursos

  * Recursos del sistema
    * La vista Historial para la memoria y el disco se ha actualizado para mostrar datos de más de 48 horas, 30 días and 5 meses
    * Se proporciona un enlace Más información, que muestra cómo se utiliza la API de métricas de la consola de administración para generar las vistas de Historial 
  * Aplicaciones
    * Proporciona información de uso para todas las aplicaciones del entorno
    * Ordenar por nombre de aplicación, memoria física, memoria reservada, disco físico, disco reservado, CPU física o Nombre de organización 
    * La búsqueda se proporciona para filtrar resultados por nombre de aplicación y Nombre de organización
    * Se proporciona un enlace Más información, que muestra cómo se utiliza la API de métricas de la consola de administración para generar la vista Aplicaciones
 
Consulte [Uso de recursos](/docs/hybrid/index.html#resourceusage) para obtener más información.

#### Actualizaciones de API for Metrics

  * Se han añadido estadísticas de entorno, que proporcionan promedios por día o mes para el consumo de memoria y de disco
  
Consulte [API for Metrics](/docs/hybrid/index.html#envappmetricsapi) para obtener más información.


### Actualizaciones de mayo para la consola de administración
{: #mayadminconsole}
Novedad desde: 30 de mayo de 2017

Con las últimas actualizaciones y mejoras de mayo, puede utilizar las siguientes nuevas características:

 * Mejoras en la página Estado, incluidos diagnósticos más precisos sobre incidentes que afectan a la plataforma y a los tiempos de ejecución de {{site.data.keyword.Bluemix_notm}}.
 * Mejoras en la página Informes y registros de seguridad:
   * Los informes se visualizan ahora en un formato de tabla, simplificando la exploración y la búsqueda de informes, incluida la capacidad de ordenar por categoría de informe, nombre de archivo o fecha de creación. 
   * Filtrado mejorado, incluido el filtrado simultáneo de varias categorías 
   * Modalidad de pantalla completa para visualizar el contenido de un informe
   * Capacidad de suprimir informes para los usuarios de administración con permiso "escritura en informes"
   * Visualización más rápida de listas de informes, cargando progresivamente bajo demanda a través de desplazamiento continuo, lo que da lugar a un mejor rendimiento en general.
 * Los informes de seguridad se pueden solicitar bajo demanda dentro de un rango de tiempo de hasta una semana y que se inicia un máximo de 3 meses antes, desde el momento de la solicitud. Tenga en cuenta que se necesita alguna configuración específica del entorno antes de que esta capacidad esté disponible para los usuarios administrativos. Los usuarios administrativos necesitarán permiso de "escritura en informes" para esta capacidad.

### Actualizaciones de abril para la consola de administración
{: #apriladminconsole}
Novedad desde: 2 de mayo de 2017

Con las últimas actualizaciones y mejoras de abril, puede utilizar las siguientes nuevas características:

 * Apps de estado recientemente diseñadas para entornos Dedicados y Locales de {{site.data.keyword.Bluemix_notm}}. Puede buscar rápidamente por nombre de componente o fecha de publicación. También puede conmutar entre la vista de publicaciones de estado del componente y las notificaciones específicas de su entorno. Consulte la publicación de blog [Nueva página de estado de {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") para obtener más información.
 * Datos de uso de servicio para seleccionar servicios desde el mosaico Uso de recursos. Consulte [Detalles de utilización del servicio](/docs/hybrid/index.html#servicesresourceusage) para obtener más información sobre qué servicios están soportados y qué puede esperar de la vista nueva.

## Compute
{: #compute_category}

### Actualizaciones más recientes para los paquetes de compilación

Visite las páginas siguientes para obtener una lista cumulativa de las actualizaciones más recientes:

* [Actualizaciones más recientes para el paquete de compilación de SDK for Nodejs](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Actualizaciones más recientes para el paquete de compilación de Liberty](/docs/runtimes/liberty/updates.html#latest_updates)
* [Actualizaciones más recientes para el paquete de compilación de ASP.NET Core](/docs/runtimes/dotnet/updates.html#latest_updates)
* [Actualizaciones más recientes para el paquete de compilación de IBM XPages for {{site.data.keyword.Bluemix_notm}}](/docs/starters/xpages/index.html#updates)

### Actualizaciones más recientes para {{site.data.keyword.containerlong_notm}}

{{site.data.keyword.containerlong_notm}} lanzó su arquitectura de Kubernetes en mayo de 2017. La arquitectura anterior para los grupos de contenedores únicos y escalables está ahora [completamente en desuso desde el 5 de diciembre de 2017](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").  

[Consulte la documentación para obtener información sobre cómo empezar con el entorno nativo de Kubernetes en {{site.data.keyword.Bluemix_notm}}](/docs/containers/container_index.html). Si tiene preguntas, puede publicarlas en Slack en https://ibm-container-service.slack.com/.

### Nuevo paquete de compilación de Liberty for Java v3.11
Novedad desde: 17 de julio de 2017

El paquete de compilación de Liberty v3.11 proporciona una nueva versión de tiempo de ejecución mensual de Liberty y contiene otras mejoras. La versión de tiempo de ejecución mensual de Liberty se ha actualizado al release [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/). El JDK de IBM se ha actualizado a las versiones 8.0.4.7 y 7.1.4.5. El paquete de compilación también proporciona versiones actualizadas del programa de utilidad de gestión de App Management y del agente de Auto-Scaling. La biblioteca predeterminada Cloudant es ahora el [java-cloudant](https://github.com/cloudant/java-cloudant) oficial, la [biblioteca Ektorp](https://github.com/helun/Ektorp) aún está disponible como opción; para obtener detalles sobre este cambio, consulte la [publicación de blog](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/). La proporción de tamaño de almacenamiento dinámico predeterminada ahora es del 50% cuando la aplicación tiene menos de 512 MB de memoria, si tiene más de 512 MB seguirá siendo del 75%. Ahora se genera un nuevo registro de tareas de transferencia, que facilita la depuración de errores de transferencia. Consulte la documentación de las [últimas actualizaciones](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html) para obtener información adicional.

### Nuevo paquete de compilación de Liberty for Java v3.10
Novedad desde: 12 de junio de 2017

El paquete de compilación de Liberty v3.10 proporciona nuevas versiones de tiempo de ejecución de Liberty trimestrales y mensuales y contiene otras mejoras. La versión de tiempo de ejecución de Liberty predeterminada se ha actualizado a 17.0.0.2. La versión de tiempo de ejecución de Liberty mensual se ha actualizado al release [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo"). El paquete de compilación también proporciona versiones actualizadas del programa de utilidad Gestión de apps y de Extreme Scale Client. Consulte la documentación de las [últimas actualizaciones](/docs/runtimes/liberty/updates.html) para obtener información adicional.

### Nuevo paquete de compilación de SDK for Node.js v3.12
Novedad desde: 16 de mayo de 2017

El paquete de compilación SDK for Node.js v3.12 proporciona las versiones de IBM SDK for Node.js 0.12.17, 0.12.18, 4.8.0, 4.8.2, 6.10.0 y 6.10.2. El valor predeterminado se ha cambiado ahora del 4.x más reciente al 6.x más reciente, de modo que actualmente es 6.10.2. Puesto que es un cambio de versión principal, esto podría afectar a las apps que dependen del valor predeterminado. Consulte [Soporte a largo plazo de versiones de Node.js y el paquete de compilación de SDK for Node.js](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") para obtener más información sobre cómo evitar problemas.

Además de los nuevos tiempos de ejecución, este release contiene un arreglo de error de paquete de compilación para un problema con el controlador del Centro de salud de App Management y las versiones 6.9.5 y 6.10.0 de Node.js.

### Nuevo paquete de compilación de Liberty for Java v3.9
Novedad desde: 27 de abril de 2017

El paquete de compilación de Liberty v3.9 proporciona una nueva versión de tiempo de ejecución mensual de Liberty y contiene otras mejoras. La versión de tiempo de ejecución predeterminada de Liberty se ha actualizado para incluir los iFixes PI77770, PI77605, IFPI77438 e IFPI79275. La versión de tiempo de ejecución mensual de Liberty se ha actualizado al release [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo"). El cálculo de memoria se ha trasladado del proceso de transferencia al proceso de inicio, lo que permite cambios de memoria de almacenamiento dinámico más sencillos con el reinicio de una aplicación. El paquete de compilación también proporciona versiones actualizadas del agente del servicio de Auto-Scaling, y Extreme Scale Client. Consulte la documentación de las [últimas actualizaciones](/docs/runtimes/liberty/updates.html) para obtener información adicional.

## Servicios
{: #services_category}

### {{site.data.keyword.containershort_notm}}: soporte de Kubernetes 1.8.x
Novedad desde: 19 de enero de 2018

Desde noviembre de 2017, {{site.data.keyword.containershort_notm}} ha dado soporte a Kubernetes `1.8.x`. Nos complace anunciar que nuestra versión predeterminada de Kubernetes es ahora `1.8.6`. En el futuro cercano, proporcionaremos soporte para `1.9.x`.

### Watson Discovery Visual Insights
Novedad desde: 30 de noviembre de 2017

Explore visualmente conexiones basadas en la comprensión de {{site.data.keyword.discoveryshort}} de elementos semánticos detectados en texto, como entidades, relaciones, conceptos, etc.

Comience a explorar las noticias del mundo con la recopilación de Noticias de {{site.data.keyword.discoveryshort}} predefinida. O bien, explore sus propias colecciones de documentos de {{site.data.keyword.discoveryshort}}. Tan solo inicie sesión con sus credenciales de {{site.data.keyword.Bluemix_notm}}. Consulte [Visual Insights experimental](https://visual-insights.bluemix.net){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") para obtener más información.

### Nuevo servicio de IBM Cloud Managed Database Server Beta
Novedad desde: 30 de noviembre de 2017

Con el nuevo servicio de IBM Cloud Managed Database Server Beta, puede crear una instancia de Microsoft SQL Server en {{site.data.keyword.Bluemix_notm}}. Puede utilizar esta instancia de SQL Server como utilizaría cualquier sistema de gestión de bases de datos, pero sin el esfuerzo y el gasto de configuración de hardware o de instalación y mantenimiento de software.

Este servicio ofrece las características siguientes:
* Elección de las versiones de Microsoft SQL Server 2012, 2014, y 2016 ediciones Enterprise y Standard
* Varias configuraciones o tamaños predefinidos para satisfacer sus requisitos de carga de trabajo de aplicación
* Totalmente gestionado por IBM, incluida la supervisión, el parcheado, la copia de seguridad y la creación de informes

Para empezar, consulte [Iniciación a IBM Cloud Managed Database Server](/docs/services/managed-sql-server/getting-started.html).

### Novedades en {{site.data.keyword.mobilepushshort}}
Novedad desde: 26 de octubre de 2017

Hemos hecho varias mejoras para el servicio de {{site.data.keyword.mobilepushshort}} en los últimos meses. El servicio ya está disponible en la región de Frankfurt junto con Dallas, Londres y Sídney. A continuación ofrecemos los detalles de las mejoras:

#### Supervisión
Ahora puede rastrear el rendimiento de las notificaciones push para periodos de tiempo específicos, rastrear el número de notificaciones enviadas y el número total de dispositivos registrados. También puede registrar ganchos (hooks) para estar informado de todos los sucesos del ciclo de vida de una notificación. Se pueden encontrar más detalles en los siguientes enlaces de documentación y publicación de blog:
* [Notificaciones de supervisión](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [Recepción de alertas sobre sucesos de webhook](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [Notificaciones de supervisión en IBM Push](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")

#### Notificaciones web
Ahora damos soporte al navegador web Safari para notificaciones web junto con Firefox, Chrome, apps y extensiones de Chrome. Los SDK de web y la información relacionada pueden encontrarse en [SDK web de notificaciones push de IBM Bluemix](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

#### Notificaciones más recientes de Android e iOS
Tenemos soporte de divisas para las notificaciones de iOS 11. También hemos incorporado varias mejoras relacionadas con notificaciones nuevas de iOS10 y Android N.

* iOS10 – Notificaciones, imágenes, botones y mapas de Rich Media, en notificaciones interactivas, soporte de serie localizado
* Android N – Notificaciones expandibles, notificaciones interactivas y silenciosas, valores de luz LED

Se pueden encontrar detalles adicionales en la documentación de [Notificaciones de Rich Media](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications), en la documentación de [Notificaciones interactivas y silenciosas](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications), y en la documentación de [Habilitación de notificaciones push avanzadas](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications).

#### Soporte de APNS HTTP/2
Apple ha introducido el soporte para el protocolo HTTP para Apple Notifications. El servicio de {{site.data.keyword.mobilepushshort}} ahora da soporte al protocolo HTTP/2. Con este soporte, las cargas útiles de notificación pueden ser de 4 KB con mayor rendimiento y proporciona la característica de comentarios instantánea. El soporte para Certificado universal permite a la app conectarse a entornos de recinto de pruebas y de producción.

#### Nuevo plan Lite 
El plan Lite para el servicio de {{site.data.keyword.mobilepushshort}} proporciona la capacidad de enviar 100.000 notificaciones gratuitas cada mes. Para obtener más información, consulte la publicación de blog [Plan Lite para el servicio de notificaciones push en Bluemix](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").



### Novedades en Mobile Analytics
Novedad desde: 26 de octubre de 2017

Hemos realizado mejoras para el servicio de {{site.data.keyword.mobileanalytics_short}} en los últimos meses. El servicio ya está disponible en las regiones de Frankfurt y Sídney junto con Dallas y Londres. A continuación ofrecemos los detalles de las mejoras:

#### Soporte de SDK web
{{site.data.keyword.mobileanalytics_short}} es ahora el servicio de canal de Omni con la adición de soporte para análisis de app web. Se pueden encontrar más detalles en [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

#### Integración con el servicio de {{site.data.keyword.mobilefoundation_short}}
El servicio de {{site.data.keyword.mobilefoundation_short}} aprovecha ahora el servicio de {{site.data.keyword.mobileanalytics_short}} para el análisis de app, usuario y rendimiento. Los usuarios pueden aprovechar la exportación a la opción de almacén de DB2 para crear análisis de adaptador y diagramas personalizados. Puede encontrar detalles adicionales en las siguientes publicaciones de blog:

* [Integración de Mobile Foundation Service con Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")
* [Creación de diagramas personalizados utilizando el servicio de IBM Bluemix Mobile Analytics y de IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")
* [Creación de diagramas para el análisis de Adaptador mediante los servicios de IBM Bluemix Mobile Analytics y de IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")

#### El contenedor modelo de {{site.data.keyword.mobilefirst_notm}} ahora incluye {{site.data.keyword.mobileanalytics_short}}
Mobile Services Boilerplate es una plantilla que proporciona un conjunto de servicios móviles para que los usuarios empiecen rápidamente. El servicio de {{site.data.keyword.mobileanalytics_short}} ahora forma parte del contenedor modelo disponible en el [catálogo](https://console.bluemix.net/catalog/starters/mobilefirst-services-starter){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").


### Actualizaciones de {{site.data.keyword.streaminganalyticsshort}}
Novedad desde: 20 de octubre de 2017

* IBM Streams Runner for Apache Beam: Ahora puede desarrollar aplicaciones de Beam localmente en su entorno de desarrollo de Streams y enviar estas apps al servicio de {{site.data.keyword.streaminganalyticsshort}} en {{site.data.keyword.Bluemix_notm}}. IBM Streams Runner for Apache Beam ejecuta conductos de Beam en un entorno de Streams. Una aplicación de Beam que se inicia con Streams Runner se traduce a un archivo SAB (Streams Application Bundle) que podrá desplegar en {{site.data.keyword.streaminganalyticsshort}}. Consulte [IBM Streams Runner for Apache Beam in Streaming Analytics](/docs/services/StreamingAnalytics/gs_beamrunner.html) para obtener más detalles.
* Puede encontrar información de los archivos de registro aún más rápido. La consola se ha actualizado para mejorar la visualización de los gráficos de aplicaciones para las topologías de Python o Java. Consulte [Mejoras en la consola](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

### IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
Novedad desde: 12 de octubre de 2017

IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services es una oferta experimental que le permite medir la experiencia de cliente, proporcionando una plataforma para crear compromisos selectivos en varios sectores del público. El servicio de App Launch proporciona información sobre las preferencias de cliente y los puntos débiles como resultado de los compromisos, y ayuda a personalizar la app para mejorar la experiencia de cliente.

Los propietarios de la app ahora pueden acelerar la entrega de innovaciones para apps móviles evitando las complejidades del ciclo de release. El servicio de App Launch permite a los propietarios de la app lanzar características en apps móviles rápidamente y medir el impacto controlando al público objetivo. El propietario de la app puede trabajar con el desarrollador de la app para definir los indicadores de rendimiento claves para las características, para medir el impacto y tomar decisiones de implantación y de retrotracción de características basadas en información en tiempo real. El servicio también proporciona la capacidad de probar varias variantes de características de aplicación, componentes de la interfaz de usuario y mensajes, y de tomar decisiones basadas en la información.

Para obtener más información, consulte la [Guía de aprendizaje de iniciación](/docs/services/app-launch/index.html#gettingstartedtemplate).

### Actualizaciones a {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}}
Novedad desde: 4 de octubre de 2017

Hay disponibles una nueva función de personalización y nuevos modelos de idiomas para el usuario mediante {{site.data.keyword.relationshipextractionshort}}. Los nuevos idiomas de soporte son el holandés, el coreano y el chino simplificado para WKS.

### Actualización del clúster de {{site.data.keyword.containerlong_notm}}
Novedad desde: 20 de septiembre de 2017

Ahora puede actualizar sus clústeres a la última versión disponible de Kubernetes en {{site.data.keyword.Bluemix_notm}}. Mediante la GUI o la CLI, actualice el maestro y los nodos de trabajador de Kubernetes a Kubernetes 1.7 y aproveche las nuevas características y parches.

Para obtener más información, consulte [Kubernetes 1.7 disponible en {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

### Nuevo IBM Voice Agent con servicio experimental de Watson
Novedad desde: 15 de septiembre de 2017

Con el nuevo servicio experimental de {{site.data.keyword.iva_full}}, puede crear un agente de voz cognitiva basado en servicios de Watson que los clientes pueden llamar y con el que pueden hablar por teléfono. Con la inteligencia artificial de Watson como eje central, el agente de voz puede comunicarse de forma conversacional, manejando interacciones complejas y resolviendo las llamadas de clientes dentro del agente de voz.

{{site.data.keyword.iva_short}} conecta y coordina sin interrupciones los servicios de {{site.data.keyword.speechtotextshort}}, {{site.data.keyword.conversationshort}} y {{site.data.keyword.texttospeechshort}} de Watson para simular la conversación de lenguaje natural. Cada agente de voz escala automáticamente para manejar varias llamadas a la vez. En este release experimental, puede personalizar el agente de voz utilizando las siguientes características principales:

* Importe el diálogo de ejemplo de {{site.data.keyword.conversationshort}} para empezar y, a continuación, cree su propio diálogo para satisfacer las necesidades de su empresa.
* Programe el comportamiento del agente de voz desde el servicio de {{site.data.keyword.conversationshort}} utilizando las API. Controle todo, desde el comportamiento invasivo hasta colgar la llamada para cualquier nodo del diálogo.
* Cree y gestione fácilmente varios agentes de voz si desea conectar distintos números de teléfono a agentes cognitivos especializados para distintos temas.
* Expanda las prestaciones del servicio conectando un motor de orquestación de servicios (SOE) para poder utilizar API de terceros. Por ejemplo, el SOE puede escuchar desencadenantes desde el servicio de {{site.data.keyword.conversationshort}} y, a continuación, utilizar las API proporcionadas para buscar información en sistemas anteriores o para proporcionar otros análisis.

Para empezar, consulte la documentación de [Iniciación a {{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html).


### Actualización del servicio de {{site.data.keyword.streaminganalyticsshort}}: La consola incluye formas nuevas de detección de problemas en sus aplicaciones
Novedad desde: 14 de agosto de 2017
 
Para las aplicaciones de Python y Java, se mostrará la ubicación del archivo de origen en función de las anotaciones de @spl_note. 
 
Para obtener detalles, consulte [Últimas mejoras en {{site.data.keyword.streaminganalyticsshort}}](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

### IBM Cloud Monitoring ahora está disponible también en la región Reino Unido
Novedad desde: 1 de agosto de 2017

Utilice el servicio de {{site.data.keyword.monitoringlong}} para ampliar las prestaciones de recopilación, de retención y de análisis en {{site.data.keyword.Bluemix_notm}} cuando trabaje con métricas. 

* Alerta en acción{{site.data.keyword.monitoringlong}} ofrece una API que se puede utilizar para establecer umbrales de rendimiento y para recibir notificaciones cuando se rebasen dichos umbrales. Defina reglas de alerta para una única instancia de servicio o de app, y reglas de alerta que informen sobre un conjunto de instancias. Cuando se active una alerta, reciba una notificación a través de un correo electrónico, un suceso de PagerDuty, una notificación de webhook o cualquier combinación de las tres opciones.

* Añadir métricas personalizadas.El plan premium de {{site.data.keyword.monitoringlong}} ofrece API que puede utilizar para añadir métricas empresariales y de aplicación relevantes a los datos de supervisión de la nube. También puede utilizarlas para enviar datos de métricas desde fuera de {{site.data.keyword.IBM_notm}} Cloud en el servicio de {{site.data.keyword.monitoringlong}}.

* Cree paneles control reutilizables y haga que sean interactivos.Grafana alojado de {{site.data.keyword.monitoringlong}} proporciona soporte para crear paneles de control personalizados con un gran abanico de opciones de visualización.  Haga que los paneles de control sean dinámicos con plantillas utilizando consultas de métricas con variables.

* Acceda al servicio mediante el catálogo de {{site.data.keyword.Bluemix_notm}}.{{site.data.keyword.monitoringlong}} está disponible como un mosaico de servicio en la sección DevOps del catálogo de {{site.data.keyword.Bluemix_notm}}.  Para el servicio de {{site.data.keyword.containershort}} con contenedores únicos y de grupo, puede acceder al servicio desde la IU de {{site.data.keyword.Bluemix_notm}}.

* Elija el plan de servicio que se adapte a sus necesidades.Puede elegir el plan de servicio Lite o el plan de servicio Premium para cubrir sus necesidades de uso. El plan Lite ofrece recopilación de métricas a la vez por minuto, retención durante 15 días, y alertas complementarias. Como alternativa, puede seleccionar el plan Premium para permitir un mayor consumo, una retención de métricas más larga, y para obtener acceso a las API de servicio, por ejemplo, para enviar o recuperar métricas desde el servicio de {{site.data.keyword.monitoringlong}}. {{site.data.keyword.monitoringlong}} ofrece la recopilación de métricas a la vez por minuto.  El plan Lite retiene métricas a resolución completa durante 15 días. El plan Premium retiene métricas a resolución completa durante 45 días.

El servicio existente de {{site.data.keyword.monitoringshort}} ha recopilado métricas en frecuencias definidas por el servicio a partir de 30 segundos, y resumidas en frecuencias de 1 hora a lo largo del tiempo. {{site.data.keyword.monitoringlong}} ahora ofrece recopilación de resolución completa en 1 minuto. El plan Lite conserva métricas durante 15 días. El plan Premium conserva métricas durante 45 días.

Para obtener más información sobre el servicio de {{site.data.keyword.monitoringlong}}, consulte [la documentación de Iniciación a la supervisión](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) o [IBM Cloud Monitoring – Renovación de servicio con nuevas características![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).


### IBM Cloud Log Analysis ahora está disponible en la región EE.UU. sur
Novedad desde: 31 de julio de 2017

El servicio de {{site.data.keyword.loganalysisfull}} proporciona los servicios de recopilación y de búsqueda de registros para la plataforma de {{site.data.keyword.Bluemix_notm}}, recopilando automáticamente los datos de servicios de {{site.data.keyword.Bluemix_notm}} y de aplicaciones desde los servicios de selección de {{site.data.keyword.Bluemix_notm}}. Utilice el servicio de {{site.data.keyword.loganalysisshort}} para:

* Conservar registros tanto tiempo como desee.  

    Los registros se almacenan en el almacenamiento de IBM Cloud. Puede descargar registros cuando los necesite.
	
* Gestionar los registros retenidos y enviar datos de registro desde fuera de {{site.data.keyword.IBM_notm}} Cloud mediante la API nueva.

* Elija la cantidad de registros que puede buscar por día.   

    Hay diferentes planes disponibles que puede utilizar para buscar hasta 500 MB, 2 GB, 5 GB y 10 GB de registros por día.

* Cree paneles control reutilizables y haga que sean interactivos. 

    Kibana alojado de {{site.data.keyword.loganalysisshort}} proporciona soporte para crear paneles de control personalizados.

* Acceda al servicio mediante el catálogo de {{site.data.keyword.Bluemix_notm}}.  

    Para el servicio de {{site.data.keyword.loganalysisshort}} con contenedores únicos y grupos, y los servicios de {{site.data.keyword.IBM_notm}} Cloud Foundry, puede acceder al servicio desde la IU de {{site.data.keyword.Bluemix_notm}}.

Para obtener más información sobre el servicio de {{site.data.keyword.loganalysisshort}}, consulte [Iniciación a {{site.data.keyword.loganalysisfull}}](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis) y la [Visión general de {{site.data.keyword.loganalysisshort}}](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov).

### Se ha cambiado el nombre de IBM dashDB for Analytics
Novedad desde: 18 de julio de 2017

La tabla siguiente resume el nombre nuevo:

| Nombre anterior               | Nombre nuevo                   | Fecha efectiva |
|-----------------------------|----------------------------|----------------|
| IBM dashDB for Analytics    | IBM Db2 Warehouse on Cloud | 18 de julio de 2017  |
{: caption="Tabla 1. Cambio de nombre de servicio" caption-side="top"}
 
Para ver una lista acumulativa de actualizaciones para Db2 Warehouse on Cloud y Db2 on Cloud, consulte: [Novedades en Db2 Warehouse on Cloud y Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo"). 

### IBM Cloud Monitoring ahora está disponible en la región EE.UU. sur
Novedad desde: 17 de julio de 2017

Utilice el servicio de {{site.data.keyword.monitoringlong}} para ampliar las prestaciones de recopilación, de retención y de análisis en {{site.data.keyword.Bluemix_notm}} cuando trabaje con métricas. 

* Alerta en acción{{site.data.keyword.monitoringlong}} ofrece una API que se puede utilizar para establecer umbrales de rendimiento y para recibir notificaciones cuando se rebasen dichos umbrales. Defina reglas de alerta para una única instancia de servicio o de app, y reglas de alerta que informen sobre un conjunto de instancias. Cuando se active una alerta, reciba una notificación a través de un correo electrónico, un suceso de PagerDuty, una notificación de webhook o cualquier combinación de las tres opciones.

* Añadir métricas personalizadas.El plan premium de {{site.data.keyword.monitoringlong}} ofrece API que puede utilizar para añadir métricas empresariales y de aplicación relevantes a los datos de supervisión de la nube. También puede utilizarlas para enviar datos de métricas desde fuera de {{site.data.keyword.IBM_notm}} Cloud en el servicio de {{site.data.keyword.monitoringlong}}.

* Cree paneles control reutilizables y haga que sean interactivos.Grafana alojado de {{site.data.keyword.monitoringlong}} proporciona soporte para crear paneles de control personalizados con un gran abanico de opciones de visualización.  Haga que los paneles de control sean dinámicos con plantillas utilizando consultas de métricas con variables.

* Acceda al servicio mediante el catálogo de {{site.data.keyword.Bluemix_notm}}.{{site.data.keyword.monitoringlong}} está disponible como un mosaico de servicio en la sección DevOps del catálogo de {{site.data.keyword.Bluemix_notm}}.  Para el servicio de {{site.data.keyword.containershort}} con contenedores únicos y de grupo, puede acceder al servicio desde la IU de {{site.data.keyword.Bluemix_notm}}.

* Elija el plan de servicio que se adapte a sus necesidades.Puede elegir el plan de servicio Lite o el plan de servicio Premium para cubrir sus necesidades de uso. El plan Lite ofrece recopilación de métricas a la vez por minuto, retención durante 15 días, y alertas complementarias. Como alternativa, puede seleccionar el plan Premium para permitir un mayor consumo, una retención de métricas más larga, y para obtener acceso a las API de servicio, por ejemplo, para enviar o recuperar métricas desde el servicio de {{site.data.keyword.monitoringlong}}. {{site.data.keyword.monitoringlong}} ofrece la recopilación de métricas a la vez por minuto.  El plan Lite retiene métricas a resolución completa durante 15 días. El plan Premium retiene métricas a resolución completa durante 45 días.

El servicio existente de {{site.data.keyword.monitoringshort}} ha recopilado métricas en frecuencias definidas por el servicio a partir de 30 segundos, y resumidas en frecuencias de 1 hora a lo largo del tiempo. {{site.data.keyword.monitoringlong}} ahora ofrece recopilación de resolución completa en 1 minuto. El plan Lite conserva métricas durante 15 días. El plan Premium conserva métricas durante 45 días.

Para obtener más información sobre el servicio de {{site.data.keyword.monitoringlong}}, consulte [la documentación de Iniciación a la supervisión](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) o [IBM Cloud Monitoring – Renovación de servicio con nuevas características![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).

### Actualización de {{site.data.keyword.contdelivery_short}}
Novedad desde: 11 de julio de 2017

Entre las ventajas de la actualización se incluyen los arreglos de errores, las mejoras de rendimiento y las mejoras en la experiencia del usuario. Entre las mejoras destacables se incluyen, si no están ya presentes en su entorno:
<ul>
<li>Arreglos y mejoras en la internacionalización y la accesibilidad.</li>
<li>Control de acceso a la cadena de herramientas, disponible desde un separador Gestionar de la cadena de herramientas.</li>
<li>Nuevas integraciones de herramientas en el catálogo de herramientas de Continuous Delivery.</li>
<li>Agrupación mejorada de varios espacios de trabajo en el IDE web de Orion.</li>
<li>Soporte para varios separadores del editor en el IDE web de Orion.</li>
<li>Soporte para temas de IU en el IDE web de Orion.</li>
</ul>

### {{site.data.keyword.uccr_short}} beta 
Novedad desde: 23 de junio de 2017

{{site.data.keyword.uccr_short}} es una solución de gestión de releases a escala empresarial que da soporte a las herramientas de desarrollo tanto nativas de la nube como locales.

La versión beta de {{site.data.keyword.uccr_short}} proporciona las siguientes características principales:
* Utilizar releases para gestionar varios planes y sucesos de despliegue, y para colaborar en los esfuerzos de release de varios equipos.
* Crear sucesos para la actividad relacionada con los releases y gestionarlos con el calendario.
* Importar sus propios sucesos y releases.
* Personalizar los sucesos de calendario para que se ajusten a su organización.
* Utilizar las tareas de correo electrónico y de tipo Slack para las notificaciones del release.

### dashDB for Transactions ha cambiado su nombre a {{site.data.keyword.DB2_on_Cloud_short}}
Novedad desde: 14 de junio de 2017

IBM {{site.data.keyword.DB2OnCloud_short}} es el nombre nuevo para dashDB for Transactions. Como parte de este cambio de nombre, el servicio autogestionado del anterior IBM {{site.data.keyword.DB2OnCloud_short}} cambiará su nombre a IBM Db2 Hosted. En este momento, solo se actualizarán los nombres de visualización, por lo que cualquier API o interfaz de línea de mandatos permanecerá sin cambios.

### Actualizaciones de {{site.data.keyword.sparks}}: el conector de Stocator-S3 incluye soporte para el servicio de IBM Cloud Object Storage entre regiones (Beta)
Novedad desde: 5 de junio de 2017

Los usuarios de {{site.data.keyword.sparks}} ahora pueden acceder y realizar análisis sobre los datos almacenados en el servicio de IBM Cloud Object Storage entre regiones. Esta capacidad se ofrece como Beta. IBM Cloud Object Storage ofrece almacenamiento de alta capacidad y rentable para el análisis y otras aplicaciones que es escalable, flexible y fácil de utilizar.

Apache Spark accede a los datos de IBM Cloud Object Storage a través de un conector de almacenamiento basado en la tecnología de Stocator, que está implícitamente diseñado para el almacenamiento de objetos y que, por tanto, es más rápido que los conectores de almacenamiento de objetos existentes. Como usuario, no necesita cambiar ni volver a compilar el código de Apache Spark.

La publicación de blog [Acceder y analizar datos en IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo") describe el uso de los datos de IBM Cloud Object Storage con {{site.data.keyword.sparks}} en {{site.data.keyword.Bluemix_notm}} e IBM Data Science Experience (DSx).

Póngase en contacto con nosotros en [sparksrv@us.ibm.com](sparksrv@us.ibm.com), si tiene alguna pregunta o comentario. Su opinión es muy importante para nosotros.

### Nuevo plan escalable disponible para {{site.data.keyword.dashdbshort_notm}} for Transactions
Novedad desde: 31 de mayo de 2017

Hay disponible un plan nuevo para {{site.data.keyword.dashdbshort}} for Transactions que puede crecer con las necesidades de base de datos. El nuevo plan Flex le permite empezar con un sistema pequeño y hacer crecer la potencia y la capacidad de almacenamiento de dicho sistema de forma fácil y rápida. {{site.data.keyword.dashdbshort}} for Transactions es compatible al 100% con DB2 y proporciona un SLA del 99,95% en los planes de alta disponibilidad.

### Nuevas actualizaciones en el servicio de {{site.data.keyword.mobilepush}} en {{site.data.keyword.Bluemix_notm}}
Novedad desde: 24 de mayo de 2017

Las siguientes son las nuevas actualizaciones disponibles para el servicio de {{site.data.keyword.mobilepush}} en {{site.data.keyword.Bluemix_notm}}

**Plan Lite**: Estamos introduciendo un nuevo Plan Lite además del Plan Básico anterior para el Servicio de {{site.data.keyword.mobilepush}}. De acuerdo con el nuevo plan, los usuarios pueden enviar hasta cien mil mensajes digitales gratis al mes. Al actualizar del plan Lite al plan básico, al usuario se le cobrará a partir de un millón de mensajes digitales empezando con el recuento de cuando se haya interrumpido el uso del plan Lite.

**Supervisión**: Ahora puede obtener información sobre las notificaciones enviadas y los dispositivos registrados en la Consola de servicio de {{site.data.keyword.mobilepush}}. También puede utilizar las API REST para el seguimiento de nivel de mensaje. Desde la entrega de mensajes hasta su envío y recepción, los detalles se pueden obtener configurando webhooks. Consulte [Supervisión para {{site.data.keyword.mobilepush}}](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications).

**Notificaciones web**: Ahora puede enviar notificaciones a los navegadores web Safari.

### Actualizaciones de Secure Gateway
Novedad desde: 24 de mayo de 2017

La última actualización de mantenimiento de Secure Gateway incluye arreglos menores de errores en el gestor de IU y de API, documentación actualizada y la actualización del cliente a la versión 1.7.1. El cliente de Secure Gateway ahora está disponible en AIX 7.1+ y admite la conexión de salida mediante un proxy squid.

### Actualizaciones del servicio de {{site.data.keyword.streaminganalyticsshort}}: Desarrolle aplicaciones de Streams en el entorno de desarrollo de Python
Novedad desde: 13 de abril de 2017

En el pasado, instaló una versión local de IBM Streams para desarrollar aplicaciones de Python. Eso ya no es así. Ahora puede desarrollar aplicaciones con Python en su entorno de desarrollo favorito o en un cuaderno interactivo de Jupyter.

Puede utilizar el contexto de STREAMING_ANALYTICS_SERVICE para enviar una aplicación de Python al servicio de {{site.data.keyword.streaminganalyticsshort}}. El servicio de {{site.data.keyword.streaminganalyticsshort}} requiere Python 3.5.

Puede crear aplicaciones de Python de ejemplo mediante cuadernos de Jupyter en IBM Data Science Experience (DSX), y enviar estas aplicaciones a la instancia de {{site.data.keyword.streaminganalyticsshort}} directamente desde DSX. Consulte las aplicaciones de Python de proceso de secuencias de ejemplo en los cuadernos de la [página de la comunidad de DSX](https://datascience.ibm.com/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

Para obtener más información sobre las actualizaciones de servicio de {{site.data.keyword.streaminganalyticsshort}}, consulte [Actualizaciones de {{site.data.keyword.streaminganalyticsshort}}: integración de DSX y desarrollo más sencillo de Python](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo").

### Actualizaciones de {{site.data.keyword.sparks}}: ahora se da soporte a Apache Spark 2.1
Novedad desde: 21 de abril de 2017

{{site.data.keyword.sparkl}} está introduciendo el soporte para Apache Spark 2.1 para crear algoritmos que aprovechan la información de datos complejos. Apache Spark 2.1 contribuirá significativamente a la secuenciación estructurada con soporte añadido para las marcas de agua de hora de sucesos y Kafka 0.10. Apache Spark 2.1 también se centró en la estabilidad y la usabilidad aumentadas en los módulos de Spark SQL, SparkR y MLlib. Para obtener más detalles sobre Spark 2.1, consulte [Spark Release 2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html).

Nos complace responder a preguntas relacionadas con {{site.data.keyword.sparkl}} o la versión más reciente de Apache Spark 2.1, y puede ponerse en contacto con ellos en sparksrv@us.ibm.com. 

### {{site.data.keyword.macm_short}} está en desuso
Novedad desde: 18 de abril de 2017

A partir del 30 de marzo de 2017, se eliminará el mosaico de servicio de {{site.data.keyword.macm_long}} del Catálogo de {{site.data.keyword.Bluemix_notm}} y ya no podrá proporcionar instancias nuevas de MACM. Sin embargo, se seguirá dando soporte a las instancias existentes. La fecha de finalización de soporte es el 30 de marzo de 2018. Suprima sus instancias de servicio de {{site.data.keyword.macm_short}} (MACM) antes de la fecha de finalización de soporte. Animamos a los usuarios a migrar a IBM Watson Content Hub. Watson Content Hub está disponible en IBM Marketplace y proporciona a los usuarios una prueba gratuita de 30 días. IBM Watson Content Hub proporciona una funcionalidad similar a MACM con nuevas funciones añadidas como la gestión de activos, el etiquetado cognitivo mediante los servicios de IBM Watson, y red de entrega de contenido (CDN, content delivery network) incluida para garantizar una experiencia óptima para sus clientes. IBM ofrece compromisos de servicio para migrar el contenido de MACM a Watson Content Hub.

### Actualizaciones del servicio de {{site.data.keyword.streaminganalyticsshort}}: Desarrolle aplicaciones de Streams en el entorno de desarrollo de Python
Novedad desde: 13 de abril de 2017

En el pasado, instaló una versión local de IBM Streams para desarrollar aplicaciones de Python. Eso ya no es así. Ahora puede desarrollar aplicaciones con Python en su entorno de desarrollo favorito o en un cuaderno interactivo de Jupyter.

Puede utilizar el contexto de STREAMING_ANALYTICS_SERVICE para enviar una aplicación de Python al servicio de {{site.data.keyword.streaminganalyticsshort}}. El servicio de {{site.data.keyword.streaminganalyticsshort}} requiere Python 3.5.

Consulte las aplicaciones de Python de proceso de secuencias de ejemplo en los cuadernos de la [página de comunidad de IBM Data Science Experience](http://datascience.ibm.com){: new_window} ![Icono de enlace externo](../icons/launch-glyph.svg "Icono de enlace externo"). 

### Actualizaciones de {{site.data.keyword.sparks}}: ahora se da soporte a Notebook en Data Science Experience
Novedad desde: 11 de abril de 2017

La nueva plataforma para trabajar con cuadernos y Spark es Data Science Experience. Regístrese en [Data Science Experience](http://datascience.ibm.com/), y empiece a crear cuadernos y a compartir su experiencia con otros científicos de datos.

Si ha trabajado con cuadernos en {{site.data.keyword.sparks}}, podrá migrarlos a Data Science Experience. Para obtener más información, consulte [Migración de la documentación de cuadernos](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx).
