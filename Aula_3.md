**História 1**

---

Como cliente, quero avaliar o pedido depois da entrega, para ajudar outros clientes a escolherem melhor.

**Critérios:**
---

##### Dado que o pedido foi entregue, quando o cliente abre o app, então aparece a opção de avaliar o pedido.


Dado que o cliente avalia com nota e comentário, quando confirma o envio, então a avaliação aparece no perfil do restaurante.


1º RNF: O sistema deve persistir a avaliação do cliente no banco de dados em até 2 segundos após a confirmação do envio. \[Eficiência de desempenho]
2º RNF: O formulário de avaliação deve ser acessível e responsivo, adaptando-se a dispositivos móveis conforme as diretrizes de WCAG 2.1 \[Usabilidade]
3º RNF: Apenas clientes que tenham o status de "pedido entregue" vinculado ao seu ID de usuário devem ter permissão para submeter uma avaliação. \[Segurança]

**História 2**

---

##### Como cliente, quero salvar um cartão de pagamento, para não digitar os dados a cada compra.


**Critérios:**
Dado que o cliente cadastra um cartão válido, quando confirma o cadastro, então o cartão fica disponível para escolha no checkout.
---


Dado que o cliente tem um cartão salvo, quando faz um novo pedido, então pode selecionar esse cartão sem redigitar os dados.


1º RNF: Os dados dos cartões salvos devem ser armazenados de forma criptografada e seguir os padrões de segurança aplicáveis ao processamento de pagamentos. \[Segurança]
---

##### 2º RNF: Os cartões cadastrados devem estar disponíveis para seleção no checkout em até 2 segundos após o carregamento da página. \[Eficiência de Desempenho]

3º RNF: O sistema deve permitir que o cliente selecione um cartão previamente salvo no checkout com no máximo 2 cliques, sem necessidade de redigitação dos dados. \[Usabilidade]

**História 3**

---

##### Como dono de restaurante, quero ver um resumo diário de vendas, para acompanhar o desempenho do dia.


**Critérios:**
Dado que o dia comercial termina, quando o restaurante abre o painel de vendas, então vê o total de pedidos e o faturamento do dia.

---

Dado que o restaurante seleciona um período diferente, quando aplica o filtro, então o resumo é recalculado para aquele período.


1º RNF: O resumo de vendas deve ser exibido em até 3 segundos após a abertura do painel ou aplicação de filtros de período. \[Eficiência de Desempenho]
---

##### 2º RNF: O sistema deve manter disponibilidade mínima de 99,5% para consulta dos relatórios e resumos de vendas. \[Confiabilidade]

##### 3º RNF: O usuário deve conseguir aplicar filtros de período para recalcular o resumo de vendas sem necessidade de treinamento prévio. \[Usabilidade]

