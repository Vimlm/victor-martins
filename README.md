# Projeto HTML e CSS com Flexbox e Media Query

Este é um projeto de exemplo que utiliza os conceitos de flexbox e media query para criar layouts responsivos em HTML e CSS. O objetivo é demonstrar como é possível criar designs flexíveis que se adaptam a diferentes tamanhos de tela, além de incluir a navegação entre páginas.

Para acessar o projeto acesse: https://vimlm.github.io/victor-martins/

## Estrutura de diretórios

O projeto está organizado da seguinte forma:

![Texto alternativo](https://images2.imgbox.com/46/c3/TLOQBToD_o.png)


- O arquivo `index.html` é a página inicial do site.
- Os arquivos `about.html`, `contact.html` e `hobbies.html` são outras páginas do site.
- A pasta `css` contém os arquivos CSS utilizados no projeto.
- O arquivo `styles.css` os imports CSS que serão puxados em todas as páginas.
- O pasta `assets` contém as as imagens utilizadas no projeto.
- O arquivo `README.md` (este arquivo) contém informações sobre o projeto.

## Uso do Flexbox

O Flexbox é um sistema de layout que permite a criação de designs flexíveis e responsivos. Neste projeto, utilizamos o Flexbox para posicionar e ajustar elementos na página de acordo com as necessidades.

Exemplo de código CSS utilizando flexbox:

```css
.container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
``` 
Nesse exemplo, a classe .container define um elemento como um container flexível. Utilizamos as propriedades flex-direction, justify-content e align-items para controlar o posicionamento e alinhamento dos elementos dentro do container.

## Media Query
A Media Query é uma técnica do CSS que permite aplicar estilos diferentes com base nas características do dispositivo ou tamanho da tela. Utilizamos as Media Queries para criar designs responsivos que se ajustam automaticamente a diferentes tamanhos de tela.

Exemplo de código CSS utilizando media query:

```css
@media screen and (max-width: 768px) {
  /* Estilos aplicados quando a largura da tela é menor ou igual a 768px */
  .container {
    flex-direction: column;
  }
}
``` 
Nesse exemplo, estamos aplicando estilos diferentes para a classe .container quando a largura da tela é igual ou menor que 768 pixels. Nesse caso, estamos modificando a propriedade flex-direction para column, fazendo com que os elementos sejam empilhados verticalmente.

## Navegação entre páginas
Este projeto inclui navegação entre páginas através de links. Você pode adicionar links para outras páginas do seu projeto da seguinte forma:

```html
<a href="sobre.html">Sobre</a>
<a href="hobbies.html">Hobbies</a>
<a href="contato.html">Contato</a>
```

No exemplo acima, os links page1.html e page2.html apontam para as respectivas páginas do projeto. Certifique-se de ajustar os caminhos dos links de acordo com a estrutura do seu projeto.





