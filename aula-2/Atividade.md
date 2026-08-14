Atividade — Making History (Elicitação de Requisitos)

Histórias de Usuário e Critérios de Aceitação

Item 1: Acompanhamento do Pedido
História de Usuário:
Como cliente, quero acompanhar o status e a localização do meu pedido em tempo real, para saber exatamente quando ele vai chegar. (MUST)

Visão INVEST:
Valiosa & Testável: Reduz a ansiedade do cliente e diminui chamados no suporte. Pode ser facilmente testada acompanhando o status do pedido.

Critérios de Aceitação:
1. Dado que tenho um pedido em andamento, quando acesso a tela do pedido, então vejo a etapa atual atualizada.
2. Dado que o pedido saiu para entrega, quando abro o mapa de acompanhamento, então vejo a localização do entregador atualizada em tempo real.
3. Dado que o status do meu pedido mudou para "saiu para entrega", quando a alteração ocorre, então recebo uma notificação no aplicativo.

Item 2: Item do Cardápio Indisponível
História de Usuário:
Como restaurante, quero marcar um item do cardápio como indisponível no painel, para evitar receber pedidos de pratos em que os ingredientes acabaram. (MUST)

Visão INVEST:
Negociável & Pequena: Pode ser um botão liga/desliga no painel, fácil de estimar e implementar em uma iteração.

Critérios de Aceitação:
1. Dado que um prato acabou na cozinha, quando desmarco a sua disponibilidade no painel do restaurante, então ele deixa de ficar disponível para compra no app do cliente.
2. Dado que um item foi marcado como indisponível, quando o cliente tenta adicioná-lo ao carrinho, então o sistema bloqueia a ação e exibe um alerta de item indisponível.
3. Dado que o estoque do prato foi reposto, quando reativo o item no painel, então ele volta a ficar visível e disponível para compra.

Item 3: Reporte de Problema na Entrega
História de Usuário:
Como entregador, quero reportar um imprevisto durante a rota, para que o suporte intervenha e o cliente seja avisado. (SHOULD)

Visão INVEST:
Independente & Estimável: Ação pontual focada no envio de alerta e alteração de status da corrida.

Critérios de Aceitação:
1. Dado que estou a caminho do destino e ocorre um imprevisto, quando seleciono "Reportar problema" e escolho o motivo, então o alerta é enviado ao suporte.
2. Dado que reportei um problema na entrega, quando o envio é confirmado, então o cliente recebe uma notificação no app informando o imprevisto.
3. Dado que o suporte valida o imprevisto, quando a rota é interrompida, então o status do pedido é alterado para "em análise/cancelado" e o entregador é liberado.