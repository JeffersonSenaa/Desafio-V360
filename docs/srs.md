# Especificação de Requeisitos de Software

## 1. Introdução

## 1.1 Visão Geral
O sistema de agendamento de entregas é uma solução de gestão logística que gerencia os agendamentos para otimizar o planejamento e a execução das entregas com base na capacidade do CD e horários de entregas. Esta ferramenta permite a alocação eficiente de horários e recursos reduzindo os atrasos nas entregas e melhorando a produtividade no CD utilizando automações, controle de fluxo e agendamento para garantir as entregas sem exceder a capacidade do Pátio e docas do Centro de Distribuição. <br>
O propósito deste documento de Especificação de Requisitos de Software(SRS) é documentar os requisitos funcionais e não funcionais do sistema podendo ser entendido a todas as partes envolvida no projeto.

## 1.2 Escopo
O sistema permitirá que fornecedores e colaboradores, de forma online, agendem entregas a partir de horários disponíveis e capacidade do CD. Os supervisores poderão gerenciar e visualizar os agendamentos em tempo real com visualizadores responsivos e interativos. Esta solução reduz os atrasos e congestionamentos melhorando a produtividade logística e abastecimento de suprimentos para o setor. Esta ferramenta é capaz de tratar entregas sem aviso prévio e agendamentos fora do horário de expediente, considerando casos especiais. Este sistema aprimora os processos logísticos no setor para garantir eficiência e gera relatórios das entregas proporcionando estatísticas que identificam gargalos e pontos de melhoria. Este software, garante integração com ERP da empresa sincronizando informações.

## 1.3 Definições e Siglas

- CD: Centro de Distribuição.
- Docas: Áreas de descarga de caminhões no Centro de Distribuição.
- Pátio: Espaço físico no Centro de Distribuição onde os caminhões aguardam para descarregar.
- Agendamento: Processo de reserva de data e hora para a entrega de materiais no CD.
- Fornecedor – Empresa ou indivíduo responsável pela entrega dos materiais
- RF: Requisito Funcional.
- RNF: Requisito Não Funcional.
- SRS: Documento de Especificação de Requisitos de Software.
- ERP – Enterprise Resource Planning (Sistema de Gestão Empresarial)

## 2. Descrição Geral

## 2.1 Perspectiva do Produto
O sistema de controle de agendamentos de entregas para o Centro de Distribuição soluciona a falta de visibilidade das entregas de materiais que são destinados ao processo produtivo da indústria. Atualmente, os diversos desafios enfrentados pelo CD como congestionamento no pátio, ociosidade das docas e dificuldades no planejamento logístico geram atrasos e paradas nas linhas de produção.

A solução proposta é o desenvolvimento de um sistema web centralizado, acessível por diferentes perfis de usuários e diferentes níveis de acesso, que permitirá o agendamento prévio das entregas, a notificação automática para mudanças de status e o monitoramento em tempo real. O sistema será integrado ao ERP da empresa e aos processos internos podendo ser acessado por fornecedores e transportadoras, garantindo uma gestão logística eficiente do fluxo de entregas e otimização das operações.

## 2.2 Funções do Sistema
Para solucionar os problemas identificados, o sistema oferecerá as seguintes funcionalidades:

- **Controlar o Agendamento de Entregas:** O sistema permitirá que fornecedores e transportadoras agendem previamente as entregas no CD.

- **Controlar a chegada de Entregas:** O sistema registrará a chegada de veículos e deverá associá-los a seus respectivos agendamentos.

- **Controlar a ocupação no Pátio e Docas:** O sistema monitorará a disponibilidade de espaço gerenciando ocupação para evitar congestionamentos e tempos de espera excessivos.

- **Gerenciar as Entregas Dentro do Expediente:** O sistema garantirá que as entregas ocorram nos horários estabelecidos e dentro do expedinte do CD, minimizando custos com horas extras. Essa funcionalidade permite exceções como entregas com urgência.

- **Monitorar o tempo Médio de Descarregamento:** O sistema deverá registrar e analisar o tempo necessário de descarregamento dos caminhões, permitindo ajustes operacionais.

- **Controlar fornecimentos sem aviso prévio:** O sistema deverá registrar e tratar casos de entregas não agendadas minimizando os impactos na operação.

- **Monitorar as entregas em Tempo Real:** O sistema deverá fornecer informações atualizadas sobre os horários de chegada dos caminhões e o status das entregas.

- **Notificar e Alertar Automaticamente mudanças em status:** O sistema deverá enviar alertas aos usuários responsáveis sobre alterações nas entregas, como atrasos ou alterações na doca de descarga.

- **Agendar Entrega:** O sistema deverá ter uma interface intuitiva para fornecedores e transportadoras realizarem agendamentos de forma eficiente e organizada.


## 2.3 Perfil dos Usuários

Os usuários deverão ter acesso a funcionalidades específicas dentro do sistema para garantir que todas as operações sejam realizadas de forma eficiente e transparente. Foi mapeado o perfil dos usuários definindo necessidades e responsabilidades distintas:

- **Supervisor de Recebimento:** Responsável por garantir a organização do pátio e docas. Necessita de um sistema que permita visualizar os agendamentos, monitorar a chegada de caminhões e otimizar os recursos disponíveis.

- **Analista de Suprimentos:** Responsável por garantir que os materiais cheguem no prazo correto para evitar impactos na produção. Necessita de visibilidade sobre os agendamentos e ferramentas para controle de atrasos e entregas fora do expediente.

- **Coordenador de Logística:** Responsável por gerenciar o fluxo logístico do CD. Necessita de um sistema que possibilite planejar e antecipar entregas, evitando problemas operacionais e custos adicionais com congestionamentos e reprogramação de equipe.

</br>
</br>
</br>