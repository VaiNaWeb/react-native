# Estilizando componentes

A maneira mais simples de estilizar componentes no React Native é inline, embora essa não seja a melhor maneira. A sintaxe do React Native para fazer isso é igual a do React para web.

```js
class OlaMundo extends Component {
  render() {
    return (
      <View>
        <Text style={{width: 400, height: 400}}>Olá mundo!</Text>
      </View>
    );
  }
}
```
Uma forma mais legal de fazer isso é usando um objeto em Javascript, passando um array de estilos. Os estilos do React Native lembram o bom e velho CSS que a gente já conhece.

```js
class OlaMundo extends Component {
  render() {
    return (
      <View>
        <Text style={[styles.textoLaranjinha]}>Olá mundo!</Text>
      </View>
    );
  }
}

const styles = StyleSheet.create({
  textoLaranjinha: {
    color: 'tomato',
    fontWeight: 'bold',
    fontSize: 30,
  },
});

```
