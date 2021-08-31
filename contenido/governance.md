# Creación de una estrategia de gobernanza en la nube en Azure

Gobernanza, establecer reglas y directivas y garantizar que estas reglas y directivas se
aplica.
* Ayuda a mantener un control de las aplicacipnes y los recursos que se administran 
en la nueb.

## Control de acceso basado en roles (RBAC) de Azure
* Roles que tienen un conjunto asociado de permisos de acceso, se se asocian a  un usuario 
o a un grupo de usuarios.
* Se aplica a un ámbito,  que es un recurso o varios. 

Ambito puede ser:
- Grupo de adminitración(colección de sucripciones).
- Una suscripción.
- Grupo de recursos.
- Un recurso.

## ¿Cuándo conviene usar RBAC de Azure?
* Un usuario administre las VMs en una sucripció y otro administre las VNs.
* Un grupo de administradores de BD administre BD SQL de una sucripción.
* Un usuario adminitre todos los recursos de un grupo de recursos.
* Una app acceda a todos los recursos de un grupo de recursos.


## ¿Cómo se aplica RBAC de Azure?
* Empleando un modelo de permiso, los cuales nos permiten realizar determinadas acciones,
como leer, escribir o eliminar.
* Se aplica a cualquiere recurso que se inice en un recurso de Azure Resource Manage.
***Azure Resource Manage*** es un servicio de administración  que proporciona 
una forma de organizar y proteger nuestros recursos en la nube.

## Bloqueos de recursos 
* Evite cambios inintencionados.
* Impide que se eliminen o modifiquen recursos por erro.
* Se pueden administrar en Azure Portal, PowerShell, la CLI de Azure o 
con una plantilla de Azure Resource Manager.
* Niveles de bloqueo 
	CanNotDelete leer y modificar pero no eliminar. 
	*ReadOnly leer pero no eliminar.
## Etiquetas
* Para orgnizar los recursos de Azure.
* Proporcionan infromación extra, o metadatos, sobre los recursos.
* Se administran a través de PowerShell, la CLI de Azure,
 plantillas de Azure Resource Manager, la API REST o Azure Portal. Y con Azure Policy
* Se componen de un nombre y un valor
	AppName
	costCenter
	Propietario
	Entorno
	Impacto
## Azure Policy 
*  Garantizar que un recurso herede las mismas etiquetas que su grupo de recursos primario. 
*  Es para controlar y auditar recuros.
*  Servicio de Azure que permite creear, asignar y adminitrar directivas 
* Evalua los recursos y resalta los que no cumplen las directivas.


## Azure Policy en acción

1. Crear una definición de directiva
Que se debe evaluar y que acción realiza, como ubicaciones predeterminadas, SKU de MVs 
permitidas, etc.

2. Asignar la definición a los recursos
Se aplica dentro de un ambito especifico, todo dentro de ese ámbito  hereda las
asignaciones  de directiva.

3. Revisar los resultados de evaluación
Revisar si se marca como conforme o inconforme para tomar las medidad oportunas.

## ¿Qué son las iniciativas Azure Policy?
* Agrupar directivas relacionadas.
* Facilita el seguimiento del estado del cumplimiento de cara a un objeto mayor
* Por ejemplo Habilitar la supervisión en Azure Security Center que contiene
varias definiciones de directivas relacionas a Azure Security Center.

##  Azure Blueprints
* Repita un conjunto de herremientas de gobernanza y recursos estándar que la
organización necesita.

### Azure Blueprints en acción
1. Crear una instancia de Azure Blueprints
2. Asignar ese plano técnico(lo que se debe implementar) 
3. Llevar un seguimiento de las asignaciones(lo que ha implementado) del plano técnico

### ¿Qué son los artefactos de plano técnico?
* Cada componente de la definición de un plano técnico.
* Contienen uno o más parametros  que se pueden configurar.

# :house: [Inicio](https://github.com/JazminQuino/SummerCloud-Grupo-2)
