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

## Mais desafios

#### 1. Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas.
```js
console.log('Boas vindas');
```
#### 2. Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o *console.log* para exibir a mensagem "Olá, [seu nome]!" no console do navegador.
```js
let nome = 'Ana Paula';
console.log(`Olá, ${nome}`);
```
#### 3. Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o *alert* para exibir a mensagem "Olá, [seu nome]!" .
```js
let nome = 'Ana Paula';
alert(`Olá, ${nome}`);
```
#### 4. Utilize o prompt e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.
```js
let linguagemPreferida = prompt('Qual a linguagem de programação que você mais gosta?');
console.log(linguagemPreferida);
```
#### 5. Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a *soma* desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.
```js
let valor1 = 7;
let valor2 = 9;
let resultado = valor1 + valor2;
console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}`);
```
#### 6. Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a *subtração* desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.
```js
let valor1 = 43;
let valor2 = 5;
let resultado = valor1 - valor2;
console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}`);
```
#### 7. Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.
```js
let idade = prompt('Qual a sua idade?');
if (idade >= 18) {
    console.log('O usuário é maior de idade');
} else {
    console.log('O usuário é menor de idade.');
}
```
#### 8. Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.
```js
let numero = prompt('Digite um número');
if (numero > 0) {
    console.log('Número positivo');
} else if (numero < 0) {
    console.log('Número negativo');
} else {
    console.log('Número é zero');
}
```
#### 9. Use um loop while para imprimir os números de 1 a 10 no console.
```js
let contador = 1;
while (contador <= 10) {
    console.log(`Contagem: ${contador}`);
    contador++;
}
```
#### 10. Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.
```js
let nota = 7; 
if (nota >= 7) {
    console.log('Aprovado');
} else {
    console.log('Reprovado');
}
```
#### 11. Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.
```js
let numeroAleatorio = Math.random();
console.log(numeroAleatorio);
```
#### 12. Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console.
```js
let numeroAleatorioInteiro = parseInt(Math.random() * 10 + 1);
console.log(numeroAleatorioInteiro);
```
#### 13. Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.
```js
let numeroAleatorioInteiro = parseInt(Math.random() * 1000 + 1);
console.log(numeroAleatorioInteiro);
```

