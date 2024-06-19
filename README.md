# alura-exercicios

Minha resolução dos exercícios no curso "Lógica de programação: mergulhe em programação com JavaScript"
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
