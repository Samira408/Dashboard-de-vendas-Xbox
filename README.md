# Dashboard - Xbox Game Pass Subscriptions

Este projeto tem como foco a criação de um **Dashboard interativo e visualmente organizado**, com base nos dados de assinantes do Xbox Game Pass. O objetivo principal é facilitar a visualização de métricas estratégicas e indicadores-chave de desempenho relacionados ao serviço de assinaturas.

## O que este Dashboard apresenta?

- **Total de assinantes ativos**
- **Receita total gerada**
- **% de usuários com renovação automática**
- Distribuição de assinantes por **tipo de plano** (Core, Standard, Ultimate)
- Adesão a recursos adicionais como:
  - EA Play Season Pass
  - Minecraft Season Pass
- Comparação entre assinaturas **mensais, trimestrais e anuais**
- Representações visuais como **gráficos de barras, pizza e indicadores numéricos**

## Objetivo do Dashboard

Fornecer uma **visão clara, rápida e estratégica** sobre o comportamento dos assinantes, ajudando na tomada de decisão sobre:
- Ofertas combinadas com Season Pass
- Preferências dos usuários quanto ao plano e renovação

## Estrutura de Construção

- Fonte de dados: aba `Bases`
- Métricas e KPIs: calculadas na aba `Cálculos`
- Visualização: construída na aba `Dashboard`, com base nos resultados de `Cálculos`
- Identidade visual: definida na aba `Assets`, com paleta de cores personalizada

## Design Visual

A identidade visual segue uma paleta de cores composta por tons de verde, cinza e branco, que remetem à marca Xbox. Gráficos utilizam essas cores para manter coerência e melhorar a leitura dos dados.

## Observações

- A aba `Dashboard` é **alimentada automaticamente** a partir das abas `Bases` e `Cálculos`.
- As fórmulas e conexões devem ser mantidas para que as visualizações estejam sempre atualizadas com base na base de dados.

Um painel eficiente transforma dados em decisões. Este Dashboard foi pensado para ser **intuitivo, direto e útil** para análises rápidas e relatórios gerenciais.

Desenvolvido por [SAMIRA MARTINS DE ARAUJO] com o apoio e inspiraçao do segundo desafio de projedo da DIO das aulas Excel com Inteligência Artificial.

