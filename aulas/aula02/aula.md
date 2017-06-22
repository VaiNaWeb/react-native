# Um pouco de Javascript

Antes de seguir aprendendo sobre o React, aprenderemos um pouquinho sobre algoritmos e Javascript. Vamos precisar dominar esses conceitos muito bem, para depois usa-los em nossos componentes.

## Variáveis

Podemos entender uma variável como uma caixinha para guardar coisas.

## Criando e chamando funções

> Uma função é um pedaço de programa envolvido por um valor. Este valor pode ser aplicado, a fim de executar o programa envolvido. Por exemplo, no ambiente do navegador.
>— Eloquente Javascript

Já conhecemos uma, a alert. O Javascript já tem várias funções disponíveis que podemos usar, mas podemos, e comumente criamos nossas próprias funções. Você pode entender uma função como uma ação. Exemplo:

```js
alert("Bom dia!");
```

Um outro exemplo:

```js
function pergunteAlgo(string) {
	return string + '?'
}
```

Criamos a função pergunteAlgo, que retorna uma string que você escreva com um sinal de interrogação ao final.

Podemos combinar funções com variáveis também. Exemplo:

```js
var ola = 'olá'

function olaMundo(ola) {
	return string + 'mundo'
}
```

## Objetos e Arrays

Objetos e arrays criam maneiras de agrupar uma conjunto de valores em um único valor. Ou seja, ao invés de tentar carregar e manter todas as coisas individualmente, eles nos permitem colocar todas as coisas relacionadas dentro de uma bolsa e carregá-las.

> Existem algumas propriedades nos arrays, como length e vários métodos. Métodos são funções que são armazenadas em propriedades e, normalmente, atuam no valor nas quais elas são propriedade.
>— Eloquente Javascript

Objetos podem também ser usados como mapas, associando valores com seus nomes. O operador in pode ser usado para verificar se um objeto contém a propriedade com o nome informado.
