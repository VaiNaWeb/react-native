# Introdução

Vamos começar a desbravar o fantástico mundo do Javascript, a linguagem de programação mais popular do mundo, muito poderosa e que está em todos os lugares. Podemos encontra-la em robôs, aplicações web, mobile, e em tantas outras coisas, inclusive em seu navegador.

Faça o teste!

Clique com o botão direito do mouse em qualquer lugar na tela e pressione Inspecionar elemento ou pressione `(ctrl + shift + i)` e clique em Console.

Digite o comando alert`("Olá mundo");`

O `alert();` é uma função em Javascript, não se preocupe em conhecer o conceito disso agora, ele vai ficar mais claro mais à diante, por enquanto entenda isso como uma ação.

## React

É uma biblioteca em Javascript para construção de interfaces.

Foi criada pelos desenvolvedores do Facebook, muito boa para construir grandes aplicações, com dados que mudam muito, como o próprio Facebook e o Instagram, por exemplo.

As aplicações construídas com React possuem interfaces que "reagem" às interações com o usuário, e essas reações conseguem ser muito suáves, o usuário mal percebe que alterações estão sendo feitas, mas elas estão.

## React Native

Vamos usar o React Native para construir aplicações mobile aproveitando os poderes do Javascript. Ele basicamente permite usar o React em plataformas mobile nativas.

## Criando um componente

O React é baseado em componentes. Podemos dividir uma interface em vários componentes, sempre que um componente fica muito complexo devemos começar a pensar em quebra-lo em novos componentes.

Componentes em React são classes em Javascript que herdam da classe base React.Component

```js
class OlaMundo extends React.Component {

}
```

O método render() é responsável por renderizar o componente.

```js
class OlaMundo extends React.Component {
  render() {
   }
}
```
A sintaxe do JSX é muito parecida com as marcações em HTML que já conhecemos. Quando escrevemos para web, o React renderiza marcações em HTML div, p, etc. Com React Native, ele renderiza componentes específicos das plataformas.

Exemplo em React:

```js
class OlaMundo extends React.Component {
  render() {
    return(
      <section>
        <p>Olá mundo!</p>
      </section>
    );
  }
}
```
Exemplo em React Native:

```js
class OlaMundo extends React.Component {
  render() {
    return(
      <View>
        <Text>Olá mundo!</Text>
      </View>
    );
  }
}
```
