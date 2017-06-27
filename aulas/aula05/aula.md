# Componentes nativos

Nos [primeiros passos na web](https://github.com/VaiNaWeb/primeiros-passos-na-web) aprendemos que precisamos marcar o nosso conteúdo com as tags, aprendendemos também que há muitas delas, como a div, section, img, etc. Não estamos mais usando HTML em um navegador, estamos na própria plataforma mobile, logo não usamos mais marcações, temos agora componentes nativos que o React Native nos permite usar.

## Image

Renderiza imagens

```js
class GatinhoFeliz extends Component {
  render() {
    return (
      <Image
       source={{uri: 'http://imgur.com/a/kI35x'}}
       style={{width: 400, height: 400}} />
    );
  }
}
```
