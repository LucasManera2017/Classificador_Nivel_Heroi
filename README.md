# Classificador_Nivel_Heroi
Desafio Dio - Classificador de Nível do Herói 

# Sistema de Ranking baseado em XP

## Descrição do Projeto

Este projeto implementa um sistema de ranking para um herói baseado em sua quantidade de pontos de experiência (XP). Dependendo do XP acumulado, o herói recebe um título de ranking correspondente.

## Tecnologias Utilizadas

- **Linguagem:** JavaScript (ES6+)
- **Ambiente:** Node.js (ou navegador)

## Funcionamento

O código define um nome para o herói e um valor de XP. A partir disso, ele determina o ranking correspondente com base nas seguintes faixas de XP:

| XP Mínimo | XP Máximo | Rank       |
| --------- | --------- | ---------- |
| 0         | 1000      | Ferro      |
| 1001      | 2000      | Bronze     |
| 2001      | 5000      | Prata      |
| 5001      | 7000      | Ouro       |
| 7001      | 8000      | Platina    |
| 8001      | 9000      | Ascendente |
| 9001      | 10000     | Imortal    |
| 10001+    | -         | Radiante   |


## Como Executar

Caso queira rodar o código no Node.js:

1. Salve o código em um arquivo `rank.js`.
2. Execute no terminal com o comando:
   ```sh
   node rank.js
