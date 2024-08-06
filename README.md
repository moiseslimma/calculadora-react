# Calculadora Simples em React

Esta é uma aplicação simples de calculadora desenvolvida em React, que permite realizar operações matemáticas básicas como adição, subtração, multiplicação e divisão.

## Funcionalidades

- **Adição (+)**
- **Subtração (-)**
- **Multiplicação (x)**
- **Divisão (/)**
- **Limpar (c)**

## Como Funciona

A calculadora tem um estado que mantém o número atual (`currentNumber`), o primeiro número (`firstNumber`) e a operação em andamento (`operation`). As operações matemáticas são executadas conforme o usuário clica nos botões correspondentes.

### Estrutura do Código

- **Componentes:**
  - `Input`: Exibe o número atual.
  - `Button`: Representa cada botão da calculadora.
- **Estilos:**
  - O layout da calculadora é estilizado usando `Container`, `Content`, e `Row`.
- **Lógica:**
  - Funções como `handleAddNumber`, `handleSumNumbers`, `handleMinusNumbers`, `handleDivide`, `handleMultiply`, e `handleEquals` implementam as operações da calculadora.