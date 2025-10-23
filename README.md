🧮 Projeto: Desafio Controle de Fluxo
📘 Descrição

Este projeto foi criado para praticar controle de fluxo em Java, usando estruturas como if, for e tratamento de exceções personalizadas.
O programa pede dois números inteiros e faz uma contagem com base na diferença entre eles.

⚙️ Como o código funciona (explicação simples)

O programa começa pedindo dois números ao usuário:

O primeiro número (parametroUm)

O segundo número (parametroDois)

Depois ele chama o método contar(parametroUm, parametroDois) que faz a lógica principal.

Dentro desse método, o programa:

Verifica se o primeiro número é maior ou igual ao segundo.

Se for, ele lança um erro personalizado (uma exceção chamada ParametrosInvalidosException) com a mensagem:

“O segundo parâmetro deve ser maior que o primeiro”

Se o segundo número for maior, o programa calcula quantas vezes precisa contar:

contagem = parametroDois - parametroUm


Em seguida, ele usa um laço for para imprimir cada número da contagem, assim:

Imprimindo o número 1
Imprimindo o número 2
...

💡 Exemplo prático

Se o usuário digitar:

Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30


O programa vai calcular:

30 - 12 = 18


E vai imprimir:

Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18


Se o usuário inverter os números:

Digite o primeiro parâmetro:
30
Digite o segundo parâmetro:
12


O programa vai mostrar:

O segundo parâmetro deve ser maior que o primeiro

🧩 Estrutura do projeto
DesafioControleFluxo/
├── Contador.java
└── ParametrosInvalidosException.java
