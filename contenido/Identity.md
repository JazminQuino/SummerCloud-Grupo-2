# Acceso seguro a las aplicaciones con servicios de identidad de Azure

## Autenticación (AuthN) y la Autorización (AuthZ).


### Autenticación
* Proceso de establecer la identidad de una persona o servicio que quiere acceder a un 
recurso. Determinar si el usuarios es quien dice ser.

### Autorizacion 
* Establece el nivek de accesi que tiene una persona o servicio autenticados. 
A que puede tener acceso y que puede hacer.

##Azure Active Directory

* Proporciona servicios de identidad que permiten a los usuarios iniciar sesión y acceder 
tanto a aplicaciones.
* Adminitra accesos e identidad basado en la nube de Microsoft.
* Servicio desponible globamente.


### Azure AD proporciona servicios como:

* Autenticación: comprobación de identidad: 
* Inicio de sesión único: puede acceder a varias aplicaicones con una sola cuenta.
*Adminitración de aplicaciones: adminitre aplicaciones en la nube y locales.
* Adminitración de dispositivos: a través de Microsoft Intune 


## Inicio de sesión único.

* Inicie sesión una sola vez y con esa credecial accesa a otras aplicaciones.


## ¿Cómo se puede conectar Active Directory con Azure AD?

Use Azure AD Connect.

Sincroniza las identidades de Active Directory local con Azure AD y guarda los cabios 
entre ambos sistemas de identidad.



## Atenticación multifactor
Solicitar una forma adicional de identificación.
Ofrece seguridad adicional ya que requiere dos o más elementos para
la autentificación completa.
* Algo que el usuario conoce. como su correo o contraseña
* Algo que el usuario tiene. como un código 
* Algo que el usuario es. Una propiedad biometrica, huella o escaneo facial.

## Azure AD Multi-Factor Authentication
Proporciona la autenticación multifactor.
Permite a los usuarios elegir una forma adicional de autenticación durante el inicio de 
sesión 

* Azure Active Directory, La edición gratuita de Azure Active Directory habilita Azure 
AD Multi-Factor Authentication para los administradores con el nivel de acceso de 
Administrador global y también a todos los usuarios.
* Autenticación multifactor para Office 365
a través de la aplicación Microsoft Authenticator,

## Acceso condicional

Herramienta de Azure AD para permitir o denegar accesos a los recursos en función 
en señales de identidad, como quién es el usuario, dónde se encuetra y desde que 
dispositivo solicita el acceso.
* Toma recopilación de señales de usuario y basado en esas señales puede tomar
decisiones para permitir o denegar accesos.

Señal, Decisión, Cumplimiento -IMAGEN