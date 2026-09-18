# Política de privacidad

**Última actualización: 18 de septiembre de 2026**

Esta Política de privacidad explica cómo el desarrollador trata la información en Oh!Mis Medicinas (la “App”).

## 1. Datos de medicamentos y tomas

La App no requiere registro ni una cuenta. Los medicamentos, suplementos, horarios, historial de tomas, inventario y notas se guardan normalmente en tu dispositivo. La App no sincroniza continuamente estos datos con nuestra nube. Los nombres de medicamentos, notas libres, notas de síntomas y términos de búsqueda sin procesar no se envían como campos personalizados de Firebase Analytics o Crashlytics.

## 2. Cambio de dispositivo

Solo cuando inicias expresamente el cambio de dispositivo desde Ajustes, la App cifra en el dispositivo tus datos de medicamentos y tomas y envía los datos cifrados a un servicio temporal de transferencia.

- El contenido se cifra con una clave derivada localmente del código de recuperación. El procesamiento normal del servidor no recibe en texto claro nombres de medicamentos, historial de tomas, notas ni síntomas.
- Los datos cifrados están disponibles durante un máximo de **72 horas**. Tras una restauración correcta o una revocación se inutilizan y eliminan lo antes posible. El límite de 72 horas actúa como protección final si hay un fallo temporal de red o limpieza.
- No almacenamos el código de recuperación y no podemos recuperar ni volver a emitir un código perdido.
- Usamos Firebase App Check y límites de solicitudes contra abusos. Puede procesarse información de red; los metadatos operativos guardan un identificador derivado unidireccional en lugar de la dirección IP sin procesar.
- No se trata de una copia de seguridad basada en cuenta ni de una sincronización continua.

## 3. Búsqueda y sugerencias de medicamentos

En países compatibles, el término de búsqueda puede enviarse a servicios públicos o de terceros, o a un proxy gestionado por nosotros, para devolver sugerencias. No añadimos historial de tomas, inventario, notas ni síntomas a esas solicitudes.

## 4. Analítica de uso

Usamos **Google Firebase Analytics** para mejorar la calidad. Puede incluir versión de la app, idioma, interacciones, recuentos agrupados e información técnica. Los eventos personalizados no deben incluir nombres de medicamentos, notas, síntomas, términos de búsqueda sin procesar, códigos de recuperación, capacidades de transferencia ni el contenido transferido. No usamos Analytics para publicidad ni seguimiento.

## 5. Diagnóstico de fallos

Usamos **Google Firebase Crashlytics** para investigar fallos y errores graves. Los diagnósticos añadidos por la App se limitan a nombres de operaciones, etapas, clasificaciones y códigos numéricos predefinidos, sin incluir contenido médico ni secretos de transferencia. No configuramos un ID de usuario personalizado de Crashlytics. Puedes desactivar la recopilación desde Ajustes; el cambio puede aplicarse por completo tras el siguiente inicio.

## 6. Publicidad y seguimiento

La App no muestra anuncios ni usa Google AdMob y no realiza seguimiento publicitario mediante ATT.

## 7. Servicios de terceros e infraestructura cloud

La App usa Firebase y Google Cloud. Los datos cifrados de transferencia y metadatos operativos mínimos se procesan y almacenan temporalmente en infraestructura de Google Cloud gestionada por nosotros.

- [Política de privacidad de Google](https://policies.google.com/privacy)
- [Privacidad y seguridad de Firebase](https://firebase.google.com/support/privacy)
- [Aviso de privacidad de Google Cloud](https://cloud.google.com/terms/cloud-privacy-notice)

## 8. Cambios

Podemos actualizar esta política cuando cambien las funciones o los servicios utilizados.

## 9. Contacto

- **Email**: k.lifetime.app+ohkusuri-support@gmail.com

---
*La versión japonesa es la versión de referencia.*
