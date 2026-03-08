---
title: "Aula 10 — Introdução à redução de dimensionalidade"
layout: default
---

## Antes de começar

Você já reparou como os aplicativos e redes sociais que usamos todos os dias funcionam super bem? Eles coletam toneladas de informações sobre nós, mas ainda assim conseguem fazer recomendações precisas e personalizadas. Como eles fazem isso sem ficar confusos ou demorar uma eternidade para processar tudo?

## O que você vai aprender nesta aula

- Entender o conceito de redução de dimensionalidade e como ela ajuda na análise de dados.
- Aprender sobre PCA (Análise de Componentes Principais) e sua aplicação em conjuntos de dados complexos.
- Conhecer T-SNE e como essa técnica preserva a proximidade local dos pontos de dados para facilitar visualizações.
- Compreender o conceito da maldição da dimensionalidade e suas implicações na análise de dados.

## Redução de Dimensionalidade

A técnica que estamos aprendendo hoje é a redução de dimensionalidade. É como se você estivesse limpando o seu quarto: joga fora as coisas desnecessárias, mas mantém os itens essenciais. No caso dos conjuntos de dados, isso significa diminuir o número de variáveis sem perder informações importantes.

Melhor visualização
Reduzir a dimensionalidade ajuda você a entender melhor seus dados, especialmente quando quer visualizá-los. Imagine tentar desenhar um gráfico 3D no papel... complicado, não é? Agora pense em reduzir isso para apenas duas dimensões. É mais fácil de ver e entender.

> 🤔 **Para refletir:** Como você acha que as redes sociais usam essa técnica para melhorar suas recomendações?

### Atividade Prática

Agora, vamos pensar em um exemplo: suponha que você está trabalhando com dados sobre jogos online. Você tem informações detalhadas sobre cada jogador, como tempo de jogo, nível, itens comprados e muito mais. Vamos reduzir essas variáveis mantendo apenas as mais relevantes para a experiência do jogador.

## PCA (Análise de Componentes Principais)

Imagine que você está em um aplicativo de redes sociais e vê várias pessoas falando sobre os mesmos tópicos, mas usando linguagens diferentes. É como se cada pessoa estivesse dando a mesma informação de formas variadas. No mundo dos dados, isso é semelhante quando temos muitas características que são muito parecidas ou até mesmo iguais.

### Transformação e Simplificação

Quando trabalhamos com conjuntos grandes de dados, frequentemente encontramos várias características que são muito parecidas ou até mesmo iguais. PCA nos ajuda a transformar essas variáveis correlacionadas em um conjunto menor de novas variáveis chamados componentes principais. Essas novas variáveis não estão correlacionadas entre si e capturam grande parte da informação dos dados originais.

> 🤔 **Para refletir:** Como você acha que simplificar essas características múltiplas pode ajudar na análise de dados?

### Exemplo Prático: Análise Genômica

Vamos supor que temos um conjunto de dados com informações sobre expressão gênica em diferentes amostras. Muitos desses genes podem estar fortemente correlacionados. Ao aplicar PCA, podemos reduzir essas centenas ou milhares de genes para uma quantidade menor de componentes principais que ainda capturam a maioria das variações importantes nos dados.

Atividade prática: Considere um conjunto de dados genômico com 100 genes. Se aplicássemos PCA, quantos componentes principais você acha que seriam suficientes para capturar mais de 95% da variância total dos dados?

## T-SNE: Trabalhando com Dados Complexos

Imagine que você está usando um aplicativo de redes sociais e quer entender melhor como os algoritmos sugerem amigos ou posts relacionados. Esses algoritmos muitas vezes lidam com dados muito complexos, mas precisamos visualizá-los para entender o que está acontecendo.

### Preservando Proximidade Local

A técnica T-SNE é uma ferramenta poderosa nessa área. Ela ajuda a preservar a proximidade local dos pontos de dados em um espaço dimensional reduzido, geralmente 2D ou 3D. Isso significa que itens semelhantes continuarão próximos uns aos outros mesmo quando os dados são visualizados de forma simplificada.

### Exemplo Prático

Vamos imaginar que você está analisando perfis de jogos em uma plataforma online para sugerir novos títulos aos usuários. Com T-SNE, podemos tomar esses dados complexos e mostrar como cada jogo se relaciona com os outros em um gráfico fácil de entender.

> 🤔 **Para refletir:** Como você acha que a visualização dessas relações pode ajudar as empresas a melhorar suas recomendações para jogadores?

## Maldição da Dimensionalidade

Vocês já perceberam que muitos aplicativos e sites recomendam coisas baseando-se em suas preferências? Eles precisam lidar com uma quantidade massiva de informações para fazer essas recomendações. Agora, imagine tentar modelar isso matematicamente... 😱

### O Que É Exatamente?

A maldição da dimensionalidade é um fenômeno que acontece quando temos muitas variáveis em nossos dados. Com mais variáveis, torna-se cada vez mais difícil encontrar padrões e fazer previsões precisas.

### Esparsidade de Dados

Imagine ter uma sala cheia de pessoas tentando jogar um jogo onde todos devem escolher entre 1024 opções diferentes! 🤯 Quanto maior o número de opções, menor a chance de alguém escolher exatamente aquela que você está pensando. É algo parecido com os dados: quanto mais dimensões (ou variáveis), mais "raros" se tornam padrões consistentes.

### Ajuste Excessivo

Quanto mais variáveis adicionamos ao nosso modelo, mais fácil é ajustá-lo perfeitamente aos nossos dados de treinamento. Mas isso não significa que ele vai funcionar bem com novos dados! 😬 É como memorizar o rosto específico de cada pessoa em vez de aprender a reconhecer características gerais.

> 🤔 **Para refletir:** Por que você acha que é tão difícil encontrar um equilíbrio entre ter muitas variáveis e ainda conseguir fazer previsões precisas?

### Atividade Prática

Vamos pensar num exemplo simples: Se alguém está tentando recomendar músicas, o modelo precisa entender gêneros, artistas, sentimentos expressos na letra... E se adicionarmos informações como horário do dia ou localização do usuário? Tudo isso aumenta a complexidade.

## Para fechar — com as suas palavras

Escreva um parágrafo sobre o que você aprendeu nesta aula e como planeja usar essa informação no futuro. Use suas próprias palavras para descrever os conceitos de redução de dimensionalidade, PCA, T-SNE e maldição da dimensionalidade.

## O que fica desta aula

```markdown
- Redução de dimensionalidade: técnica usada para simplificar conjuntos de dados complexos.
- PCA (Análise de Componentes Principais): método para transformar variáveis correlacionadas em um conjunto menor de componentes principais não correlacionados.
- T-SNE: ferramenta que preserva a proximidade local dos pontos de dados, facilitando visualizações 2D ou 3D.
- Maldição da dimensionalidade: fenômeno onde mais variáveis tornam difícil encontrar padrões e fazer previsões precisas.
```

## Para ir além

1. [Artigo sobre PCA](https://towardsdatascience.com/a-one-stop-shop-for-principal-component-analysis-5582fb7e0a9c)
2. [Guia prático de T-SNE](https://www.kaggle.com/code/alexisperrier/tsne-explained/notebook)

## Referências

- "Pattern Recognition and Machine Learning" por Christopher M. Bishop
- "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" por Aurélien Géron