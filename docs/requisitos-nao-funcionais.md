# Requisitos Não Funcionais

O sistema de Agendamento de Entregas deve conter requisitos não funcionais que garantem a eficiência do sistema, segurança, compatibilidade e conformidade com normas. Esses requisitos, buscam assegurar uma a ferramenta robusta e confiável atendendo aos padrões necessários para uma operação eficiente.

### RNF01 - Segurança e Controle de Acesso
O acesso ao sistema deve ser por meio de autenticação via login e senha com criptografia. 

### RNF02 - Segurança
Devem ser armazenados com criptografia AES-256 todos os dados de usuários e transações.

### RNF03 - Segurança e Controle de Acesso
O sistema permite criação de diferentes níveis de acesso. 

### RNF04 - Integração
O sistema deve ter compatibilidade com ERP da empresa via API REST.

### RNF05 - Conformidade e Normas
O sistema deve estar em conformidade com a LGPD (Lei Geral de Proteção de Dados).

### RNF06 - Usabilidade
O sistema deve ser responsivo sendo uma aplicação Web e Mobile.

### RNF07 - Usabilidade
O sistema deve seguir as heurísticas de usabilidade de Nielsen para garantia de clareza e fácil navegação.

### RNF08 - Desempenho
Para consultas de status de entrega, o tempo de resposta deve ser igual ou inferior a 1 segundo.

### RNF09 - Desempenho
Para as páginas principais, o tempo de carregamento deve ser inferior a 3 segundos.
