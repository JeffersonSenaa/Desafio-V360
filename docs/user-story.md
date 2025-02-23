# User Story Map

## Backlog de Requisitos
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


## User Stories
| Requisito | Descrição |
| :---:     | :-------: |
| US01 | Eu, como coordenador de Logística, desejo agendar uma entrega para definir o horário que essa entrega ocorrerá. |
| US02 | Eu, como coordenador de logística, desejo controlar os agendamentos para distribuir os horários conforme capacidade do CD. |
| US03 | Eu, como analista de suprimentos, desejo ter acesso ao monitoramento das entregas em tempo real para monitorar quando serão realizadas |
| US04 | Eu, como analista de suprimentos, desejo ser notificado por mudanças nos status das entregas para ter conhecimento do andamento da entrega. |
| US05 | Eu, como supervisor de recebimento, desejo ter conhecimento da ocupação do pátio e docas do CD para ter controle sobre os recebimentos. |
| US06 | Eu, como supervisor de recebimento, desejo gerenciar a chegada das entregas para garantir que não haja atrasos ou superlotação. |
| US07 | Eu, como spervisor de Suprimentos, desejo monitorar o tempo médio de descarregamento para  melhorar a gestçao logística. |
| US08 | Eu, como supervisor de recebimento, desejo gerenciar fornecimentos sem aviso prévio para fazer realocações necessárias para capacidade do CD. |
| US09 | Eu, como supervisor de recebimento, desejo gerenciar entregas fora do expediente para considerar apenas entregas urgentes nesses horários. |


## Matriz de Rastreabilidade US - RF
Segue a matriz de rastreabilidade completa, relacionando os requisitos (colunas) com as funcionalidades (linhas). Cada célula indica se o requisito atende diretamente (✔) ou parcialmente (○).


| US / RF                   | RF01| RF02| RF03| RF04| RF05| RF06| RF07| RF08| RF09|
|------------------------------------------|---|----|----|----|----|---|---|--|---|
| **US01** - Agendar uma entrega          | ✔ | ○    |    |    |   |   |   |   | ✔    |
| **US02** - Controlar agendamentos       | ✔ | ○    |     |     |    |   |   |   | ✔    |
| **US03** - Monitorar entregas em tempo real |   | ✔    | ○    |   |   |   | ✔    |   |   |
| **US04** - Notificação de mudanças      |   | ✔    |   |   |   |   |   | ✔    |   |
| **US05** - Ocupação do pátio e docas     |   |   | ✔    |   |   |   |   |   |   |
| **US06** - Gerenciar chegada de entregas |   | ✔    | ○    |   |   | ✔    |   |   |   |
| **US07** - Monitorar tempo de descarregamento |   |   |   |   | ✔    |   | ✔    |   |   |
| **US08** - Fornecimentos sem aviso prévio |   |   | ○    |   |   | ✔    |   |   |   |
| **US09** - Gerenciar entregas fora do expediente |   |   |   | ✔    |   |   |   |   |   |  

## MosCow - Priorização
Foi priorizado as US's que mais contemplam os requisitos.

Tabela de priorização utilizando MoSCoW, baseada na quantidade de **RFs cobertos** por cada **User Story (US)**. A principal métrica utilizada fé o número de Requisitos atendidos por cada US.

###  Tabela de Priorização MoSCoW
| **User Story** | **RFs Cobertos** | **MoSCoW** | **Justificativa** |
|---------------|---------------|----------|----------------|
| **US01** - Agendar uma entrega | 2 (RF01, RF09) | **Must Have** | Essencial para iniciar qualquer planejamento logístico. |
| **US02** - Controlar agendamentos | 2 (RF01, RF09) | **Must Have** | Sem essa funcionalidade, não há controle sobre os horários. |
| **US03** - Monitorar entregas em tempo real | 3 (RF02, RF03, RF07) | **Must Have** | Importante para otimizar o fluxo, mas o sistema pode operar sem isso no MVP. |
| **US04** - Notificação de mudanças | 2 (RF02, RF08) | **Should Have** | Facilita o acompanhamento, mas não bloqueia o funcionamento do sistema. |
| **US05** - Ocupação do pátio e docas | 1 (RF03) | **Could Have** | Agrega valor, mas não é essencial para as operações iniciais. |
| **US06** - Gerenciar chegada de entregas | 3 (RF02, RF03, RF06) | **Must Have** | Fundamental para evitar atrasos e superlotação. |
| **US07** - Monitorar tempo de descarregamento | 2 (RF05, RF07) | **Should Have** | Melhora eficiência, mas pode ser adicionado depois. |
| **US08** - Fornecimentos sem aviso prévio | 2 (RF03, RF06) | **Must Have** | Útil para situações imprevisíveis, mas não é crítico. |
| **US09** - Gerenciar entregas fora do expediente | 1 (RF04) | **Could Have** | Específico para exceções, não é prioritário para o MVP. |



## Modelagem
<center>
<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVIagfK8k=/?moveToViewport=-2892,-2332,6730,3375&embedId=39056193675" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe></center>