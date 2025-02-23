# Requisitos Funcionais

Foram levantados e analisados os requisitos da solução afim de solucionar os problemas encontrados no fluxo de tarefas atual. Com isso, este produto propõe melhorias e qualidade nos processos realizados no centro de distribuição.

## Tabela de Requisitos
| Requisito | Descrição |
| :---:     | :-------: |
| RF01 | Controlar Agendamento de Entregas |
| RF02 | Controlar chegada de Entregas |
| RF03 | Controlar ocupação no Pátio e Docas |
| RF04 | Gerenciar Entregas Dentro do Expediente |
| RF05 | Monitorar Tempo Médio de Descarregamento |
| RF06 | Controlar Fornecimentos sem Aviso Prévio |
| RF07 | Monitorar Entregas em Tempo Real |
| RF08 | Notificar e Alertar Automaticamente mudanças em status |
| RF09 | Agendar Entrega |

## Descrição dos Requisitos e Critérios de Aceitação

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

## RF05 - Monitorar Tempo Médio de Descarregamento
O sistema deve calcular e armazenar tempos médios de descarregamento para otimizar a gestão logística e gerenciamento dos agendamentos.

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


## Associação do RF com as Personas

**Supervisor de Recebimento** </br>
Problemas: 

- Falta de organização no pátio e docas, causando congestionamento ou ociosidade.
- Desconhecimento sobre a chegada dos caminhões, impactando a produtividade.
- Dificuldades para descarregar os caminhões de forma eficiente.

**Requisitos que solucionam o problema:**

| **RF** | **Descrição** | **Justificativa** |
|--------|-------------|------------------|
| **RF02** | Controlar a chegada de Entregas | Garantir a visibilidade sobre quais caminhões estão chegando ou quando chegarão. |
| **RF03** | Controlar a ocupação no Pátio e Docas | Evita superlotação ou ociosidade, melhorando o fluxo. |
| **RF05** | Monitorar o Tempo Médio de Descarregamento | Ajudar a otimização do processo de descarregamento, reduzindo atrasos. |
| **RF06** | Controlar os Fornecimentos sem Aviso Prévio | Permitir realocação rápida de espaço e recursos para entregas inesperadas. |


**Analista de Suprimentos** </br>
Problemas:

- Falta de visibilidade sobre os agendamentos de entrega.
- Materiais chegando fora do horário previsto ou fora do expediente.
- Problemas com armazenamento e custos extras devido à falta de controle.

**Requisitos que solucionam o problema:**

| **RF** | **Descrição** | **Justificativa** |
|--------|-------------|------------------|
| **RF01** | Controlar o Agendamento de Entregas | Garantir que as entregas sejam programadas de forma eficiente. |
| **RF04** | Gerenciar as Entregas Dentro do Expediente | Evitar as entregas fora do horário, reduzindo custos extras e desorganização. |
| **RF07** | Monitorar as Entregas em Tempo Real | Visibilidade sobre o status das entregas, permitindo melhor planejamento. |
| **RF08** | Notificar e Alertar Automaticamente mudanças em status | Ajudar a reagir rapidamente a alterações nos agendamentos e minimizar impactos. |


**Coordenador de Logística** </br>
Problemas:

- Falta de um sistema de agendamento e monitoramento das entregas.
- Congestionamento no pátio e desorganização dos recursos devido à falta de planejamento.
- Impacto no tempo de espera dos motoristas e aumento dos custos operacionais.

**Requisitos que solucionam o problema:**

| **RF** | **Descrição** | **Justificativa** |
|--------|-------------|------------------|
| **RF01** | Controlar Agendamento de Entregas | Permite distribuir as entregas ao longo do dia e evitar congestionamento. |
| **RF02** | Controlar chegada de Entregas | Dá visibilidade antecipada sobre quais caminhões estão chegando. |
| **RF03** | Controlar ocupação no Pátio e Docas | Evita sobrecarga ou ociosidade dos espaços de descarga. |
| **RF06** | Controlar Fornecimentos sem Aviso Prévio | Minimiza impactos das entregas não planejadas. |
| **RF07** | Monitorar Entregas em Tempo Real | Permite acompanhar o fluxo de entregas e tomar decisões rápidas. |
