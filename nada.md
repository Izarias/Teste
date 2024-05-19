<center>
Tabela 3: Caso de uso UC01

| UC01                | Solicitar Benefício                                              |
| ------------------- | ---------------------------------------------------------------- |
| Descrição           | Permitir que o trabalhador solicite um benefício, como seguro-desemprego ou auxílio-doença. |
| Atores              | Trabalhador (Usuário Primário); Sistema de Banco de Dados (Usuário Secundário); Órgão Governamental (Usuário Secundário) |
| Frequência          | Sempre que o trabalhador precisar solicitar um benefício.        |
| Pré-condições       | O trabalhador deve estar autenticado no sistema e ter os documentos necessários para a solicitação. |
| Fluxo Básico        | <b> FB01 </b> <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Benefícios". <li>O trabalhador seleciona o benefício desejado. <li>O sistema exibe os requisitos e documentos necessários para a solicitação do benefício. <li>O trabalhador preenche o formulário de solicitação e anexa os documentos necessários. <li>O sistema verifica a consistência das informações e documentos fornecidos. <li>Se todas as informações estiverem corretas, o sistema envia a solicitação para o órgão governamental responsável. <li>O trabalhador recebe uma confirmação de que a solicitação foi enviada com sucesso. </ol> |
| Fluxos Alternativos | <b> FA01 </b> <ol> <li>Se o trabalhador não tiver todos os documentos necessários, ele pode salvar a solicitação como rascunho e completá-la posteriormente. </ol>             |
| Fluxos de exceção   | <b> FE01 </b> <ol> <li>Se ocorrer um erro na validação das informações ou documentos, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <li>Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <li>Se a solicitação for rejeitada pelo órgão governamental, o trabalhador recebe uma notificação com o motivo da rejeição. </ol>             |
| Pós-condições       | A solicitação de benefício é registrada e enviada ao órgão governamental responsável para análise. |
| Data de Criação     | 19/05/2024                                                        |
| Rastreabilidade     | [Requisitos Funcionais RF01, RF02]                              |

**Fonte:** [Bruno Araújo](https://github.com/brunocva)

</center>
