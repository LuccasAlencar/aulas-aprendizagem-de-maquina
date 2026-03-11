---
title: "Aula 11 — Aplicações práticas de modelos não supervisionados"
layout: default
---

## 🎯 Objetivos da Aula
- Aplicar conceitos de clusterização em problemas reais de negócios.
- Entender a análise de anomalias (Segurança e Fraude).
- Dominar a técnica RFM para marketing.

---

## 1. Segmentação de Clientes (Ouro do Marketing)
Empresas não tratam todos os clientes de forma igual. Usando modelos não supervisionados, elas criam "Personas".

### A Técnica RFM:
* **Recência (R):** Quando foi a última compra?
* **Frequência (F):** Quantas vezes ele compra por mês?
* **Valor Monetário (M):** Quanto ele gasta no total?

**Aplicação:** O modelo agrupa clientes com R, F e M altos em um cluster chamado "VIPs". Clientes com R baixo (não compram há muito tempo) vão para o cluster "Risco de Abandono".

## 2. Detecção de Anomalias
Aqui, o objetivo não é criar grupos equilibrados, mas sim identificar quem **não pertence a grupo nenhum**.
- **Cartão de Crédito:** Se você gasta R$ 50,00 por dia em SP e surge uma compra de R$ 5.000,00 em Dubai, o modelo não supervisionado detecta que esse ponto de dado está longe de todos os seus clusters habituais.

---

## ✍️ Atividade de Caso Real: Otimizando um E-commerce
Você recebeu os dados de navegação de um site. Existem três grupos claros de comportamento:
1. Pessoas que ficam 30 segundos e saem.
2. Pessoas que colocam itens no carrinho mas não finalizam.
3. Pessoas que compram toda semana.

**Pergunta:** Se você fosse o programador desse site, que tipo de "interação automática" (notificação, e-mail, cupom) você criaria para o **Grupo 2** para movê-los para o **Grupo 3**?

---

## 🚀 Desafio Final do Módulo
Pesquise sobre "Sistemas de Recomendação Híbridos". Eles misturam o que aprendemos na Aula 7 (Supervisionado) com o que aprendemos hoje (Não Supervisionado).
- Como o YouTube usa a Clusterização para te colocar em um "balde de usuários parecidos"?
- Como ele usa a Classificação para decidir qual vídeo específico te mostrar agora?

---

## ✅ Conclusão do Módulo
Parabéns! Você passou pelos fundamentos de Machine Learning:
1. Supervisionado (Regressão e Classificação).
2. Não Supervisionado (Clusterização e Redução de Dados).
3. Aplicações práticas e Ética.

## 📚 Referências
- [Analytics Vidhya: Unsupervised Learning Guide](https://www.analyticsvidhya.com/blog/2021/04/unleashing-the-power-of-unsupervised-learning/)
- [Guia RFM para Data Science](https://www.optimizesmart.com/rfm-analysis-guide/)