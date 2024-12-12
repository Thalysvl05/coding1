1. Introdução aos Algoritmos

Conceito de algoritmo: Sequência de passos lógicos e finitos para resolver um problema.

Importância: Utilizado para solucionar problemas de forma estruturada e eficiente.

Pseudocódigo: Representação textual do algoritmo antes de implementá-lo em código.

Fluxogramas: Representação gráfica de algoritmos.

2. Tipos Primitivos em JavaScript

Definição: Tipos básicos de dados para armazenar valores.

Principais tipos:

String: Representa textos. Exemplo: "Olá, mundo!"

Number: Representa números inteiros e decimais. Exemplo: 42, 3.14

Boolean: Representa valores lógicos (verdadeiro ou falso). Exemplo: true, false

Undefined: Valor de uma variável declarada mas não inicializada.

Null: Representa intencionalmente a ausência de valor.

Operadores de Tipos:

typeof: Determina o tipo de dado. Exemplo: typeof 42 // "number"

Conversão implícita e explícita entre tipos.

3. Estruturas Condicionais

Definição: Permitem a execução de diferentes blocos de código dependendo de uma condição.

If/Else:

if (condicao) {
  // Bloco executado se a condicao for verdadeira
} else {
  // Bloco executado se a condicao for falsa
}

Else If: Para verificar várias condições sequenciais.

Switch/Case: Alternativa ao if para condições múltiplas:

switch (variavel) {
  case valor1:
    // Bloco de código
    break;
  case valor2:
    // Bloco de código
    break;
  default:
    // Bloco de código
}

4. Arrays (Vetores)

Definição: Coleção ordenada de elementos que podem ser acessados por índices.

Criação:

let numeros = [1, 2, 3, 4, 5];

Métodos comuns:

.push(): Adiciona elementos ao final.

.pop(): Remove o último elemento.

.shift(): Remove o primeiro elemento.

.unshift(): Adiciona elementos ao início.

.length: Retorna o tamanho do array.

.map(), .filter(), .reduce(): Funções de alta ordem para manipulação de arrays.

5. Funções

Definição: Blocos reutilizáveis de código que realizam uma tarefa específica.

Declaração:

function saudacao(nome) {
  return `Olá, ${nome}!`;
}

Funções anônimas:

const somar = function(a, b) {
  return a + b;
};

Arrow Functions:

const multiplicar = (a, b) => a * b;

Parâmetros e retorno: Recebem valores de entrada e podem retornar resultados.

6. Objetos

Definição: Coleção de pares chave-valor que representa entidades do mundo real.

Criação:

let pessoa = {
  nome: "João",
  idade: 25,
  profissao: "Desenvolvedor"
};

Acesso a propriedades:

Notção de ponto: pessoa.nome

Notção de colchetes: pessoa["idade"]

Adicionando ou alterando propriedades:

pessoa.altura = 1.75;
pessoa.idade = 26;

Métodos em objetos:

let carro = {
  marca: "Toyota",
  ligar: function() {
    console.log("Carro ligado!");
  }
};
carro.ligar();


