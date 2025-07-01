# Hotel
## Construindo um Sistema de Hospedagem de um Hotel no C#
## Sistema de Hospedagem de um Hotel

### Author: Macedo, Glener Diniz - Desenvolvedor Full Stack
### Data.: 1 de julho de 2025.

### Orientador:
Leonardo Buta - Full-Stack

<p align="center">
  <img src="https://raw.githubusercontent.com/gdmacedo/Hotel/refs/heads/main/0002.jpg" alt="">
</p>


## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de explorando a linguagem C#.

### DESCRIÇÃO:
Neste Laboratório foi proposto um desafio para construir um sistema de hospedagem, com o intuito de ser usado para realizar uma reserva em um hotel.

<p align="center">
  <img  src="https://raw.githubusercontent.com/gdmacedo/Glener-Talk/main/developer-MacedoGDiniz.jpg" alt="Macedo, Glener Diniz">
</p>

## Contexto
Fui contratado para construir um sistema de hospedagem, que será usado para realizar uma reserva em um hotel. Precisei usar a classe Pessoa, que representa o hóspede, a classe Suíte, e a classe Reserva, que fará um relacionamento entre ambos.

O programa tem a missão de cálcular corretamente os valores dos métodos da classe Reserva, que precisará trazer a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% para caso a reserva seja para um período maior que 10 dias.

#### Classes
Com o uso da classe Pessoa, que representa o hóspede, a classe Suíte, e a classe Reserva, que fará um relacionamento entre ambos.


## Regras e validações
1. Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
2. O método ObterQuantidadeHospedes da classe Reserva deverá retornar a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria deverá retornar o valor da diária (Dias reservados x valor da diária).
3. Caso seja feita uma reserva igual ou maior que 10 dias, deverá ser concedido um desconto de 10% no valor da diária.


![Diagrama de classe estacionamento](diagrama_classe_hotel.png)


Neste módulo, o programa tem a finalidade de calcular corretamente os valores dos métodos da classe Reserva, que precisará trazer a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% para caso a reserva seja para um período maior que 10 dias.


#### Conteúdos
- Desafio de projeto: Construindo um sistema de hospedagem de um hotel no C#
- Entendendo o Desafio e Materiais Complementares
