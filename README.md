# Introducao-js
Resumo sobre o curso introdução a javascript

## Caixas de Diálogo
No JavaScript temos algumas maneiras de interagir com o usuario, uma delas é a criação de caixas de diálogo, essas são basicamente pop-ups que irá aparecer no navegador. JS nos dar 3 tipos, elas são:
- alerta
- confirmação
- prompt de entrada.

### Alerta
Criada apartir da função `alert()`, podendo receber como parametro `strings`.

### Confirmação
Sua criação se deve pela função `confirm()`, além de receber o como parametro uma `string` essa possui uma caracteristica em especial, possui um retorno do tipo `boolean`, sendo assim retorna `true` ou `false`.

### Prompt de entrada
Diferentemente de `alert()` e `confirm()`, a função `prompt()` possui em sua estrutura um caixa de input que retornará ao usuário uma `string`. Seu parâmetro também será uma `string()`

## Método querySelector
o método `querySelector()` e `querySelectorAll()` nos dará acesso a DOM, desse modo podemos selecionar um elemento presente no HTML passando como parâmetro identificadores, classes e tags. 
Essa função também trará um retorno, que terá tipo HTML.
Esse método deverá ser antecedido pelo local onde se encontra o que deseja ser selecionado.

### Diferença entre `querySelector()` e `querySelectorAll()`
`querySelector()` selecionará apenas o primeiro com o seletor indicado como parâmetro, já o `querySelectorAll()` guardará todos os elementos com o seletor indicado em um array.

Ex1:
```javascript
var nome = document.querySelectorAll(".nome")
```

Ex2:
```javascript
var pessoasValidas = document.querySelector(".pessoas-validas")
var nome = pessoasValidas.querySelector(".nome")
```

### Como guardar e modificar um texto dentro de uma tag?
Quando selecionamos um elemento e o colocamos em uma variável, podemos ter acesso a algumas propriedades do html

