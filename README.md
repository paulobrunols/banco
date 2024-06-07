# P-Banco

Este projeto tem como objetivo aplicar as técnicas de aprendizado do Módulo de Backend do curso de Desenvolvedor FullStack 27 da Digital College.


# Resumo do desafio

Criar um sistema de gestão bancária por meio de uma API, composta por dois endpoints:
"/conta" e "/transacao". O endpoint "/conta" deve criar e fornecer informações sobre o número da conta e o saldo. O endpoint "/transacao" será responsável por realizar diversas operações financeiras.

Os endpoints utilizarão padrões de entrada e saída no formato JSON.

# Etapas do Desafio
Aqui estão as etapas do desafio:
Há três formas de transação disponíveis: débito, crédito e Pix, cada uma com taxas diferentes.
Taxa de débito: 3% sobre a operação
Taxa de crédito: 5% sobre a operação
Taxa do Pix: Sem custo

Após criar a conta e definir as taxas, execute sua api com as seguintes operações:
1. Validar se uma conta existe
2. Criar uma conta com saldo inicial de R$ 500
3. Consultar o saldo dela
4. Efetue uma compra no valor de R$50 utilizando a opção de débito.
5. Execute uma compra de R$100 usando a opção de crédito.
6. Realize uma transferência via Pix no valor de R$75.

