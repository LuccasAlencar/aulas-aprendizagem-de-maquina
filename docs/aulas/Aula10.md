---
title: "Aula 10 — Introdução à redução de dimensionalidade"
layout: default
---

## 🎯 Objetivos da Aula
- Compreender a "Maldição da Dimensionalidade".
- Aprender a simplificar dados sem perder a essência.
- Introdução teórica ao PCA e t-SNE.

---

## 1. O Problema: A Maldição da Dimensionalidade
Em Machine Learning, mais dados nem sempre é melhor. Se você tem 1.000 colunas (características) para cada linha de dado:
1. O processamento fica extremamente lento.
2. O modelo começa a achar padrões onde não existem (ruído).
3. É impossível para um humano visualizar o gráfico.

**Dimensionalidade** é o número de colunas/características de um dataset.

## 2. A Solução: Redução de Dimensionalidade
É a arte de projetar dados de um espaço de alta dimensão (ex: 100D) para um espaço de baixa dimensão (2D ou 3D).

### 2.1 PCA (Principal Component Analysis)
O PCA olha para onde os dados "variam" mais e cria novos eixos para representar essa variação. É como tirar uma foto 2D de uma estátua 3D: você perde uma dimensão, mas ainda consegue reconhecer quem é a pessoa.

### 2.2 t-SNE
Diferente do PCA, o t-SNE é focado em manter os vizinhos próximos. Se dois pontos de dados são parecidos em 100D, o t-SNE vai tentar mantê-los grudados no gráfico 2D. É excelente para visualizar clusters complexos.

---

## 🧩 Exercício de Imaginação
Você tem um conjunto de dados de músicas com 50 características: batidas por minuto, volume, quantidade de guitarras, uso de sintetizadores, duração, etc.
1. Como você explicaria para um leigo por que não podemos simplesmente fazer um gráfico com as 50 características?
2. Se usarmos o PCA para reduzir para 2 dimensões, o que ganharíamos em termos de análise visual?

---

## 🛠️ Atividade Prática: Resumo de Texto
Reduzir dimensionalidade é como resumir um texto. 
**Tarefa:** Pegue o parágrafo acima sobre "PCA" e resuma-o em apenas **5 palavras**. 
*O que você fez foi selecionar as "características principais" e descartar o restante. Isso é redução de dimensionalidade!*

---

## 📖 Referências
- Livro: "Pattern Recognition and Machine Learning" - Christopher Bishop.
- [StatQuest: PCA de forma simples (Vídeo)](https://www.youtube.com/watch?v=FgakZw6K1QQ)