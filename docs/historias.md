# Histórias de usuário — BilhetePass

54 histórias, organizadas em 5 atividades e 16 tarefas.

Formato: **Como `<papel>`, quero `<ação>`, para `<benefício>`**. R1 = primeira release (a jornada completa, fina). R2 = profundidade.

Papéis: **dono de espaço**, **produtor**, **visitante**, **comprador**, **participante**, **staff**, **plataforma**.

---

## Oferecer um espaço

### Cadastrar espaço

| # | Release | História |
|---|---|---|
| H01 | R1 | Como **dono de espaço**, quero **cadastrar meu espaço com endereço, capacidade e fotos**, para **que produtores de evento consigam encontrá-lo.** |
| H02 | R2 | Como **dono de espaço**, quero **definir o valor da diária e da caução**, para **negociar sem precisar responder cada proposta do zero.** |

### Gerenciar disponibilidade

| # | Release | História |
|---|---|---|
| H03 | R1 | Como **dono de espaço**, quero **bloquear datas no calendário do meu espaço**, para **não receber propostas em dias que já tenho compromisso.** |
| H04 | R2 | Como **dono de espaço**, quero **ser impedido de bloquear uma data que já tem reserva confirmada**, para **não desmarcar um aluguel por engano.** |

### Responder propostas

| # | Release | História |
|---|---|---|
| H05 | R1 | Como **dono de espaço**, quero **ver as propostas de aluguel recebidas**, para **decidir quais aceitar.** |
| H06 | R1 | Como **dono de espaço**, quero **aceitar ou recusar uma proposta**, para **fechar o aluguel ou liberar a data.** |
| H07 | R2 | Como **dono de espaço**, quero **ser avisado quando duas propostas disputam a mesma data**, para **escolher conscientemente qual aceitar.** |


## Realizar um evento

### Alugar um espaço

| # | Release | História |
|---|---|---|
| H08 | R1 | Como **produtor**, quero **buscar espaços por cidade, capacidade e data**, para **achar um lugar que comporte meu público.** |
| H09 | R1 | Como **produtor**, quero **enviar uma proposta de aluguel ao dono do espaço**, para **reservar o local do meu evento.** |
| H10 | R2 | Como **produtor**, quero **acompanhar o status da minha proposta**, para **saber se posso seguir com a divulgação.** |
| H11 | R2 | Como **produtor**, quero **ver o valor total do aluguel já calculado**, para **avaliar se o espaço cabe no meu orçamento.** |

### Publicar evento

| # | Release | História |
|---|---|---|
| H12 | R1 | Como **produtor**, quero **cadastrar um evento com data, local e descrição**, para **que ele possa receber ingressos à venda.** |
| H13 | R1 | Como **produtor**, quero **ser impedido de publicar um evento cuja soma dos lotes excede a capacidade do espaço**, para **não vender ingresso que não cabe no lugar.** |
| H14 | R2 | Como **produtor**, quero **editar um evento já publicado**, para **corrigir data, local ou descrição sem recriar tudo.** |
| H15 | R2 | Como **produtor**, quero **duplicar um evento de uma edição anterior**, para **não reconfigurar tipos e lotes a cada ano.** |

### Configurar ingressos e cupons

| # | Release | História |
|---|---|---|
| H16 | R1 | Como **produtor**, quero **criar tipos de ingresso divididos em lotes com preço, quantidade e vigência**, para **vender mais barato no começo e subir o preço conforme o evento se aproxima.** |
| H17 | R2 | Como **produtor**, quero **definir qual percentual de cada lote pode ser vendido como meia-entrada**, para **cumprir a lei sem comprometer a receita.** |
| H18 | R2 | Como **produtor**, quero **criar cupons percentuais ou de valor fixo, com validade e limite de usos**, para **fazer campanha sem baixar o preço de tabela.** |
| H19 | R2 | Como **produtor**, quero **desativar um cupom mantendo o desconto de quem já o aplicou**, para **encerrar a campanha sem prejudicar quem está no meio da compra.** |
| H20 | R2 | Como **produtor**, quero **emitir cortesias nominais dentro de uma cota**, para **convidar parceiros sem perder o controle da lotação.** |

### Acompanhar e cancelar

| # | Release | História |
|---|---|---|
| H21 | R1 | Como **produtor**, quero **ver as vendas do evento em tempo real**, para **decidir se abro um novo lote.** |
| H22 | R2 | Como **produtor**, quero **exportar o relatório de presença**, para **prestar contas aos patrocinadores.** |
| H23 | R2 | Como **produtor**, quero **cancelar o evento reembolsando todos os compradores**, para **resolver de uma vez quando o show não acontece.** |


## Comprar ingresso

### Descobrir eventos

| # | Release | História |
|---|---|---|
| H24 | R1 | Como **visitante**, quero **abrir a página de um evento e ver os ingressos disponíveis**, para **decidir se vale a pena comprar.** |
| H25 | R2 | Como **visitante**, quero **buscar eventos por cidade e por data**, para **encontrar o que posso assistir no fim de semana.** |
| H26 | R2 | Como **visitante**, quero **favoritar um evento**, para **ser avisado quando um novo lote abrir.** |

### Escolher ingressos

| # | Release | História |
|---|---|---|
| H27 | R1 | Como **comprador**, quero **escolher quantos ingressos de cada tipo vou levar**, para **comprar de uma vez para mim e meus acompanhantes.** |
| H28 | R1 | Como **comprador**, quero **ver aplicado o preço do lote vigente na data de hoje**, para **não ser cobrado por um valor que já expirou.** |
| H29 | R1 | Como **comprador**, quero **ser impedido de selecionar um ingresso cujo lote esgotou**, para **não pagar por algo que não existe mais.** |
| H30 | R2 | Como **comprador**, quero **aplicar um cupom de desconto no meu pedido**, para **pagar menos pelo mesmo ingresso.** |
| H31 | R2 | Como **comprador**, quero **comprar meia-entrada declarando o benefício a que tenho direito**, para **pagar o valor reduzido previsto em lei.** |
| H32 | R2 | Como **comprador**, quero **entrar na fila de espera de um lote esgotado**, para **ser avisado se alguém cancelar.** |

### Identificar participantes

| # | Release | História |
|---|---|---|
| H33 | R1 | Como **comprador**, quero **informar o nome e o e-mail de quem vai usar cada ingresso**, para **que meus convidados recebam o bilhete direto.** |
| H34 | R2 | Como **comprador**, quero **ser avisado se repetir o mesmo participante em dois ingressos**, para **não emitir um bilhete que será barrado na portaria.** |

### Pagar

| # | Release | História |
|---|---|---|
| H35 | R1 | Como **comprador**, quero **pagar meu pedido com cartão de crédito**, para **concluir a compra na hora.** |
| H36 | R1 | Como **comprador**, quero **receber a confirmação de que o pagamento foi aprovado**, para **ter certeza de que os ingressos são meus.** |
| H37 | R2 | Como **comprador**, quero **pagar com Pix**, para **comprar sem depender de limite de cartão.** |
| H38 | R2 | Como **comprador**, quero **ser avisado se minha reserva expirou antes do pagamento**, para **não pagar por um ingresso que voltou ao estoque.** |


## Usar o ingresso

### Receber o ingresso

| # | Release | História |
|---|---|---|
| H39 | R1 | Como **participante**, quero **ver meus ingressos com o QR code**, para **apresentá-los na entrada do evento.** |
| H40 | R2 | Como **participante**, quero **receber meu ingresso por e-mail**, para **tê-lo mesmo sem acesso ao aplicativo.** |
| H41 | R2 | Como **participante**, quero **pedir a reemissão do meu ingresso**, para **recuperá-lo sem que o código antigo continue valendo.** |

### Transferir ou cancelar

| # | Release | História |
|---|---|---|
| H42 | R2 | Como **participante**, quero **transferir meu ingresso para outra pessoa antes do evento**, para **não perder o valor pago.** |
| H43 | R2 | Como **comprador**, quero **cancelar minha compra e receber o reembolso proporcional à proximidade do evento**, para **recuperar parte do valor.** |
| H44 | R2 | Como **participante**, quero **ser impedido de transferir uma cortesia, porque ela é nominal e intransferível.** |

### Entrar no evento

| # | Release | História |
|---|---|---|
| H45 | R1 | Como **staff**, quero **ler o QR do ingresso e registrar o check-in**, para **liberar a entrada só de quem tem ingresso válido.** |
| H46 | R2 | Como **staff autorizado no evento**, quero **reverter um check-in feito por engano**, para **não impedir a entrada de quem ainda não entrou.** |
| H47 | R2 | Como **staff**, quero **conferir o comprovante do benefício de meia-entrada**, para **cobrar a diferença de quem não puder comprovar.** |
| H48 | R2 | Como **staff**, quero **que o sistema bloqueie a entrada ao atingir a lotação do espaço**, para **não exceder a capacidade legal do local.** |


## Fechar o evento

### Avaliar

| # | Release | História |
|---|---|---|
| H49 | R1 | Como **participante**, quero **avaliar o evento que frequentei**, para **ajudar outras pessoas a decidir.** |
| H50 | R2 | Como **participante**, quero **que só quem teve check-in confirmado possa avaliar**, para **que as notas reflitam quem realmente foi.** |
| H51 | R2 | Como **produtor e como dono de espaço, queremos nos avaliar mutuamente após o evento**, para **construir reputação na plataforma.** |

### Receber o repasse

| # | Release | História |
|---|---|---|
| H52 | R1 | Como **produtor**, quero **ver quanto vou receber e quando**, para **planejar meu fluxo de caixa.** |
| H53 | R2 | Como **produtor**, quero **receber o repasse já descontadas taxas, reembolsos e o aluguel do espaço**, para **não precisar fazer a conta por fora.** |
| H54 | R2 | Como **plataforma, queremos reter o repasse enquanto houver disputa aberta**, para **proteger compradores e donos de espaço.** |

---

## Funcionalidades

| Funcionalidade | Atividade | Complexidade |
|---|---|---|
| Oferta de espaços | Oferecer um espaço | Alta |
| Locação de espaço | Realizar um evento | Alta |
| Publicação e configuração do evento | Realizar um evento | Alta |
| Cortesias e convidados | Realizar um evento | Média |
| Relatórios do organizador | Realizar um evento | Média |
| Cancelamento do evento | Realizar um evento | Alta |
| Descoberta de eventos | Comprar ingresso | Média |
| Compra de ingressos | Comprar ingresso | Alta |
| Meia-entrada: benefício e cota | Comprar ingresso | Alta |
| Fila de espera e reserva temporária | Comprar ingresso | Alta |
| Gestão do meu ingresso | Usar o ingresso | Alta |
| Check-in de participantes | Usar o ingresso | Alta |
| Lotação em tempo real | Usar o ingresso | Média |
| Avaliações pós-evento | Fechar o evento | Alta |
| Repasse financeiro | Fechar o evento | Alta |

**15 funcionalidades** — 11 altas e 4 médias.

## Pendências

- [ ] Atribuir as funcionalidades aos integrantes
- [ ] Preencher o formulário de funcionalidades de cada um
- [ ] Protótipos das funcionalidades novas (espaços, avaliações, repasse, cancelamento)
- [ ] Exportar o mapa atualizado para `docs/mapa/`
