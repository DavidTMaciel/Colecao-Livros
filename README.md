# Catálogo de Livros em Java

Este é um simples projeto em Java que implementa um catálogo de livros. Ele inclui duas classes principais: `Livro` e `CatalogoLivros`.

## Descrição

### Classe `Livro`

A classe `Livro` representa um livro com as seguintes propriedades:

- Título
- Autor
- Ano de publicação

A classe possui construtor, getters e um método `toString` para exibir informações sobre o livro.

### Classe `CatalogoLivros`

A classe `CatalogoLivros` representa um catálogo de livros e inclui as seguintes funcionalidades:

- Adicionar um livro ao catálogo.
- Pesquisar livros por autor.
- Pesquisar livros por intervalo de anos de publicação.
- Pesquisar um livro por título.

O programa também possui um método `main` para demonstrar as funcionalidades.

## Uso

Para executar o programa, siga as seguintes etapas:

1. Compile os arquivos Java com o seguinte comando:

   ```shell
   javac Livro.java CatalogoLivros.java
2. Execute o programa com o seguinte comando:
   ```shell
    java CatalogoLivros

## O programa irá:

  1. Inicializar um catálogo de livros vazio.
  2. Adicionar alguns livros ao catálogo.
  3. Realizar pesquisas por autor, intervalo de anos e título.
  4. Exibir os resultados das pesquisas.

##  Exemplo de Saída
```arduino
[Livro{titulo='Livro 1', autor='Autor 2', anoPublicacao=2022}]
[Livro{titulo='Livro 2', autor='Autor 2', anoPublicacao=2020}, Livro{titulo='Livro 3', autor='Autor 3', anoPublicacao=2023}]
Livro{titulo='Livro 1', autor='Autor 1', anoPublicacao=2020}
