# alura-exercicios

Minha resolução dos exercícios no curso "Lógica de programação: mergulhe em programação com JavaScript
-----------
### Aula 1


**Desafio 1**
> Mostre um alerta com a mensagem "Boas vindas ao nosso site!".

```js
alert("Boas Vindas ao nosso site!");
```

**Desafio 2**
> Declare uma variável chamada nome e atribua a ela o valor "Lua".

```js
let nome = "Lua";
```

**Desafio 3**
> Crie uma variável chamada idade e atribua a ela o valor 25.

```js
let idade = 25;
```

**Desafio 4**
> Defina uma variável numeroDeVendas e atribua a ela o valor 50.

```js
let numeroDeVendas = 50;
```

**Desafio 5**
> Defina uma variável saldoDisponivel e atribua a ela o valor 1000.

```js
let saldoDisponivel = 1000;
```

**Desafio 6**
> Exiba um alerta com o texto "Erro! Preencha todos os campos"

```js
alert = "Erro! Preencha todos os campos";
```

**Desafio 7**
> Declare uma variável chamada mensagemDeErro e atribua a ela o valor "Erro! Preencha todos os campos" Agora exiba um alerta com o valor da variável

```js
let mensagemDeErro = "Erro! Preencha todos os campos";
alert(mensagemDeErro); 
```

**Desafio 8**
> Use um prompt para perguntar o nome do usuário e armazená-lo na variável nome.

```js
let nome = prompt("Qual seu nome?");
```

**Desafio 9**
> Peça ao usuário para digitar sua idade usando um prompt e armazene-a na variável idade.

```js
let idade = prompt("Qual sua idade?");
```

**Desafio 10**
> Agora, caso a idade seja maior ou igual que 18, exiba um alerta com a mensagem "Pode tirar a habilitação!".

```js
let idade = prompt("Qual sua idade?");

if (idade >= 18) {
alert("Pode tirar a habilitação!");
}
```
--------------------

### Aula 2

**Desafio 1**
> Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".

```js

```

**Desafio 2**
> Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.

```js

```

**Desafio 3**
> Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".

```js

```

**Desafio 4**
> Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.

```js

```

**Desafio 5**
> Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.

```js

```
-------------

### Aula 3

**Desafio 1**
> Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.

```js

```

**Desafio 2**
> Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.

```js

```

**Desafio 3**
> Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.

```js

```

**Desafio 4**
> Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.

```js

```
--------------------

### Aula 4

**Desafio 1**
> Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas.

```js
let msg = 'Bem vindo!';
console.log(msg);
```

**Desafio 2**
> Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador.

```js
let nome = 'Felipe';
console.log(`Olá, ${nome}!`);
```

**Desafio 3**
> Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o alert para exibir a mensagem "Olá, [seu nome]!" .

```js
let nome = 'Felipe';
alert(`Olá, ${nome}!`);
```

**Desafio 4**
> Utilize o prompt e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.

```js
let pergunta = prompt('Qual a linguagem de programação que você mais gosta?');
console.log(`A linguagem que você mais gosta é ${pergunta}`);
```

**Desafio 5**
> Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.

```js
let valor1 = 3;
let valor2 = 7;
let resultado = valor1 + valor2;

console.log(`A soma de ${valor1} e ${valor2} é igual a ${resultado}`);
```

**Desafio 6**
> Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.

```js
let valor1 = 73;
let valor2 = 7;
let resultado = valor1 - valor2;

console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}`);
```

**Desafio 7**
> Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.

```js
let idade = prompt('Insira a sua idade:');

if (idade >= 18) {
  console.log('Você é maior de idade.');
} else {
  console.log('Você é menor de idade.');
}
```

**Desafio 8**
> Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.

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

**Desafio 9**
> Use um loop while para imprimir os números de 1 a 10 no console.

```js
let contador = 1;
while (contador <= 10) {
  console.log(contador);
  contador++;
}
```

**Desafio 10**
> Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.

```js
let nota = 9

if (nota >= 7) {
  console.log(`Você tirou nota ${trueNota} e foi Aprovado!`);
} else {
  console.log(`Você tirou nota ${trueNota} e foi Reprovado`);
}
```

**Desafio 11**
> Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.

```js
let randNumero = Math.random();
console.log(randNumero);
```

**Desafio 12**
> Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console.

```js
let randIntNumero = parseInt(Math.random() * 10) + 1;
console.log(randIntNumero);
```

**Desafio 13**
> Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.

```js
let randInt1000 = parseInt(Math.random() * 1000 + 1);
console.log(randInt1000);
```
---------------------
## Curso "Lógica de programação: explore funções e listas"
--------------------
### Aula 1

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
---------------------------------
### Aula 2

**Desafio 1**
```js
exibirOla();

function exibirOla() {
    console.log('Olá, mundo!');
}
```

**Desafio 2**
```js
exibirOlaNome('Felipe');

function exibirOlaNome(nome) {
    console.log(`Olá, ${nome}!`);
}
```

**Desafio 3**
```js
let resultadoDobro = calcularDobro(5);
console.log(resultadoDobro);

function calcularDobro(numero) {
    return numero * 2;
}
```

**Desafio 4**
```js
let media = calcularMedia(4, 7, 10);
console.log(media);

function calcularMedia(a, b, c) {
    return (a + b + c) / 3;
}
```

**Desafio 5**
```js
let maiorNumero = encontrarMaior(70, 47);
console.log(maiorNumero);

function encontrarMaior(a, b) {
    return a > b ? a : b;
}
```

**Desafio 6**
```js
let resultado = quadrado(2);
console.log(resultado);

function quadrado(numero) {
    return Math.pow(numero, 2);
}
```
---------------------
### Aula 3

**Desafio 1**
> Crie uma função que calcule o índice de massa corporal (IMC) de uma pessoa, a partir de sua altura, em metros, e peso, em quilogramas, que serão recebidos como parâmetro.

```js
function calculoIMC(altura, peso) {
  let imc = peso / (altura ** 2);
}
```

**Desafio 2**
> Crie uma função que calcule o índice de massa corporal (IMC) de uma pessoa, a partir de sua altura, em metros, e peso, em quilogramas, que serão recebidos como parâmetro.

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

**Desafio 2 - versão Instrutor**
> Crie uma função que calcule o índice de massa corporal (IMC) de uma pessoa, a partir de sua altura, em metros, e peso, em quilogramas, que serão recebidos como parâmetro.

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

**Desafio 3**
> Crie uma função que converte um valor em dólar, passado como parâmetro, e retorna o valor equivalente em reais. Para isso, considere a cotação do dólar igual a R$4,80.

```js

```

**Desafio 4**
> Crie uma função que mostre na tela a área e o perímetro de uma sala retangular, utilizando altura e largura que serão dadas como parâmetro.

```js

```

**Desafio 5**
> Crie uma função que mostre na tela a área e o perímetro de uma sala circular, utilizando seu raio que será fornecido como parâmetro. Considere Pi = 3,14.

```js

```

**Desafio 6**
> Crie uma função que mostre na tela a tabuada de um número dado como parâmetro.

```js

```

