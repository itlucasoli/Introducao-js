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
o método `querySelector()` e `querySelectorAll()` nos dará acesso a DOM, desse modo podemos selecionar um elemento presente no html passando como parâmetro identificadores, classes e tags.
```
var nome = document.querySelector("#info-nome")
```
