### Consultar Seguro Desemprego

A tabela x mostra quando o usuário(trabalhador) consulta requerimentos de Seguro Desemprego.

<details>
  <summary size="20"><b> Tabela x: Consultar seguro desemprego. </b></summary> 
<center>
Tabela x: Caso de uso UC00

| UC01                | Solicitar Benefício                                              |
| ------------------- | ---------------------------------------------------------------- |
| Descrição           | Permitir que o trabalhador consulte requerimentos de seguro desemprego. |
| Atores              | Trabalhador (Usuário Primário); Sistema de Banco de Dados (Usuário Secundário); Órgão Governamental (Usuário Secundário) |
| Frequência          | Quando o trabalhador quiser verificar se atende aos requisitos de elegibilidade para o seguro-desemprego ou acompanhar seu requerimento.    |
| Pré-condições       | O trabalhador deve estar autenticado no sistema escolher a opção Benefícios. |
| Fluxo Básico        | <b> FB01 </b> <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Benefícios". <li>O trabalhador seleciona a opção Seguro Desemprego. <li>O trabalhador seleciona a opção consultar. <li>O trabalhador seleciona Seguro Desemprego ou Seguro Desemprego do empregado doméstico. <li>O sistema verifica a existência de requisições de seguro desemprego. <li>Se houverem requisições feitas, irão aparecer na tela.</ol> |
| Fluxos Alternativos | <b> FA01 </b> <ol> <li>Se o trabalhador acessar a opção Menu, Benefícios e Seguro Desemprego, ainda pode fazer a consulta da mesma maneira.</ol>             |
| Fluxos de exceção   | <b> FE01 </b> <ol> <li>Se não houverem requisições feitas pelo trabalhador para Seguro Desemprego, o aplicativo apresentará a mensagem "Não foram encontradas requerimentos de Seguro-Desemprego. </ol>             |
| Pós-condições       | Os requerimentos de Seguro Desemprego são mostrados na tela. |
| Data de Criação     | 19/05/2024                                                        |
| Rastreabilidade     | [Requisitos Funcionais F12]                              |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

