# Desafío TDC Innovation 2023

En este desafío, tendrás la oportunidad de explorar Hotmart Developers, un hub
de API públicas gestionado por [Hotmart](https://hotmart.com). La plataforma de
APIs está disponible en la dirección
[developers.hotmart.com](https://developers.hotmart.com).

Antes de participar en el desafío, es necesario crear una cuenta en Hotmart, en
caso de que aún no la tengas. En esta
[página](https://developers.hotmart.com/docs/pt-BR/start/about/) encontrarás
todos los detalles sobre cómo comenzar en la plataforma. Una vez que hayas
iniciado tu cuenta, deberás crear una credencial y hacer una solicitud al
endpoint que devuelve información sobre el _TDC Innovation_.

```
curl --location --request GET 'https://developers.hotmart.com/events/api/v1/:event_name/:event_year:/:event_edition' \
	--header 'Content-Type: application/json' \
	--header 'Authorization: Bearer :access_token'
```

Solo para reforzar, el nombre del evento es _TDC_ y estamos hablando de la
edición _Innovation_ del año en curso. Después de obtener esta información, tu
tarea consiste en enviar un correo electrónico a
[vagner.clementino@hotmart.com](mailto:vagner.clementino@hotmart.com) con el
contenido del payload del endpoint. Tus solicitudes serán validadas en los
registros de la propia plataforma. Los tres primeros participantes en enviar el
retorno (payload) de la solicitud recibirán un kit personalizado y un descuento
para el evento [Hot ‘N Code
Conference](http://hotm.art/hnc-2023?src=2088&utm_source=2088).

¡No pierdas tiempo! Accede a
[developers.hotmart.com](https://developers.hotmart.com), crea tu cuenta,
realiza la solicitud al endpoint indicado y envía el correo electrónico con la
información solicitada. ¡Buena suerte! 

---

