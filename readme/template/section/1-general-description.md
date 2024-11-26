## Descripción general

[DESCRIPCION DEL API]
 
# Exposición Servidores (URL BASE)
| Ambiente | URL|
| :-------- | :------- |
| Desarrollo | [URL API] |
| Certificación |  [URL API] |
| Producción |  [URL API] |
 
# Repositorio Contrato Open API
[REPOSITORIO CONTRATO GIT HUB]
 
# Autenticacion
Esta API está protegida por el protocolo Open Authentication (OAuth). Luego del intercambio de token con OAuth, se concede un token OAuth válido para acceder a los diferentes endpoints API en nombre de un usuario de la aplicación autorizada.
Para ello, se deben generar el Cliente CAS:

##### 1. Gestionar la creación del Cliente CAS
[Solicitud de Creación de Cliente CAS](https://bcp-ti.atlassian.net/wiki/spaces/privadoAUTH/pages/328730014/Manual+de+ejecuci+n+para+creaci+n+de+clientes+CAS)
 
##### 2. Gestionar la creación del Subscription-Key
[Solicitud para la creación de una suscripción](https://bcp-ti.atlassian.net/wiki/spaces/AAGDAPUB/pages/364740671/Suscripciones+en+Azure+APIM)
 