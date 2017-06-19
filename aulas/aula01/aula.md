# Olá mundo

Vamos começar a desbravar o fantástico mundo do Javascript. Essa viagem, ops, essas aulas serão dividas em três partes, vamos começar aprendendo sobre Javascript, então React e depois React Native, ao final percebemos que na verdade tá tudo junto e misturado.

## Javascript 

É uma linguagem de programação poderosa e que está em todos os lugares, em robôs, aplicações web, mobile, e em tantas outras coisas, inclusive no seu navegador.

Faça o teste!

Clique com o botão direito do mouse em qualquer lugar na tela e pressione Inspecionar elemento ou pressione `(ctrl + shift + i)` e clique em Console.

Digite o comando alert`("Olá mundo");`

O `alert();` é uma função em Javascript, não se preocupe em conhecer o conceito disso agora, ele vai ficar mais claro mais à diante, por enquanto entenda isso como uma ação.

## React

É uma biblioteca em Javascript para construção de interfaces.
Foi criada pelos desenvolvedores do Facebook, muito boa para construir grandes aplicações, com dados que mudam muito, como o próprio Facebook e Instagram, por exemplo.

## React Native

Vamos usar o React Native para construir aplicações mobile nativas aproveitando os poderes do Javascript. O Native é muito similar ao React, por isso vamos aprender React antes, e depois será fácil aprender ele também.

## Criando um componente

O React é baseado em componentes. Podemos dividir uma interface em vários componentes, sempre que um componente fica muito complexo devemos começar a questionar quebra-lo em novos componentes.

Componentes em React são classes em Javascript que herdam da classe base React.Component

```js
class HelloWorld extends React.Component {

}
```

O método render() é responsável por renderizar o componente.

```js
class HelloWorld extends React.Component {
  render() {
   }
}
```

O React usa JSX uma extensão de sintaxe para Javascript que parece adicionar o próprio HTML dentro do JS.

```js
class HelloWorld extends React.Component {
  render() {
    return(
      <section>
      	<p>Olá mundo</p>
      </section> 
    );
  }
}
```
