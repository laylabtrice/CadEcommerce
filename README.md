# CadEcommerce

## Resumo do Projeto
Este projeto é um site de compras, onde o usário tem acesso aos produtos disponíveis para que conclua sua compra de acordo com seus interesses. Também possuí as funcionalidades de adicionar novos produtos, categorias e marcas, onde após serem adicionados são automaticamentes lincados com o banco de dados do sistema.

## Índice
 
1. [Resumo do Projeto](#resumo-do-projeto)
2. [Estrutura do Projeto](#estrutura-do-projeto)
3. [Outros códigos](#outros-códigos)
4. [Controller](#controller)
5. [Telas](#telas)
6. [Como Executar o Projeto](#como-executar-o-projeto)
7. [Métodos utilizados](#métodos-utilizados)
8. [Tecnologias utilizadas](#tecnologias-utilizadas)
9. [Fontes](#fontes)
10. [Sobre Execução](#sobre-execução)

## Estrutura do Projeto  
1.   `index.php `  
![Index](https://github.com/laylabtrice/CadEcommerce/blob/main/img/INDEX.png) 
Código básico do site para aplicação de uma compra.

2.   `produtos.php `  
![produtos](https://github.com/laylabtrice/CadEcommerce/blob/main/img/PRODUTOS.png)  
Estruturação dos produtos do site.

3.   `carrinho.php `  
![Carrinho](https://github.com/laylabtrice/CadEcommerce/blob/main/img/CARRINHO.png) 
Código da página de carrinho, para aparecer os produtos que forem selecionados.

4.   `categoria.php `  
![Categoria](https://github.com/laylabtrice/CadEcommerce/blob/main/img/CATEGORIA.png)  
Código para página de cadastro de categorias, ligado com o banco de dados.

5.   `marca.php `  
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
![Produto busca](https://github.com/laylabtrice/CadEcommerce/blob/main/img/prodbusca.png)    
Busca produtos do banco de dados.    

2. ´produtos-pedido.php´  
![Produto pedido](https://github.com/laylabtrice/CadEcommerce/blob/main/img/prodpedido.png)    
Para o pedido dos produtos.  

3. ´produtos-resumo.php´  
![Produto resumo](https://github.com/laylabtrice/CadEcommerce/blob/main/img/prodresumo.png)     
Mostra resumo dos produtos salvos no banco de dados.  

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

- *Cadastra Produto*  
![Cad produto](https://github.com/laylabtrice/CadEcommerce/blob/main/img/cadproduto.png)    

- *Cadastra Categoria*  
![Cad categoria](https://github.com/laylabtrice/CadEcommerce/blob/main/img/cadcategoria.png)    

*Será notificado ao final do cadastro se foi concluido com sucesso ou se não foi possível cadastrar.*

## Como Executar o Projeto

1. *Inicio*: Certifique que possui uma plataforma com suporte para PHP em seu computador.
2. *Clonar*: Clone este repositório em seu servidor web.
3. *Abra o Navegador*: Abra o navegador e acesse o caminho do projeto no servidor web para visualizar a tela inicial.

## Métodos utilizados
- 1.  `include_once() `: Inclui e avalia o arquivo especificado durante a execução do script, garantindo que ele só seja incluído uma vez.
- 2.  `mysqli_query() `: Executa uma consulta no banco de dados MySQL.
- 3.  `while `: Estrutura de repetição que executa um bloco de código enquanto a condição for verdadeira.
- 4.  `mysqli_fetch_assoc() `: Busca uma linha de resultado como uma matriz associativa.
- 5.  `echo `: Exibe uma ou mais strings.
- 6.  `mysqli_affected_rows() `: Retorna o número de linhas afetadas pela última consulta.
- 7.  `mysqli_close() `: Fecha a conexão com o banco de dados MySQL.
- 8.  `__construct() `: Método construtor de uma classe, executado automaticamente na criação de um objeto.
- 9.  `session_start() `: Inicia uma nova sessão ou resume uma sessão existente.
- 10.  `$mysqli->query `: Método orientado a objetos para executar uma consulta no banco de dados MySQL.
- 11.  `mysqli_fetch_object() `: Busca uma linha de resultado como um objeto.
- 12.  `array() `: Cria um "Array".
- 13.  `$_SESSION[''] `: Superglobal que armazena e acessa variáveis de sessão.
- 14.  `exit; `: Finaliza execução.
- 15.  `header('Location:') `: Envia um cabeçalho HTTP de redirecionamento para o navegador.
- 16.  `max() `: Retorna o valor máximo de um array ou de uma lista de argumentos.
- 17.  `str_replace() `: Substitui todas as ocorrências de uma string por outra.
- 18.  `unset() `: Destrói a variável especificada, liberando qualquer recurso associado.
- 19.  `new Carrinho() `: Cria um novo carrinho.
- 20.  `$mysqli->set_charset('utf8') `: Define o conjunto de caracteres da conexão MySQL para UTF-8.
- 21.  `die() `: Termina a execução do script e opcionalmente imprime uma mensagem.
- 22.  `array_keys() `: Retorna todas as chaves de um array.
- 23.  `mysqli_connect() `: Abre uma nova conexão com um servidor MySQL.
- 24.  `$mysqli->connect_error `: Mensagem de erro caso conexão falhe.

## Tecnologias Utilizadas

- *HTML*: Utilizado para a estrutura das páginas.
- *CSS*: Utilizado para a estilização do site.
- *PHP*: Programação dos códigos.
- *JavaScript*: Apresentar POPUP de janela na tela.
![PopUP](https://github.com/laylabtrice/CadEcommerce/blob/main/img/java.png)
- *Jquery*: Para tela FrontEnding junto do CSS.
- *MYSQL/MYSQLI*: Execução com banco de dados MYSQL.

## Fontes
- [PHP - banco de dados](https://www.hostinger.com.br/tutoriais/como-inserir-dados-no-mysql-com-php)
- [Manual geral de PHP](https://www.php.net/docs.php)
- [JavaScript - document ready](https://learn.jquery.com/using-jquery-core/document-ready/)
- [MYSQLI](https://www.php.net/manual/en/function.mysqli-connect.php)
- [Jquery](https://ebaconline.com.br/blog/o-que-e-jquery#:~:text=jQuery%20%C3%A9%20usado%20para%20criar,com%20pouca%20experi%C3%AAncia%20em%20programa%C3%A7%C3%A3o.)

## Sobre execução

Projeto desenvolvido por [@laylabtrice](https://github.com/laylabtrice) em sala durante aulas de Desenvolvimento de Sistemas WEB, do professor Leonardo Santiago Sidon da Rocha. 




