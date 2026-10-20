# Comandos Básicos de JavaScript

Este material apresenta quatro comandos utilizados para exibir informações e interagir com páginas web usando JavaScript.

## 1. `document.write()`

Escreve conteúdo diretamente no documento HTML.

```javascript
document.write("Olá, mundo!");
```

**Resultado:** exibe `Olá, mundo!` na página.

Também permite inserir elementos HTML:

```javascript
document.write("<h1>Aprendendo JavaScript</h1>");
```

> **Atenção:** utilizar `document.write()` após o carregamento da página pode apagar o conteúdo existente. Por isso, seu uso é evitado em aplicações modernas.

## 2. `console.log()`

Exibe informações no console do navegador. É muito utilizado para testar códigos e identificar erros.

```javascript
console.log("Olá, mundo!");
console.log(10 + 5);
```

**Resultado no console:**

```text
Olá, mundo!
15
```

Para visualizar o resultado, abra o navegador, pressione `F12` e acesse a aba **Console**.

## 3. `innerHTML`

Permite inserir ou alterar conteúdo HTML dentro de um elemento específico.

**HTML:**

```html
<p id="mensagem"></p>
```

**JavaScript:**

```javascript
document.getElementById("mensagem").innerHTML = "Olá, mundo!";
```

**Resultado na página:**

Olá, mundo!

### Entendendo o código

- `document`: representa o documento HTML.
- `getElementById("mensagem")`: localiza o elemento pelo seu identificador (`id`).
- `innerHTML`: permite acessar ou alterar o conteúdo HTML do elemento.
- `=`: atribui um novo valor.

> **Dica:** para inserir apenas texto, prefira `textContent`, que não interpreta o conteúdo como HTML.

```javascript
document.getElementById("mensagem").textContent = "Olá, mundo!";
```

## 4. `alert()`

Exibe uma janela de alerta no navegador.

```javascript
alert("Olá, mundo!");
```

**Resultado:** uma janela com a mensagem `Olá, mundo!` e um botão para confirmar.

Esse comando pode ser utilizado para apresentar avisos e testar se determinada parte do código foi executada.

## 📊 Comparação dos comandos

| Comando | Onde aparece? | Finalidade |
|---|---|---|
| `document.write()` | Página HTML | Escrever conteúdo no documento |
| `console.log()` | Console do navegador | Testar e depurar códigos |
| `innerHTML` | Elemento HTML | Inserir ou alterar conteúdo HTML |
| `alert()` | Janela de alerta | Exibir mensagens ao usuário |
