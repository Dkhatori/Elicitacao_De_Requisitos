## História 1 — Acompanhamento do pedido

**1 - Como cliente do aplicativo, eu quero acompanhar o status do meu pedido em tempo real após a compra,para que eu saiba quando ele foi aceito, está sendo preparado, saiu para entrega e foi entregue.**

A - Dado que o pagamento do pedido foi confirmado, quando o restaurante aceitar o pedido, então o status do pedido deve mudar para "Em preparo" na tela de acompanhamento.

B - Dado que o pedido está com status "Saiu para entrega", quando o entregador iniciar o trajeto, então o cliente deve visualizar a localização estimada do entregador e o tempo estimado de chegada.

C - Dado que o pedido foi entregue, quando o entregador confirmar a entrega no app, então o status deve mudar para "Entregue" e o cliente deve receber uma notificação push.

---

## História 2 — Item indisponível no cardápio

**Como dono/gerente de restaurante parceiro, eu quero marcar um item do cardápio como indisponível, para que os clientes não consigam pedir algo que não pode ser preparado no momento.**

A - Dado que o gerente do restaurante está na tela de gestão do cardápio, quando ele marcar um item como "indisponível", então esse item deve deixar de aparecer como opção para pedido no app do cliente.

B - Dado que um item foi marcado como indisponível, quando um cliente estiver visualizando o cardápio do restaurante, então o item deve aparecer sinalizado (ex: esmaecido ou com etiqueta "indisponível") em vez de simplesmente sumir sem explicação.

C - Dado que um item indisponível volta a ter estoque, quando o gerente marcar o item novamente como "disponível", então o item deve voltar a aparecer normalmente como opção de pedido no cardápio.

---

## História 3 — Reporte de problema durante a entrega

**Como entregador, eu quero reportar um problema durante a entrega (endereço não encontrado, cliente ausente, item danificado, etc.), para que o suporte e o cliente sejam informados rapidamente e uma solução seja encaminhada.**

A - Dado que o entregador está com uma entrega em andamento, quando ele acessar a opção "Reportar problema" no app, então deve ser exibida uma lista de categorias de problema (ex: endereço incorreto, cliente ausente, item danificado).

B - Dado que o entregador selecionou uma categoria de problema e confirmou o envio, quando o reporte for enviado, então o suporte deve receber uma notificação imediata com os dados do pedido e a descrição do problema.

C - Dado que um problema foi reportado, quando o cliente abrir o acompanhamento do pedido, então ele deve visualizar um aviso informando que houve um imprevisto na entrega.