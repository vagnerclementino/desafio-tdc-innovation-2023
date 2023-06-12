# TDC Innovation 2023 Challenge

# Desafío TDC Innovation 2023

Welcome to the challenge of our API Gateway proposed at [TDC
Innovation](https://thedevconf.com/tdc/2023/innovation/)! In this challenge,
you will have the opportunity to explore Hotmart Developers, a hub of public
APIs managed by [Hotmart](https://hotmart.com). The API platform is available
at [developers.hotmart.com](https://developers.hotmart.com).

Before participating in the challenge, it is necessary to create an account on
Hotmart if you don't have one yet. On this
[page](https://developers.hotmart.com/docs/pt-BR/start/about/), you will find
all the details on how to get started on the platform. After starting your
account, you should create a credential and make a request to the endpoint that
returns some information about _TDC Innovation_.

```
curl --location --request GET 'https://developers.hotmart.com/events/api/v1/:event_name/:event_year:/:event_edition' \
	--header 'Content-Type: application/json' \
	--header 'Authorization: Bearer :access_token'
```

Just to reinforce, the name of the event is _TDC_, and we are referring to the
current year's edition, _Innovation_. After obtaining this information, your
task is to send an email to
[vagner.clementino@hotmart.com](mailto:vagner.clementino@hotmart.com) with the
content of the endpoint's payload. Your requests will be validated in the logs
of the platform itself. The first three participants to send back the request's
payload will receive a personalized kit and a discount for the [Hot ‘N Code
Conference](http://hotm.art/hnc-2023?src=2088&utm_source=2088) event.

Don't waste time! Access
[developers.hotmart.com](https://developers.hotmart.com), create your account,
make the request to the indicated endpoint, and send the email with the
requested information. Good luck!

---

