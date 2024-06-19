# alura-exercicios

Minha resolução dos exercícios no curso "Lógica de programação: mergulhe em programação com JavaScript
-----------
### Aula 2

**Desafio 1**
> Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".

```js
let diaSemana = prompt('Qual é o dia da semana?');

if (diaSemana == 'Sábado' || diaSemana == 'Domingo') {
  alert('Bom final de semana!');
} else {
  alert('Boa semana!');
}
```

```js
let diaSemana = prompt('Qual é o dia da semana?');
let textoDiaSemana = diaSemana == 'Sábado' || diaSemana == 'Domingo' ? 'Bom fim de' : 'Boa';
alert(`${textoDiaSemana} semana!`);
```

**Desafio 2**
> Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.

```js
let numero = prompt('Digite um número positivo ou negativo:');

if (numero > 0) {
  alert('O número é positivo');
} else {
  alert('O número é negativo');
}
```

**Desafio 3**
> Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".

```js
let pontoJogo = 120;

if (pontoJogo >= 100) {
  console.log('Parabéns, você venceu!');
} else {
  console.log('Tente novamente para ganhar.');
}
```

**Desafio 4**
> Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.

```js
let saldoConta = 1230;
alert(`Seu saldo em conta é R$${saldoConta}`);
```

**Desafio 5**
> Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.

```js
let nome = prompt('Diga seu nome');
alert(`Bem vindo, ${nome}!`);

```

-------------

### Aula 3

**Desafio 1**
> Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.

```js
let contador = 1;
while (contador <= 10) {
  console.log(contador);
  contador++;
}
```

**Desafio 2**
> Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.

```js
let contador = 10;
while (contador >= 0) {
  console.log(contador);
  contador--;
}
```

**Desafio 3**
> Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.

```js
let num = prompt('Digite um número para a contagem regressiva:');

while (num >= 0) {
  console.log(num);
  num--;
}
```

**Desafio 4**
> Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.

```js
let num = prompt('Digite um número para a contagem progressiva:');
let contador = 0;

while (contador <= num) {
  console.log(contador);
  contador++;
}
```

--------------------

### Aula 4

**Desafio 1**
> Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas.

```js
console.log('Bem vindo!');
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
let valor2 = 37;
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
let numero = prompt('Digite um valor:');

if (numero > 0) {
  alert('O número é positivo');
} else if (numero < 0) {
  alert(`O número é negativo`);
} else {
  alert(`O número zero`);
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
  console.log(`Aprovado`);
} else {
  console.log(`Reprovado`);
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
> Faça o download de outro projeto e abra no Visual Studio Code.
>
>Altere o conteúdo da tag h1 com document.querySelector e atribua o seguinte texto: Hora do Desafio.
>
>Crie uma função que exiba no console a mensagem O botão foi clicado sempre que o botão Console for pressionado.
>
>Crie uma função que exiba um alerta com a mensagem: Eu amo JS, sempre que o botão Alerta for pressionado.
>
>Crie uma função que é executada quando o botão prompt é clicado, perguntando o nome de uma cidade do Brasil. Em seguida, exiba um alerta com a mensagem concatenando a resposta com o texto: Estive em {cidade} e lembrei de você.
>
>Ao clicar no botão soma, peça 2 números inteiros e exiba o resultado da soma em um alerta.


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
> Criar uma função que exibe "Olá, mundo!" no console.

```js
exibirOla();

function exibirOla() {
    console.log('Olá, mundo!');
}
```

**Desafio 2**
> Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.

```js
exibirOlaNome('Felipe');

function exibirOlaNome(nome) {
    console.log(`Olá, ${nome}!`);
}
```

**Desafio 3**
> Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.

```js
let resultadoDobro = calcularDobro(5);
console.log(resultadoDobro);

function calcularDobro(numero) {
    return numero * 2;
}
```

**Desafio 4**
> Criar uma função que recebe três números como parâmetros e retorna a média deles.

```js
let media = calcularMedia(4, 7, 10);
console.log(media);

function calcularMedia(a, b, c) {
    return (a + b + c) / 3;
}
```

**Desafio 5**
> Criar uma função que recebe dois números como parâmetros e retorna o maior deles.

```js
let maiorNumero = encontrarMaior(70, 47);
console.log(maiorNumero);

function encontrarMaior(a, b) {
    return a > b ? a : b;
}
```

**Desafio 6**
> Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo

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
let dolares = 50;
let reais = converterDolarParaReal(dolares);
console.log(`US$${dolares.toFixed(2)} se converte em R$${reais}`);

function converterDolarParaReal(valorEmDolar) {
  let cotacaoDolar = 4.8; // US$ 1,00 = R$ 4,80
  let valorEmReais = valorEmDolar * cotacaoDolar; 
  return valorEmReais.toFixed(2);
}
```

**Desafio 4**
> Crie uma função que mostre na tela a área e o perímetro de uma sala retangular, utilizando altura e largura que serão dadas como parâmetro.

```js
let alturaSala = 4;
let larguraSala = 6;

perimetroEAreaSalaRetangular(alturaSala, larguraSala);

function perimetroAreaSalaRetangular(altura, largura) {
  let perimetro = 2 * (altura + largura);
  let area = altura * largura;
  
  console.log(`A área da sala é ${area}m²`);
  console.log(`O perímetro da sala é ${perimetro}m`);
}
```

**Desafio 5**
> Crie uma função que mostre na tela a área e o perímetro de uma sala circular, utilizando seu raio que será fornecido como parâmetro. Considere Pi = 3,14.

```js
let raioSala = 4;
perimetroAreaSalaCircular(raioSala);

function perimetroAreaSalaCircular(raio) {
  let pi = 3.14;
  let area = pi * raio ** 2;
  let perimetro = 2 * pi * raio;

  console.log(`A área do círculo é ${area}m²`);
  console.log(`O perímetro do círculo é ${perimetro}m`);
}

```

**Desafio 6**
> Crie uma função que mostre na tela a tabuada de um número dado como parâmetro.

```js
let numero = 3;
tabuada(numero);

function tabuada(num) {
  let resultado;
  for(let i = 1; i <= 10; i++) {
    resultado = num * i;
    console.log(`${num} × ${i} = ${resultado}`);
  }
}
```








