# 🃏 Super Trunfo de Países - Nível Aventureiro

Este é o segundo nível do projeto **Super Trunfo em C**, agora com um **menu interativo** e lógica de **comparação entre atributos** das cartas! O jogador escolhe um atributo e o programa compara os valores entre dois países.

---

## 🎯 Objetivo

Permitir que o usuário selecione um atributo para comparar duas cartas do Super Trunfo, utilizando:

- Estrutura `switch` para o menu interativo
- Estruturas `if-else` para decidir quem vence a comparação
- Regras diferentes para atributos como densidade demográfica

---

## 📋 Atributos disponíveis para comparação

- 🧑‍🤝‍🧑 **População** (int)  
- 🌍 **Área (km²)** (float)  
- 💰 **PIB** (float)  
- 🗺️ **Número de Pontos Turísticos** (int)  
- 👥 **Densidade Demográfica** (calculada: população / área) *(menor valor vence)*

---

## 📂 Arquivo principal

- `super_trunfo_aventureiro.c`

---

## ▶️ Como compilar e executar

```bash
gcc super_trunfo_aventureiro.c -o super_trunfo_aventureiro
./super_trunfo_aventureiro
