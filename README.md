# super-trunfo_dg
# Super Trunfo - Cadastro de Cartas em C

Este é um projeto simples em linguagem C que permite ao usuário cadastrar duas cartas do jogo Super Trunfo com informações de cidades brasileiras fictícias. Cada carta inclui dados como estado, código, nome da cidade, população, área, PIB e número de pontos turísticos.

Funcionalidades

- Cadastro manual de duas cartas do Super Trunfo.
- Exibição organizada das informações cadastradas.

Informações de Cada Carta

- **Estado:** Uma letra de `A` a `H`
- **Código da Carta:** Formato `EX`: `A01`, `B03`
- **Nome da Cidade:** String
- **População:** Número inteiro
- **Área:** Float (em km²)
- **PIB:** Float (em bilhões de reais)
- **Número de Pontos Turísticos:** Número inteiro

 Regras do Projeto

- Sem uso de estruturas de repetição (`for`, `while`) ou decisão (`if`, `else`)
- Código com instruções sequenciais
- Leitura e exibição apenas de duas cartas

 Como Compilar e Executar

1. Clone ou baixe o projeto.
2. Compile o código usando o `gcc`:

   ```bash
   gcc -o super_trunfo super_trunfo.c

