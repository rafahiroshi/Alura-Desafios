# Alura-Desafios-2 (Condicionais e concatenação)
Treinamento com desafios, cursando Alura. Se você se interessar, aqui está o link: https://www.alura.com.br/

#### Desafios - Minhas respostas feitas antes de verificar @alura-cursos.

Percebi que no site da Alura as instruções são diferentes do perfil @alura-cursos no site do GitHub, mas no final praticamente resulta no mesmo, a diferença que percebi é que no GitHub as instruções são mais completas e claras, decidi por escolha minha, deixar como estava no site da Alura.

1) Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".

```js
//Variável da pergunta que armazena a resposta do usuário.
let respostaUsuario = prompt('Que dia da semana é hoje?');

//Se a resposta do usuário for Sábado ou Domingo, uma mensagem de alerta será exibida com a mensagem "Bom fim de semana!".
if(respostaUsuario == 'Sábado' || 'Domingo') alert('Bom fim de semana!');
//Senão uma mensagem de alerta será exibida com a mensagem "Boa semana!";
else alert('Boa semana!');
```

2) Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.

```js
//Variável que armazena o número escolhido pelo usuário.
let numeroEscolhido = prompt('Escolha um número:');

//Se o número escolhido for maior que zero, um alerta aparecerá falando que você escolheu um número positivo.
if(numeroEscolhido > 0) alert('Você escolheu um número positivo');
//Se o número escolhido for menor que zero, um alerta aparecerá falando que você escolheu um número negativo.
if(numeroEscolhido < 0) alert('Você escolheu um número negativo');
```

3) Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".

```js
//Variável da pontuação.
let pontuacao;

//Se a pontuação for maior ou igual a cem, uma mensagem de alerta será exibido com a mensagem "Parabéns, você venceu!".
if(pontuacao >= 100) alert('Parabéns, você venceu!');
//Senão uma mensagem de alerta será exibida com a mensagem "Tente novamente para ganhar.".
else alert('Tente novamento para ganhar.');
```

4) Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.

```js
//Variável que armazena o saldo da conta.
let saldoConta = 0;

//Mensagem de alerta informando o saldo da conta - Um template com string.
alert(`O atual saldo da sua conta é de R$${saldoConta}`);
```

5) Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.

```js
//Variável em prompt que armazena o nome do usuário.
let nomeUsuario = prompt('Insira seu nome, por favor:');

//Mensagem de alerta dando boas-vindas usando template com string.
alert(`Boas-vindas ${nomeUsuario}!`);
```