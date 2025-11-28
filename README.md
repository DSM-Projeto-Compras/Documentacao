<span id="topo">

<h1 align="center">Sprint 12: 14/11/2025 a 28/11/2025</h1>

<p align="center">
    <a href="https://github.com/DSM-Projeto-Compras/Documentacao/blob/sprint-11/README.md">Sprint 11</a> &nbsp |&nbsp &nbsp
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#problemas">Diário e Desafios</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a> 
</p>

Nesta sprint o objetivo foi finalizar o desenvolvimento do projeto Gerenciador de Pedidos de Compras

### Tempo de desenvolvimento da sprint : 98 horas e 45 minutos
### Tempo de desenvolvimento do projeto: 376 horas e 5 minutos

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

### RF 12, RF 13, RF 14, RF 15, RNF 12 : Alteração do status de um pedido, Realizar cadastro de fornecedores, Listagem de fornecedores, Chatbot funcional com reconhecimento de voz, Cobertura e documentação de testes



Esses requisitos se referem a conclusão dos status de pedido do sistema Gerenciador de Pedidos de Compra

### RF 12 : Alteração do status de um pedido

- **Funcionário diretor de serviços administrativos** visualiza que um pedido foi feito trocando o status para visto, avalia o pedido, decide se o pedido será aceito ou negado, caso negado, deve haver justificativa, caso aceito, passará para o estado de aguardando compra, em seguida será determinado ou cadastrado o fornecedor responsável por vender o produto, seguindo o status para aguardando a entrega, uma vez que atualizado, passará para o estado de aguardando retirada do usuário, quando atualizado, o pedido será finalizado.  
- **Funcionário Geral** visualiza que seu pedido está pendente até que o funcionário diretor de serviços administrativos visualize, o tornando pendente, em seguida o funcionário geral (usuário) aguarda o deferimento ou cancelamento do pedido, caso cancelado, o usuário poderá ler a descrição e compreender o motivo do cancelamento, caso deferido, o usuário visualizara os estágios até que o produto esteja a seu aguardo na diretoria de serviços administrativos.
- **Testes de Caixa-Preta** foram realizados em todos os inputs encontrados na aplicação.

### RF 13 : Realizar cadastro de fornecedores

- **Funcionário diretor de serviços administrativos** cadastra fornecedores pela tela de cadastro de fornecedores ou ao alterar o status de um pedido de aprovado para realizado.

### RF 14 : Listagem de fornecedores

- **Funcionário diretor de serviços administrativos** visualiza os fornecedores cadastrados e suas informações mais essênciais, pode clicar em um fornecedor para abrir um modal com todas as informações dele.

### RF 15 : Chatbot funcional com reconhecimento de voz

- **Funcionário Geral** pode escolher navegar pelo site com reconhecimento de voz e caso tenha dúvidas sobre como preencher o pedido, pode abrir a aba do chatbot e fazer perguntas pertinentes a aplicação sobre como utilizar da forma correta.



</div>

<span id="problemas">

## :bookmark_tabs: Diário e Desafios

- **RF 12, RF 13, RF 14, RF 15, RNF 12** : Foi desenvolvida a nova tela de gerenciamento de pedidos (AdminOrdersTemplate) apresenta um fluxo de status em kanban (Aprovado → Realizado → Entregue → Finalizado), permitindo atribuir fornecedores aos pedidos através do relacionamento supplierId e gerenciar transições de estado. As consultas de produtos no backend passaram a incluir dados completos do fornecedor (mesmo desativado), garantindo rastreabilidade e exibição correta na interface, enquanto o modelo de Supplier filtra apenas fornecedores ativos nas listagens e valida CNPJ considerando apenas registros ativos. Foi desenvolvido um chatbot para que os usuários possam tirar dúvidas sobre a usabilidade do sistema, junto um sistema de reconhecimento de voz para conversar com o chatbot e realizar navegação por voz, o sistema de reconhecimento de voz utiliza o SpeechRecognition do google chrome, então é uma ferramenta exclusiva do navegador. Ouve adição de validators para formulários do frontend. A cobertura de testes foi estendida para as features de fornecedores. 

→ [Voltar ao topo](#topo)
    
<span id="links">

## :link: Links úteis

- Repositório do projeto: [Projeto de compras](https://github.com/DSM-Projeto-Compras/Documentacao)
- Site do projeto: [https://front-end-wine-nu.vercel.app](https://front-end-wine-nu.vercel.app)
- ChatBot funcional: [ChatBot](https://front-end-wine-nu.vercel.app/pages/chat-bot)
- Voltar ao [documento principal](https://github.com/DSM-Projeto-Compras/Documentacao)
