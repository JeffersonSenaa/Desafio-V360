# Requisitos Funcionais

Foram levantados e analisados os requisitos da solução afim de solucionar os problemas encontrados no fluxo de tarefas atual. Com isso, este produto propõe melhorias e qualidade nos processos realizados no centro de distribuição.


## RF01 - Controlar Agendamento de Entregas
O sistema deve Controlar o Agendamento de Entregas obtendo gerenciamento eficaz considerando a capacidade do pátio e das docas.

Critérios de Aceitação:

- Bloqueio de agendamento quando superado a capacidade do pátio e docas no horário selecionado.
- Notificação de agendamento ao fornecedor e equipe responsável pelo recebimento.

## RF02 - Controlar chegada de Entregas
O sistema deve registrar e monitorar a chegada de caminhões ao CD notificando os responsáveis e garantindo que há vaga no pátio ou docas.

Critérios de Aceitação:

- O sistema atualiza o status quando um caminhão chega ao CD ou encerra o descarregamento.
- O sistema alerta aos responsáveis quando chega caminhões sem agendamento.
- O sistema exibe a lista de caminhões que chegaram e estão aguardando para descarregar.

## RF03 - Controlar ocupação no Pátio e Docas
O sistema deve monitorar a disponibilidade e ocupação do pátio e das docas em tempo real sinalizando congestionamentos e sugerindo redistribuição de cargas evitando gargalos.

Critérios de Aceitação:

- O sistema exibe em tempo real a ocupação do pátio e docas com taxa de ocupação. Exemplo: Pátio e docas 80% ocupados.
- O sistema alerta os supervisores para quando a capacidade máxima estiver próxima de ser atingida.

## RF04 - Gerenciar Entregas Dentro do Expediente
O sistema deve restringir ou alertar sobre entregas que estejam fora do horário comercial mas possibilitando exceções como entregas urgentes.

Critérios de Aceitação:

- O campo de horários no agendamento deve se restringir apenas a horários comerciais.
- Quando pressionado opção de urgência é possível selecionar horário fora do horário comercial.

## RF05 - Gerenciar Tempo Médio de Descarregamento
O sistema deve calcular e armazenar tempos médios de descarregamento para otimização e gerenciamento dos agendamentos.

Critérios de Aceitação:

- O sistema calcula o tempo de descarregamento desde o inicio do processo até a conclusão.
- O sistema gera relatórios mensais sobre os tempos médios de descarregamento.
- O sistema permite visualizar estatísticas de tempo médio por fornecedor e tipo de carga.

## RF06 - Controlar Fornecimentos sem Aviso Prévio
O sistema deve registrar e tratar entregas inesperadas possibilitando um plano de contingência  que otimize o recebimento desses caminhões.

Critérios de Aceitação:

- O sistema notifica os responsáveis sobre uma entrega inesperada.
- O sistema permite realocar recursos para descarregar a carga imprevista.

## RF07 - Monitorar Entregas em Tempo Real
O sistema deve permitir que os usuários acompanhem o status das entregas em tempo real disponibilizando dashboards com informações sobre entregas em andamento, concluídas e atrasadas.

Critérios de Aceitação:

- O sistema exibe um dashboard com as entregas em andamento, concluídas e pendentes.
- O dashboard possui um campo de filtro de entregas por fornecedor, status e horário.
- O sistema atualiza automaticamente o status das entregas conforme a chegada e descarregamento dos caminhões. 

## RF08 - Notificar e Alertar Automaticamente mudanças em status
O sistema deve enviar notificações de alertas para supervisores e motoristas sobre eventuais mudanças de status ou problemas nas entregas.

Critérios de Aceitação:

- O sistema envia notificações por pop-up quando uma entrega está a caminho ou atrasada.
- O sistema envia notificações por pop-up sobre mudanças de horário no agendamento seja ao fornecedor ou supervisor.

## RF09 - Agendar Entrega
O sistema deve possuir área de agendamento com horários disponíveis.

Critérios de Aceitação:

- O agendamento possui campos de inserção dos dados da entrega, veículo e seleção de horários disponíveis.
