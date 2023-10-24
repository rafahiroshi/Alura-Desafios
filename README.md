# Alura-Desafios-3 (Loops e tentativas)
Treinamento com desafios, cursando Alura. Se você se interessar, aqui está o link: https://www.alura.com.br/

#### Desafios - Minhas respostas feitas antes de verificar @alura-cursos.

Percebi que no site da Alura as instruções são diferentes do perfil @alura-cursos no site do GitHub, mas no final praticamente resulta no mesmo, a diferença que percebi é que no GitHub as instruções são mais completas e claras, decidi por escolha minha, deixar como estava no site da Alura.

1) Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.

```js
// Variável de contagem que começa do 1.
let contador = 1;

// Enquanto o contador for menor que dez, o contador será ele mesmo mais um.
while (contador < 10) contador++;
```

2) Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.

```js
// Variável de contagem que começa do 10.
let contador = 10;

// Enquanto o contador for maior que um, o contador será ele mesmo menor um.
while (contador > 0) contador--;
```

3) Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.

```js
// Variável do número escolhido.
let numeroUsuario = prompt('Escolha um número, por favor:');

// Enquanto o número escolhido pelo usuário for maior que zero.
while (numeroUsuario > 0) {
    // Mostrará no console o valor da variável de contagem regressiva.
    console.log(contagemRegressiva);
    // A contagem regressiva será igual a ela mesma menos um.
    numeroUsuario--;
}
```

4) Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.

```js
// Variável do número escolhido.
let numeroUsuario = prompt('Escolha um número, por favor:');
// Variável de contagem progressiva será igual ao número escolhido pelo usuário.
let contagemProgressiva = 0;

// Enquanto a contagem progressiva for menor que o número escolhido pelo usuário.
while (contagemProgressiva < numeroUsuario) {
    // Mostrará no console o valor da variável de contagem progressiva.
    console.log(contagemProgressiva);
    // A contagem progressiva será ela mesma menos um.
    contagemProgressiva++;
}
```