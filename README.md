# Resolução dos desafios do curso *Lógica de programação: mergulhe em programação com JavaScript*

## Variáveis, alert(), prompt() e estruturas de decisão

#### 1. Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".

```js
diaDaSemana = prompt('Que dia da semana é hoje?');

if (diaDaSemana == 'Sábado') {
    alert('Bom fim de semana!');
} else if (diaDaSemana == 'Domingo') {
    alert('Bom fim de semana!');
} else {
    alert('Boa semana!');
}
```

#### 2. Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.

```js
numero = prompt('Digite um número positivo ou negativo');

if (numero > 0) {
    alert('Número positivo!');
} else {
    alert('Número negativo!');
}
```

#### 3. Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".

```js
pontuacao = 89;

if (pontuacao >= 100) {
    alert('Parabéns, você venceu!');
} else {
    alert('Tente novamente para ganhar!');
}
```

#### 4. Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.

```js
let saldoConta = 389;
alert(`Seu saldo é de R$ ${saldoConta}.` );
```

#### 5. Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.

```js
nome = prompt('Digite seu nome');
alert(`Boas-vindas, ${nome}!`);
```

## Loops de repetição


#### 1. Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.
```js
let contador = 1;

while (contador <= 10) {
    console.log(`${contador} kobolds`);
    contador++;
}
```
#### 2. Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.
```js
let contador = 10;

while (contador >= 0) {
    console.log(`${contador} kobolds`);
    contador--;
}
```
#### 3. Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.
```js
let numeroMaximo = prompt('Digite quantos kobolds você viu');

while (numeroMaximo >= 0) {
    console.log(`${numeroMaximo} kobolds`);
    numeroMaximo--;
}
```
#### 4. Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.
```js
// Peça um número
let numeroMaximo = prompt('Digite quantos kobolds você viu');
let contador = 0;

// Conte de zero até o numeroMaximo
while (contador <= numeroMaximo) {
    console.log(`${contador} kobolds`);
    contador++;
}
```
