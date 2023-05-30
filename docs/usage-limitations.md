---
title: Limitaciones de uso
layout: default
published: true
---
## Limitaciones de uso

Es importante tener en cuenta que nuestro servicio de API de WhatsApp tiene ciertas limitaciones que debes conocer. Debido a las normativas de WhatsApp, no es posible mantener un flujo directo de envío de mensajes. Para garantizar un flujo de salida seguro, ordenado y constante utilizamos una cola de espera. El intervalo entre mensajes puede variar dependiendo del servicio al que esté orientado.

Otro aspecto importante a considerar es el acceso a documentos adjuntos mediante URLs. Para que el servicio pueda acceder a los archivos adjuntos, es necesario que las URLs sean públicas y no se encuentren bajo ningún sistema de autorización. De lo contrario, el recurso será inaccesible y el mensaje no se enviará correctamente. Cabe mencionar que los archivos adjuntos tienen un límite de tamaño de 10 MB y pueden ser de cualquier formato.
