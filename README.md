# assistente_de_delivery
Criando um Assistente de Delivery com AWS Step Functions e Bedrock

com base no exercicio proposto foi criado este assistente no AWS Step Functions

na pasta de codigo estara disponibilizado o codigo do assistente de delivery 


#Explicação do Fluxo:

- ReceberPedido: Recebe o pedido do cliente.
- VerificarDisponibilidade: Verifica a disponibilidade do produto.
- CalcularCustoEntrega: Calcula o custo de entrega baseado na localização.
- ConfirmarPedido: Confirma o pedido com base na disponibilidade do produto.
- Se disponível, prossegue para o processamento de pagamento.
- Se indisponível, notifica o cliente da indisponibilidade.
- ProcessarPagamento: Processa o pagamento do cliente.
- NotificarCliente: Notifica o cliente sobre a confirmação do pedido.
- AcompanharEntrega: Acompanha o status da entrega até a conclusão.
