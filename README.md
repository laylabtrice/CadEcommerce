# CadEcommerce

## Resumo do Projeto
Este projeto é um site de compras, onde o usário tem acesso aos produtos disponíveis para que conclua sua compra de acordo com seus interesses. Também possuí as funcionalidades de adicionar novos produtos, categorias e marcas, onde após serem adicionados são automaticamentes lincados com o banco de dados do sistema.

## Índice
 
1. [Resumo do Projeto](#resumo-do-projeto)
2. [Estrutura do Projeto](#estrutura-do-projeto)
3. [Outros códigos](#outros-códigos)
4. [Controller](#controller)
5. [Model](#model)
6. [Telas](#telas)
7. [Como Executar o Projeto](#como-executar-o-projeto)
8. [Tecnologias utilizadas](#tecnologias-utilizadas)
9. [Fontes](#fontes)
10. [Sobre Execução](#sobre-execução)

## Estrutura do Projeto  
1.  ´index.php´  
![Index](https://github.com/laylabtrice/CadEcommerce/blob/main/img/INDEX.png) 
Código básico do site para aplicação de uma compra.

2.  ´produtos.php´  
![produtos](https://github.com/laylabtrice/CadEcommerce/blob/main/img/PRODUTOS.png)  
Estruturação dos produtos do site.

3.  ´carrinho.php´  
![Carrinho](https://github.com/laylabtrice/CadEcommerce/blob/main/img/CARRINHO.png) 
Código da página de carrinho, para aparecer os produtos que forem selecionados.

4.  ´categoria.php´  
![Categoria](https://github.com/laylabtrice/CadEcommerce/blob/main/img/CATEGORIA.png)  
Código para página de cadastro de categorias, ligado com o banco de dados.

5.  ´marca.php´  
![Marca](https://github.com/laylabtrice/CadEcommerce/blob/main/img/MARCA.png)  
Código para página de cadastro de marcas, ligado com o banco de dados.

6.  ´pedido.php´  
![Pedido](https://github.com/laylabtrice/CadEcommerce/blob/main/img/PEDIDO.png)  
Código para aparecer o pedido que foi feito após a compra  

## Outros códigos  
1. ´insere-categoria.php´  
![Insere categoria](https://github.com/laylabtrice/CadEcommerce/blob/main/img/inserecate.png) 
Código para inserir categoria cadastrada ao banco de dados. 

2. ´insere-marca.php´  
![Insere marca](https://github.com/laylabtrice/CadEcommerce/blob/main/img/inseremarca.png)  
Código para inserir marca cadastrada ao banco de dados. 

3. ´insere-produto.php´  
![Insere produto](https://github.com/laylabtrice/CadEcommerce/blob/main/img/insereproduto1.png)![Insere produto](https://github.com/laylabtrice/CadEcommerce/blob/main/img/insereproduto2.png) 
Código para inserir produto cadastrado ao banco de dados. 

## Controller  

- *Carrinho*
1. ´carrinho-add.php´  
![Carrinho add](https://github.com/laylabtrice/CadEcommerce/blob/main/img/CARRINHOADD.png)  
Inicializa um carrinho de compras e adiciona um item a ele.  

2. ´carrrinho-busca.php´  
![Carrinho busca](https://github.com/laylabtrice/CadEcommerce/blob/main/img/carrinhobusca.png) 
Executa uma operação de busca no carrinho.  

3. ´carrinho-remover.php´  
![Carrinho remove](https://github.com/laylabtrice/CadEcommerce/blob/main/img/carrinhoremove.png)  
Executa a função de deletar item no carrinho.

- *Conexão*
1. ´conexao.php´  
![Conexão](https://github.com/laylabtrice/CadEcommerce/blob/main/img/conexao.png) 
Conecta ao banco de dados. 

- *Produtos*  
1. ´produtos-busca.php´  
![]()  

2. ´produtos-pedido.php´  
![]()  

3. ´produtos-resumo.php´  
![]()  

## Model  
1. ´cadMarca.php´  
![]()  

2. ´Carrinho.class.php´  
![]()  

3. ´Produtos.class.php´  
![]()  

## Telas
### 1. *Tela Inicial*
![Tela Inicial](https://github.com/laylabtrice/CadEcommerce/blob/main/img/p%C3%A1ginainicial.png)  

### 2. Para realizar compra
- *Adicionar quantidade de itens*  
![Notificação para itens](https://github.com/laylabtrice/CadEcommerce/blob/main/img/additem.png)  
- *Carrinho*
![Carrinho](https://github.com/laylabtrice/CadEcommerce/blob/main/img/carrinho1.png)  
- *Ao realizar compra*
![Compra feita](https://github.com/laylabtrice/CadEcommerce/blob/main/img/pedidofeito.png) 

### Cadastrar  

- *Cadastra Marca*  
![Cad marca](https://github.com/laylabtrice/CadEcommerce/blob/main/img/cadmarca.png)  

- *Cdastra Produto*  
![Cad produto](https://github.com/laylabtrice/CadEcommerce/blob/main/img/cadproduto.png)  

- *Cadastra Categoria*  
![Cad categoria](https://github.com/laylabtrice/CadEcommerce/blob/main/img/cadcategoria.png)  

## Como Executar o Projeto

1. *Inicio*: Certifique que possui uma plataforma com suporte para PHP em seu computador.
2. *Clonar*: Clone este repositório em seu servidor web.
3. *Abra o Navegador*: Abra o navegador e acesse o caminho do projeto no servidor web para visualizar a tela inicial.

## Tecnologias Utilizadas

- *HTML*: Utilizado para a estrutura das páginas.
- *CSS*: Utilizado para a estilização do site.
- *PHP*: 
- *JavaScript*:

## Fontes
- [PHP - banco de dados](https://www.hostinger.com.br/tutoriais/como-inserir-dados-no-mysql-com-php)
- [JavaScript - document ready](https://learn.jquery.com/using-jquery-core/document-ready/)

## Sobre execução

Projeto desenvolvido por [@laylabtrice](https://github.com/laylabtrice) em sala durante aulas de Desenvolvimento de Sistemas WEB, do professor Leonardo Santiago Sidon da Rocha. 




