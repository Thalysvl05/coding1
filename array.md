# Este é o dicionario de metodos array

.map()
>Aplica uma função a cada elemento de um array, retornando um novo array com os resultados.
```js
let numeros = [1, 2, 3];
let dobrar =
numeros.map(function(num) {return num * 2; // Multiplica cada número por 2
});
console.log(dobrar); // [2, 4, 6]
```
.split()
>Divide uma string em parte com base em um delimitador, retornando um array.
```js
let frase = "Recife, Olinda, Jaboatão";
let cidades = frase.split(", "); //Divide a string na vírgula e espaço
console.log(cidades); // ["Recife", "Olinda", "Jaboatão"]
```

.sort
>Organiza os elementos de um array. Ele modifica o array original e retorna o array ordenado.
```js
let frutas = ["banana", "laranja", "maçã", "abacaxi"];
frutas.sort();
console.log(frutas); // ["abacaxi", "banana", "laranja", "maçã"]
```

.filter()
>Cria um novo array com todos os elementos que passam em um teste (ou seja, uma função de filtragem).
```js
let numeros = [5, 12, 8, 130, 44];
let maioresQueDez = numeros.filter(numero => numero > 10);
console.log(maioresQueDez); // [12, 130, 44]
```

.toLowerCase()
>Converte todas as letras de uma string em minúsculas.
```js
let texto = "Olá Mundo!";
let textoMinusculo = texto.toLowerCase();
console.log(textoMinusculo); // "olá mundo!"
```
