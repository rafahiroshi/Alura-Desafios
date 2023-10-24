# Alura-Desafios-4 (Boas práticas de programação)
Treinamento com desafios, cursando Alura. Se você se interessar, aqui está o link: https://www.alura.com.br/

#### Desafios - Minhas respostas feitas antes de verificar @alura-cursos.

Percebi que no site da Alura as instruções são diferentes do perfil @alura-cursos no site do GitHub, mas no final praticamente resulta no mesmo, a diferença que percebi é que no GitHub as instruções são mais completas e claras, decidi por escolha minha, deixar como estava no site da Alura.

1) Crie um programa que utilize o `console.log` para exibir uma mensagem de boas-vindas.

```js
console.log('Olá, seja bem-vinda(o)!');
```

2) Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador.

```js
let nome = 'Rafael';
console.log(`Olá, ${nome}!`);
```

3) Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o `alert` para exibir a mensagem "Olá, [seu nome]!" .

```js
let nome = 'Rafael';
alert(`Olá, ${nome}!`);
```

4) Utilize o `prompt` e faça a seguinte pergunta: `Qual a linguagem de programação que você mais gosta?`. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.

```js
let qualLinguagem = prompt('Qual linguagem de programação que você mais gosta?');
console.log(qualLinguagem);
```

5) Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.

```js
let valor1 = 4;
let valor2 = 11;
let resultado = valor1 + valor2;

console.log(`A soma de ${valor1} e ${valor2} é igual a ${resultado}.`);
```

6) Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.

```js
let valor1 = 8;
let valor2 = 20;
let resultado = valor1 - valor2;

console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}.`);
```

7) Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.

```js
let idade = prompt('Insira sua idade, por favor:');

if(idade >= 18) console.log('O usuário é maior de idade.');
else console.log('O usuário é menor de idade.');
```

8) Crie uma variável "numero" e peça um valor com `prompt` verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.

```js
let numero = prompt('Um número, por favor:');

if(numero > 0) alert('O número escolhido é positivo(maior que zero).');
else {
    if(numero == 0) alert('O número escolhido não é positivo e nem negativo(o seu número é igual a zero).');
    alert('O número escolhido é negativo(menor que zero).');
}
```

9) Use um loop while para imprimir os números de 1 a 10 no console.

```js
let numeros = 1;

while (numeros < 10) {
    console.log(numeros);
    // A variável numeros será igual a ela mesma mais um.
    numeros++;
}
```

10) Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.

```js
let nota = 6;

if(nota >= 7) console.log('Aprovado');
else console.log('Reprovado');
```

11) Use o `Math.random` para gerar qualquer número aleatório e exiba esse número no console.

```js
let numeroAleatorio = Math.random();
console.log(numeroAleatorio);
```

12) Use o `Math.random` para gerar um número inteiro entre 1 e 10 e exiba esse número no console.

```js
let numeroAleatorio = parseInt(Math.random()*11);
console.log(numeroAleatorio);
```

13) Use o `Math.random` para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.

```js
let numeroAleatorio = parseInt(Math.random()*1001);
console.log(numeroAleatorio);
```