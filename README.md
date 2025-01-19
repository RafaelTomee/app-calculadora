Calculadora Flutter

Este repositório contém o código-fonte de uma calculadora simples desenvolvida utilizando Flutter, com suporte a operações básicas de soma, subtração, multiplicação e divisão. A calculadora também é capaz de interpretar expressões matemáticas completas usando a biblioteca expressions.

Principais Características
Interface Dinâmica: Construída com widgets do Flutter, apresentando botões para os números, operadores e uma funcionalidade de limpar a tela.
Manipulação de Expressões: A lógica de avaliação das expressões matemáticas utiliza a biblioteca expressions, garantindo flexibilidade e precisão no processamento.
Funcionalidades Básicas:
Inserir números e operadores para compor expressões.
Avaliar a expressão ao pressionar o botão "=".
Limpar os campos de expressão e resultado com o botão "Limpar".
Tratamento de Erros: Caso a expressão seja inválida, o resultado exibirá "Erro".
Estrutura do Código
Classe Principal (Calculadora)
A classe Calculadora é um widget stateful que gerencia a interface e o estado da calculadora.

Métodos Principais:

_pressionarBotao: Atualiza o estado da calculadora com base no botão pressionado.
_calcularResultado: Avalia a expressão matemática usando a biblioteca expressions e exibe o resultado.
_avaliarExpressao: Converte os operadores (x → *, ÷ → /) e avalia a expressão.
Interface:

Composta por uma grade de botões para entrada de números e operadores.
Exibe a expressão inserida e o resultado calculado na parte superior da interface.
Como Usar
Clone este repositório.
Execute o aplicativo no emulador ou dispositivo físico com o comando:
bash
Copiar
Editar
flutter run
Insira números e operadores usando os botões e pressione "=" para calcular.
