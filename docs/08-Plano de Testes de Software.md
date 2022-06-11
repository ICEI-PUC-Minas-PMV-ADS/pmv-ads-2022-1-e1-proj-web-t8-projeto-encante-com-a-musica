# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Enumere quais cenários de testes foram selecionados para teste. Neste tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo de usuários que foi escolhido para participar do teste e as ferramentas utilizadas.

Os requisitos para realização dos testes de software são: 

* Site publicado na Internet 

* Navegador da Internet - Chrome, Firefox ou Edge 

* Conectividade de Internet para acesso às plataformas (APISs) 

 

Os testes funcionais a serem realizados no aplicativo são descritos a seguir.

| Casos de teste  | CT-01 – Links da Página Fale  Conosco |
| ------- | -------- |
| Requisitos Associados  | RF-10 - O site deve permitir visualizar as informações de contato do mantenedor.  <br>RF-13 - O site deve permitir que o usuário entre em contato com o projeto para sanar dúvidas através de mensagem de texto. <br>  RF-14 – O site deve permitir que pacientes e familiares entre em contato com o projeto através de mensagens de texto para solicitar visita dos voluntários.     |
|  Objetivo do Teste   | Verificar se todos os links que estão na página Fale Conosco e que direcionam para outras páginas estão funcionando.  |
| Passos    | 1) Acessar o Navegador <br>2) Informar o endereço do Site <br>3) Visualizar a página Fale Conosco <br>4) Clicar nos links  |
| Critérios de Êxito   |Todos os links ao serem clicados devem direcionar para a página correspondente; |

| Caso de Teste   | CT-02 – Campos de formulário da Página Fale Conosco  |
| ------|-------|
| Requisitos Associados | RF-10 - O site deve permitir visualizar as informações de contato do mantenedor. <br>RF-13 - O site deve permitir que o usuário entre em contato com o projeto para sanar dúvidas através de mensagem de texto. <br>RF-14 – O site deve permitir que pacientes e familiares entre em contato com o projeto através de mensagens de texto para solicitar visita dos voluntários.  | 
| Objetivo do Teste   | Verificar se somente depois que todos os campos tiverem sido preenchidos corretamente é que o usuário conseguirá enviar o formulário. | 
|Passos    | 1) Acessar o Navegador <br>2) Informar o endereço do Site <br>3) Visualizar a página Fale Conosco <br>4) Preencher o formulário  | 
| Critérios de Êxito   | Os campos Nome e Sobrenome só poderá aceitar letras; <br>No campo E-mail o usuário deverá colocar um e-mail válido conforme: example@example.com; <br>Nos Campos “Quem” e “Assunto” ao clicar em selecionar, as opções disponíveis devem ser visualizadas; <br>O Campo “Mensagem” deverá possibilitar ao usuário escrever uma mensagem. <br>Após todos os campos preenchidos, se o usuário tiver inserido corretamente as informações, o formulário será enviado. Caso contrário, deverá retornar uma mensagem no campo preenchido incorretamente.  | 
 
|Casos de Teste| CT-03 – Listar “Todas” da Página Busque por Instituições  |
|-----|-----|
|Requisitos Associados  |RF-07 - O site deve permitir que o voluntário pesquise instituições e grupos cadastrados. <br>RF-08 - O site deve permitir que o voluntário pesquise locais em sua região que precisem de voluntários. |
|Objetivo do Teste  | Verificar se ao clicar em “Todas” a página carrega todas as instituições que estão no banco de dados. |
|Passos|1) Acessar o Navegador<br>  2) Informar o endereço do Site <br> 3) Visualizar a página Busque por Instituições<br>4) Clicar no botão “Todas” |
|Critérios de Êxito|Ao clicar em ‘Todas” a página deverá trazer do banco de dados todas as instituições cadastradas.|

|Casos de Teste|CT-04 – Links do menu de navegação da página de cadastro de instituição |
|-----|-----|
|Requisitos Associados  |RF-05 – O site deve permitir que a instituição médica/hospitalar realize login e senha após um cadastro.  |
|Objetivo do Teste  |Verificar se os links do menu de navegação da página de cadastro de instituição estão funcionando e direcionando para a página correspondente. |
|Passos|1) Acessar o Navegador<br>  2) Informar o endereço do Site<br>  3) Visualizar a página principal <br>4) Acessar a página de cadastro de instituição pelo link no cabeçalho <br>5) Visualizar a página de cadastro <br> 6) Clicar nos links |
|Critérios de Êxito|Todos os links ao serem clicados devem direcionar para a página correspondente; |

|Casos de Teste|CT-05 – Campos de formulário da página Cadastro de Instituição |
|-----|-----|
|Requisitos Associados  |RF-05 – O site deve permitir que a instituição médica/hospitalar realize login e senha após um cadastro.|
|Objetivo do Teste  |Verificar se somente depois que todos os campos tiverem sido preenchidos corretamente é que o usuário conseguirá enviar o formulário. |
|Passos|1) Acessar o Navegador<br> 2) Informar o endereço do Site<br> 3) Visualizar a página principal<br> 4) Acessar a página de cadastro de instituição pelo link do cabeçalho<br>5) Preencher o cadastro |
|Critérios de Êxito|O campo CNPJ só deve aceitar números.<br> O campo e-mail deve aceitar somente um e-mail válido. <br>O campo senha e confirmação de senha devem ter os caracteres substituídos por símbolos para garantir a segurança do conteúdo.  |


|Casos de Teste|CT-06 – Links da página de informações sobre o tratamento paliativo |
|-----|-----|
|Requisitos Associados  |RF-01 - O site deve apresentar uma página com informações sobre o tratamento paliativo com música.|
|Objetivo do Teste  |Verificar se a página apresenta links que direcionam para artigos científicos  |
|Passos|1) Acessar o Navegador<br> 2) Informar o endereço do Site <br>3) Visualizar a página principal <br>4) Acessar a página de informações sobre tratamento paliativo pelo link no cabeçalho<br>5) Clicar nos links para artigos científicos sobre esse tratamento|
|Critérios de Êxito|Todos os links apresentados que direcionam para artigos científicos em outras páginas web devem estar funcionando|

|Casos de Teste|CT-07 – Links da home page. |
|-----|-----|
|Requisitos Associados  |RF-01 - O site deve apresentar uma página com informações sobre o tratamento paliativo com música. |
|Objetivo do Teste  |Verificar se todos os links que estão na página home page é que direcionam para outras páginas estão funcionando. |
|Passos|1) Acessar o Navegador<br> 2) Informar o endereço do Site <br> 3) Visualizar a página home page <br>4) Clicar nos links |
|Critérios de Êxito|Todos os links ao serem clicados devem direcionar para a página correspondente;|


|Casos de Teste|CT-08 – Visualizar voluntários cadastrados da página Busque por Voluntários|
|-----|-----|
|Requisitos Associados  |RF-06 -O site deve permitir que o voluntário realize buscas por categorias instrumentais e categorias de vozes. <br>RF-07-O site deve permitir que o voluntário pesquise instituições e grupos cadastrados. |
|Objetivo do Teste  |Verificar se o banco de dados contendo os dados dos voluntários será carregado corretamente |
|Passos|1) Acessar o Navegador <br>2) Informar o endereço do Site <br>3) Visualizar a página principal <br>4) Ir até o menu Voluntários<br> 5) Clicar no sub-menu Busque por Voluntários |
|Critérios de Êxito|Ao clicar em voluntários cadastrados deverá aparecer as informações dos voluntários contidas no banco de dados |

|Casos de Teste|CT-09 – Visualizar grupos  cadastrados d.a página Busque por Voluntários |
|-----|-----|
|Requisitos Associados  |RF-01 - O site deve apresentar na página principal notícias dinâmicas obtidas por meio de canais de notícias da Internet (API) <br>RF-02 - O site deve apresentar, para cada notícia, uma imagem correspondente ao assunto apresentado (thumbnail) |
|Objetivo do Teste  |Verificar se o banco de dados contendo os dados dos grupos cadastrados será carregado corretamente |
|Passos|1) Acessar o Navegador <br>2) Informar o endereço do Site<br> 3) Visualizar a página principal <br>4) Ir até o menu Voluntários<br> 5) Clicar no sub-menu Busque por Voluntários |
|Critérios de Êxito|Ao clicar em grupos cadastrados deverá aparecer as informações dos grupos contidas no banco de dados |

#9. Registro de Testes de Software

Os resultados obtidos nos testes de software realizados são descritos abaixo. 

|Caso de Teste|CT-01 – Links da Página Fale Conosco – Antes da integração|
|-----|-----|
|Objetivo do Teste|Verificar se todos os links que estão na página Fale Conosco e que direcionam para outras páginas estão funcionando. |
|Critérios de Êxito|Todos os links ao serem clicados devem direcionar para a página correspondente; |
|Registro de Execução  |Êxito no teste.  |

|Caso de Teste|CT-02 – Campos de formulário da Página Fale Conosco – Antes da integração |
|-----|-----|
|Objetivo do Teste|Verificar se somente depois que todos os campos tiverem sido preenchidos corretamente é que o usuário conseguirá enviar o formulário|
|Critérios de Êxito|Os campos Nome e Sobrenome só poderá aceitar letras; <br>No campo E-mail o usuário deverá colocar um e-mail válido conforme: example@example.com;<br> Nos Campos “Quem” e “Assunto” ao clicar em selecionar, as opções disponíveis devem ser visualizadas; <br>O Campo “Mensagem” deverá possibilitar ao usuário escrever uma mensagem. <br>Após todos os campos preenchidos, se o usuário tiver inserido corretamente as informações, o formulário será enviado. Caso contrário, deverá retornar uma mensagem no campo preenchido incorretamente.|
|Registro de Execução  |Êxito no teste.  |

|Casos de Teste|CT-03 – Listar “Todas” da Página Busque por Instituições - Antes da integração |
|-----|-----|
|Objetivo do Teste  |RF-07 - O site deve permitir que o voluntário pesquise instituições e grupos cadastrados. <br>RF-08 - O site deve permitir que o voluntário pesquise locais em sua região que precisem de voluntários. |
|Critérios de Êxito|Verificar se ao clicar em “Todas” a página carrega todas as instituições que estão no banco de dados.|
|Registro de Execução|Êxito no teste.|

|Casos de Teste|CT-04 – Links da página de cadastro de instituição - Antes da integração |
|-----|-----|
|Objetivo do Teste  |Verificar se os links do menu de navegação da página de cadastro de instituição estão funcionando e direcionando para a página correspondente. |
|Critérios de Êxito|Todos os links ao serem clicados devem direcionar para a página correspondente|
|Registro de Execução|Êxito no teste.|

|Casos de Teste|CT-05 – Campos de formulário da página Cadastro de Instituição - Antes da integração |
|-----|-----|
|Objetivo do Teste  |Verificar se somente depois que todos os campos tiverem sido preenchidos corretamente é que o usuário conseguirá enviar o formulário. |
|Critérios de Êxito|O campo CNPJ só devem aceitar números. <br> O campo e-mail deve aceitar somente um e-mail válido. <br>O campo senha e confirmação de senha devem ter os caracteres substituídos por símbolos para garantir a segurança do conteúdo. |
|Registro de Execução|Êxito no teste.|

|Casos de Teste|CT-06 – Links da página de informações sobre o tratamento paliativo – Antes da integração |
|-----|-----|
|Objetivo do Teste  |Verificar se a página apresenta links que direcionam para artigos científicos e se estão direcionando corretamente.|
|Critérios de Êxito|Todos os links apresentados devem direcionam para artigos científicos em outras páginas web.|
|Registro de Execução|Êxito no teste.|

