---
title: "Aula 7 — Aplicações práticas de modelos supervisionados"
layout: default
---

## 🎯 Objetivos da Aula
- Diferenciar com profundidade problemas de Regressão e Classificação.
- Mapear o ciclo de vida de um dado rotulado.
- Analisar estudos de caso reais (Netflix, Bancos e Saúde).

## 💡 Cenário Inicial
Imagine que você trabalha no **setor de crédito de um banco**. Milhares de pessoas pedem empréstimos por minuto. 
1. Como decidir quem recebe o dinheiro? (Sim/Não)
2. Se a pessoa receber, qual o limite máximo de crédito que o perfil dela suporta? (Valor numérico)

Aqui temos os dois pilares do Aprendizado Supervisionado em um único exemplo!

---

## 1. O Conceito de "Dados Rotulados" (Ground Truth)
No aprendizado supervisionado, o modelo é como um aluno que tem acesso ao gabarito das provas passadas. 
- **Features (X):** As características (idade, salário, histórico de dívidas).
- **Label (y):** O rótulo ou resposta (pagou a dívida? Sim/Não).

Sem o rótulo histórico, o modelo supervisionado não consegue aprender.

## 2. Regressão: Quando o Resultado é um Número
A regressão busca prever um valor contínuo dentro de um intervalo infinito.

### 2.1 Casos de Uso Reais:
* **Mercado Imobiliário:** Prever o preço de venda de um imóvel com base na metragem, bairro e número de quartos.
* **Logística:** O Uber prevê o tempo de chegada (ETA) analisando tráfego, clima e distância.
* **Varejo:** Prever quanto uma loja vai vender no Black Friday para ajustar o estoque.

## 3. Classificação: Quando o Resultado é uma Categoria
A classificação busca atribuir uma "etiqueta" ou classe ao dado.

### 3.1 Classificação Binária vs. Multiclasse:
* **Binária (2 opções):** E-mail é Spam ou não? Transação é fraude ou legítima?
* **Multiclasse (3+ opções):** Classificar uma imagem de animal em "Cão", "Gato" ou "Papagaio". Reconhecimento de dígitos manuscritos (0 a 9).

---

## ✍️ Atividade Prática: Brainstorming de Dados
Preencha a tabela abaixo mentalmente ou no seu caderno para os seguintes cenários:

| Cenário | O que seria a Feature (X)? | O que seria o Rótulo (y)? | Tipo de Modelo |
| :--- | :--- | :--- | :--- |
| Filtro de Fotos | Pixels da imagem | Nome da pessoa na foto | Classificação |
| Previsão do Tempo | Umidade, Vento, Pressão | Temperatura em Graus | ? |
| Diagnóstico Médico | Exames de sangue | Doente / Saudável | ? |

---

## 🛠️ Exercício de Fixação (Mão na Massa)
Um hospital quer usar IA para otimizar o atendimento. Eles têm dois problemas:
1. Identificar se um tumor é benigno ou maligno através de biópsias.
2. Estimar quantos dias um paciente ficará internado para liberar leitos.

**Responda:**
- Qual desses problemas é de **Classificação**? Justifique.
- Qual é de **Regressão**? Justifique.
- Quais seriam as possíveis "Features" (dados de entrada) para o problema número 2?

---

## 📚 Referências e Links Úteis
1. [Scikit-Learn: Supervised Learning Guide](https://scikit-learn.org/stable/supervised_learning.html)
2. [Vídeo: Estatística para Machine Learning - Regressão Linear](https://www.youtube.com/watch?v=Ku3qTm5Df4g)
3. **Leitura:** "Hands-On Machine Learning" - Aurélien Géron (Capítulo 3 e 4).