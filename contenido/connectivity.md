# Conectividad de red segura en Azure

##  Azure Firewall

* Servicio de red adminitrado y basado en la nube, ayuda a proteger los recuros en las
redes vituales de Azure.
* Firewall con estado, análisa el conexto completo de una conexión de red.
* Incluye alta disponibilidad y escalabilidad sin restricciones, reglas
de filtrado entrante y saliente, compotibilidad con DNAT y registro de Azure Monitor.

### ¿Qué se puede configurar con Azure Firewall?
Reglas de:
* Red que definen la dirección de origen, el protocolo, el puerto de destino y 
la dirección de destino.
* Traducción de direcciones de red (NAT) que definen los puertos y las direcciones
 IP de destino. 

##  Azure DDoS Protection
* Ayuda a proteger sus recursos de Azure frente a ataques DDoS.
* Análiza y descarta el tráfico de DDoS en la red perimentral de Azure.
* Identifica el intento de ataque sobre la red y evita más tráfico.

Niveles de servicio disponibles para DDoS Protection
* Basic: es parte de su sucripción de Azure, garantiza que la infraestrucutra 
no se vea afectada durante un ataque.
* Estándar: supervición de tráfico simpre activa y mitigación de ataques 
en tiempo real, las directivas de protección se ajustan con tráfico dedicado y 
algoritmos de Machine Learning.

Tipos de ataques que ayuda a evitra

* Ataques volumétrico: desborar la capa de red con tráfico aparentemente legítimo.
* Ataques de protocolo: aprovechan vulneravilidades en la capa 3 y 4 
* Ataques de nivel de recurso: dirigidos a paquetes de aplicaciones web para interrumpir
la trasmición de datos entre host.

## Grupos de seguridad de red (NSG)
* Permiten filtrar el tráfico de red desde u¿y hacia los recuros de Azure en una VN 
de Azure.
* Firewall interno.
* Contienes varias reglas de seguridad entrantes y salientes que permite filtrar el 
tráfico con los recuros por dirección IP de origen y destino.
* Una regla de grupo de seguridad de red le permite filtrar el tráfico desde y hacia los recursos por dirección IP de origen y destino, puerto y protocolo.



Nombre, prioridad, origen o destino, protocolo, dirección, intervalo de puertos y acción.

