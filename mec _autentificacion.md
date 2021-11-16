Un mecanismo de autenticación define reglas sobre información de seguridad, como si una credencial es reenviable a otro 
proceso de Java™ y el formato de cómo se almacena la información de seguridad en credenciales y señales. Puede seleccionar 
y configurar un mecanismo de autenticación utilizando la consola administrativa.

Autenticación es el proceso de establecer si un cliente es quién o qué dice estar en un contexto determinado. Un cliente 
puede ser un usuario, una máquina o una aplicación. Un mecanismo de autenticación en WebSphere Application Server normalmente
colabora estrechamente con un registro de usuarios. El registro de usuarios es el repositorio de cuentas de grupos y usuarios 
con el que se consulta el mecanismo de autenticación al realizar la autenticación. El mecanismo de autenticación es responsable
de crear un credencial, que es una representación de producto interno de un usuario cliente autenticado satisfactoriamente.
No todas las credenciales se crean por igual. Las habilidades de la credencial se determinan mediante el mecanismo de autenticación configurado.

## **TIPOS DE MECANISMOS**
IPsec: Proporciona autenticación basada en host y en certificado, y cifrado de tráfico de red.

Kerberos: Utiliza el cifrado para autenticar y autorizar a un usuario que está iniciando sesión en el sistema.

LDAP: El servicio de directorios LDAP puede proporcionar autenticación y autorización a nivel de red.

Comandos de inicio de sesión remoto: Permite a los usuarios iniciar sesión en un sistema remoto a través de la red con rlogin, RCP o FTP y utilizar sus recursos.

SASL: Es una estructura que proporciona autenticación y servicios de seguridad opcionales a los protocolos de red.

Secure Shell: Proporciona autenticación mediante el uso de contraseñas, claves públicas, o ambos.
