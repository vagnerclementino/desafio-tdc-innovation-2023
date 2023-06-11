# Desafío TDC Innovation 2023

Bienvenido al desafío de nuestro API Gateway propuesto en [TDC
Innovation](https://thedevconf.com/tdc/2023/innovation/). En este desafío,
tendrás la oportunidad de explorar Hotmart Developers, un hub de API públicas
administrado por [Hotmart](https://hotmart.com). La plataforma de APIs está
disponible en la dirección
[developers.hotmart.com](https://developers.hotmart.com).

Antes de participar en el desafío, es necesario crear una cuenta en Hotmart, en
caso de que aún no tengas una. En esta
[página](https://developers.hotmart.com/docs/pt-BR/start/about/) encontrarás
todos los detalles sobre cómo comenzar en la plataforma. Después de iniciar tu
cuenta, debes crear una credencial y hacer una solicitud al punto final que
devuelve información sobre _TDC Innovation_.

```
curl --location --request GET 'https://developers.hotmart.com/events/api/v1/:event_name/:event_year:/:event_edition' \
	--header 'Content-Type: application/json' \
	--header 'Authorization: Bearer :access_token'
```

Solo para reforzar, el nombre del evento es _TDC_ y estamos hablando de la
edición _Innovation_ del año actual. Después de obtener esta información, tu
tarea consiste en enviar un correo electrónico a
[vagner.clementino@hotmart.com](mailto:vagner.clementino@hotmart.com) con el
contenido de la carga útil (payload) del punto final. Tus solicitudes serán
validadas en los registros de la plataforma misma. Los primeros tres
participantes en enviar el retorno (payload) de la solicitud recibirán un kit
personalizado

---

