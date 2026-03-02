---
title: "Aula 5 — Introdução à regressão"
layout: default
---

## Antes de começar

Antes de mergulharmos nos detalhes sobre a regressão linear e outros algoritmos de regressão, pense em uma situação na qual você gostaria de fazer previsões com base em dados. Como seria essa experiência?

## O que você vai aprender nesta aula
- Entender o conceito básico da regressão linear e como ela é usada para fazer previsões.
- Conhecer outros tipos de algoritmos de regressão, incluindo polinomial e ridge regression.
- Explorar aplicações práticas da regressão em áreas como redes sociais e finanças.
- Compreender a importância da aprendizagem supervisionada na identificação de padrões e previsões.

## Regressão Linear

Quando você usa um app de fitness e insere sua altura e peso, ele faz uma estimativa da sua idade? Na verdade, não é bem assim. Mas o que acontece quando esses apps precisam prever alguma coisa baseada em vários dados como altura e peso? Eles usam modelos estatísticos chamados regressão linear.

A regressão linear é um tipo de modelo supervisionado usado para prever uma variável contínua com base em dados observados. Dá para usar a altura e o peso dos estudantes da sua escola, por exemplo, para tentar prever a idade deles. 🤔 **Para refletir:** Como você acha que a precisão dessas predições seria?

Vamos fazer um experimento simples. Pegue as alturas e pesos de cinco amigos (com permissão), registre esses dados em uma planilha. Agora, tente prever a idade média deles usando apenas essa informação.

E agora para algo mais complexo: e se você quisesse saber como o número de horas estudadas afeta as notas na escola? Como você aplicaria a regressão linear nesse caso?

Qual outro tipo de dado da sua vida cotidiana você gostaria de usar para fazer previsões?

## Algoritmos de Regressão

Já notaram quantas vezes os aplicativos e redes sociais usam previsões? Eles fazem isso usando algoritmos de regressão. Hoje, vamos falar sobre alguns desses algoritmos, como a Regressão Linear, Polinomial e Ridge.

### Regressão Linear

Pense na Regressão Linear assim: você tem uma série de dados no gráfico que parecem formar uma linha reta. O objetivo é usar essa linha para prever o futuro com base nos padrões do passado. Um exemplo prático? Empresas usam isso pra prever vendas futuras usando as vendas dos últimos meses.

> 🤔 **Para refletir:** Como você acha que uma loja de roupas poderia usar Regressão Linear para melhorar suas vendas?

Agora, peguem os dados das vendas da sua escola na última semana e tente traçar uma linha que represente essa tendência. Use um papel e caneta ou qualquer software que você gosta.

### Outros Algoritmos de Regressão

Não é só a Linear Regression quem tem esse talento para prever o futuro. Temos também Polynomial Regression, que ajuda quando os dados não são tão retos assim, e Ridge Regression, que ajuda a fazer predições mais precisas mesmo com muita informação.

E aí? Como você se sentiria usando esses algoritmos para prever coisas no seu dia a dia ou na sua escola?

Qual desses outros tipos de regressão gostariam de saber mais?

## Aplicações da Regressão

Vamos começar por um lugar comum em suas vidas diárias - redes sociais. Já reparou como certas páginas do Instagram mostram anúncios personalizados justamente no momento que você está pensando em comprar algo? Adivinha... isso é resultado de algoritmos de regressão trabalhando nos bastidores!

### Regressão nas Finanças

Agora, pense um pouco mais amplamente. Imagine o mercado de ações. Ele não para de se mover, certo? Agora, imagine alguém tentando prever essas movimentações. Isso é exatamente onde entra a regressão - ela ajuda a entender e até mesmo prever tendências baseadas em dados passados.

> 🤔 **Para refletir:** Como você pensa que a previsão do comportamento de mercado pode afetar as decisões de investimento?

### Atividade Prática

Vamos simplificar isso. Pense num jogo onde você precisa prever os próximos movimentos com base nos movimentos anteriores. Aqui, a regressão serve como uma espécie de "profeta" do jogo, dando pistas sobre o que pode acontecer a seguir.

### Regressão em Ação

Entender isso te ajuda a ver a matemática não só num papel ou numa tela, mas como um instrumento poderoso no mundo real. Então... **como você vê a regressão sendo usada em outros setores além das finanças e do marketing?**

Vamos explorar mais sobre isso na próxima aula!

## Aprendizagem Supervisionada: Como Apps de Email Usam IA

Já parou para pensar como apps de email sabem quais mensagens são spam e quais não são? Pois bem, isso é feito com algo chamado **aprendizagem supervisionada**.

### Como Funciona?

A aprendizagem supervisionada envolve treinar modelos com dados rotulados. Isso significa que o modelo recebe informações já classificadas para aprender padrões e fazer previsões. No caso dos emails, um modelo pode ser ensinado a identificar palavras-chave ou estruturas de texto típicas do spam.

### Exemplo: Identificando Spam

Imagine que estamos criando uma ferramenta que analisa novos emails e decide se são spam ou não. Para isso:

1. Recolhemos um grande conjunto de emails.
2. Classificamos cada email manualmente como spam ou não-spam.
3. Treinamos nosso modelo usando esses dados rotulados.

Agora, quando um novo email chega, o modelo usa tudo que aprendeu durante a fase de treino para decidir se ele é spam ou não!

> 🤔 **Para refletir:** Como você acha que os padrões de spam podem mudar com o tempo? E como isso afeta a precisão do nosso modelo?

### Atividade: Classifique um Email

Vamos praticar! Aqui está um email:

```plaintext
Assunto: Ganhe milhares em prêmios!
Corpo: Você ganhou uma grande quantia de dinheiro. Clique aqui para receber seu prémio.
```

Você acha que é spam ou não? Por quê?

### Próximo Passo

Sabemos como apps identificam emails indesejados, mas como eles lidam com outros tipos de conteúdo online? Como você acha que a aprendizagem supervisionada pode ser usada em outras áreas da internet?

## Para fechar — com as suas palavras
Escreva um parágrafo sobre o que achou mais interessante nesta aula e por quê.

## O que fica desta aula
```plaintext
- Regressão Linear: modelo estatístico usado para prever uma variável contínua baseada em dados observados.
- Algoritmos de regressão: incluem Polynomial Regression e Ridge Regression, usados quando os dados não são retos ou com muita informação respectivamente.
- Aprendizagem supervisionada: técnica que envolve treinar modelos com dados rotulados para identificar padrões e fazer previsões.
```

## Para ir além
1. [Artigo sobre Regressão Linear](https://www.analyticsvidhya.com/blog/2021/05/a-comprehensive-guide-to-linear-regression/)
2. [Guia de Aprendizagem Supervisionada](https://machinelearningmastery.com/supervised-and-unsupervised-machine-learning-algorithms/)

## Referências
- "Introduction to Statistical Learning", Gareth James, Daniela Witten, Trevor Hastie e Robert Tibshirani.
- "Hands-On Machine Learning with Scikit-Learn and TensorFlow", Aurélien Géron.