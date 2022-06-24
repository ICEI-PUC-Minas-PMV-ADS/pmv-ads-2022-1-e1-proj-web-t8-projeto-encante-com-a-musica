# Registro de Testes de Software

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>, <a href="8-Plano de Testes de Software.md"> Plano de Testes de Software</a>

Relatório com as evidências dos testes de software realizados no sistema pela equipe, baseado em um plano de testes pré-definido.

Os resultados obtidos nos testes de software realizados são descritos abaixo. 


|Caso de Teste|CT-01 – Campos de formulário da Página Fale Conosco |
|-----|-----|
|Objetivo do Teste|Verificar se somente depois que todos os campos tiverem sido preenchidos corretamente é que o usuário conseguirá enviar o formulário|
|Critérios de Êxito|Os campos Nome e Sobrenome só poderá aceitar letras; <br>No campo E-mail o usuário deverá colocar um e-mail válido conforme: example@example.com;<br> Nos Campos “Quem” e “Assunto” ao clicar em selecionar, as opções disponíveis devem ser visualizadas; <br>O Campo “Mensagem” deverá possibilitar ao usuário escrever uma mensagem. <br>Após todos os campos preenchidos, se o usuário tiver inserido corretamente as informações, o formulário será enviado. Caso contrário, deverá retornar uma mensagem no campo preenchido incorretamente.|
|Registro de Execução  |Êxito no teste.  |

## Caso de Teste 01 - Print da tela

<img src="img/testefaleconosco.png">
<img src="img/testefaleconosco2.png">

|Casos de Teste|CT-02 – Listar “Todas” da Página Busque por Instituições |
|-----|-----|
|Objetivo do Teste  |RF-07 - O site deve permitir que o voluntário pesquise instituições e grupos cadastrados. <br>RF-08 - O site deve permitir que o voluntário pesquise locais em sua região que precisem de voluntários. |
|Critérios de Êxito|Verificar se ao clicar em “Todas” a página carrega todas as instituições que estão no banco de dados.|
|Registro de Execução|Êxito no teste.|

## Caso de Teste 02 - Print da tela

<img src="img/testebuscaint.png">
<img src="img/testebuscaint2.png">

|Casos de Teste|CT-03– Campos de formulário da página Cadastro de Instituição |
|-----|-----|
|Objetivo do Teste  |Verificar se somente depois que todos os campos tiverem sido preenchidos corretamente é que o usuário conseguirá enviar o formulário. |
|Critérios de Êxito|O campo CNPJ só devem aceitar números. <br> O campo e-mail deve aceitar somente um e-mail válido. <br>O campo senha e confirmação de senha devem ter os caracteres substituídos por símbolos para garantir a segurança do conteúdo. |
|Registro de Execução|Êxito no teste.|

## Caso de Teste 03 - Print da tela

<img src="img/testecadastro.png">
<img src="img/testecadastro2.png">

|Casos de Teste|CT-04 – Links da página de informações sobre o tratamento paliativo|
|-----|-----|
|Objetivo do Teste  |Verificar se a página apresenta links que direcionam para artigos científicos e se estão direcionando corretamente.|
|Critérios de Êxito|Todos os links apresentados devem direcionam para artigos científicos em outras páginas web.|
|Registro de Execução|Êxito no teste.|

## Caso de Teste 04 - Print da tela

<img src="img/testesobre.png">
<img src="img/testesobre2.png">


|Casos de Teste|CT-05 – Links da home page|
|-----|-----|
|Objetivo do Teste  |Verificar se todos os links localizados na home page estão sendo direcionados para as outras páginas corretamente|
|Critérios de Êxito|Todos os links da página devem ser direcionados as outras páginas corretamente|
|Registro de Execução|Êxito no teste.|

## Caso de Teste 05 - Print da tela

|Casos de Teste|CT-06 – Visualizar voluntários cadastrados da página Busque por Voluntários |
|-----|-----|
|Objetivo do Teste  |Verificar se o banco de dados contendo os dados dos voluntários será carregado corretamente |
|Critérios de Êxito|Ao clicar no botão "Voluntários cadastrados" deverá aparecer na tela as informações dos voluntários cadastrados no banco de dados|
|Registro de Execução|Êxito no teste.|

## Caso de Teste 06 - Print da tela

<img src="img/testebuscavol.png">
<img src="img/testebuscavol2.png">

|Casos de Teste| CT-07 – Visualizar grupos  cadastrados da página Busque por Voluntários|
|-----|-----|
|Objetivo do Teste  |Verificar se o banco de dados contendo os dados dos grupos cadastrados será carregado corretamente |
|Critérios de Êxito|Ao clicar no botão "Grupos cadastrados" deverá aparecer na tela as informações dos voluntários cadastrados no banco de dados|
|Registro de Execução|Êxito no teste.|

## Caso de Teste 07 - Print da tela

<img src="img/telabuscagrupos.png">