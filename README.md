# Autenticacion por Doble Factor utilizando Authy

Se trata de una implementaci�n simple de Java, Spring y AngularJS de un sitio web que usa Twilio Authy para proteger todos los activos dentro de una carpeta con autenticaci�n de dos factores. 

Utiliza dos canales para entrega, SMS y SoftTokens. Se debe instalar la aplicaci�n Authy (https://authy.com/download/) para probar Soft Token.

#### Demostraci�n de autenticaci�n de dos factores
- La ruta URL "/ protected" est� protegida con sesi�n de usuario y Twilio Authy Two-Factor Authentication
- Contrase�as �nicas SMS 
- SoftTokens

### EJECUCION
- Clonar este repositorio
- Ejecutar desde consola `gradle build`
- Registrarse en una Cuenta Authy-Twilio (https://www.twilio.com/).
- Configure una aplicaci�n de seguridad de cuenta a trav�s de Twilio Console(https://twilio.com/console).
- Copiar la clave API de aplicaci�n del DashBoard de nuestra cuenta y pegarla en el archivo `.env.`
- Setear la variable ACCOUNT_SECURITY_API_KEY=qYH3doeJyKnB2CqDfFQL3A1qSzb0MFFt
- Ejecutar `gradle appRun` desde el repositorio clonado para ejecutar la aplicaci�n
