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
| **Notas e Comentários**    | É importante monitorar e testar continuamente o desempenho do sistema para garantir que a capacidade de processamento de 10.000 transações por segundo seja mantida.                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>
