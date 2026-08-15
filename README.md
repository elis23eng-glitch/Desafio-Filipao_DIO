# Desafio-Filipao_DIO

## Desafio Classificador de nível de Herói

Este projeto resolve o desafio de lógica proposto pela plataforma DIO: classificar o nível de um herói com base na quantidade de experiência (XP).

## Objetivo

Crie uma variável para armazenar o nome e outra para armazenar a quantidade de XP de um herói. Em seguida, use uma estrutura de decisão para determinar o nível do personagem.

## Regras de Classificação

- Menor do que 1.000 XP: Ferro
- Entre 1.001 e 2.000 XP: Bronze
- Entre 2.001 e 5.000 XP: Prata
- Entre 5.001 e 7.000 XP: Ouro
- Entre 7.001 e 8.000 XP: Platina
- Entre 8.001 e 9.000 XP: Ascendente
- Entre 9.001 e 10.000 XP: Imortal
- Acima de 10.000 XP: Radiante

## Exemplo de Solução

```javascript
let nomeHeroi = "Arthur";
let xpHeroi = 7500;
let nivelHeroi;

if (xpHeroi <= 1000) {
  nivelHeroi = "Ferro";
} else if (xpHeroi <= 2000) {
  nivelHeroi = "Bronze";
} else if (xpHeroi <= 5000) {
  nivelHeroi = "Prata";
} else if (xpHeroi <= 7000) {
  nivelHeroi = "Ouro";
} else if (xpHeroi <= 8000) {
  nivelHeroi = "Platina";
} else if (xpHeroi <= 9000) {
  nivelHeroi = "Ascendente";
} else if (xpHeroi <= 10000) {
  nivelHeroi = "Imortal";
} else {
  nivelHeroi = "Radiante";
}

console.log(`O Herói de nome ${nomeHeroi} está no nível de ${nivelHeroi}`);
```

## Saída Esperada

Ao final, a mensagem exibida será:

```bash
O Herói de nome Arthur está no nível de Platina
```

## Tecnologias Utilizadas

- JavaScript
- Node.js

## Como Executar

No terminal, dentro da pasta do projeto, execute:

```bash
node index.js
```
