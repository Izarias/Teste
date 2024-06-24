<details>
  <summary><b> RF22 - Pedro Izarias  </b></summary>

#### Versões do Requisito
A tabela abaixo mostra as versões do requisito RF22.

**Tabela 90:** Versão do requisito RF22.

| Versão | Rastreabilidade |
| ------ | --------------- |
| Versão 1 | [RF22](Elicitacao/ResquisitosCorrigidos.md) |

**Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Estrutura de Desenvolvimento do Requisito
A tabela abaixo mostra a estrutura do requisito RF22.

**Tabela 91:** Estrutura do requisito RF22.

| Características | Explicação | Rastreabilidade |
| --------------- | ---------- | --------------- |
| Nome do Requisito | Usuário empresa pode atualizar dados dos funcionários | [RF22](Elicitacao/ResquisitosCorrigidos.md) |
| Alocação no App | Na região de gerenciamento de funcionários | [Diagrama de Caso de Uso](ignore/IgnoreDiagramaCasoUso.md) |
| Resolução de requisitos em conflito | Este requisito não conflita com outros requisitos, mas necessita de uma base de dados atualizada e precisa. | - |
| Verificação | Verificar se a funcionalidade permite a atualização correta dos dados dos funcionários ou realizar testes com dados reais. | - |
| Correção de Defeitos | Através de relatórios e de feedbacks de usuários. | - |
| Análise de impacto na evolução | Baixo impacto: Afeta principalmente a interface de usuário e a atualização de dados de funcionários. | - |

**Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Artefatos Gerados Pelos Requisitos Funcionais
A tabela abaixo mostra os artefatos gerados pelo requisito RF22.

**Tabela 92:** Artefatos Gerados pelo requisito RF22.

| Artefato | Identificador | Rastreabilidade |
| -------- | ------------- | --------------- |
| Cenário | <li> [Visualizar aba "Emprego"](modelagem/cenarios.md) <br> <li> [Atualização dos Contratos de Trabalho](modelagem/cenarios.md) | [Cenários](modelagem/cenarios.md) |
| Léxico | **Verbo:** <br> <li> [Atualizar Dados](modelagem/lexico.md) <br> <br> **Objeto:** <br> <li> [Funcionário](modelagem/lexico.md) <br> <li> [Dados do Funcionário](modelagem/lexico.md) <br> <br> **Estado:** <br> <li> [Dados Atualizados](modelagem/lexico.md) | [Léxicos](modelagem/lexico.md) |
| Casos de Uso | <li> [UC03 - Trabalhador acessa detalhes dos contratos de trabalho](modelagem/casoDeUso.md) <br> <li> [UC10 - Verificar dados relacionados ao FGTS e INSS](modelagem/casoDeUso.md) | [Casos de Uso](modelagem/casoDeUso.md) |
| Especificação Suplementar | **Para a implementação:** <br> <li> RI01 - Integração com eSocial <br> <li> RI03 - Permitir integração com vários outros softwares <br> <br> **Para a confiabilidade:** <br> <li> CON02 - O sistema deve possuir as informações atualizadas e condizentes com a realidade. <br> <li> CON03 - O sistema deve manter íntegra as informações sobre o usuário e seus contratos de trabalho. | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário | [HI22 - Atualizar dados do funcionário](modelagemAgil/historiaUsuario.md) | [História de Usuário](modelagemAgil/historiaUsuario.md) |
| Backlog | <li> [Tema: TM02 - Contratos de Trabalho e Benefícios](modelagemAgil/backlog.md) <br> <li> [Épico: EP03 – Contratos](modelagemAgil/backlog.md) <br> <li> [História: HI22 - Como usuário, eu quero atualizar os dados dos funcionários para manter as informações atualizadas.](modelagemAgil/backlog.md) | [Backlog](modelagemAgil/backlog.md) |

**Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Elos
A tabela abaixo mostra os elos do requisito RF22.

**Tabela 93:** Elos do requisito RF22.

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO | Requisitos Relacionados |
| ----------- | --------- | --------------------- | ---------------- | ----------------------- |
| Recurso | Desenvolvimento | <li> Módulo de Atualização de Dados <br> <li> Base de Dados de Funcionários <br> <li> Componentes de Interface para Atualização de Dados | O Módulo de Atualização de Dados utiliza a Base de Dados de Funcionários e os Componentes de Interface para permitir a atualização dos dados dos funcionários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF04: Usuário pode atualizar suas informações pessoais <br> <li> RF06: Usuário trabalhador pode atualizar contratos de trabalho <br> <li> RF14: Usuário trabalhador pode atualizar(declarar) currículo <br> <li> RF25: Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos) <br> <br> Requisitos não funcionais: <br> <li> RNF05: Todos os textos do sistema devem seguir os padrões tipográficos e de siglas, abreviações e erros conforme as normas. <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. <br> <li> RNF20: O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%. |

**Autor:** [Pedro Izarias](https://github.com/Izarias)

</details>

<details>
  <summary><b> RF23 - Pedro Izarias  </b></summary>
A tabela abaixo mostra as versões do requisito RF23.

**Tabela 94:** Versão do requisito RF23.
  
#### Versões do Requisito

| Versão                              | Rastreabilidade                                  |
| ----------------------------------- | ------------------------------------------------ |
| Versão 1                            | [RF23](Elicitacao/ResquisitosCorrigidos.md)      |

- **Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Estrutura de Desenvolvimento do Requisito
A tabela abaixo mostra a estrutura do requisito RF23.

**Tabela 95:** Estrutura do requisito RF23.

| Características                     | Explicação                                                                                  | Rastreabilidade                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Nome do Requisito                   | Usuário pode gerenciar suas notificações por meio do aplicativo                             | [RF23](Elicitacao/ResquisitosCorrigidos.md)         |
| Alocação no App                     | Na área de configurações de perfil do usuário e dentro de cada seção de notificações específicas | [Diagrama de Caso de Uso](ignore/IgnoreDiagramaCasoUso.md) |
| Resolução de requisitos em conflito | Este requisito não conflita com outros requisitos, mas depende da funcionalidade de envio e recebimento de notificações. | -                                                   |
| Verificação                         | Verificar se o usuário pode configurar suas preferências de notificação e se as notificações são entregues corretamente. | Será realizada pelo grupo em breve                   |
| Correção de Defeitos                | Através de relatórios de feedbacks dos usuários.                                       | Não foi necessário corrigir falhas para esse requisito no decorrer do desenvolvimento. |
| Análise de impacto na evolução      | Baixo impacto: Afeta principalmente a interface de usuário e a funcionalidade de notificação. | -                                                   |

#### Artefatos Gerados Pelos Requisitos Funcionais
A tabela abaixo mostra os artefatos gerados pelo requisito RF23.

**Tabela 96:** Artefatos Gerados pelo requisito RF23.

| Artefato                            | Identificador                                           | Rastreabilidade                               |
| ----------------------------------- | ------------------------------------------------------- | --------------------------------------------- |
| Cenário                             | - Não foi possível identificar um cenário específico para este requisito.                   | -                                             |
| Léxico                              | - Verbo: [Gerenciar Notificações](modelagem/lexico.md) <br> - Objeto: [Notificação](modelagem/lexico.md) | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC05 - Configurar preferências de notificação](modelagem/casoDeUso.md)                   | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI05 - Integração com serviço de notificações push](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON05 - O sistema deve garantir a entrega de notificações em tempo real](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 | [HI23 - Gerenciar notificações pelo aplicativo](modelagemAgil/historiaUsuario.md)           | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF23.

**Tabela 97:** Elos do requisito RF23.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| ----------- | ----------------- | -------------------------------------------------------- | --------------- | ----------------------- |
| Recurso     | Desenvolvimento   | - Módulo de gerenciamento de notificações <br> - Serviço de envio de notificações push <br> - Interface de usuário para configuração de preferências de notificação | O módulo de gerenciamento de notificações junto com o serviço de envio de notificações e a interface de usuário para configuração de preferências **são recursos** para o requisito de gerenciar notificações. | RF12: Usuário pode configurar suas preferências de notificação <br> RF18: Sistema deve garantir a entrega de notificações em tempo real |

</details>

<details>
  <summary><b> RF24 - Pedro Izarias  </b></summary>
A tabela abaixo mostra as versões do requisito RF24.

**Tabela 98:** Versão do requisito RF24.

#### Versões do Requisito

| Versão                              | Rastreabilidade                                  |
| ----------------------------------- | ------------------------------------------------ |
| Versão 1                            | [RF24](Elicitacao/ResquisitosCorrigidos.md)      |

- **Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Estrutura de Desenvolvimento do Requisito
A tabela abaixo mostra a estrutura do requisito RF24.

**Tabela 99:** Estrutura do requisito RF24.

| Características                     | Explicação                                                                                  | Rastreabilidade                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Nome do Requisito                   | Usuário pode enviar feedbacks sobre a aplicação                                             | [RF24](Elicitacao/ResquisitosCorrigidos.md)         |
| Alocação no App                     | Na área de configurações de perfil do usuário e dentro de cada seção de feedback específica | [Diagrama de Caso de Uso](ignore/IgnoreDiagramaCasoUso.md) |
| Resolução de requisitos em conflito | Este requisito não conflita com outros requisitos, mas depende da funcionalidade de envio e recebimento de feedbacks. | -                                                   |
| Verificação                         | Verificar se o usuário pode acessar a função de enviar feedbacks e se esses feedbacks são recebidos e processados corretamente. | Será realizada pelo grupo em breve                   |
| Correção de Defeitos                | Através de relatórios de feedbacks dos usuários.                                       | Não foi necessário corrigir falhas para esse requisito no decorrer do desenvolvimento. |
| Análise de impacto na evolução      | Baixo impacto: Afeta principalmente a interface de usuário e a funcionalidade de feedback. | -                                                   |

#### Artefatos Gerados Pelos Requisitos Funcionais
A tabela abaixo mostra os artefatos gerados pelo requisito RF24.

**Tabela 100:** Artefatos Gerados pelo requisito RF24.

| Artefato                            | Identificador                                           | Rastreabilidade                               |
| ----------------------------------- | ------------------------------------------------------- | --------------------------------------------- |
| Cenário                             | - Não foi possível identificar um cenário específico para este requisito.                   | -                                             |
| Léxico                              | - Verbo: [Enviar Feedbacks](modelagem/lexico.md) <br> - Objeto: [Feedback](modelagem/lexico.md) | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC06 - Enviar feedback sobre a aplicação](modelagem/casoDeUso.md)                      | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI06 - Integração com sistema de gerenciamento de feedbacks](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON06 - O sistema deve processar feedbacks de forma eficiente](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 | [HI24 - Enviar feedback sobre a aplicação](modelagemAgil/historiaUsuario.md)               | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF24.

**Tabela 101:** Elos do requisito RF24.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| ----------- | ----------------- | -------------------------------------------------------- | --------------- | ----------------------- |
| Recurso     | Desenvolvimento   | - Módulo de envio de feedbacks <br> - Serviço de recebimento e processamento de feedbacks | O módulo de envio de feedbacks junto com o serviço de recebimento e processamento **são recursos** para o requisito de enviar feedbacks sobre a aplicação. | RF13: Usuário pode enviar feedbacks sobre funcionalidades <br> RF19: Sistema deve processar feedbacks de forma eficiente |

</details>

<details>
  <summary><b> RF25 - Pedro Izarias  </b></summary>
A tabela abaixo mostra as versões do requisito RF25.

**Tabela 102:** Versão do requisito RF25.

#### Versões do Requisito

| Versão                              | Rastreabilidade                                  |
| ----------------------------------- | ------------------------------------------------ |
| Versão 1                            | [RF25](Elicitacao/ResquisitosCorrigidos.md)      |

- **Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Estrutura de Desenvolvimento do Requisito
A tabela abaixo mostra a estrutura do requisito RF25.

**Tabela 103:** Estrutura do requisito RF25.

| Características                     | Explicação                                                                                  | Rastreabilidade                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Nome do Requisito                   | Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos) | [RF25](Elicitacao/ResquisitosCorrigidos.md)         |
| Alocação no App                     | Na área de gestão de recursos humanos e na seção de administração de contratos de trabalho | [Diagrama de Caso de Uso](ignore/IgnoreDiagramaCasoUso.md) |
| Resolução de requisitos em conflito | Este requisito não conflita diretamente com outros requisitos, mas requer integração com funcionalidades de gerenciamento de dados e segurança. | -                                                   |
| Verificação                         | Verificar se a funcionalidade permite adicionar, atualizar e encerrar contratos de trabalho de forma eficiente e segura. | Será realizada pelo grupo em breve                   |
| Correção de Defeitos                | Através de relatórios de erros e feedbacks dos usuários.                                       | Não foi necessário corrigir falhas para esse requisito no decorrer do desenvolvimento. |
| Análise de impacto na evolução      | Médio impacto: Afeta diretamente a gestão de recursos humanos e a administração de contratos de trabalho na empresa. | -                                                   |

#### Artefatos Gerados Pelos Requisitos Funcionais
A tabela abaixo mostra os artefatos gerados pelo requisito RF25.

**Tabela 104:** Artefatos Gerados pelo requisito RF25.

| Artefato                            | Identificador                                           | Rastreabilidade                               |
| ----------------------------------- | ------------------------------------------------------- | --------------------------------------------- |
| Cenário                             | - Não foi possível identificar um cenário específico para este requisito.                   | -                                             |
| Léxico                              | - Verbo: [Gerenciar Contratos de Trabalho](modelagem/lexico.md) <br> - Objeto: [Contrato de Trabalho](modelagem/lexico.md) | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC12 - Gerenciar contratos de trabalho](modelagem/casoDeUso.md)                      | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI12 - Integração com sistema de gestão de contratos](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON09 - O sistema deve garantir a integridade dos dados de contratos](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 | [HI25 - Gerenciar contratos de trabalho na empresa](modelagemAgil/historiaUsuario.md)               | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF25.

**Tabela 105:** Elos do requisito RF25.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| ----------- | ----------------- | -------------------------------------------------------- | --------------- | ----------------------- |
| Recurso     | Desenvolvimento   | - Módulo de gestão de contratos <br> - Banco de Dados para Armazenamento de Contratos | O módulo de gestão de contratos junto com o banco de dados para armazenar os contratos **são recursos** para o requisito de gerenciar contratos de trabalho na empresa. | RF13: Usuário pode gerenciar contratos de trabalho <br> RF22: Usuário empresa pode atualizar dados dos funcionários |

</details>

<details>
  <summary><b> RF26 - Pedro Izarias  </b></summary>
A tabela abaixo mostra as versões do requisito RF26.

**Tabela 106:** Versão do requisito RF26.

#### Versões do Requisito

| Versão                              | Rastreabilidade                                  |
| ----------------------------------- | ------------------------------------------------ |
| Versão 1                            | [RF26](Elicitacao/ResquisitosCorrigidos.md)      |

- **Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Estrutura de Desenvolvimento do Requisito
A tabela abaixo mostra a estrutura do requisito RF26.

**Tabela 107:** Estrutura do requisito RF26.

| Características                     | Explicação                                                                                  | Rastreabilidade                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Nome do Requisito                   | Usuário empresa pode gerenciar benefícios trabalhistas (adicionar novos, atualizar já existentes e encerrar benefícios) | [RF26](Elicitacao/ResquisitosCorrigidos.md)         |
| Alocação no App                     | Na área de gestão de recursos humanos e na seção de administração de benefícios trabalhistas | [Diagrama de Caso de Uso](ignore/IgnoreDiagramaCasoUso.md) |
| Resolução de requisitos em conflito | Este requisito não conflita diretamente com outros requisitos, mas requer integração com funcionalidades de gerenciamento de dados e segurança. | -                                                   |
| Verificação                         | Verificar se a funcionalidade permite adicionar, atualizar e encerrar benefícios trabalhistas de forma eficiente e segura. | Será realizada pelo grupo em breve                   |
| Correção de Defeitos                | Através de relatórios de erros e feedbacks dos usuários.                                       | Não foi necessário corrigir falhas para esse requisito no decorrer do desenvolvimento. |
| Análise de impacto na evolução      | Médio impacto: Afeta diretamente a gestão de recursos humanos e a administração de benefícios trabalhistas na empresa. | -                                                   |

#### Artefatos Gerados Pelos Requisitos Funcionais
A tabela abaixo mostra os artefatos gerados pelo requisito RF26.

**Tabela 108:** Artefatos Gerados pelo requisito RF26.

| Artefato                            | Identificador                                           | Rastreabilidade                               |
| ----------------------------------- | ------------------------------------------------------- | --------------------------------------------- |
| Cenário                             | - Não foi possível identificar um cenário específico para este requisito.                   | -                                             |
| Léxico                              | - Verbo: [Gerenciar Benefícios Trabalhistas](modelagem/lexico.md) <br> - Objeto: [Benefício Trabalhista](modelagem/lexico.md) | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC13 - Gerenciar benefícios trabalhistas](modelagem/casoDeUso.md)                      | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI13 - Integração com sistema de gestão de benefícios](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON10 - O sistema deve garantir a integridade dos dados de benefícios](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 | [HI26 - Gerenciar benefícios trabalhistas na empresa](modelagemAgil/historiaUsuario.md)               | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF26.

**Tabela 109:** Elos do requisito RF26.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| ----------- | ----------------- | -------------------------------------------------------- | --------------- | ----------------------- |
| Recurso     | Desenvolvimento   | - Módulo de gestão de benefícios <br> - Banco de Dados para Armazenamento de Benefícios | O módulo de gestão de benefícios junto com o banco de dados para armazenar os benefícios **são recursos** para o requisito de gerenciar benefícios trabalhistas na empresa. | RF27: Usuário empresa pode gerenciar benefícios trabalhistas <br> RF22: Usuário empresa pode atualizar dados dos funcionários |

</details>

<details>
  <summary><b> RF27 - Pedro Izarias  </b></summary>
A tabela abaixo mostra as versões do requisito RF27.

**Tabela 110:** Versão do requisito RF27.

#### Versões do Requisito

| Versão                              | Rastreabilidade                                  |
| ----------------------------------- | ------------------------------------------------ |
| Versão 1                            | [RF27](Elicitacao/ResquisitosCorrigidos.md)      |

- **Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Estrutura de Desenvolvimento do Requisito
A tabela abaixo mostra a estrutura do requisito RF27.

**Tabela 111:** Estrutura do requisito RF27.

| Características                     | Explicação                                                                                  | Rastreabilidade                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Nome do Requisito                   | Usuário empresa pode gerenciar benefícios trabalhistas (adicionar novos, atualizar já existentes e encerrar benefícios) | [RF27](Elicitacao/ResquisitosCorrigidos.md)         |
| Alocação no App                     | Na área de gestão de recursos humanos e na seção de administração de benefícios trabalhistas | [Diagrama de Caso de Uso](ignore/IgnoreDiagramaCasoUso.md) |
| Resolução de requisitos em conflito | Este requisito não conflita diretamente com outros requisitos, mas requer integração com funcionalidades de gerenciamento de dados e segurança. | -                                                   |
| Verificação                         | Verificar se a funcionalidade permite adicionar, atualizar e encerrar benefícios trabalhistas de forma eficiente e segura. | Será realizada pelo grupo em breve                   |
| Correção de Defeitos                | Através de relatórios de erros e feedbacks dos usuários.                                       | Não foi necessário corrigir falhas para esse requisito no decorrer do desenvolvimento. |
| Análise de impacto na evolução      | Médio impacto: Afeta diretamente a gestão de recursos humanos e a administração de benefícios trabalhistas na empresa. | -                                                   |

#### Artefatos Gerados Pelos Requisitos Funcionais
A tabela abaixo mostra os artefatos gerados pelo requisito RF27.

**Tabela 112:** Artefatos Gerados pelo requisito RF27.

| Artefato                            | Identificador                                           | Rastreabilidade                               |
| ----------------------------------- | ------------------------------------------------------- | --------------------------------------------- |
| Cenário                             | - Não foi possível identificar um cenário específico para este requisito.                   | -                                             |
| Léxico                              | - Verbo: [Gerenciar Benefícios Trabalhistas](modelagem/lexico.md) <br> - Objeto: [Benefício Trabalhista](modelagem/lexico.md) | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC13 - Gerenciar benefícios trabalhistas](modelagem/casoDeUso.md)                      | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI13 - Integração com sistema de gestão de benefícios](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON10 - O sistema deve garantir a integridade dos dados de benefícios](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 | [HI27 - Gerenciar benefícios trabalhistas na empresa](modelagemAgil/historiaUsuario.md)               | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF27.

**Tabela 113:** Elos do requisito RF27.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| ----------- | ----------------- | -------------------------------------------------------- | --------------- | ----------------------- |
| Recurso     | Desenvolvimento   | - Módulo de gestão de benefícios <br> - Banco de Dados para Armazenamento de Benefícios | O módulo de gestão de benefícios junto com o banco de dados para armazenar os benefícios **são recursos** para o requisito de gerenciar benefícios trabalhistas na empresa. | RF26: Usuário empresa pode gerenciar benefícios trabalhistas <br> RF22: Usuário empresa pode atualizar dados dos funcionários |

</details>

<details>
  <summary><b> RF28 - Pedro Izarias  </b></summary>
A tabela abaixo mostra as versões do requisito RF28.

**Tabela 114:** Versão do requisito RF28.

#### Versões do Requisito

| Versão                              | Rastreabilidade                                  |
| ----------------------------------- | ------------------------------------------------ |
| Versão 1                            | [RF28](Elicitacao/ResquisitosCorrigidos.md)      |


- **Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Estrutura de Desenvolvimento do Requisito
A tabela abaixo mostra a estrutura do requisito RF28.

**Tabela 115:** Estrutura do requisito RF28.

| Características                     | Explicação                                                                                  | Rastreabilidade                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Nome do Requisito                   | Usuário empresa pode gerenciar dados pessoais e contratuais de funcionários                 | [RF28](Elicitacao/ResquisitosCorrigidos.md)         |
| Alocação no App                     | Na área de gestão de recursos humanos e na seção de administração de dados dos funcionários  | [Diagrama de Caso de Uso](ignore/IgnoreDiagramaCasoUso.md) |
| Resolução de requisitos em conflito | Este requisito não conflita diretamente com outros requisitos, mas requer integração com funcionalidades de gerenciamento de dados e segurança. | -                                                   |
| Verificação                         | Verificar se a funcionalidade permite acesso, atualização e gerenciamento eficiente dos dados pessoais e contratuais dos funcionários. | Será realizada pelo grupo em breve                   |
| Correção de Defeitos                | Através de relatórios de erros e feedbacks dos usuários.                                       | Não foi necessário corrigir falhas para esse requisito no decorrer do desenvolvimento. |
| Análise de impacto na evolução      | Médio impacto: Afeta diretamente a gestão de recursos humanos e a administração de dados dos funcionários na empresa. | -                                                   |

#### Artefatos Gerados Pelos Requisitos Funcionais
A tabela abaixo mostra os artefatos gerados pelo requisito RF28.

**Tabela 116:** Artefatos Gerados pelo requisito RF28.

| Artefato                            | Identificador                                           | Rastreabilidade                               |
| ----------------------------------- | ------------------------------------------------------- | --------------------------------------------- |
| Cenário                             | - Não foi possível identificar um cenário específico para este requisito.                   | -                                             |
| Léxico                              | - Verbo: [Gerenciar Dados Pessoais e Contratuais](modelagem/lexico.md) <br> - Objeto: [Dados Pessoais e Contratuais](modelagem/lexico.md) | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC14 - Gerenciar dados pessoais e contratuais de funcionários](modelagem/casoDeUso.md)  | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI14 - Integração com sistema de gestão de dados](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON11 - O sistema deve garantir a segurança e privacidade dos dados dos funcionários](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 | [HI28 - Gerenciar dados pessoais e contratuais de funcionários na empresa](modelagemAgil/historiaUsuario.md)               | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF28.

**Tabela 117:** Elos do requisito RF28.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| ----------- | ----------------- | -------------------------------------------------------- | --------------- | ----------------------- |
| Recurso     | Desenvolvimento   | - Módulo de gestão de dados pessoais e contratuais <br> - Banco de Dados para Armazenamento de Dados dos Funcionários | O módulo de gestão de dados pessoais e contratuais junto com o banco de dados para armazenar esses dados **são recursos** para o requisito de gerenciar dados pessoais e contratuais de funcionários na empresa. | RF27: Usuário empresa pode gerenciar benefícios trabalhistas <br> RF22: Usuário empresa pode atualizar dados dos funcionários |

</details>
