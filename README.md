# Desafio TDC Innovation 2023

*Este texto está disponível nos seguintes idiomas: [Português](./README.md),
[Inglês](./translate/en/README.md), [Espanhol](./translate/es/README.md).*

---

Bem-vindo ao desafio do nosso API Gateway proposto no [TDC
Innovation](https://thedevconf.com/tdc/2023/innovation/)! Neste desafio, você
terá a oportunidade de explorar o Hotmart Developers, um hub de API públicas
gerenciado pela [Hotmart](https://hotmart.com). A plataforma de APIs está
disponível no endereço
[developers.hotmart.com](https://developers.hotmart.com).

Antes de participar do desafio, é necessário criar uma conta no Hotmart, caso
você ainda não tenha uma. Nessa
[página](https://developers.hotmart.com/docs/pt-BR/start/about/) tem todos os
detalhes sobre como começar na plataforma. Após iniciar sua conta, você deverá
criar uma credencial e fazer uma requisição para o endpoint que retorna algumas
informações sobre o *TDC Innovation*.

```shell
curl --location --request GET 'https://developers.hotmart.com/events/api/v1/:event_name/:event_year:/:event_edition' \
 --header 'Content-Type: application/json' \
 --header 'Authorization: Bearer :access_token'
```

Apenas reforçando que o nome do evento é *TDC* e estamos falando da edição
*Innovation* do ano corrente. Após obter essa informação, sua tarefa consiste
em enviar um e-mail para
[vagner.clementino@hotmart.com](mailto:vagner.clementino@hotmart.com) com o
conteúdo do payload do endpoint. Suas requisições serão validadas nos logs da
própria plataforma. Os três primeiros participantes a enviar retorno
(payload) da requisição receberão um kit personalizado e um desconto para o
evento [Hot ‘N Code Conference](http://hotm.art/hnc-2023?src=2088&utm_source=2088).

Não perca tempo! Acesse o
[developers.hotmart.com](https://developers.hotmart.com), crie sua conta, faça
a requisição para o endpoint indicado e envie o e-mail com as informações
solicitadas. Boa sorte!

--
