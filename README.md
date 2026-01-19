# 🦸‍♂️ Desafio Classificador de Nível de Herói

Este é um **desafio de código** do **Bootcamp Santander 2025 - Fundamentos de Lógica de Programação**, no curso **Decisões e Repetições no Código**, que aborda **estruturas condicionais, repetição e tomada de decisão**.

---

## 📌 Objetivo
Criar um programa em **JavaScript** que classifique o nível de um herói com base em sua experiência (XP).

---

## 🛠️ O que deve ser utilizado
- Variáveis  
- Operadores  
- Laços de repetição  
- Estruturas de decisão  

---

## 🚀 Regras de Classificação
- Se XP for menor do que 1.000 → **Ferro**  
- Se XP for entre 1.001 e 2.000 → **Bronze**  
- Se XP for entre 2.001 e 5.000 → **Prata**  
- Se XP for entre 5.001 e 7.000 → **Ouro**  
- Se XP for entre 7.001 e 8.000 → **Platina**  
- Se XP for entre 8.001 e 9.000 → **Ascendente**  
- Se XP for entre 9.001 e 10.000 → **Imortal**  
- Se XP for maior ou igual a 10.001 → **Radiante**

---

## 💻 Código em JavaScript

```javascript

let nome = "Devinho";  
let xp = 7500;          


let nivel = "";


if (xp < 1000) {
    nivel = "Ferro";
} else if (xp >= 1001 && xp <= 2000) {
    nivel = "Bronze";
} else if (xp >= 2001 && xp <= 5000) {
    nivel = "Prata";
} else if (xp >= 5001 && xp <= 7000) {
    nivel = "Ouro";
} else if (xp >= 7001 && xp <= 8000) {
    nivel = "Platina";
} else if (xp >= 8001 && xp <= 9000) {
    nivel = "Ascendente";
} else if (xp >= 9001 && xp <= 10000) {
    nivel = "Imortal";
} else if (xp >= 10001) {
    nivel = "Radiante";
}

console.log(`O Herói de nome ${nome} está no nível de ${nivel}`);

O Herói de nome Devinho está no nível de Platina
