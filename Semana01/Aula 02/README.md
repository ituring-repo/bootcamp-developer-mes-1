# S01 - Aula 02 - Github e primeiros passos no JavaScript

## 🎯 Objetivos:
* Aprender usar o Github em um fluxo de trabalho local + remoto;
* Dar os primeiros passos no JavaScript.
___

## Tópicos
1. [Git e Github aplicado](#fluxo-remoto)
2. [Variáveis](#variaveis)
3. [Tipos de dados](#tipos-dados)
4. [Operações](#operacoes)
___

<div id='fluxo-remoto'/>

## Git e Github aplicado
#### O que é o Github ?
O GitHub é como uma rede social de pessoas programadoras, focada em compartilhamento de código. Podemos mostrar nosso trabalho e contribuir com o trabalho dos outros.

#### Como transformar um repositório local em remoto ?
  - Conectando o repositório local a um remoto (Demonstração)
  - Clonando um repositório remoto (o jeito mais fácil)

#### Fluxo de trabalho local + remoto
  - Ciclo de vida: local + remoto
  - Atualizando um repositório remoto com base no local
  - Modificando um repositório remoto (no Github)
  - Atualizando um repositório local com base no remoto

<div id='variaveis'/>

## Variáveis
- O que são variáveis ?
- Regras de nomenclatura
- Declaração - var, let e const
- Atribuir valores


<div id='tipos-dados'/>

## Tipos de dados

Atualmente JavaScript possui 7 tipos de dados divididos em dois grupos:

Primitivos (dados imutáveis):
  * `String` - texto
  * `Number` - números
  * `Boolean` - verdadeiro e false
  * `null` - valor nulo
  * `undefined` - valor indefinido
  * `Symbol` (ES6)- tipo de dado cuja as instâncias são únicas e imutáveis

Objetos (coleção de propriedades - podem ser referenciados)
  * `Object`

Para saber mais: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Grammar_and_Types

<div id='operacoes'/>

## Operações

Em JavaScript temos os seguintes grupos de operadores:

* Operadores aritméticos
* Operadores de atribuição
* Operadores de comparação
* Operadores lógicos
* Operadores bit a bit
* Operadores de string
* Operador condicional (ternário)
* Operador vírgula
* Operadores unário
* Operadores relacionais

Para saber mais sobre operadores: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Expressions_and_operators
Para saber mais sobre conversão de tipos: https://www.w3schools.com/js/js_type_conversion.asp

## Template string
  - Combinação de texto e variáveis 
  ```javascript
      `Podemos escrever uma string combinando texto e variáveis, ${aqui entra uma variável}, legal né?`
  ```
