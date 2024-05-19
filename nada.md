<center>
Tabela 3: Caso de uso UC01

| UC01                | Solicitar Benefício                                              |
| ------------------- | ---------------------------------------------------------------- |
| Descrição           | Permitir que o trabalhador consulte requerimentos de seguro desemprego. |
| Atores              | Trabalhador (Usuário Primário); Sistema de Banco de Dados (Usuário Secundário); Órgão Governamental (Usuário Secundário) |
| Frequência          | Quando o trabalhador quiser verificar se atende aos requisitos de elegibilidade para o seguro-desemprego ou acompanhar seu requerimento.    |
| Pré-condições       | O trabalhador deve estar autenticado no sistema escolher a opção Benefícios. |
| Fluxo Básico        | <b> FB01 </b> <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Benefícios". <li>O trabalhador seleciona a opção Seguro Desemprego. <li>O trabalhador seleciona a opção consultar. <li>O trabalhador seleciona Seguro Desemprego ou Seguro Desemprego do empregado doméstico. <li>O sistema verifica a existência de requisições de seguro desemprego. <li>Se houverem requisições feitas, irão aparecer na tela.</ol> |
| Fluxos Alternativos | <b> FA01 </b> <ol> <li>Se o trabalhador não tiver todos os documentos necessários, ele pode salvar a solicitação como rascunho e completá-la posteriormente. </ol>             |
| Fluxos de exceção   | <b> FE01 </b> <ol> <li>Se ocorrer um erro na validação das informações ou documentos, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <li>Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <li>Se a solicitação for rejeitada pelo órgão governamental, o trabalhador recebe uma notificação com o motivo da rejeição. </ol>             |
| Pós-condições       | A solicitação de benefício é registrada e enviada ao órgão governamental responsável para análise. |
| Data de Criação     | 19/05/2024                                                        |
| Rastreabilidade     | [Requisitos Funcionais RF01, RF02]                              |

**Fonte:** [Bruno Araújo](https://github.com/brunocva)

</center>
