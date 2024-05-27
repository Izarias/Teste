<details>
  <summary size="20"><b>  Tempo de Processamento de Solicitações </b></summary> 
 
</center>

**Tabela x:** Tempo de Processamento de Solicitações

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF01](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Tempo de Processamento de Solicitações                                                                                               |
| **Tipo de Requisito**      | Desempenho                                                                                                                                    |
| **Descrição**              | O sistema deve processar solicitações da carteira de trabalho em no máximo 2 minutos                      |
| **Justificativa/Racionalidade** | Garantir uma experiência eficiente e satisfatória para os usuários, especialmente considerando o alto volume de solicitações esperadas devido à importância e à frequência de uso do serviço                   |
| **Critérios de Aceitação** |  <li> O sistema deve processar solicitações da carteira de trabalho em no máximo 2 minutos                                                       |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Média Prioridade                                                                                                                                    |
| **Interdependências**      | RNF02 (Para garantir que o sistema processe solicitações em no máximo 2 minutos, mesmo sob carga pesada de até 1 milhão de usuários simultâneos, é essencial que o sistema seja altamente escalável) e RNF03 (A habilidade do sistema de suportar um aumento de 100% no volume de dados, transações e usuários sem degradação perceptível no desempenho é crucial para manter o tempo de processamento dentro do limite de 2 minutos)                                                                                        |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>

<details>
  <summary size="20"><b>  Escalabilidade do Sistema e Personalização de Interfaces de Usuário </b></summary> 
 
</center>

**Tabela x:** Escalabilidade do Sistema e Personalização de Interfaces de Usuário

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF02](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Escalabilidade do Sistema e Personalização de Interfaces de Usuário                                                                                |
| **Tipo de Requisito**      | Desempenho                                                                                                                                    |
| **Descrição**              | O sistema deve ser capaz de escalar para suportar até 1 milhão de usuários simultâneos e permitir personalização das interfaces de usuário.        |
| **Justificativa/Racionalidade** |  A necessidade de garantir que o sistema seja capaz de lidar eficientemente com um grande volume de usuários simultâneos, oferecendo ao mesmo tempo a flexibilidade de personalização das interfaces de usuário conforme as preferências e necessidades individuais                   |
| **Critérios de Aceitação** |  <li> O sistema deve ser capaz de suportar até 1 milhão de usuários simultâneos sem degradação significativa no desempenho <li> Os usuários devem ter a capacidade de personalizar as interfaces de acordo com suas preferências individuais                                                   |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Média Prioridade                                                                                                                                    |
| **Interdependências**      | RNF01 (A capacidade de escalabilidade do sistema pode afetar diretamente o tempo de processamento de solicitações) e RNF03 (Um sistema escalável é fundamental para manter a capacidade de processamento de transações mesmo em momentos de alta demanda)                    |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>

<details>
  <summary size="20"><b>  Suporte a Aumento de Volume Sem Degradação de Desempenho </b></summary> 
 
</center>

**Tabela x:** Suporte a Aumento de Volume Sem Degradação de Desempenho

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF03](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Suporte a Aumento de Volume Sem Degradação de Desempenho                                                                                |
| **Tipo de Requisito**      | Desempenho                                                                                                                                    |
| **Descrição**              | O sistema deve suportar um aumento de 100% no volume de dados, transações e número de usuários sem degradação perceptível no desempenho        |
| **Justificativa/Racionalidade** | A justificativa baseia-se na necessidade de garantir que o sistema possa crescer de forma eficiente e sustentável, acompanhando o aumento da demanda de usuários e transações sem comprometer a qualidade do serviço.         |
| **Critérios de Aceitação** |  <li> O sistema deve suportar um aumento de 100% no volume de dados e transações sem uma degradação perceptível no desempenho. <li> O sistema deve suportar um aumento de 100% no número de usuários simultâneos sem comprometer o desempenho                                      |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Média Prioridade                                                                                                                                    |
| **Interdependências**      | RNF01 (O tempo de processamento das solicitações pode ser afetado pelo aumento no volume de dados e usuários) e RNF02 (A escalabilidade do sistema é essencial para suportar o aumento de volume sem degradação de desempenho)                    |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>


<details>
  <summary size="20"><b>  Capacidade de Processamento de Transações </b></summary> 
 
</center>

**Tabela x:** Capacidade de Processamento de Transações

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF04](Elicitacao/RequisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Capacidade de Processamento de Transações                                                                                              |
| **Tipo de Requisito**      | Desempenho                                                                                                                                    |
| **Descrição**              | O sistema deve ser capaz de processar até 10.000 transações por segundo, mesmo em picos de uso nacional.                      |
| **Justificativa/Racionalidade** | Garantir que o sistema possa lidar com altos volumes de transações simultâneas, especialmente durante picos de uso, para assegurar a eficiência e a continuidade dos serviços prestados.                   |
| **Critérios de Aceitação** | <li> O sistema deve processar até 10.000 transações por segundo durante picos de uso sem degradação perceptível no desempenho.                                                       |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Alta Prioridade                                                                                                                                    |
| **Interdependências**      | RNF01 (O tempo de processamento das solicitações pode ser afetado pela capacidade de processamento de transações), RNF02 (A escalabilidade do sistema é necessária para suportar picos de uso) e RNF03 (Suporte ao aumento de volume de dados e usuários é essencial para manter a capacidade de processamento).                                                                                        |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>

<details>
  <summary size="20"><b>  Tempo de Processamento de Solicitações com Taxa de Sucesso </b></summary> 
 
</center>
**Tabela y:** Tempo de Processamento de Solicitações com Taxa de Sucesso

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF13](Elicitacao/RequisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Tempo de Processamento de Solicitações com Taxa de Sucesso                                                                                              |
| **Tipo de Requisito**      | Desempenho                                                                                                                                           |
| **Descrição**              | O sistema deve processar solicitações de carteira de trabalho em no máximo 2 minutos, com uma taxa de sucesso de 99%.                     |
| **Justificativa/Racionalidade** | Garantir uma experiência eficiente e confiável para os usuários, minimizando erros e atrasos no processamento das solicitações de carteira de trabalho.                   |
| **Critérios de Aceitação** | <li> O sistema deve processar solicitações de carteira de trabalho em no máximo 2 minutos. <li> O sistema deve manter uma taxa de sucesso de 99% no processamento das solicitações.                                                      |
| **Origem/Fonte**           | [Análise de documentos e storytelling](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                   |
| **Prioridade**             | Alta Prioridade                                                                                                                                       |
| **Interdependências**      | RNF01 (Tempo de Processamento de Solicitações) e RNF03 (Suporte a Aumento de Volume).                                                                                         |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema       |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)


</center>

</details>

<details>
  <summary size="20"><b>  Autenticação Biométrica Rápida </b></summary> 
 
</center>
**Tabela z:** Autenticação Biométrica Rápida

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF15](Elicitacao/RequisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Autenticação Biométrica Rápida                                                                                              |
| **Tipo de Requisito**      | Segurança/Desempenho                                                                                                                                    |
| **Descrição**              | O acesso às funcionalidades principais do aplicativo deve exigir autenticação biométrica e ser completado em menos de 30 segundos.                     |
| **Justificativa/Racionalidade** | Assegurar que o acesso ao aplicativo seja seguro e rápido, oferecendo uma experiência de usuário eficiente e protegida.                   |
| **Critérios de Aceitação** | <li> O sistema deve completar a autenticação biométrica em menos de 30 segundos. <li> A autenticação biométrica deve ser necessária para acessar as funcionalidades principais do aplicativo.                                                      |
| **Origem/Fonte**           | [Storytelling](Elicitacao/TecnicasElicitacao/Execucao/Storytelling.md)                                                                  |
| **Prioridade**             | Alta Prioridade                                                                                                                                       |
| **Interdependências**      | RNF08 (Segurança: Autenticação e Criptografia) e RNF03 (Suporte a Aumento de Volume, para garantir desempenho adequado durante picos de uso).                                                                                         |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>

<details>
  <summary size="20"><b>  Atualização de Dados do Usuário  </b></summary> 
 
</center>
**Tabela a:** Atualização de Dados do Usuário

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF16](Elicitacao/RequisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Atualização de Dados do Usuário                                                                                              |
| **Tipo de Requisito**      | Desempenho/Usabilidade                                                                                                                                    |
| **Descrição**              | O sistema deve permitir ao usuário atualizar seus dados em no máximo 15 minutos, sem a necessidade de intermediários, com uma taxa de sucesso de 95%.                     |
| **Justificativa/Racionalidade** | Facilitar a manutenção de dados precisos e atualizados pelos próprios usuários, melhorando a eficiência do sistema e a satisfação do usuário.                   |
| **Critérios de Aceitação** | <li> O sistema deve permitir ao usuário atualizar seus dados em no máximo 15 minutos. <li> O sistema deve manter uma taxa de sucesso de 95% nas atualizações de dados.                                                      |
| **Origem/Fonte**           | [Storytelling](Elicitacao/TecnicasElicitacao/Execucao/Storytelling.md)                                                                  |
| **Prioridade**             | Média Prioridade                                                                                                                                    |
| **Interdependências**      | RNF03 (Suporte a Aumento de Volume) e RNF12 (Vocabulários Controlados e Taxonomias Padrão).                                                                                         |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>





