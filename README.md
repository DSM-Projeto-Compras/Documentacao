# Projeto de Compras 
<br id="topo">
<p align="center">
    <a href="#sobre">Sobre</a>  |  
    <a href="#backlogs">Backlogs & User Stories</a>  |
    <a href="#prototipo">Protótipo & Documentação</a>  | 
    <a href="#link">Links Uteis</a>  |
    <a href="#tecnologias">Tecnologias</a>  |  
    <a href="#equipe">Equipe</a>  |
     
    
</p>

<span id="sobre">

## :bookmark_tabs: Sobre
A partir de pedidos do administrativo da Faculdade Técnica de Votorantim, o desenvolvimento do site para facilitar o trabalho do funcionário responsável pelo trabalho de compras, consiste em um sistema de 2 frentes: a do **funcionário geral**, que pode gerar um pedido para um produto e acompanhar o andamento do pedido e o **funcionário de compras**, que visualiza pedidos realizados e os processa, mantendo o **funcionário geral** informado.

>_Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Produtividade e Colaboração entre funcionários da instituição_

Baseado em necessidades apontadas por funcionários, o usuário utilizará o sistema para armazenar dados que serão utilizados posteriormente em um novo pedido de compra, de forma que organize opções de compras e otimize tempo de pesquisa.

A partir desta ideia, o aplicativo utiliza de uma API desenvolvida para cadastrar produtos, sendo permitida a consulta, inclusão, mudança e exclusão de cada um.


:pushpin: Status do Projeto: **✔️ Concluído** 

### 🏁 Entregas de Sprints
| Sprint | Previsão | Status | Histórico |
|:--:|:----------:|:----------------|:-------------------------------------------------:|
| 01 | 20/05/2024 |  ✔️Concluído    |[ver relatório](https://github.com/paulovictorio/Documentacao_projetoCompras/blob/sprint-01/README.md)|
| 02 | 03/06/2024 |  ✔️Concluído    |[ver relatório](https://github.com/paulovictorio/Documentacao_projetoCompras/blob/sprint-02/README.md)|
| 03 | 17/06/2024 |  ✔️Concluído    |[ver relatório](https://github.com/paulovictorio/Documentacao_projetoCompras/blob/sprint-03/README.md)|

### :clapper: Apresentação Final
Confira a seguir uma demonstraão das funcionalidades para cada tipo de usuário do sistema:
<details>
   <summary>Diretor de Serviços Administrativos</summary>
    <div align="center">
        <img src="./interface_admin.gif">
    </div>
</details>
<details>
   <summary>Funcionários</summary>
    <div align="center">
          <img src="./interface_usuario.gif">
    </div>
</details>
    
→ [Voltar ao topo](#topo)

<span id="backlogs">
    
## 👷 Backlogs & User Stories
<div align="center">
    <img src="requisitos.png">
   <img src="requisitosnf.png">

   <img src="user_stories.png">
</div>

→ [Voltar ao topo](#topo)

    
## Protótipo e Documentação
### 🏠 Protótipo 
<span id="prototipo">
    Com base nos dados coletados em pesquisas, foi possível montar um protótipo de alta fidelidade com o uso da ferramenta Figma. Esta ferramenta possibilitou uma visualização prévia do front-end do projeto, o suficiente para obter o alinhamento entre a equipe de desenvolvimento e o cliente. Desta forma, o projeto prototipado possui algumas funções básicas de acesso a telas e respostas a cliques em botões, posteriormente sendo funcionalidades aplicadas na própria aplicação.
    O acesso ao protótipo pode ser feito <a href="https://www.figma.com/proto/aoRbpLGfGNXeTD0hLtrsDr/Projeto-Integrador?node-id=0-1&t=P5UiG1z4EAXU1bLR-1">aqui</a>

### 🐳 Docker
<span id="docker">
    Este projeto também possui contêineres e imagens docker, permitindo replicar o software tal como planejado. Para isso, se encontram em cada repositório Frontend e Backend um arquivo Dockerfile, que contém instruções gerais de como inicializar o projeto, e um arquivo docker-compose, que possui uma forma automatizada de inicializar o projeto.
    Para gerar e iniciar uma imagem e container docker, basta inserir em um terminal aberto para cada repositório:
    
```bash
docker-compose up --build
``` 
    

### 📄 Documentação 
As documentações deste projeto possuem mais detalhes do planejamento e da arquitetura do software. 
Elas podem ser acessadas pelos links: [Documentação do projeto](documentacao_compras_pi.pdf)
E [Documentação ihc](ihc_compras.pdf). <br>

<span id="link">
    
> 🔗 **Links gerais** <br>
> - Link do sistema funcional: [clique aqui para acessar](https://projeto-mvc-restful-frontend.vercel.app)
> - Repositório do projeto: [clique aqui para acessar](https://github.com/thiago-diegoli/Projeto-MVC-RESTful)


## 🛠️ Tecnologias Utilizadas 
<span id="tecnologias">
    <p align="center">
      <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,typescript,react,tailwind,docker,nodejs,mongodb,vercel,vscode,figma" />
  </a>
</p>
</span>


## :busts_in_silhouette: Equipe


<span id="equipe">
    

|    Função     |                  Nome                 |                          GitHub                              | 
| :-----------: | :-----------------------------------: | :----------------------------------------------------------: |
| Product Owner | Eduardo Brando Almeida                |[![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Eduardo-Brando-Almeida)|
| Dev Team | Paulo César Ap. Q. V. Victório             |[![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/paulovictorio)|
| Dev Team  | Felipe Thiago da Silva                    |[![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Felipe-Thiago)|
| Dev Team | Thiago Saldanha Diegoli                    |[![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/thiago-diegoli)|
| Dev Team | Yara Paes de Bona                          |[![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/YaraPaesB)|

→ [Voltar ao topo](#topo)


## 🪪 Licença

The MIT License (MIT) 2024
