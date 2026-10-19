# Histórias de usuário — BilhetePass

33 histórias, organizadas em 3 atividades e 11 tarefas.

Formato: **Como `<papel>`, quero `<ação>`, para `<benefício>`**.
A coluna indica a posição no [mapa da história do usuário](mapa/).
R1 = primeira release (o fluxo completo, fino). R2 = profundidade.

Papéis do domínio: **organizador**, **visitante**, **comprador**, **participante**, **staff**.

---

## Coluna 1 — Publicar o evento · organizador

| # | Release | História |
|---|---|---|
| H01 | R1 | Como **organizador**, quero **cadastrar um evento com data, local e descrição**, para **que ele possa receber ingressos à venda**. |
| H02 | R1 | Como **organizador**, quero **criar tipos de ingresso divididos em lotes com preço, quantidade e vigência**, para **vender mais barato no começo e aumentar o preço conforme o evento se aproxima**. |
| H03 | R2 | Como **organizador**, quero **criar cupons de desconto percentual ou de valor fixo, com validade e limite de usos**, para **fazer campanhas sem baixar o preço de tabela**. |
| H28 | R2 | Como **organizador**, quero **editar um evento já publicado**, para **corrigir data, local ou descrição sem precisar recriar tudo**. |
| H29 | R2 | Como **organizador**, quero **duplicar um evento de uma edição anterior**, para **não reconfigurar tipos e lotes a cada ano**. |
| H30 | R2 | Como **organizador**, quero **desativar um cupom**, para **encerrar uma campanha antes do prazo previsto**. |
| H31 | R2 | Como **organizador**, quero **acompanhar o uso dos meus cupons**, para **saber qual campanha converteu melhor**. |
| H32 | R2 | Como **organizador**, quero **ver as vendas do evento em tempo real**, para **decidir se abro um novo lote**. |
| H33 | R2 | Como **organizador**, quero **exportar o relatório de presença**, para **prestar contas aos patrocinadores do evento**. |
| H04 | R2 | Como **organizador**, quero **definir qual percentual de cada lote pode ser vendido como meia-entrada**, para **cumprir a lei sem comprometer a receita do evento**. |

## Coluna 2 — Descobrir o evento · visitante

| # | Release | História |
|---|---|---|
| H05 | R1 | Como **visitante**, quero **abrir a página de um evento e ver os tipos de ingresso disponíveis com seus preços**, para **decidir se vale a pena comprar**. |
| H06 | R2 | Como **visitante**, quero **buscar eventos por cidade e por data**, para **encontrar o que posso assistir no fim de semana**. |
| H07 | R2 | Como **visitante**, quero **favoritar um evento**, para **ser avisado quando um novo lote abrir**. |

## Coluna 3 — Escolher ingressos · comprador

| # | Release | História |
|---|---|---|
| H08 | R1 | Como **comprador**, quero **escolher quantos ingressos de cada tipo vou levar**, para **comprar de uma vez para mim e meus acompanhantes**. |
| H09 | R1 | Como **comprador**, quero **ver aplicado automaticamente o preço do lote vigente na data de hoje**, para **não ser cobrado por um valor que já expirou**. |
| H10 | R1 | Como **comprador**, quero **ser impedido de selecionar um ingresso cujo lote já esgotou**, para **não pagar por algo que não existe mais**. |
| H11 | R2 | Como **comprador**, quero **aplicar um cupom de desconto no meu pedido**, para **pagar menos pelo mesmo ingresso**. |
| H12 | R2 | Como **comprador**, quero **comprar meia-entrada declarando o benefício a que tenho direito**, para **pagar o valor reduzido previsto em lei**. |
| H13 | R2 | Como **comprador**, quero **entrar na fila de espera de um lote esgotado**, para **ser avisado se alguém cancelar e liberar ingressos**. |

## Coluna 4 — Identificar participantes · comprador

| # | Release | História |
|---|---|---|
| H14 | R1 | Como **comprador**, quero **informar o nome e o e-mail de quem vai usar cada ingresso**, para **que meus convidados recebam o bilhete direto**. |
| H15 | R2 | Como **comprador**, quero **ser avisado se eu repetir o mesmo participante em dois ingressos do pedido**, para **não emitir um bilhete que será barrado na portaria**. |
| H16 | R2 | Como **participante**, quero **transferir meu ingresso para outra pessoa antes do evento**, para **não perder o valor pago quando não puder comparecer**. |

## Coluna 5 — Pagar · comprador

| # | Release | História |
|---|---|---|
| H17 | R1 | Como **comprador**, quero **pagar meu pedido com cartão de crédito**, para **concluir a compra na hora e garantir os ingressos**. |
| H18 | R1 | Como **comprador**, quero **receber a confirmação de que o pagamento foi aprovado**, para **ter certeza de que os ingressos são meus**. |
| H19 | R2 | Como **comprador**, quero **pagar com Pix**, para **comprar sem depender de limite de cartão**. |
| H20 | R2 | Como **comprador**, quero **cancelar minha compra e receber o reembolso proporcional à proximidade do evento**, para **recuperar parte do valor quando meus planos mudam**. |

## Coluna 6 — Guardar o ingresso · participante

| # | Release | História |
|---|---|---|
| H21 | R1 | Como **participante**, quero **ver meus ingressos com o QR code**, para **apresentá-los na entrada do evento**. |
| H22 | R2 | Como **participante**, quero **receber meu ingresso por e-mail**, para **tê-lo em mãos mesmo sem acesso ao aplicativo**. |
| H23 | R2 | Como **comprador**, quero **reenviar o ingresso ao participante nomeado**, para **resolver quando ele diz que não recebeu**. |

## Coluna 7 — Entrar no evento · staff

| # | Release | História |
|---|---|---|
| H24 | R1 | Como **staff**, quero **ler o QR do ingresso e registrar o check-in**, para **liberar a entrada só de quem tem ingresso válido e ainda não usado**. |
| H25 | R2 | Como **staff autorizado no evento**, quero **reverter um check-in feito por engano**, para **não impedir a entrada de quem ainda não entrou**. |
| H26 | R2 | Como **staff**, quero **conferir o comprovante do benefício de meia-entrada na portaria**, para **cobrar a diferença de quem não puder comprovar**. |
| H27 | R2 | Como **organizador**, quero **consultar quantos participantes já entraram**, para **acompanhar o público em tempo real**. |

---

## Rastreabilidade — história → protótipo

| Coluna | Frames no Figma |
|---|---|
| 1 · Publicar o evento | `configuracao-de-ingressos`, `gerenciar-cupons` |
| 2 · Descobrir | `detalhe-do-evento` |
| 3 · Escolher ingressos | `selecao-de-ingressos` |
| 4 · Identificar | `identificacao-de-participantes` |
| 5 · Pagar | `checkout-pagamento`, `confirmacao-compra` |
| 6 · Guardar o ingresso | `meus-ingressos` |
| 7 · Entrar no evento | `checkin-participantes`, `checkin-estados-erro` |

## Pendências

- [ ] Atribuir o dono de cada história (integrante responsável)
- [ ] Conferir a conta do enunciado por integrante: 2 altas · ou 1 média + 2 baixas · ou 4 baixas
- [ ] Exportar o mapa do FigJam/Miro para `docs/mapa/`
- [ ] Exportar os 10 frames do Figma para `docs/prototipos/`
