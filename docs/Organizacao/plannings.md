As reuniões de planejamento são essenciais para o desenvolvimento de um projeto. Elas são responsáveis por definir o que será feito, por quem e em quanto tempo. A equipe Ativar Cidadão utilizou o método de planejamento chamado de **Sprint Planning**.

## Aprovações
Após a reunião de planejamento, a equipe Ativar Cidadão realizou uma reunião de aprovação com o supervisor junto ao negócio, o Centro de Informações Estratégicas em Vigilância em Saúde de Campo Grande-MS (CIEVS-CG), para validar o que foi planejado e garantir que o projeto está alinhado com as expectativas do cliente, para seguir o desenvolvimento.

## Lista de atividades por Sprint
=== "Sprint 01"

    | **Épico**          | **História de Usuário**        | **Tarefas**                                             | **Responsável**   |
    |--------------------|--------------------------------|---------------------------------------------------------|-------------------|
    | CHATBOT            | Orquestrar trilha de perguntas | Projetar e documentar arquitetura do Chatbot            | Breno e Guilherme |
    |                    |                                | Estudar sobre árvores de decisão                        | Guilherme e Breno |
    |                    |                                | Desenvolver POC da trilha utilizando árvore de decisão  | Guilherme e Breno |
    |                    | Integrar API do WhatsApp       | Estudar API do WhatsApp                                 | Breno e Guilherme |
    |                    |                                | Conseguir a aquisição e acesso do WhatsApp Business API | Guilherme e Breno |
    |                    |                                | Configurar o WhatsApp Business API                      | Breno e Guilherme |
    | AUTENTICAÇÃO       | Redefinir Senha                | Desenvolver protótipo de baixa fidelidade               | Enzo              |
    |                    | Realizar Login                 | Estudar TypeORM                                         | Sobrinho          |
    |                    |                                | Desenvolver backend do login                            | Sobrinho          |
    |                    |                                | Desenvolver testes de integração (API)                  | Sobrinho          |
    |                    |                                | Desenvolver frontend do login                           | Maycon            |
    |                    |                                | Desenvolver protótipo de baixa fidelidade               | Enzo              |
    |                    |                                | Desenvolver protótipo de alta fidelidade                | Enzo              |
    |                    |                                | Documentar a API no Swagger                             | Sobrinho          |
    |                    |                                | Escrever histórias de usuário e critérios de aceitação  | Lameirão          |
    | GESTÃO DE USUÁRIOS | Listagem de Usuários           | Desenvolver frontend de listagem de usuário             | Maycon            |
    |                    |                                | Desenvolver protótipo de baixa fidelidade               | Lameirão          |
    |                    |                                | Desenvolver protótipo de alta fidelidade                | Lameirão          |
    |                    |                                | Escrever história de usuário e critérios de aceite      | Lameirão          |
    |                    | Cadastrar Usuário              | Desenvolver backend do cadastro de usuário              | Sobrinho          |
    |                    |                                | Desenvolver testes de integração (API)                  | Sobrinho          |
    |                    |                                | Desenvolver frontend de cadastro de usuário             | Maycon            |
    |                    |                                | Desenvolver protótipo de baixa fidelidade               | Lameirão          |
    |                    |                                | Desenvolver protótipo de alta fidelidade                | Lameirão          |
    |                    |                                | Escrever histórias de usuário e critérios de aceitação  | Lameirão          |
    |                    |                                | Documentar a API no Swagger                             | Sobrinho          |
    |                    | Editar Usuário                 | Desenvolver frontend de edição de usuário               | Maycon            |
    |                    |                                | Escrever histórias de usuário e critérios de aceitação  | Lameirão          |
    |                    |                                | Desenvolver protótipo de baixa fidelidade               | Lameirão          |
    |                    |                                | Desenvolver protótipo de alta fidelidade                | Lameirão          |
    |                    | Visualizar Usuário             | Desenvolver protótipo de baixa fidelidade               | Lameirão          |
    |                    |                                | Desenvolver protótipo de alta fidelidade                | Lameirão          |
    | DASHBOARDS         | Visualizar dados gerais        | Desenvolver tela de dashboards                          | Enzo              |
    |                    |                                | Desenvolver protótipo de baixa fidelidade               | Lameirão          |
    |                    |                                | Desenvolver protótipo de alta fidelidade                | Lameirão          |
    | DOCUMENTAÇÃO       | -                              | Definir e documentar style guide da aplicação           | Enzo              |

=== "Sprint 02"
    | Épico              | História de Usuário                 | Tarefas                                                            | Responsável                 |
    |--------------------|-------------------------------------|--------------------------------------------------------------------|-----------------------------|
    | CHATBOT            | Criar trilha de perguntas do Chabot | Reunião com o CIEVS para criação de uma trilha de perguntas prévia | Guilherme                   |
    |                    |                                     | Desenvolver a trilha de perguntas no Chatbot                       | Guilherme                   |
    |                    |                                     | Persistir variáveis da conversa no banco do Chabot                 | Guilherme                   |
    |                    |                                     | Desenvolver custom action para cadastrar um rumor                  | Guilherme, Sobrinho e Breno |
    | AUTENTICAÇÃO       | Realizar Login                      | Desenvolver testes de integração (API)                             | Sobrinho                    |
    |                    |                                     | Documentar caso de testes                                          | Lameirão                    |
    |                    |                                     | Criar evidências para o caso de teste                              | Lameirao                    |
    | GESTÃO DE USUÁRIOS | Listagem de Usuários                | Desenvolver teste de integração (API)                              | Sobrinho                    |
    |                    |                                     | Documentar caso de testes                                          | Enzo                        |
    |                    |                                     | Criar paginação no Backend                                         | Breno                       |
    |                    |                                     | Criar paginação no Frontend                                        | Maycon                      |
    |                    |                                     | Criar evidências para caso de teste                                | Enzo                        |
    |                    | Cadastrar Usuário                   | Desenvolver testes de integração (API)                             | Sobrinho                    |
    |                    |                                     | Documentar caso de testes                                          | Enzo                        |
    |                    |                                     | Criar evidências para a caso de teste                              | Enzo                        |
    |                    |                                     | Adicionar confirmação de senha no frontend                         | Lameirão                    |
    |                    | Editar Usuário                      | Desenvolver frontend de edição de usuário                          | Maycon                      |
    |                    |                                     | Escrever histórias de usuário e critérios de aceitação             | Lameirão                    |
    |                    |                                     | Desenvolver teste de integração (API)                              | Sobrinho                    |
    |                    |                                     | Documentar no Swagger                                              | Sobrinho                    |
    |                    |                                     | Documentar casos de testes                                         | Enzo                        |
    |                    |                                     | Criar evidências para caso de teste                                | Enzo                        |
    |                    | Visualizar Usuário                  | Criar história de usuário                                          | Lameirão                    |
    |                    |                                     | Desenvolver backend para visualizar um único usuário               | Sobrinho                    |
    |                    |                                     | Desenvolver frontend para visualizar um único usuário              | Lameirão                    |
    |                    | Realizar logout                     | Desenvolver backend para fazer Logout                              | Breno                       |
    |                    |                                     | Desenvolver frontend para fazer Logout                             | Enzo                        |
    |                    |                                     | Criar história de usuário                                          | Lameirão                    |
    |                    |                                     | Criar evidências para caso de teste                                | Enzo                        |
    |                    |                                     | Documentar casos de teste                                          | Enzo                        |
    | GESTÃO DE RUMORES  | Cadastro de rumores                 | Escrita da história de usuário                                     | Lameirão                    |
    |                    |                                     | Desenvolver custom action para cadastrar um rumor                  | Guilherme                   |
    |                    |                                     | Desenvolver backend para fazer cadastro de rumor                   | Breno e Sobrinho            |
    |                    |                                     | Desenvolver serviço para cadastrar conversas no backend            | Breno e Sobrinho            |

=== "Sprint 03"
    | Épico             | História de Usuário                      | Tarefas                                                                 | Responsável | Status   |
    |-------------------|------------------------------------------|-------------------------------------------------------------------------|-------------|----------|
    | Gestão de Rumores | Cadastro de Rumores                      | Desenvolver custom action para cadastrar um rumor                       | Guilherme   | Pendente |
    |                   |                                          | Desenvolver backend para fazer cadastro de rumor                        | Breno       | Pendente |
    |                   |                                          | Desenvolver testes de integração                                        | Breno       | Pendente |
    |                   |                                          | Ajustar documentação do Swagger para o endpoint                         | Breno       | Pendente |
    |                   |                                          | Escrita da história de usuário                                          | Lameirão    | Pendente |
    |                   | Listagem de Rumores                      | Desenvolver protótipo de baixa fidelidade                               | Lameirão    | Pendente |
    |                   |                                          | Desenvolver protótipo de alta fidelidade                                | Lameirão    | Pendente |
    |                   |                                          | Validação com o negócio                                                 | Lameirão    | Pendente |
    |                   |                                          | Desenvolver a história de usuário                                       | Maycon      | Pendente |
    |                   |                                          | Desenvolver o frontend para listagem de rumor                           | Maycon      | Pendente |
    |                   |                                          | Desenvolver o backend para listagem de rumor                            | Breno       | Pendente |
    |                   |                                          | Criar testes de integração para o Backend                               | Breno       | Pendente |
    |                   |                                          | Criar testes funcionais para o Frontend                                 | Enzo        | Pendente |
    |                   |                                          | Criar evidência para o Frontend                                         | Enzo        | Pendente |
    |                   | Avaliação de Rumor                       | Desenvolver protótipo de baixa fidelidade                               | Lameirão    | Pendente |
    |                   |                                          | Desenvolver protótipo de alta fidelidade                                | Lameirão    | Pendente |
    |                   |                                          | Validação com o negócio                                                 | Lameirão    | Pendente |
    |                   |                                          | Criar história de usuário                                               | Lameirão    | Pendente |
    |                   |                                          | Desenvolver backend para avaliação de rumor                             | Breno       | Pendente |
    |                   |                                          | Criar evidências para o caso de uso                                     | Maycon      | Pendente |
    |                   |                                          | Documentar caso de testes                                               | Maycon      | Pendente |
    |                   |                                          | Desenvolver testes de integração                                        | Breno       | Pendente |
    |                   |                                          | Desenvolver frontend para avaliação de rumor                            | Enzo        | Pendente |
    |                   | Visualização de Rumor                    | Desenvolver protótipo de baixa fidelidade                               | Lameirão    | Pendente |
    |                   |                                          | Documentar caso de testes                                               | Enzo        | Pendente |
    |                   |                                          | Desenvolver protótipo de alta fidelidade                                | Lameirão    | Pendente |
    |                   |                                          | Validação com o negócio                                                 | Lameirão    | Pendente |
    |                   |                                          | Criar história de usuário                                               | Lameirão    | Pendente |
    |                   |                                          | Desenvolver backend para visualizar um rumor                            | Breno       | Pendente |
    |                   |                                          | Desenvolver frontend para visualizar um rumor                           | Lameirão    | Pendente |
    |                   |                                          | Criar testes de integração                                              | Breno       | Pendente |
    |                   |                                          | Criar evidências para o caso de uso                                     | Enzo        | Pendente |
    | -                 | Refinar a trilha de perguntas do Chatbot | Criar tratamento para as variáveis tipar Chatbot                        | Guilherme   | Pendente |
    |                   |                                          | Mapear atributos para o envio do Backend (Chatbot)                      | Guilherme   | Pendente |
    |                   |                                          | Criar fluxos alternativos para o Chatbot (Chatbot)                      | Sobrinho    | Pendente |
    |                   |                                          | Estudar na literatura sobre processo de desenvolvimento de Chatbot      | Sobrinho    | Pendente |
    |                   |                                          | Criar mais casos de usos para treinar o Chatbot (Chatbot)               | Sobrinho    | Pendente |
    |                   |                                          | Estudar alternativa para reenvio de rumores em caso de falha do Backend | Sobrinho    | Pendente |
    |                   |                                          | Criar validação dos dados de entrada (Chatbot)                          | Guilherme   | Pendente |

=== "Sprint 04"
    | **Épico**         | **História de Usuário**  | **Tarefas**                                | **Responsável** | **Status** |
    |-------------------|--------------------------|--------------------------------------------|-----------------|------------|
    | Gestão de Rumores | Exportação dos Rumores   | Desenvolvimento do Frontend                | Enzo            |            |
    |                   |                          | Desenvolver testes de integração           | Breno           |            |
    |                   |                          | Criar protótipo de baixa fidelidade        | Lameirão        |            |
    |                   |                          | Criar protótipo de alta fidelidade         | Lameirão        |            |
    |                   |                          | Validação com o negócio                    | Lameirão        |            |
    |                   |                          | Criar evidências para o caso de uso        | Maycon          |            |
    |                   |                          | Criar casos de testes                      | Maycon          |            |
    |                   |                          | Criar a história de usuário                | Lameirão        |            |
    |                   |                          | Realizar estudo sobre exportação           | Breno           |            |
    |                   |                          | Desenvolver endpoints necessários          | Breno           |            |
    | Dashboards        | Visualizar dados gerais  | Desenvolver protótipo de baixa fidelidade  | Lameirão        |            |
    |                   |                          | Desenvolver o frontend                     | Maycon          |            |
    |                   |                          | Desenvolver protótipo de alta fidelidade   | Lameirão        |            |
    |                   |                          | Validação com o negócio                    | Lameirão        |            |
    |                   |                          | Escrever a história de usuário             | Lameirão        |            |
    |                   |                          | Desenvolver o backend                      | Sobrinho        |            |
    |                   |                          | Criar testes de integração para o Backend  | Sobrinho        |            |
    |                   |                          | Criar testes funcionais para o Frontend    | Maycon          |            |
    |                   |                          | Criar evidência para o Frontend            | Enzo            |            |
    |                   |                          | Criar caso de testes                       | Enzo            |            |
    | Chatbot           | Timeout Chabot           | Desenvolver o timeout funcional no chatbot | Guilherme       |            |
    | Infraestrutura    | Implantação da aplicação | Atividades Maycon                          | Maycon          |            |
    |                   |                          | Atividades Lameirão                        | Lameirão        |            |
