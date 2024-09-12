# DIO - Trilha .NET - Explorando a linguagem C#
www.dio.me

## Desafio de projeto
Para este desafio, foi necessário usar conhecimentos adquiridos no módulo de explorando a linguagem C#, da trilha .NET da DIO.

## Contexto
Fui contratado para construir um sistema de hospedagem, que será usado para realizar uma reserva em um hotel. Será necessário usar a classe Pessoa, que representa o hóspede, a classe Suíte, e a classe Reserva, que fará um relacionamento entre ambos.

Este programa calcula corretamente os valores dos métodos da classe Reserva, que têm a quantidade de hóspedes e o valor da diária e concede um desconto de 10% para caso a reserva seja para um período maior que 10 dias.

## Regras e validações
1. Não é possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
2. O método ObterQuantidadeHospedes da classe Reserva retorna a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria retornar o valor da diária (Dias reservados x valor da diária).
3. Caso seja feita uma reserva igual ou maior que 10 dias, é concedido um desconto de 10% no valor da diária.


![Diagrama de classe estacionamento](diagrama_classe_hotel.png)

## Solução
O código estava pela metade sendo realizadas implementações, alterações e testes para ficar completo
e atender as demandas exigidas tornando o código funcional.
