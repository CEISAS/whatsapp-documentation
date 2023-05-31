---
title: Limitaciones de uso
layout: default
nav_order: 2
published: true
---

## Limitaciones de uso

Es importante tener en cuenta que nuestro servicio de API de WhatsApp tiene ciertas limitaciones que debes conocer. Debido a las normativas de WhatsApp hemos tenido que aplicar distintas soluciones para seguir brindando un servicio estable.

**Envío de mensajes no solicitados:** El uso de nuestro servicio para enviar spam o anuncios molestos puede resultar en que los usuarios marquen tus mensajes como spam, lo que puede provocar que se bloquee el número de WhatsApp utilizado para el envío de los mensajes. En general, te recomendamos utilizar nuestro servicio únicamente para enviar mensajes a tus clientes y no para enviar spam o anuncios molestos. Los mensajes que envíes deben ser relevantes, como notificaciones, recordatorios o cualquier otro mensaje que los clientes estén esperando.

**Acceso a documentos adjuntos:** Para que el servicio pueda acceder a los archivos adjuntos, es necesario que las URLs sean públicas y no se encuentren bajo ningún sistema de autorización. De lo contrario, el recurso será inaccesible y el mensaje no se enviará correctamente. Te recomendamos que verifiques la configuración de los recursos adjuntos antes de enviar mensajes para asegurarte de que puedan ser accedidos sin problemas.

**Límite en el tamaño de los archivos adjuntos:** Los archivos adjuntos tienen un límite de tamaño de 10 MB y pueden ser de cualquier formato. Si necesitas enviar archivos más grandes, te recomendamos que los dividas en varias partes o que utilices servicios de almacenamiento en la nube para compartirlos.

**Flujo de envío de mensajes:** Debido a las normativas de WhatsApp, no es posible mantener un flujo directo de envío de mensajes. Para garantizar un flujo de salida ordenado y constante, utilizamos una cola de espera. El intervalo entre mensajes puede variar dependiendo del servicio al que esté orientado.
