# 📱 Calculadora Flutter

Uma aplicação de calculadora simples desenvolvida em **Flutter**, com interface moderna utilizando **Material 3**. Este projeto é ideal para quem está aprendendo Flutter e deseja entender como estruturar layouts responsivos, gerenciar estado e aplicar lógica de avaliação de expressões matemáticas.

## 🔧 Funcionalidades

- Interface amigável e centralizada.
- Avaliação de expressões matemáticas (adição, subtração, multiplicação, divisão e ponto decimal).
- Botão "Limpar" para reiniciar a conta.
- Avaliação de expressões usando a biblioteca [`expressions`](https://pub.dev/packages/expressions).

## 📸 Captura de Tela

![image](https://github.com/user-attachments/assets/f2186a67-4e92-4384-aa4c-880cde305fe9)


## 🧠 Como funciona

O projeto é dividido em duas partes principais:

### `main.dart`
- Define a estrutura geral do aplicativo (`App`, `HomePage`).
- Cria um layout com três colunas e espaço reservado para a calculadora no centro da tela.

### `calculadora.dart`
- Componente `Calculadora` com botões e lógica de avaliação.
- Usa `GridView` para dispor os botões numéricos e operadores.
- Usa a biblioteca `expressions` para interpretar e resolver as expressões.

## 🧑‍💻 Autor
Feito por Rafael Tomé da SIlva – Projeto de estudo em Flutter do Talento Tech Parana.
