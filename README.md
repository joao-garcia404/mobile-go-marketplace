<img alt="GoStack" src="https://i.imgur.com/pHg9Or3.png" />

<h1 align="center">
  Desafio 08: GoMarketplace GoStack
</h1>

## Sobre o desafio

Desafio de uma aplicação em React Native com gerenciamento de carrinho de compras e e listagem de produtos, utilizando TypeScript, AsyncStorage, e uma Fake API
(JSON server).

----------------------------------------------------------------------------------------------------------------------------------------------------------------

## Aplicação

<img alt="GoMarketplace" src="https://i.imgur.com/fT0IMk4.png" />

Essa aplicação possui um layout que pode ser acessado a partir deste <a href="https://www.figma.com/file/VgK3hsmyGbqiGu9FdqfUzF/GoMarketplace?node-id=0:1">Link<a/>.

---------------------------------------------------------------------------------------------------------------------------------------------------------------

## Funcionalidades

- `Listagem` de produtos de uma fake API.
- `Adição` e `remoção` de produtos no carrinho de compras.
- `Exibir` o valor total de itens no carrinho. 

## Testes da aplicação 

- `should be able to list the products`: A aplicação permiti que sejam listados na tela `Dashboard`, todos os produtos 
que são retornados da Fake API. A listagem exibi o `title` e o `price` que são formatados.

- `should be able to add a product to the cart`: Possibilidade de adicionar produtos da tela `Dashboard` ao `carrinho`.

- `should be able to list the products on the cart`: Possibilidade de listar os produtos que estão salvos no carrinho e exibir na página de carrinho, o `nome` 
do produto, e o `subtotal total` de cada produto.

- `should be able to calculate the cart total`: A página `Dashboard`, e a página `Cart` exibi o valor total de todos os itens que estão no carrinho.

- `should be able to show the total quantity of itens in the cart`: A página `Dashboard`e `Cart` exibi o número total de produtos que estão no carrinho.

- `should be able to increment product quantity on the cart`: A aplicação permiti que seja possível `incrementar` a quantidade de um produto do carrinho.

- `should be able to decrement product quantity on the cart`: A aplicação permiti que seja possível `decrementar` a quantidade de um produto do carrinho.

- `should be able to navigate to the cart`: A aplicação deve permitir a `navegação` entre a página de produtos e o carrinho de compras.

- `should be able to add products to the cart`: A aplicação deve permitir adicionar itens ao carrinho.

- `should store products in AsyncStorage while adding, incrementing and decrementing`: Todas as atualizações feitas no carrinho devem ser salvas no AsyncStorage.

- `should load products from AsyncStorage`: Todos os produtos que foram adicionados no carrinho devem ser buscados no AsyncStorage. 

----------------------------------------------------------------------------------------------------------------------------------------------------------------

## :memo: Licença

Esse projeto está sob a licença MIT. Veja a página [LICENSE](https://opensource.org/licenses/MIT) para mais detalhes.
