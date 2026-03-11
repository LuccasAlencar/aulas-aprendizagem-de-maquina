---
title: "Aula 8 — Exercícios de fixação"
layout: default
---

## 🎯 Objetivos da Aula
- Consolidar a intuição sobre como máquinas "enxergam" padrões.
- Resolver problemas práticos de lógica de Machine Learning.
- Discutir a ética por trás do reconhecimento de padrões.

---

## 1. O que é um "Padrão" para a Máquina?
Nós, humanos, reconhecemos um rosto instantaneamente. Para o computador, um rosto é uma **matriz de números** (pixels). O reconhecimento de padrão acontece quando o algoritmo identifica que certas combinações de números (bordas, cores, texturas) se repetem em todos os rostos.

### Exemplo: Redes Sociais
O Instagram não "sabe" o que é um sorriso. Ele sabe que quando os pixels ao redor da boca formam uma curva ascendente específica, ele deve aplicar o filtro de "felicidade".

---

## 📝 Bateria de Exercícios

### Parte 1: Identificação de Padrões
Considere os seguintes dados de uma loja de games:
- Cliente A: Comprou *God of War*, *Elden Ring*, tem 25 anos.
- Cliente B: Comprou *FIFA 24*, *NBA 2K*, tem 20 anos.
- Cliente C: Comprou *Elden Ring*, *Dark Souls*, tem 28 anos.

**Pergunta 1:** Se um Cliente D de 26 anos comprar *God of War*, qual jogo o sistema deveria recomendar por padrão? Por quê?

### Parte 2: Visão Computacional
Explique o processo de reconhecimento de padrões no desbloqueio facial do celular (FaceID). 
- O que acontece se você estiver de óculos? 
- Como o modelo trata essa "variação" no padrão?

---

## 🕵️ Desafio Interativo: O Viés no Padrão
Às vezes, os modelos aprendem padrões errados. Se treinarmos um modelo para identificar "Criminosos" usando apenas fotos de pessoas com roupas escuras, o que o modelo vai aprender?
- ( ) Que roupas definem o caráter.
- ( ) Que qualquer pessoa de roupa escura é um padrão suspeito.

**Reflexão:** Como desenvolvedor, como você evitaria que o computador aprendesse padrões preconceituosos?

---

## ✅ Checklist de Revisão
- [ ] Sei explicar a diferença entre entrada (input) e saída (output).
- [ ] Entendo que padrões são correlações matemáticas.
- [ ] Consigo dar 3 exemplos de reconhecimento de padrões no meu celular.

## 📖 Referências
- **Material didático:** Livro "Introdução aos Sistemas Digitais", Capítulo 5.
- [Explorável: Como Redes Neurais enxergam](https://poloclub.github.io/cnn-explainer/)