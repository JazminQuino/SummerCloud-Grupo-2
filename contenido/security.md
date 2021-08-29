# Protección frente a amenazas de seguridad en Azure

 ##¿Qué es Azure Security Center?
* Es un servico de supervición con el que puede tener visibilidad del ***nivel de
seguridad*** en todos los serviios en Azure así como su entorno local.
* Obtenga una vista centralizada de todas sus alertas de seguridad.

Con Azure Secutity Center:
* Supervise las configuraciones de las cargas de trabajo.
* Configuración automatica a los nuevos recurso.
* Recomendaciones basadas en las configuraciones actuales.
* Supervise de forma continua los recursos y realize valoraciones de seguridad.
* Con aprendizaje automático puede detectar y bloquer malwer.
* Detecte y analize posibles amanazas.
* Control de acceso Just-In-Time a los puertos.

### Protección frente a amenazas
* Acceso a MV Just-In-Time: bloque el tráfico de forma predeterminada en puertos 
de red específicos de MVs.
* Controles de aplicaciones adaptables: examine que aplicaciones que se ejecutan 
en las MVs reciba una alerta cuando se ejecute una aplicación no autorizada.
* Protección de red adaptable: supervise los patrones de tráfico de Internet de las MVs. 
* Supevición de la imtegridad de los archivos: supervise los cambios en archivos 
importantes.

## Azure Sentinel (SIEM)
* Sistema de administración de eventos e información de seguridad dedicado.
* Análisis de seguridad inteligente y análisis de amenazas.
* Admite una serie de orígenes de datos que puede analizar en
 busca de eventos de seguridad.
* Puede investigar alertas o incidentes concretos.
* Agrega datos de seguridad de muchos orígenes diferentes y proporciona capacidades
adicionales para la detección de amenazas y la respuesta a estas

Azure Sentinel
* Recopilar datos en la nube a gran escala.
* Detectar amenazas no detectadas anteriormente.
* Investigar amenazas con IA.
* Responder a incidentes rápidamente.

Detectar amenazas
* Análisis integrados: plantillas diseñadas que se basan en amenazas conocidad, se 
pueden personalizar y buscan actividad que parezca sospechosa en el entorno. 
* Análisis peersonalizado: reglas que buscan criteros concretos en el entorno


## Azure Key Vault
* Servicios para en almacenamiento de los secretos de las aplicaciones 
en una única ubicación central.
* Acceso seguro a la información con un control de acceso y registro.

Con Azure Key Vault puede:

- Adimitración de secretos tokens, contraseñas, certificados, claves 
de API y más.
- Administrar claves de cifrado ya que facilita la creación y control de las mismas.
- Adminitrar certificados SSL/TLS, aprovisione, adminitre e implentelos.
- Almacenamiento claves y secretos respaldos por módulos de seguridad de hardware(HSM).

Ventajas Azure Key Vault 
* Secretos de aplicaciones centralizados.
* Secretos y claves almacenados de forma segura.
* Supervisión y control de acceso.
* Administración simplificada de secretos de aplicación.
* Integración con otros servicios de Azure


## Azure Dedicated Host
Son servidores físicos dedicados a MVs  de Azure y Linux para un único cliente.


Ventajas de Azure Dedicated Host

* Visibilidad y cotrol sobre la infraestructura que ejecuta las MVs.
* Ayuda con requisitos de  cumplimiento con la implemetación de cargas de trabajo en un 
servidor aislado.
* Permite elegir el tamaño de las MVs dentro del Host.