# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Não deixe de enumerar os casos de teste de forma sequencial e de garantir que o(s) requisito(s) associado(s) a cada um deles está(ão) correto(s) - de acordo com o que foi definido na seção "2 - Especificação do Projeto". 

Por exemplo:
 
| **Caso de Teste** 	| **CT-01 – Cadastrar perfil** 	|
|:---:	|:---:	|
|	Requisito Associado 	| RF-001 - A aplicação deve apresentar, na página principal, a funcionalidade de cadastro de usuários para que esses consigam criar e gerenciar seu perfil. |
| Objetivo do Teste 	| Verificar se o usuário consegue se cadastrar na aplicação. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar em "Criar conta" <br> - Preencher os campos obrigatórios (e-mail, nome, data de nascimento,endereco, login, senha, confirmação de senha, tipo, telefone, RG, CPF, ) <br> - Aceitar os termos de uso <br> - Clicar em "Confirmar" |
|Critério de Êxito | O cadastro foi realizado com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-02 – Gerenciar produtos** 	|
|	Requisito Associado 	| RF-002 - A aplicação deve ter, na página principal do perfil do empreendedor, a página de "Gerenciar produtos". Dentre dessa página com as funcionalidades "registrar", "editar", "deletar" e "Quantidade" para que os usuários empreendedores consigam gerenciar seus produtos no seu perfil. |
| Objetivo do Teste 	| Verificar se o usuário consegue se cadastrar os produtos no seu perfil na aplicação. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Gerenciar produtos"|
|Critério de Êxito | O usuário empreendedor consegue gerenciar produtos com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-03 – Visualizar os comentários** 	|
|	Requisito Associado 	| RF-003 - A aplicação deve permitir os usuários (os empreendedores e os clientes) consigam visualizar os comentários na páginas dos produtos. |
| Objetivo do Teste 	| Verificar se o usuário consegue visualizar a seção de comentários nas página dos produtos. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Produtos" <br> - escolher um produto e clicar neste|
|Critério de Êxito | O usuário consegue visualizar a seção de comentários na página do produto escolhido com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-04 – Enviar comentários** 	|
|	Requisito Associado 	| RF-004 - A aplicação deve permitir os usuários (tanto empreendedores e quanto os clientes) possam interagir na seção de comentários na páginas dos produtos. |
| Objetivo do Teste 	| Verificar se o usuário consegue fazer um comentário na a seção de comentários nas página dos produtos. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Produtos" <br> - escolher um produto e clicar <br> - preencher no campo do "comentário" <br> - clicar "Enviar"|
|Critério de Êxito | O usuário consegue fazer um comentário na seção de comentários na página do produtos escolhido com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-05 – Visualizar a informação "vegano" ou "não vegano"** 	|
|Requisito Associado | RF-005	- A aplicação deve apresentar a informação "vegano" ou "não vegano" nas páginas dos produtos |
| Objetivo do Teste 	| Verificar se o usuário cliente consegue visualizar a informação. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Clicar em "Produtos"<br> - escolher um e clicar|
|Critério de Êxito | O usuário cliente consegue visualizar as informações "vegano" ou "não vegano" na página do produto escolhido com sucesso. E o usuário empreendedor consegue escolher entre as opções "vegano" ou "não vegano" ao registrar o produto no sistema com sucesso.|
|  	|  	|
| **Caso de Teste** 	| **CT-06 – Pesquisar os produtos** 	|
|Requisito Associado | RF-006	- A aplicação deve permitir que os usuários clientes consigam pesquisar os produtos por diferentes critérios |
| Objetivo do Teste 	| Verificar se o usuário cliente consegue pesquisar visualizar, adicionar e excluir os produtos no carrinhos de compras. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Clicar em "Produtos"<br> - Aparece as opções "Cabelo", "Pele" e "Acessórios"|
|Critério de Êxito | O usuário consegue visualizar apenas os produtos referente à opção selecionada  com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-07 – Gerenciar o carrinhos de compras** 	|
|Requisito Associado | RF-007	- A aplicação deve permitir que os usuários clientes consigam visualizar, adicionar e excluir os produtos no carrinhos de compras|
| Objetivo do Teste 	| Verificar se o usuário cliente consegue pesquisar e filtrar por diferentes critérios. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Clicar em "Produtos"<br> - clicar em "adicionar no carrinho" <br> - clicar em "carrinho de compras"<br> - selecionar a quantidade <br> - clicar em "Excluir" <br> - Voltar para a página de compras|
|Critério de Êxito | O usuário consegue visualizar, adicionar e excluir os produtos no carrinhos de compras e voltar para a página dos produtos com sucesso.|
|  	|  	|
| **Caso de Teste** 	| **CT-08 – Finalizar pedido** 	|
|Requisito Associado | RF-008	- A aplicação deve ter a funcionalidade "Finalizar pedido" no carrinhos de compras|
| Objetivo do Teste 	| Verificar se o usuário cliente consegue pesquisar e filtrar por diferentes critérios. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Clicar em "Produtos"<br> - clicar em "adicionar no carrinho" <br> - clicar em "carrinho de compras"<br> - selecionar a quantidade <br> - clicar em "Finalizar pedido" <br> - Aparecer o preço final|
|Critério de Êxito | O usuário consegue finalizar o pedido e receber o preço final com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-09 – Visualizar o número atualizado da quantidade de produtos disponíveis** 	|
|Requisito Associado | RF-009	- A aplicação deve apresentar uma atualização do número referente a quantidade de produtos disponíveis para o usuário empreendedor. Toda vez que um produto for vendido o sistema precisa atualizar a quantidade|
| Objetivo do Teste 	| Verificar se o usuário empreendedor consegue visualizar o número atualizado da quantidade de produtos disponíveis. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Gerenciar produtos"<br> - clicar em "Quantidade" <br> - Visualizar a quantidade atualizada após a venda|
|Critério de Êxito | O usuário consegue finalizar o pedido e receber o preço final com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-10 – Visualizar o relatório de vendas** 	|
|Requisito Associado | RF-010	- A aplicação deve apresentar um relatório de vendas para o usuário Empreendedor|
| Objetivo do Teste 	| Verificar se o usuário empreendedor consegue visualizar  número atualizado da quantidade de produtos disponíveis. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Preencher os campos e-mail e senha <br>  - Clicar em "login"  <br> - clicar em "Relatório" <br> - Visualizar relatório de vendas|
|Critério de Êxito | O usuário Empreendedor consegue finalizar visualizar relatório de vendas com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-11 – Teste de responsividade** 	|
|Requisito Associado | RNF-01	- A aplicação deve ter responsividade|
| Objetivo do Teste 	| Verificar as páginas renderizarem bem em uma variedade de dispositivos e tamanhos de janela ou tela do mínimo ao máximo. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Repetir o processo em diferentes tamanhos de dispositivos|
|Critério de Êxito | O usuário consegue visualizar as páginas redenrizadas em diferentes tamanhos de telas com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-12 – Teste de integridade e segurança de dados** 	|
|Requisito Associado | RNF-02	- A aplicação estar dentro das normas da LGPD|
| Objetivo do Teste 	| Verificar se dados foram registrados corretamente no banco de dados após o cadastro do usuário e o registro do produto. Também verificar a exclusão dos dados no Banco de dados após os usuários exluírem os produtos, e alteração dos dados após os usuários atualizarem o perfi e depois da venda a atualiação da quantidade. |
| Passos 	| - Verificar os dados no Banco de dados após o cadastro de usuário<br> - Verificar os dados no Banco de dados após o registro de produto <br> -Verificar os dados no Banco de dados após exclusão dos produtos <br> - Verificar os dados usuários no Banco de dados após a alteração do perfil <br> -Verificar os dados de quantidade de produtos no Banco de dados após as vendas |
|Critério de Êxito | O usuário consegue visualizar os dados atualizado com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-13 – Efetuar login** 	|
|Requisito Associado | RF-03	- A aplicação deve possuir opção de fazer login, sendo o login o endereço de e-mail. |
| Objetivo do Teste 	| Verificar se o usuário consegue realizar login. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" |
|Critério de Êxito | O login foi realizado com sucesso. |
|  	|  	|
| **Caso de Teste** 	| **CT-14 – Seção de comentários** 	|
|Requisito Associado | RNF-04	- A aplicação deve possuir uma Seção de comentários nas páginas de cada produto |
| Objetivo do Teste 	| Verificar se cada produto tem uma seção de comentário com o campo que permite o usuário preencher e enviar o comentário. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://ecoempreendedor.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" <br> - Escolher um produto e clicar neste<br> - Na página do produto visualizar a Seção de comentários <br> - Clicar em no campo de comentário e preencher <br> - Enviar o comentário <br> - Visualizar o comentário.|
|Critério de Êxito | O comentário foi realizado com sucesso. |
 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)
> - [Criação e Geração de Planos de Teste de Software](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)
