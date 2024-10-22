# Adder

Um circuito adder (somador) é um tipo de circuito lógico que realiza a operação de adição de números binários. Os somadores são fundamentais em sistemas digitais e são utilizados em processadores, calculadoras e outros dispositivos eletrônicos que realizam operações aritméticas. Existem diferentes tipos de somadores, sendo os mais comuns:

1. Somador de Meio (Half Adder)
Descrição: Um somador de meio é um circuito que soma dois bits de entrada, gerando uma saída de soma e uma saída de carry (transportar).

Entradas: Dois bits (A e B).
Saídas: Soma (S) e Carry (C).

Tabela Verdade:

Imagem ------------



2. Somador Completo (Full Adder)
Descrição: Um somador completo é um circuito que soma dois bits de entrada e um bit de carry que pode vir de uma adição anterior. Ele também gera uma saída de soma e uma saída de carry.

Entradas: Três bits (A, B e Carry-in).
Saídas: Soma (S) e Carry-out (C).

Tabela Verdade:

Imagem ------------


3. Circuitos Somadores em Cadeia
Os somadores completos podem ser encadeados para formar circuitos que realizam a adição de números binários com mais de um bit. Por exemplo, para somar dois números de 4 bits, você precisaria de quatro somadores completos, onde a saída de carry de cada somador seria conectada como entrada de carry do próximo.

Importância

Os circuitos adder são essenciais para a aritmética digital e a lógica computacional, permitindo que processadores e outros circuitos realizem operações matemáticas. Eles são a base para a implementação de operações aritméticas em microprocessadores e circuitos integrados.
