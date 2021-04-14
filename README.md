<h1 align="center" >
  <img alt="Abas Online" src="https://abas.online/wp-content/themes/abas/images/marca-abas-positiva.svg" width="200px" />
</h1>

<h2 align="center" > Teste Dev Mobile </h2>

## 1 - Sobre o App

O objetivo é criar um app para o cadastro de contas bancárias pessoais.

## 2 - Tecnologias

O app poderá ser desenvolvido nas tecnologias Ionic ou React Native.
  
  #### 2.1 - Diferencial (opcional) 
  
  Desenvolvido em React Native.
  Utilizar a linguagem TypeScript para escrita do código.

## 3 - Funcionalidades

O app deverá possuir as seguintes funcionalidades:

- __Tela Inicial:__ A tela inicial deverá listar todas as contas bancárias cadastradas na aplicação.
    - No topo da tela inicial deverá possuir um botão para cadastrar uma nova conta bancária. Ao clicar neste botão o usuário deverá ser direcionado para __Tela de Listagem __
    - As contas cadastradas deverão ser exibidas abaixo do botão de cadastrar nova conta e ficarão armazenadas no local storage do dispositivo. O cadastro das contas serão realizadas conforme as funcionalidades descritas abaixo.
    - Se não existir conta cadastrada deverá exibir uma mensagem de que não existe conta cadastrada logo abaixo ao botão de cadastro de nova conta do topo da tela.

- __Tela de Listagem:__ Apresentar um tela de listagem de todos os bancos para que seja selecionado um banco para o cadastro.
    - Para listagem de todos os bancos deverá ser utilizada a api pública: https://brasilapi.com.br/api/banks/v1
    - No topo da tela de listagem, deverá existir um campo com um botão para consulta do banco pelo código do banco. Este campo receberá o código do banco e ao clicar no botão irá apresentar apenas o banco consultado na tela de listagem. Para consultar o banco através do código deverá ser utilizada a api pública: https://brasilapi.com.br/api/banks/v1/{code}
    - Ao clicar em um banco da tela de listagem o usuário deverá ser redirecionado para a para __Tela de Cadastro __

- __Tela de Cadastro:__ Cadastro da conta
    - Nesta tela deverá exibir todas as informações do banco retornadas pela api.
    - Abaixo das informações do banco deverá existir dois campos para o usuário informar a agencia e conta de cadastro.
    - Abaixo dos campos deverá possuir um botão para cadastrar a conta.
    - O cadastro da conta deverá ser armazenado no local storage do dispositivo - Armazenar (Codigo do Banco, Agencia e Conta).

A documentação da API: https://brasilapi.com.br/docs#tag/BANKS

## 4 - Instruções
- Criar repositório no Github para desenvolvimento do projeto;
- Após finalizar, enviar link do repositório para **fernando@abas.online**, **pedro@abas.online**, **lucas.silva@abas.online**,  e **mariana.machado@groupsoftware.com.br**.

## 5 - E por fim
- Gostaríamos de ver o histórico de seus commits;
- Vamos avaliar a maneira que você escreveu seu código e a solução apresentada;
- Caso encontre algum impedimento no decorrer do desenvolvimento, entregue da maneira que preferir e faça uma explicação sobre o impedimento;
- Avaliaremos também sua postura, honestidade e a maneira que resolve problemas.
