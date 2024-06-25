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
| Léxico | **Verbo:** <br> <li> Atualizar dados pessoais <br> <br> **Objeto:** <br> <li> Perfil do Trabalhador  <br>  | [Léxicos](modelagem/lexico.md) |
| Casos de Uso | <li> [UC03 - Trabalhador acessa detalhes dos contratos de trabalho](modelagem/casoDeUso.md) <br> <li> [UC10 - Verificar dados relacionados ao FGTS e INSS](modelagem/casoDeUso.md) | [Casos de Uso](modelagem/casoDeUso.md) |
| Especificação Suplementar | **Para a implementação:** <br> <li> RI01 - Integração com eSocial <br> <li> RI03 - Permitir integração com vários outros softwares <br> <br> **Para a confiabilidade:** <br> <li> CON02 - O sistema deve possuir as informações atualizadas e condizentes com a realidade. <br> <li> CON03 - O sistema deve manter íntegra as informações sobre o usuário e seus contratos de trabalho. | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário | HI05 - Alterar os dados do perfil  | [História de Usuário](modelagemAgil/historiaUsuario.md) |
| Backlog | <li> [Tema: TM02 - Contratos de Trabalho e Benefícios](modelagemAgil/backlog.md) <br> <li> [Épico: EP03 – Contratos](modelagemAgil/backlog.md) <br> <li> [História: HI22 - Como usuário, eu quero atualizar os dados dos funcionários para manter as informações atualizadas.](modelagemAgil/backlog.md) | [Backlog](modelagemAgil/backlog.md) |

**Autor:** [Pedro Izarias](https://github.com/Izarias)

#### Elos
A tabela abaixo mostra os elos do requisito RF22.

**Tabela 93:** Elos do requisito RF22.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Atualização de Dados de Funcionários <br> <li> Banco de Dados para Armazenamento de Dados de Funcionários <br> <li> Interface de Usuário para Atualização de Dados. | O banco de dados para armazenar os dados dos funcionários atualizados e a interface de usuário para permitir a atualização dessas informações são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF03: Usuário pode consultar suas informações pessoais <br> <li> RF04: Usuário pode atualizar suas informações pessoais <br> <br>  Requisitos não funcionais: <br> <li> RNF14: O aplicativo deve seguir padrões de design aceitos por empresas e instituições, com uma taxa de conformidade de 95% nas avaliações de usabilidade. <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real.|


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
| Nome do Requisito                   | Usuário empresa pode consultar contratos de trabalho                            | [RF23](Elicitacao/ResquisitosCorrigidos.md)         |
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
| Léxico                              | - Verbo: Consultar Vínculos Empregatícios <br> - Objeto: <br> Contrato de Trabalho <br>- Vínculo Empregatício | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC05 - Configurar preferências de notificação](modelagem/casoDeUso.md)                   | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI05 - Integração com serviço de notificações push](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON05 - O sistema deve garantir a entrega de notificações em tempo real](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 |  HI06 - Visualizar contratos Antigo <br> HI08 - Visualizar gráficos de contratos <br> HI11 - Visualizar contratos Antigos    | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF23.

**Tabela 97:** Elos do requisito RF23.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Consulta de Contratos de Trabalho <br> <li> Banco de Dados para Armazenamento de Contratos de Trabalho <br> <li> Interface de Usuário para Consulta de Contratos. | O banco de dados para armazenar os contratos de trabalho e a interface de usuário para permitir a consulta dessas informações são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF05: Usuário trabalhador pode consultar contratos de trabalho <br> <br>  Requisitos não funcionais: <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real.|

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
| Nome do Requisito                   | Usuário empresa pode gerar relatórios trabalhistas                                           | [RF24](Elicitacao/ResquisitosCorrigidos.md)         |
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
| Léxico                              | - Verbo: Emitir PDF do Contrato de Trabalho <br> - Objeto: Informação do Contrato | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC06 - Enviar feedback sobre a aplicação](modelagem/casoDeUso.md)                      | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI06 - Integração com sistema de gerenciamento de feedbacks](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON06 - O sistema deve processar feedbacks de forma eficiente](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 |   HI22 - Visualizar relatório de atividades da conta.   | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF24.

**Tabela 101:** Elos do requisito RF24.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Geração de Relatórios <br> <li> Banco de Dados para Armazenamento de Informações Trabalhistas <br> <li> Interface de Usuário para Geração de Relatórios. | O banco de dados para armazenar as informações trabalhistas e a interface de usuário para permitir a geração de relatórios são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF06: Usuário trabalhador pode consultar benefícios <br> <br>  Requisitos não funcionais: <br> <li> RNF12: O sistema deve permitir a exportação de dados em formatos compatíveis com outros sistemas de gestão.|

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
| Léxico                              | - Verbo: <br>Adicionar Novo Contrato de Trabalho <br> Atualizar dados pessoais <br> - Objeto: Contrato de Trabalho <br> - Estado: <br> Contrato Ativo <br> Contrato Finalizado | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC12 - Gerenciar contratos de trabalho](modelagem/casoDeUso.md)                      | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI12 - Integração com sistema de gestão de contratos](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON09 - O sistema deve garantir a integridade dos dados de contratos](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 | HI09 - Realizar anotações em contratos <br> HI17 - Alterar Dados de Contrato     | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF25.

**Tabela 105:** Elos do requisito RF25.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Gerenciamento de Contratos de Trabalho <br> <li> Banco de Dados para Armazenamento de Contratos <br> <li> Interface de Usuário para Gerenciamento de Contratos. | O módulo de gerenciamento de contratos de trabalho e a interface de usuário para permitir o gerenciamento são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF05: Usuário trabalhador pode consultar contratos de trabalho <br> <br>  Requisitos não funcionais: <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real.|

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
| Nome do Requisito                   | Usuário empresa pode cadastrar benefícios para a empresa | [RF26](Elicitacao/ResquisitosCorrigidos.md)         |
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
| Léxico                              |  - Objeto: Benefício | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC13 - Gerenciar benefícios trabalhistas](modelagem/casoDeUso.md)                      | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI13 - Integração com sistema de gestão de benefícios](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON10 - O sistema deve garantir a integridade dos dados de benefícios](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 | HI12 - Solicitar benefícios    | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF26.

**Tabela 109:** Elos do requisito RF26.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Cadastro de Benefícios <br> <li> Banco de Dados para Armazenamento de Benefícios <br> <li> Interface de Usuário para Cadastro de Benefícios. | O módulo de cadastro de benefícios e a interface de usuário para permitir o cadastro são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF07: Usuário trabalhador pode consultar dados de contato <br> <br>  Requisitos não funcionais: <br> <li> RNF12: O sistema deve permitir a exportação de dados em formatos compatíveis com outros sistemas de gestão.|

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
| Nome do Requisito                   | Usuário empresa pode gerenciar benefícios trabalhistas | [RF27](Elicitacao/ResquisitosCorrigidos.md)         |
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
| Léxico                              | - Verbo: Solicitar Benefício <br> - Objeto: Benefício <br> - Estado: Benefício Aprovado | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC13 - Gerenciar benefícios trabalhistas](modelagem/casoDeUso.md)                      | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI13 - Integração com sistema de gestão de benefícios](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON10 - O sistema deve garantir a integridade dos dados de benefícios](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 | HI14 -  manual a respeito dos benefícios que tenho direito <br> HI13 -  Consultar dados a respeito de INSS e FGTS <br> HI11 - Visualizar contratos Antigos     | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF27.

**Tabela 113:** Elos do requisito RF27.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Gerenciamento de Benefícios Trabalhistas <br> <li> Banco de Dados para Armazenamento de Benefícios <br> <li> Interface de Usuário para Gerenciamento de Benefícios. | O módulo de gerenciamento de benefícios trabalhistas e a interface de usuário para permitir o gerenciamento são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF08: Usuário pode gerenciar informações trabalhistas <br> <br>  Requisitos não funcionais: <br> <li> RNF12: O sistema deve permitir a exportação de dados em formatos compatíveis com outros sistemas de gestão.|

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
| Nome do Requisito                   | Usuário empresa escolher modo de status: "Possui vagas de emprego" ou "Não posui vagas de emprego"                 | [RF28](Elicitacao/ResquisitosCorrigidos.md)         |
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
| Léxico                              |  - Estado: Conexão Estável <br> Não Autorizado | [Léxicos](modelagem/lexico.md)                |
| Casos de Uso                        | - [UC14 - Gerenciar dados pessoais e contratuais de funcionários](modelagem/casoDeUso.md)  | [Casos de Uso](modelagem/casoDeUso.md)        |
| Especificação Suplementar           | - Para a implementação: [RI14 - Integração com sistema de gestão de dados](modelagem/especSuplementar.md) <br> - Para a confiabilidade: [CON11 - O sistema deve garantir a segurança e privacidade dos dados dos funcionários](modelagem/especSuplementar.md) | [Especificação Suplementar](modelagem/especSuplementar.md) |
| História de Usuário                 |     HI18 - Publicar Vagas Disponíveis no Mural de Vagas <br>   HI20 - Status de contratação   | [História de Usuário](modelagemAgil/historiaUsuario.md) |

#### Os Elos
A tabela abaixo mostra os elos do requisito RF28.

**Tabela 117:** Elos do requisito RF28.

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Interface de Usuário para Configuração de Status de Vagas de Emprego <br> <li> Integração com Sistema para Atualização em Tempo Real <br> <li> Garantia de Acessibilidade das Informações aos Candidatos. | A interface para configuração do status e a integração com o sistema são recursos essenciais para o requisito. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF10: Usuário pode buscar vagas de emprego disponíveis <br> <br>  Requisitos não funcionais: <br> <li> RNF15: O sistema deve garantir que as informações de vagas de emprego sejam atualizadas em tempo real.|

</details>
