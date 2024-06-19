# alura-exercicios

### Minha resolução dos exercícios no curso "Lógica de programação: mergulhe em programação com JavaScript

#### Aula 1

Desafio 1

```js
alert("Boas Vindas ao nosso site!");
```

Desafio 2

```js
let nome = "Lua";
```

Desafio 3

```js
let idade = 25;
```

Desafio 4

```js
let numeroDeVendas = 50;
```

Desafio 5

```js
let saldoDisponivel = 1000;
```

Desafio 6

```js
alert = "Erro! Preencha todos os campos";
```

Desafio 7

```js
let mensagemDeErro = "Erro! Preencha todos os campos";
alert(mensagemDeErro); 
```

Desafio 8

```js
let nome = prompt("Qual seu nome?");
```

Desafio 9

```js
let idade = prompt("Qual sua idade?");
```

Desafio 10

```js
let idade = prompt("Qual sua idade?");

if (idade >= 18) {
alert("Pode tirar a habilitação!");
}
```

### Aula 2



### Aula 3



### Aula 4

Desafio 1

```js
let msg = 'Bem vindo!';
console.log(msg);
```

Desafio 2

```js
let nome = 'Felipe';
console.log(`Olá, ${nome}!`);
```

Desafio 3

```js
let nome = 'Felipe';
alert(`Olá, ${nome}!`);
```

Desafio 4

```js
let pergunta = prompt('Qual a linguagem de programação que você mais gosta?');
console.log(`A linguagem que você mais gosta é ${pergunta}`);
```

Desafio 5

```js
let valor1 = 3;
let valor2 = 7;
let resultado = valor1 + valor2;

console.log(`A soma de ${valor1} e ${valor2} é igual a ${resultado}`);
```

Desafio 6

```js
let valor1 = 73;
let valor2 = 7;
let resultado = valor1 - valor2;

console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}`);
```

Desafio 7

```js
let idade = prompt('Insira a sua idade:');

if (idade >= 18) {
  console.log('Você é maior de idade.');
} else {
  console.log('Você é menor de idade.');
}
```

Desafio 8

```js
let numero = parseFloat(prompt('Digite um valor:')); // 

if (numero == 0) {
  alert('Você escolheu o número 0!');
} else if (numero > 0) {
  alert(`O número ${numero} é positivo`);
} else {
  alert(`O número ${numero} é negativo`);
}
```

Desafio 9
```js
let contador = 1;
while (contador <= 10) {
  console.log(contador);
  contador++;
}
```

Desafio 10
```js
let nota = 9

if (nota >= 7) {
  console.log(`Você tirou nota ${trueNota} e foi Aprovado!`);
} else {
  console.log(`Você tirou nota ${trueNota} e foi Reprovado`);
}
```

Desafio 11
```js
let randNumero = Math.random();
console.log(randNumero);
```

Desafio 12
```js
let randIntNumero = parseInt(Math.random() * 10) + 1;
console.log(randIntNumero);
```

Desafio 13
```js
let randInt1000 = parseInt(Math.random() * 1000 + 1);
console.log(randInt1000);
```


### Curso "Lógica de programação: explore funções e listas"

#### Aula 1

```js
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora do Desafio';

function botaoConsole() {
    console.log('O botão foi clicado!');
}

function botaoAlerta() {
    alert('Eu amo JS');
}

function botaoPrompt() {
    let cidade = prompt('Qual a última cidade que você visitou?');
    alert(`Estive em ${cidade} e lembrei de você`);
}

function botaoSoma() {
    let num1 = parseInt(prompt('Digite o primeiro número para somar:'));
    let num2 = parseInt(prompt('Digite o segundo número para somar'));
    let soma = num1 + num2

    alert(`${num1} + ${num2} = ${soma}`);
}
```

#### Aula 2

Desafio 1
```js
exibirOla();

function exibirOla() {
    console.log('Olá, mundo!');
}
```

Desafio 2
```js
exibirOlaNome('Felipe');

function exibirOlaNome(nome) {
    console.log(`Olá, ${nome}!`);
}
```

Desafio 3
```js
let resultadoDobro = calcularDobro(5);
console.log(resultadoDobro);

function calcularDobro(numero) {
    return numero * 2;
}
```

Desafio 4
```js
let media = calcularMedia(4, 7, 10);
console.log(media);

function calcularMedia(a, b, c) {
    return (a + b + c) / 3;
}
```

Desafio 5
```js
let maiorNumero = encontrarMaior(70, 47);
console.log(maiorNumero);

function encontrarMaior(a, b) {
    return a > b ? a : b;
}
```

Desafio 6
```js
let resultado = quadrado(2);
console.log(resultado);

function quadrado(numero) {
    return Math.pow(numero, 2);
}
```

### Aula 3

Desafio 1
```js
function calculoIMC(altura, peso) {
  let imc = peso / (altura ** 2);
}
```

Desafio 2
```js
let num = 7;
calculoFatorial(num);

function calculoFatorial(num) {
  let n = num;
  let fatorial = n;
  if (n == 0 || n == 1) {
    return 1;
  }

  while(n >= 2) {
    fatorial *= (n - 1);
    n--;
  }
  return fatorial;
}
```

Desafio 2 v2

```js
let numero = 5;
let resultado = calcularFatorial(numero);
console.log(`O fatorial de ${numero} é ${resultado}`);

function calcularFatorial(numero) {
  if (numero === 0 || numero === 1) {
    return 1;
  }

  let fatorial = 1;
  for (let i = 2; i <= numero; i++) {
    fatorial *= i;
  }

  return fatorial;
}
```

Desafio 3
```js

```

Desafio 4
```js

```

Desafio 5
```js

```

Desafio 6
```js

```

