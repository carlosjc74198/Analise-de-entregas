# Análise de Dados de Entregas da Cury Company

![Badge em Desenvolvimento](https://img.shields.io/badge/Status-Análise%20Entregas%20Cury%20Company-green)
![Badge Versão](https://img.shields.io/badge/Versão-1.0.1-blue)

## Descrição do Projeto

A Cury Company é uma empresa de tecnologia que criou um aplicativo que conecta restaurantes, entregadores e pessoas. Através desse aplicativo, é possível realizar o pedido de uma refeição em qualquer restaurante cadastrado e recebê-lo no conforto da sua casa por um entregador também cadastrado no aplicativo da Cury Company.

A empresa realiza negócios entre restaurantes, entregadores e pessoas, gerando muitos dados sobre entregas, tipos de pedidos, condições climáticas, avaliação dos entregadores, entre outros. Apesar do crescimento em termos de entregas, o CEO não tem visibilidade completa dos KPIs de crescimento da empresa.

## Problema de Negócio

A Cury Company possui um modelo de negócio chamado Marketplace, que faz o intermédio do negócio entre três clientes principais: Restaurantes, entregadores e pessoas compradoras. Para acompanhar o crescimento desses negócios, o CEO gostaria de ver as seguintes métricas de crescimento:

### Do lado da empresa:
- Quantidade de pedidos por dia.
- Quantidade de pedidos por semana.
- Distribuição dos pedidos por tipo de tráfego.
- Comparação do volume de pedidos por cidade e tipo de tráfego.
- Quantidade de pedidos por entregador por semana.
- Localização central de cada cidade por tipo de tráfego.

### Do lado do entregador:
- Menor e maior idade dos entregadores.
- Pior e melhor condição de veículos.
- Avaliação média por entregador.
- Avaliação média e desvio padrão por tipo de tráfego.
- Avaliação média e desvio padrão por condições climáticas.
- Os 10 entregadores mais rápidos por cidade.
- Os 10 entregadores mais lentos por cidade.

### Do lado dos restaurantes:
- Quantidade de entregadores únicos.
- Distância média dos restaurantes e dos locais de entrega.
- Tempo médio e desvio padrão de entrega por cidade.
- Tempo médio e desvio padrão de entrega por cidade e tipo de pedido.
- Tempo médio e desvio padrão de entrega por cidade e tipo de tráfego.
- Tempo médio de entrega durante os Festivais.

## Objetivo do Projeto

O objetivo desse projeto é criar um conjunto de gráficos e/ou tabelas que exibam essas métricas da melhor forma possível para o CEO.

## Premissas Assumidas para a Análise

- A análise foi realizada com dados entre 11/02/2022 e 06/04/2022.
- Marketplace foi o modelo de negócio assumido.
- As três principais visões do negócio foram:
  - Visão transação de pedidos
  - Visão restaurante
  - Visão entregadores

## Estratégia da Solução

O painel estratégico foi desenvolvido utilizando as métricas que refletem as três principais visões do modelo de negócio da empresa:

1. **Visão do Crescimento da Empresa**
   - Pedidos por dia
   - Porcentagem de pedidos por condições de trânsito
   - Quantidade de pedidos por tipo e por cidade
   - Pedidos por semana
   - Quantidade de pedidos por tipo de entrega
   - Quantidade de pedidos por condições de trânsito e tipo de cidade

2. **Visão do Crescimento dos Restaurantes**
   - Quantidade de pedidos únicos
   - Distância média percorrida
   - Tempo médio de entrega durante festival e dias normais
   - Desvio padrão do tempo de entrega durante festivais e dias normais
   - Tempo de entrega médio por cidade
   - Distribuição do tempo médio de entrega por cidade
   - Tempo médio de entrega por tipo de pedido

3. **Visão do Crescimento dos Entregadores**
   - Idade do entregador mais velho e do mais novo
   - Avaliação do melhor e do pior veículo
   - Avaliação média por entregador
   - Avaliação média por condições de trânsito
   - Avaliação média por condições climáticas
   - Tempo médio do entregador mais rápido
   - Tempo médio do entregador mais rápido por cidade

## Top 3 Insights de Dados

1. A sazonalidade da quantidade de pedidos é diária.
2. Há uma variação de aproximadamente 10% do número de pedidos em dias sequenciais.
3. As cidades do tipo Semi-Urban não possuem condições baixas de trânsito.
4. As maiores variações no tempo de entrega acontecem durante o clima ensolarado.

## Conclusão

O objetivo desse projeto é criar um conjunto de gráficos e tabelas que exibam essas métricas da melhor forma possível para o CEO. Da visão da Empresa, podemos concluir que o número de pedidos cresceu entre a semana 06 e a semana 13 do ano de 2022.

## Próximos Passos

- Reduzir o número de métricas.
- Criar novos filtros.
- Adicionar novas visões de negócio.

## ✒️ Autor

* **José Carlos Carneiro** - *Desenvolvimento Inicial*

## Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes

## Contato

Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato: 🚀
- LinkedIn: [José Carlos Carneiro]https://www.linkedin.com/in/josé-carlos-carneiro/


