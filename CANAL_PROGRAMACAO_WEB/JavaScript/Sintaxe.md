# JavaScript: Sintaxe 

Toda linguagem de programação tem sua própria sintaxe, ou seja, suas regras para escrever o código corretamente.

No JavaScript, podemos trabalhar com vários tipos de conteúdo, como textos, números e funções.

## Números e textos

Exemplo:

```javascript
console.log(5 + 5);
```

Resultado no console:

```text
10
```

O JavaScript interpreta `5 + 5` como uma expressão matemática, pois os valores não estão entre aspas.

Agora, observe:

```javascript
console.log("5 + 5");
```

Resultado no console:

```text
5 + 5
```

Como a expressão está entre aspas, o JavaScript interpreta seu conteúdo como texto, em vez de realizar a soma.

## JavaScript é case sensitive

O JavaScript diferencia letras maiúsculas de letras minúsculas.

Por isso, `pessoa` é diferente de `PESSOA` e de `Pessoa`.

Exemplo:

```javascript
let pessoa = "Fernanda";
let PESSOA = "Maria";

console.log(pessoa);
console.log(PESSOA);
```

Resultado no console:

```text
Fernanda
Maria
```

Nesse exemplo, `pessoa` e `PESSOA` são variáveis diferentes.

**Importante:** mantenha o mesmo padrão de letras ao utilizar nomes de variáveis, funções e outros identificadores.


