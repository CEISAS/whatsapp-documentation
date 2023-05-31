---
layout: default
title: Audio
parent: Envio de mensajes
nav_order: 3
---

# Audio

Enviar un audio a uno o varios números de WhatsApp.

### Petición

| URL                      | METHOD |
| :----------------------- | :----- |
| /api/v1/sendAudioMessage | POST   |

### Parametros

| Parametro | Tipo   | Descripción            | Ejemplo                                         |
| :-------- | :----- | :--------------------- | :---------------------------------------------- |
| token\*   | STRING | Token de autenticación | `123e4567-e89b-12d3-a456-426614174000`          |
| phone\*   | STRING | Número(s) de teléfono  | `+571234567890`, `+571234567890, +571234567891` |
| audio\*   | STRING | URL del audio          | `https://example.com/audio.mp3`                 |
| priority  | NUMBER | Prioridad del mensaje  | `1`, `2`, `3`, `4`, `5`                         |

{: .note }
Puedes enviar el mismo mensaje a diferentes números si los separas por comas.

{: .warning }
Es necesario que la URL sea de acceso público y no se encuentren bajo ningún sistema de autorización.

{: .warning }
La URL tiene que devolver un archivo de audio (con formato mp3 o ogg).

{: .warning }
El valor de la prioridad debe estar entre 1 y 5, siendo 1 la prioridad más alta y 5 la más baja.
