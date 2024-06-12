<span id="topo">

<h1 align="center">Sprint 2: 20/05/2024 a 03/06/2024</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Com a segunda Sprint, o projeto teve um aprofundamento maior no desenvolvimento, visto que todos os requisitos estavam estabelecidos e, neste momento, partem para a construção mais específica de funcionalidades envolvendo a lógica de negócio a ser atingida. Foram implementadas funções de listagem dos produtos (incluindo descrição e escolha deles), realização do pedido em si, definição de um histórico a ser visto tal como funções comuns a ele, como edição e exclusão de dados.

<span id="objetivos">
    
## :dart: Objetivos da Sprint

Os requisitos abrangidos por essa sprint são:
- **RF 04:** Escolher produto
- **RF 05:** Escolher descrição do pedido
- **RF 06:** Escolher quantidade desejada
- **RF 07:** Realizar pedido
- **RF 08:** Visualizar pedido no histórico
- **RF 09:** Excluir pedido realizado
- **RNF 18:** Funcionamento de um histórico de produtos
- **RNF 19:** Funcionamento de um filtro de pesquisa do histórico
- **RNF 20:** Status com "Pendente" como padrão

<span id="entregas">
    
## :heavy_check_mark: Entregas

<div align="center">

Para entregas da sprint, tivemos os artefatos SCRUM validados, como Backlog do Produto, Backlog das Sprints e User Stories, através de comunicação direta entre o P.O. e o cliente.


Para avaliar a permanência do projeto nos requisitos e a validade das funções, foram realizados testes simuntâneos ao desenvolvimento, tal como diz a metodologia TDD (desenvolvimento orientado a testes). A construção seguiu conforme alguns dos requisitos funcionais já da primeira sprint, e podem ser observadas a seguir:

### RF 04: Encontrar o produto desejado para realizar pedido
Este requisito se trata da consulta do usuário ao produto que quiser, cadastrado no sistema através da BEC. Esse requisito possui variações, e pode ser acessado das seguintes formas:
- **Funcionário Geral** pesquisa por um produto para compôr seu pedido.
- **Funcionário diretor de serviços administrativos** pesquisa por um produto para obter maiores informações da BEC.

### RF 05, RF 06 e RF 07: Definir descrição, quantidade e realizar pedido
Estes requisitos se tratam das informações que compõem um pedido do usuário comum e, portanto, estão totalmente relacionados ao funcionário geral. Isso direciona às seguintes vias:
- **Funcionário Geral** pode esclarecer possíveis dúvidas do pedido.
- **Funcionário Geral** pode escolher a quantidade desejada de um determinado produto no mesmo pedido.
- **Funcionário Geral** pode solicitar a compra de um pedido, atribuindo os requisitos anteriores e exportando essas informações ao funcionário de compras.

### RF 08: Visualizar pedido no histórico
Este requisito está associado aos dois tipos de funcionário, e inclui a inserção do pedido em um histórico composto de dados como "Nome do solicitante", "Data da solicitação", "Status", entre outros dados como demonstrados na definição das classes de usuário. Desta forma, este requisito está relacionado a:
- **Funcionário Geral** pode acompanhar o andamento e obter um retorno de seu pedido.
- **Funcionário diretor de serviços administrativos** gerencia os pedidos realizados, atribuindo status de forma automática e justificativas a pedidos pendentes.
- **Funcionário diretor de serviços administrativos** filtra por informações específicas de pedidos anteriores.

### RF 09: Excluir pedido realizado
Este requisito segue o requisito 09, mas aborda uma funcionalidade específica ao funcionário geral, permitindo a ele excluir um pedido que tenha sido preenchido erroneamente.

</div>

<details>
   <summary>Diagrama de classes</summary>
   <h4>Diagrama de classes mapeado do frontend</h4>
   <img src="![image](https://github.com/paulovictorio/Documentacao_projetoCompras/assets/78160698/de5618c8-1eaa-4d95-96b0-fe73053c7ea2)
">
</details>

→ [Voltar ao topo](#topo)
<span id="links">
<div align="center">


## :link: Links úteis

→[Voltar ao principal](https://github.com/paulovictorio/Documentacao_projetoCompras/blob/main/README.md)
