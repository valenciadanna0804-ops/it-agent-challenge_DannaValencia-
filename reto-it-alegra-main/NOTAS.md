# NOTAS DE IMPLEMENTACIÓN Y EVALUACIÓN  - IT AGENT CHALLENGE 
* **Candidata:** Danna Sofia Valencia Mosquera 
* **Rol:** Software Engineering Student 
* **Agente Creado:** Sofi (Analista IT)
* **Sub-agentes** Sammy ( Agente de offboarding)
* **fecha:** Agosto 2026

En este documento redactare como fue mi experiencia en este reto, que herramientas utilice, como cree a mi agente Sofi, que correcciones tuve que hacer a lo largo de este este proceso y que haria con mayor tiempo. 

## 1. Herramientas Utilizadas: 
Para esta evaluación utilice Gemini y VS code Extension
Siendo sincera esta fue la primera vez que realize un proceso como este, al inicio me sentia un poco perdida pero poco a poco fui entendiendo más, tambien tuve que instalar node.js para confinuar con este proceso. 
### Paso a Paso para la configuración
Se configuraron las instrucciones iniciales de contexto y rol del sistema en GEMINI.md para poder continuar con el proceso de creación de mi agente Sofi bajo las instrucciones del reto. 

## Creación de Sofi

Antes de iniciar con las 3 tares configure a mi agente indicandole que rol hiba a tener, en que equipo estaria y las reglas que debiamos seguir y ahi si continue con la resolución de esta actividad 
**Analisis de datos y finanzas** Como tarea le pude a Sofi el analisis y cruce de información de los archivos "usuarios.csv", "licencias.csv", y logins.csv para detectar los tipos de riesgos de seguridad que tiene la empresa, para este punto quise personificar el informe que me diera mi agente ya que dividimos los tipos de riegos, siendo rojo riesgo alto, amarillo riesgo moderado y verde riesgo bajo. En este punto se me ocurrio darle nombre a mi agente asi que la nombre SOfi y tambien le solicite que los informes, registros y demas documentos quedaran firmados por las dos (tarea 2) y por sammmy (tarea 3) para asi darle propiedad a nuestro trabajo.

**Resolución de ticktes** Como tarea le pedi a Sofi responder los 5 tickets que el equipo tenian pendientes, etiquetandolos con #Respuesta IT, dejando en el ticket una justificación de el porque de la desición y una respuesta a la persona que creo el ticket, adicional decidi etiquetar el estado de cada ticket por color siendo naranja rechazado, moradao escalado y azul aprobado, para asi dar un poco mas de orden y dinamismo.
**Estandarizacion y creacin de Sammy el agente de retiros: Para este punto le pedi a Sofi que terminara el docuemnto de playbooks/offboarding.md, donde se detallo un paso a paso y un protocolo de reitro que debe ser seguido por el agente encargado, en este caso creamos a sammy nuestro asistente de retiros para que nos ayude a procesar estos casos de manera automatica. Para comprobar que sammy funcionara bien lo pusismos a prueba con el ticket 5 el caso de Maria Lopez, lo cual resulto en la creacion del informe evidencia/offboarding-maria-fernanda-lopez.md. 

## Que tuve que corregir 
**Organizacion** Sofi genero un informe extenso de la tarea dos pero quedo desorganizado, por lo cual le pedi que lo ordenara en un resumen del informe, que explicara que se hizo en el punto 1 y en el punto 2, y por ultimo una conclusión. 
**Formato en los ticket** En la primera instrucción de este punto sofi creo la justificación de la resolucion de cada ticket, pero faltaba un mensaje de respuesta al solicitante para que asi supuera en que estado y que solución tenia su ticket. 

## 4. ¿Qué haria con mas tiempo?
Implementaria nuevos agentes para cada proceso, un agente para la revision de credenciasles, un agente para el analisis financiero, un agente que responda los tickets (la creación de agentes que sean cofuguarados para manejar esenarios especificos: ej recuperacion de contraseñas), tal vez un dashboard que nos indique por color que accesos el estado de riesgo de cada acceeso, en los tickets que se creen por color en los importantes como solicitud de accesos, o los retiros sean resaltados a los tickets normales como lo son no se fallas en la camara, tambien crearia alertas para saber si alguien que esta retirado este intentanto ingresar a los sistemas.