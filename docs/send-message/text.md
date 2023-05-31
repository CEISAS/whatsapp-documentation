---
layout: default
title: Mensaje de texto
parent: Envio de mensajes
nav_order: 7
---
## Mensaje de texto
Enviar mensaje de texto a uno o varios números de WhatsApp.

### Petición
| URL        				 | METHOD            |
|:---------------------------|:------------------|
| /api/v1/sendTextMessage    | POST  			 |

### Parametros
| Parametro      	 | Tipo		| Descripción 			 | Ejemplo   		 |
|:-------------------|:---------|:-----------------------|:------------------|
| token 			 | STRING	| Token de autenticación | 123e4567-e89b-12d3-a456-426614174000
| phone 			 | STRING	| Número(s) de teléfono  | +571234567890
| message 			 | STRING	| Mensaje 				 | hola!
| priority			 | NUMBER	| Prioridad del mensaje  | 1

{: .note } Puedes enviar el mismo mensaje a diferentes números si los separas por comas. Por ejemplo: `+571234567890, +579876543210`.

{: .warning } El valor de la prioridad debe estar entre 1 y 5, siendo 1 la prioridad más alta y 5 la más baja.