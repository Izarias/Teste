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
