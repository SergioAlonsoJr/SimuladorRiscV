# SimuladorRiscV

## Apresentação do Problema

O desafio foi criador um simulador de Risc V em C++ como aprendizado. Esse conhecimento vai ser útil para aprender SystemC no futuro.

## Descrição das Instruções implementadas

- add
- addi
- and
- andi
- auipc
- beq
- bne
- bge
- bgeu
- blt
- bltu
- jal
- jalr
- lb
- or
- lbu
- lw
- lui
- nop
- sltu
- ori
- sb
- slli
- slt
- srai
- srli
- sub
- sw
- xor
- ecall (print int, print string e exit)

[A descrição de cada instrução pode ser encontrada nesse link](https://msyksphinz-self.github.io/riscv-isadoc/html/index.html)

## Testes e Resultados

O simulador passou nos 22 testes do [arquivo de testes](https://github.com/SergioAlonsoJr/SimuladorRiscV/blob/master/testador.asm)

## Compilador Empregado:

Compilado no Visual Studio 2022 com C++ 14 Standard

## Sistema Operational

Windows 11 x64

## IDE

Visual Studio 2022 Community
