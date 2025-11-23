<span id="topo">

<h1 align="center">Sprint 12: 14/11/2025 a 28/11/2025</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#problemas">Diário e Desafios</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a> 
</p>

Nesta sprint o objetivo foi finalizar o desenvolvimento do projeto Gerenciador de Pedidos de Compras

<span id="objetivos">

## :dart: Objetivos da Sprint

Os requisitos abrangidos por essa sprint são:
- **RF 12:** Alteração do status de um pedido (administrador)
- **RF 13:** Realizar cadastro de fornecedores
- **RF 14:** Listagem de fornecedores
- **RF 15:** ChatBot funcional com reconhecimento de voz
- **RNF 12:** Cobertura e documentação de testes

<span id="entregas">

## :heavy_check_mark: Entregas

<div align="center">

### RF 12, RF 13, RF 14, RF 15, RNF 12 : Alteração do status de um pedido, Realizar cadastro de fornecedores, Listagem de fornecedores, Chatbot fincional com reconhecimento de voz, Cobertura e documentação de testes



Esses requisitos se referem a conclusão dos status de pedido do sistema Gerenciador de Pedidos de Compra

### RF 12 : Alteração do status de um pedido

- **Funcionário diretor de serviços administrativos** visualiza que um pedido foi feito trocando o status para visto, avalia o pedido, decide se o pedido será aceito ou negado, caso negado, deve haver justificativa, caso aceito, passará para o estado de aguardando compra, em seguida será determinado ou cadastrado o fornecedor responsável por vender o produto, seguindo o status para aguardando a entrega, uma vez que atualizado, passará para o estado de aguardando retirada do usuário, quando atualizado, o pedido será finalizado.  
- **Funcionário Geral** visualiza que seu pedido está pendente até que o funcionário diretor de serviços administrativos visualize, o tornando pendente, em seguida o funcionário geral (usuário) aguarda o deferimento ou cancelamento do pedido, caso cancelado, o usuário poderá ler a descrição e compreender o motivo do cancelamento, caso deferido, o usuário visualizara os estágios até que o produto esteja a seu aguardo na diretoria de serviços administrativos.
- **Testes de Caixa-Preta** foram realizados em todos os inputs encontrados na aplicação.

### RF 13 : Realizar cadastro de fornecedores

- **Funcionário diretor de serviços administrativos** cadastra fornecedores pela tela de cadastro de fornecedores ou ao alterar o status de um pedido de aprovado para realizado.

### RF 14 : Listagem de fornecedores

- **Funcionário diretor de serviços administrativos** visualiza os fornecedores cadastrados e suas informações mais essênciais, pode clicar em um fornecedor para abrir um modal com todas as informações dele.





</div>

## :bookmark_tabs: Diário e Desafios

- **RF 02, RF 10, RF 11, RNF 12** : Durante a atualização do sistema web, atualizações na implementação da pesquisa por itens na BEC foi removida do front-end web e mobile e passada para o back-end, aplicando o conceito de um sistema S.O.L.I.D, porém desviando atenção da equipe de desenvolvimento, de qualquer forma, a atualização do sistema WEB foi finalizada e a documentação de testes junto dos testes de caixa preta foram concluídos. A nova feature da troca de senha de administradores já entrou em produção antes do início da próxima sprint.

→ [Voltar ao topo](#topo)
    
<span id="links">
