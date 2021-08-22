## Desafio VTEX IO - Gama Academy

O desafio principal é compreender a lógica do desenvolvimento da estrutura da VTEX, bem como sua documentação.

Não consegui

### briefing para desenvolvimento:

Template de criação

* Criar a solução a partir de um boiler template padrão da Vtex IO
* Utilizar o **[Markdown](https://pt.wikipedia.org/wiki/Markdown)** e o CSS  para formatação.

### Para esta tela utilizar os componentes:

* **[Flex layout](https://vtex.io/docs/components/all/vtex.flex-layout@0.17.0/)** para criar as cores em CSS.
* Dar prioridade as páginas criada nos arquivos.jsonc colocando comentários dos blocos criados
* Utilizar o **[Slider layout](https://vtex.io/docs/app/vtex.slider-layout)** para mostrar os produtos em destaque 
* Criar um componente **[Tab Layout](https://vtex.io/docs/components/all/vtex.tab-layout@0.4.3/)** para separar os produtos por categoria.
* Criar um bloco de **[lista de produtos](https://vtex.io/docs/app/vtex.product-list@0.31.0/)**. ( Sugestão paginação por 8 itens da categoria)
* Criar **[Minicard](https://vtex.io/docs/components/content-blocks/vtex.minicart@2.60.0/)** para lista dos produtos no carrinho.
* Ao clicar no produto ir para tela com **[Product Summary](https://vtex.io/docs/components/all/vtex.product-summary@2.53.0/)**.

### Layout Mobile

* Criar um componente customizado para falar com suporte no whatsapp no rodapé.
    * utilizar o VTEX **[Componentes com React](https://vtex.io/docs/components/all/vtex.store-components@3.150.0/)** para criar o componente.
    * API https://www.convertte.com.br/gerador-link-whatsapp/.

* Criar um componente customizado para cadastrar leads (possíveis clientes prospectos).
    * Nome,
    * Email
    * Telefone
    * Este componente pode servir de isca digital , dando uma bonificação para o prospecto que preencher as informações da lead.
    * Utilizar o VTEX **[Componentes com React](https://vtex.io/docs/components/all/vtex.store-components@3.150.0/)** para criar o componente.
    * Sugestão de layout:
        * uma tela básica aparecendo uma caixa para o mesmo preencher o Nome Copleto, e-mail e telefone.
    * Mais sugestões para ajudar no layout:
    * **[Link 1](https://vtex.io/docs/getting-started/desenvolva-componentes-usando-vtex-io-e-react/5/)**.
    * https://vtex.io/docs/components/all/vtex.stack-layout@0.1.0/.

### AWS API Gateway

* Com o objetivo de armazenar as leads que o Vtex componente irá utilizar no React, criar uma API Gateway na AWS para colocar as informações - https://aws.amazon.com/pt/api-gateway/
* Um exemplo de arquivo API Gateway para estudo:
* https://github.com/awslabs/aws-api-gateway-developer-portal/blob/master/cloudformation/template.yaml
* https://github.com/mattpodolak/email-api-lambda
* https://github.com/amazon-archives/realworld-serverless-application/blob/master/backend/sam/app/api.template.yaml

### Opcional

Criar um item no adm do vtex para trazer o conteúdo das leads cadastradas na API Gateway AWS - Conteúdo do vídeo da aula 9 do curso.