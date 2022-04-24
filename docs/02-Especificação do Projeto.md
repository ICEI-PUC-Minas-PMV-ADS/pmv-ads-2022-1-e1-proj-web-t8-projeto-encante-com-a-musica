# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação dos usuários em um trabalho de imersão feita pelos membros da equipe a partir da observação dos usuários em seu local natural e por meio de entrevistas. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários


## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas na Figuras que se seguem.

<img src="img/Amanda.png">
<img src="img/Adriano Oliveira.png">
<img src="img/Jeferson Silva.png">
<img src="img/Luana Oliveira.png">
<img src="img/Instituição.png">


Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Adriano             | poder encontrar mais informações sobre o tratamento paliativo com música    | para entender sobre seus objetivos e discutir com amigos e familiares  |
|Amanda Ribeiro      | quer se cadastrar no site                 | para se voluntariar  |
|Adriano Oliveira    | buscar por pessoas e saber sobre suas habilidades músicas                  | para poder se conectar e trocar experiências |
|Amanda Ribeiro        | encontrar locais em sua região, que precisem de voluntários para o tratamento paliativo com música                  | para poder exercer o trabalho voluntário nesses locais  |
|Adriano Oliveira         | pesquisar sobre instituições e grupos já cadastrados                 | para poder exercer o trabalho voluntário nesses locais |
|Adriano Oliveira       | pesquisar sobre instituições e grupos já cadastrados                 | para saber se já existe algum grupo com projeto em andamento em alguma instituição |
|Amanda Ribeiro       | poder compartilhar as informações do site nas minhas redes sociais                  | para divulgar o projeto para o maior número de pessoas possíveis |
|Amanda Ribeiro       | saber como apoiar o projeto financeiramente                 | pois acredito nessa iniciativa |
|Adriano Oliveira       | conseguir acessar o site também do celular                 | pois é o aparelho que mais utilizo para acessar a internet |
|Amanda Ribeiro       | poder encontrar uma sessão com galeria/vídeos e ou comentários de ações sociais que já foram promovidas                | para conhecer um pouco mais do projeto |
|Adriano Oliveira       | poder conseguir entrar em contato com o projeto Encante com Música                | para sanar dúvidas |
|Jeferson Silva        | quer realizar solicitação de visita de voluntários musicai                 | para a sobrinha que está em tratamento do câncer |
|Hospital N. Senhora       | poder cadastrar a instituição para receber voluntários                  | pois quer oferecer a música como forma de tratamento para seus pacientes |
|Luana Oliveira       | Quer solicitar a visita dos voluntários no hospita                 | pois está com câncer e sente que a música alivia sua dor |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |


Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site deve apresentar uma página com informações sobre o tratamento paliativo com música. | ALTA | 
|RF-002| O site deve apresentar uma página com a história do projeto.   | ALTA|
|RF-003| O site deve apresentar uma página com notícias relacionadas ao tratamento paliativo com música.   | MÉDIA|
|RF-004| O site deve permitir que o voluntário realize login e senha após cadastro.   | ALTA|
|RF-005| O site deve permitir que a instituição médica/hospitalar realize login e senha após um cadastro.s   | ALTA|
|RF-006| O site deve permitir que o voluntário realize buscas por categorias instrumentais e categorias de vozes.   | ALTA|
|RF-007| O site deve permitir que o voluntário pesquise instituições e grupos cadastrados.   | ALTA|
|RF-008| O site deve permitir que o voluntário pesquise locais em sua região que precisem de voluntários.   | ALTA|
|RF-009| O site deve apresentar como o voluntário pode apoiar financeiramente o projeto.   | BAIXA|
|RF-010| O site deve permitir visualizar as informações de contato do mantenedor do site  | MÉDIA|
|RF-011| O site deve permitir encontrar uma sessão com galeria/vídeos e comentários de ações sociais que já foram promovidas   | ALTA|
|RF-012| O site deve permitir compartilhar informações nas redes sociais   | MÉDIA|
|RF-013| O site deve permitir que o usuário entre em contato com o projeto para sanar dúvidas através de mensagem de texto.   | ALTA|
|RF-014| EO site deve permitir que pacientes e familiares entre em contato com o projeto através de mensagens de texto para solicitar visita dos voluntários.  | ALTA|


### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve funcionar 24 horas por dia, todos os dias da semana. | MÉDIA | 
|RNF-002| O site deverá ser responsivo para permitir a visualização em um celular de forma adequada. |  BAIXA | 
|RNF-003| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge).|  BAIXA | 
|RNF-004| Como o site será para uma Ong a extensão do link deverá ser .org |  BAIXA | 
|RNF-005| O site deverá ter acessibilidade audiovisual. |  MÉDIA | 
|RNF-006| O site deverá conter paleta de cores de diferentes tipos para leitura noturna e daltonismo. |  MÉDIA | 
 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 26/06/2022 |



Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
