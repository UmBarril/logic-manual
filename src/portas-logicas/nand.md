# NAND

A porta NAND é uma combinação das portas AND e NOT. Ela realiza a operação "E-NÃO" da álgebra booleana, ou seja, primeiro faz a operação AND (E) e depois inverte o resultado com uma operação NOT (NÃO). A porta NAND gera uma saída 0 (falsa) apenas quando todas as entradas forem 1. Se qualquer uma das entradas for 0, a saída será 1 (verdadeira).

Ou seja:
Se as entradas forem 1 e 1, a saída será 0.
Se as entradas forem 1 e 0, a saída será 1.

Tabela verdade:

| A | B | Saída |
|---|---|-------|
| 0 | 0 |   1   |
| 0 | 1 |   1   |
| 1 | 0 |   1   |
| 1 | 1 |   0   |

A porta NAND é muito importante porque pode ser usada para construir qualquer outra porta lógica. Isso significa que, com apenas portas NAND, podemos criar circuitos lógicos complexos. Ela é muito comum em circuitos digitais por sua versatilidade e simplicidade.

---

Teste a porta NAND no nosso simulador (AINDA EM CONTRUÇÃO). Clique [Aqui](https://umbarril.github.io/logic-simulator).
