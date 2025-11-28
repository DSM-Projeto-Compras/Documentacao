<span id="topo">

<h1 align="center">Sprint 5: 19/05/2025 a 05/06/2025</h1>

<p align="center">
    <a href="https://github.com/DSM-Projeto-Compras/Documentacao/blob/sprint-04/README.md">Sprint 4</a> &nbsp |&nbsp &nbsp
    <a href="#objetivos">Objetivos da sprint</a>  
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a> &nbsp |&nbsp &nbsp
    <a href="https://github.com/DSM-Projeto-Compras/Documentacao/blob/sprint-06/README.md">Sprint 6</a>
</p>

Nesta sprint o objetivo foi começar a adaptar o projeto para o uso em dispositivos mobiles, definindo novos requisitos e planejando a criação de ambientes na nuvem.

<span id="objetivos">

## :dart: Objetivos da Sprint

Os requisitos abrangidos por essa sprint são:
- **RF 01:** Realizar cadastro
- **RF 02:** Realizar login 
- **RF 03:** Rodapé 
- **RF 04:** Requisitar produto
- **RF 05:** Visualização do histórico de pedidos
- **RF 07:** Visualização dos detalhes de um pedido
- **RF 08:** Visualização da justificativa de um pedido negado
- **RNF 01:** Linguagens JavaScript e React Native
- **RNF 02:** Uso da biblioteca expo dev
- **RNF 04:** Uso de Banco de Dados SQLite para dados de usuários e requisições
- **RNF 05:** Uso da API de pesquisa da BEC
- **RNF 06:** Criptografia da senha dos usuários
- **RNF 07:** Segurança contra injeção de SQL
- **RNF 08:** Sistema ativo a todo o tempo
- **RNF 09:** Responsividade entre diferentes dispositivos móveis
- **RNF 10:** Autenticação do usuário por SPA

<div align="center">

![demo](./demo.gif)
</div>

<span id="entregas">

## :heavy_check_mark: Entregas

<div align="center">

### RF 01 e RF 02: Realizar cadastro e Realizar Login

Este requisito se trata do cadastro e login de usuários, apenas os funcionários gerais realizam o cadastro, como descrito no caso de uso. Ambos os usuários realizarão login, porém terão telas especificas, por exemplo:

- **Funcionário geral** tem uma página com a opção de realizar pesquisas com a web service da BEC, opção de quantidade e discrição do pedido.
- **Funcionário diretor de serviços administrativos** tem uma página com o histórico dos pedidos realizados e um filtro para realizar pesquisas especificas.

### RF 03 : Rodapé

Este requisito se refere à funcionalidade de trocar de abas no mobile, permitindo ao usuário (administrador ou não) trocar entre a visualização do histórico de pedidos, novos cadastros ou sair do sistema

- **Funcionário diretor de serviços administrativos** alterna entre o histórico de pedidos, a tela de cadastro de novos usuários e sair do sistema
- **Funcionário Geral** alterna entre o histórico de pedidos próprios, a tela de requisição de novos pedidos e sair do sistema

### RF 04 : Requisitar produto

Este requisito se refere à função do usuário comum de requisitar um produto para que o administrador o consiga analisar e decidir se será aceito e salvo ou não.

### RF 05, RF 07 e RF 08 : Visualização do histórico de pedidos, Visualização dos detalhes de um pedido e Visualização da justificativa de um pedido negado

Este requisito se refere à visualização de pedidos realizados pelo usuário e entregues ao administrador e suas variações caso o pedido seja aprovado ou negado.

- **Funcionário diretor de serviços administrativos** visualiza pedidos realizados por usuários e os classifica em aprovado ou negado, inserindo uma justificativa ao usuário caso um pedido seja negado e alterando seu status
- **Funcionário Geral** visualiza pedidos anteriormente realizados por ele e é permitido os alterar caso estejam pendentes, visualizando a mudança de status que o administrador decidir e tendo edições bloqueadas caso alguma escolha seja feita, permitindo-o visualizar os detalhes do pedido.

</div>


→ [Voltar ao topo](#topo)
    
<span id="links">

## :link: Links úteis

- Repositório do projeto: [Projeto de compras](https://github.com/DSM-Projeto-Compras/Documentacao)
- Site do projeto: [https://front-end-wine-nu.vercel.app](https://front-end-wine-nu.vercel.app)
- Voltar ao [documento principal](https://github.com/DSM-Projeto-Compras/Documentacao)
