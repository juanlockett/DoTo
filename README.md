# DoTo
Proyecto de lista de items, creado en flask con firestore service.

Ruta donde se encuentra alojado el proyecto:
https://do-to-producction.rj.r.appspot.com/

El proycto cuenta con un modulo de autenticación y alta de usuarios, sumado al modulo que le da la funcionalidad de lista.

Para deploy en producción:
Configurar Google SDK. COnsultar documentación:
https://cloud.google.com/sdk/docs/quickstart
Tambien va a poder encontrar en la documentación los pasos para configurar la cuenta.

Crear el proyecto en Google Cloud Platform y activar el servicio de Firestore.


Para hacer deploy del proyecto, ejecutamos en la terminal "gccloud app deploy app.yaml"

