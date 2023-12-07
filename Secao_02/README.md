##
### Seção 2 - Tipos de dados e operadores lógicos
##

<p align="center">
  <img alt="...." src="./src/js.png" width="70%">
</p>



### 16 - Introdução da seção

- Exemplo:
    - javascript_16

### 17 - O que são tipos de dados?

**O que são tipos de dados?**

- A classificação/categoria de um dado;
- Dados são por exemplo: 13, ‘olá’, True;
- Os tipos de dados existentes no JavaScript são:
- Number (Aritimético, Special Numbers);
- String;
- Boolean (Comparações, operadores lógicos);
- Empty Values (null, undefined);

- Exemplo:
    - javascript_17


### 18 - Tipo de dado: number

**Number**

- Obviamente este tipo trata de números;
```js
console.log(typeof 13);
console.log(typeof 1.8);
console.log(typeof -5);
```


- Exemplo:
    - javascript_18

### 19 - Operações aritméticas com number

- Operação mais feita com os números em JS;
- E o resultado da operação aritmética produz um novo Number;
```js
console.log(2 + 2);
console.log(2 * 4 - 3);
console.log(8 / 4);
//Funciona com a mesma da matemática;
console.log(5 + (2 * 4));
```

- `+` -> soma;
- `-` -> subtração;
- `/` -> divisão;
- `*` -> multiplicação;
- `%` -> resto;

- Exemplo:
    - javascript_19



### 20 - Conhecendo os special numbers

**Numbers: Special Numbers**

- Considerados números, mas não funcionam como números;
```js
Infinity;
-Infinity;
NaN (Not A Number);
```

- Exemplo:
    - javascript_20


### 21 - Tipo de dado: string

**Strings**

- String = texto;

```js
console.log(typeof ‘Isso é uma String’);
console.log(typeof “Este texto aqui também”);
console.log(typeof `E este também`); //(template literals)
```

- Exemplo:
    - javascript_21



### 22 - Mais sobre strings

```js
// A \ pode dar um ‘escape’ na String, e isso permite ‘efeitos especiais’;

// Por exemplo: \n pula uma linha
console.log("Essa é uma String \n De duas linhas");
// Para inserir uma ‘ ou “ devemos iniciar a String com a aspa inversa que desejamos inserir;

// O template literals serve para computar valores também, ex:
console.log(`A soma de 2 + 2 é ${2+2}`);

// Concatenação é um processo de ‘somar’ Strings, veja:
console.log("salada" + "de" + "fruta");
```

- Exemplo:
    - javascript_22



### 23 - Tipo de dado: boolean

**Booleans**

- Serve para guardar um valor de uma comparação, por exemplo;
- Os únicos valores possíveis são:
- True (verdadeiro);
- False (falso);
```js
console.log(5 > 2); //true
console.log(3 > 10); //false
```

- Exemplo:
    - javascript_23


### 24 - Comparações com booleans

**Booleans: comparações**

- Maior que: `>`
- Menor que: `<`
- Maior ou igual: `>=`
- Menor ou igual: `<=`
- Igual: `==`
- Diferente: `!=`
- Idêntico: `===`

- Exemplo:
    - javascript_24



### 25 - Operadores lógicos: teoria

**Booleans:** Operadores lógicos

- Por meio de uma comparação resultam em um Boolean
- `&&` - and -> para ser true, os dois "lados" da comparação precisam
ser true
- `||` - or -> para ser true, basta um dos "lados" da comparação ser true;
- `!` - not -> inverter os valores (true vira false);

- Tabela verdade

<p align="center">
  <img alt="...." src="./src/tabela-verdade" width="70%">
</p>

- `&&` and
- `||` - or 
- `!` - not

- Exemplo:
    - javascript_25