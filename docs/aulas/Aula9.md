---
title: "Aula 9 — Introdução à clusterização"
layout: default
---

## 🎯 Objetivos da Aula
- Entender o conceito de Aprendizado Não Supervisionado.
- Aprender o funcionamento da Clusterização (Agrupamento).
- Visualizar aplicações em Marketing e Biologia.

---

## 1. O que é Aprendizado Não Supervisionado?
Ao contrário das aulas anteriores, aqui **não temos o gabarito**. O algoritmo recebe uma massa de dados bruta e sua missão é: "Encontre alguma estrutura ou ordem aqui dentro".

### Analogia: A Biblioteca Bagunçada
Imagine que derrubaram 10.000 livros no chão de uma biblioteca. Você não sabe os títulos, mas pode agrupá-los por:
- Cor da capa.
- Espessura do livro.
- Idioma (se conseguir identificar os caracteres).

Você criou grupos (clusters) sem saber previamente a categoria oficial de cada livro.

## 2. Clusterização na Prática
O algoritmo mais famoso é o **K-Means**. Ele tenta encontrar "centros" para os grupos e puxar os dados mais parecidos para perto deles.

### Onde usamos isso?
* **Segmentação de Mercado:** Agrupar clientes por comportamento de compra (os que gastam muito, os que só compram em promoção, os que compram uma vez por ano).
* **Genética:** Agrupar espécies de plantas com base em características de DNA semelhantes.
* **Segurança:** Agrupar logs de rede para detectar comportamentos estranhos que não se encaixam em nenhum grupo comum (anomalias).

---

## ✍️ Atividade Interativa: Criando Clusters
Imagine que você tem dados de 100 jogadores de um RPG:
- Atributos: Força (0-100) e Inteligência (0-100).

Se você rodar um algoritmo de clusterização e ele encontrar 3 grupos, como você nomearia esses grupos baseando-se na lógica de jogos?
1. Alta Força / Baixa Inteligência = ?
2. Baixa Força / Alta Inteligência = ?
3. Média Força / Média Inteligência = ?

---

## ⚠️ Cuidado: O número "K"
Na clusterização, nós geralmente precisamos dizer ao computador em quantos grupos queremos dividir os dados. 
- Se eu pedir 2 grupos em uma sala com homens, mulheres e crianças, o que pode acontecer?
- Se eu pedir 50 grupos, os grupos ainda serão úteis?

## 📚 Para ir além
1. [Visualização Interativa do algoritmo K-Means](https://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
2. [Artigo: Diferença entre Classificação e Clusterização](https://www.geeksforgeeks.org/difference-between-classification-and-clustering/)