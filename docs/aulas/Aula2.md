---
title: "Aula 2: Tipos de aprendizagem de Máquina"
layout: default
---

# Aula 2: Tipos de aprendizagem de Máquina

**Componente:** Aprendizagem de Máquina  
**Código:** C1-U1-A2  

---

## Antes de começar

Quando você está navegando pelas redes sociais, notou que algumas páginas ou vídeos parecem aparecer exatamente quando você mais os quer ver? Como isso acontece?

---

## O que você vai aprender nesta aula

- Distinguir entre aprendizado supervisionado e não supervisionado em Aprendizagem de Máquina.
- Analisar situações práticas onde o aprendizado supervisionado é aplicado, como aprovação ou recusa de compras fictícias feitas por um adolescente com seu primeiro cartão de crédito.
- Entender quando e como o aprendizado não supervisionado pode ser útil em ambientes sem informações rotuladas.

---

## 1. Aprendendo a partir do que você já sabe

Quando você usa uma plataforma online para comprar itens, geralmente existe um sistema por trás que aprova ou recusa pedidos com base em vários fatores. Esses sistemas muitas vezes usam o aprendizado de máquina. Hoje, vamos explorar como esses sistemas funcionam.

### Aprendizado Supervisionado

Imagina que você é responsável por decidir se uma compra feita pelo João deve ser aprovada ou não, com base nos itens comprados e no histórico de compras dele. Se os dados sobre as compras e as decisões tomadas para aprovar ou recusar essas compras estão disponíveis antecipadamente (com rótulos, como aprovação ou não), então estamos falando de aprendizado supervisionado.

> 🤔 **Para refletir:** Por que é importante ter dados rotulados?

Com o aprendizado supervisionado, um sistema pode aprender a tomar decisões sem precisar de muita intervenção humana. Mas e quando os rótulos não estão disponíveis? É aí que entra...

---

## 2. Quando as regras mudam: Aprendizado Não Supervisionado

Imagine agora que João fez uma compra muito estranha, algo que você nunca viu antes e para o qual não há precedentes em seus dados anteriores sobre aprovações ou recusas. Como decidir se aprovamos essa compra? 

Nesse caso, usamos aprendizado não supervisionado. Essa técnica nos ajuda a identificar padrões ou agrupamentos sem precisar de rótulos.

### Testa você mesmo

Vou te dar um exemplo: João comprou uma guitarra virtual no jogo que ele joga. O sistema sabe que João gosta de jogos e, em geral, aprova compras ligadas a jogos que trazem entretenimento duradouro. Mas o sistema também observa que essa compra é única e diferente das outras.

> Se fosse você, como decidiria se aprovava ou recusava esta compra? Seria aprendizado supervisionado ou não supervisionado?

---

## 3. Padrões escondidos: Aprendizado Não Supervisionado

Agora vamos pensar em outro cenário: João está comprando coisas semelhantes de lojas diferentes, mas o sistema detecta que ele está criando um padrão na compra de produtos específicos em várias plataformas. O aprendizado não supervisionado ajuda a identificar esse comportamento sem precisar ser explicitamente informado do que procurar.

> 🤔 **Para refletir:** Como essa técnica poderia ajudar outras empresas além daquela onde João está comprando?

---

## Para fechar — com as suas palavras

Agora, tente explicar os conceitos de aprendizado supervisionado e não supervisionado usando a situação do cartão de crédito do João. Quais seriam os pontos principais que você destacaria para alguém que nunca ouviu falar sobre esses tipos de aprendizagem?

---

## O que fica desta aula

```python
# Definição curta dos conceitos-chave
supervisionado = "Aprendizado que utiliza dados rotulados."
nao_supervisionado = "Identifica padrões sem rótulos específicos."
```

---

## Para ir além

1. [Artigo sobre aprendizagem de máquina para iniciantes](https://www.education.com/science-fair/article/machine-learning/)
2. [Curso online interativo sobre aprendizado supervisionado e não supervisionado](https://app.datacamp.com/courses/supervised-and-unsupervised-learning-in-python)

---

## Referências

- Educação Profissional Paulista
- Técnico em Ciência de Dados

---

*[Nome do curso e instituição]*