#  📊 Projeto de Análise de Vendas: Dataset Coffee Sale
 

Este projeto tem como objetivo estudar e praticar técnicas de análise de dados utilizando o dataset **Coffee Sales**, disponível no Kaggle.

# DataSet
O DataSet utilizado para o projeto foi [Coffee Sales](https://www.kaggle.com/datasets/ihelon/coffee-sales/data)


## 🧠 Objetivos
- Identificar padrões nos métodos de pagamento utilizados.
- Calcular a média de gasto por método de pagamento.
- Determinar os produtos mais rentáveis e os mais vendidos.
- Descobrir os horários com maior volume de faturamento.
- Analisar o faturamento por dia da semana (mês de março).
- Comparar o faturamento do mês entre diferentes anos.


## 🛠️ Ferramentas Usadas
- Python
- Pandas
- Matplotlib & Seaborn
- Jupyter Notebook
- Git & GitHub









## 📌 Insights & Learnings

### 💸 Métodos de Pagamento

![Métodos de Pagamento](https://github.com/Czaarx/analise-dados-coffee_Sales/blob/main/graficos/Preferencia%20de%20Pagamento.png?raw=true) 

![Mediana Métodos de Pagamento](https://github.com/Czaarx/analise-dados-coffee_Sales/blob/main/graficos/mediana%20por%20tipo%20de%20pagamento.png?raw=true)


Baseado nos gráficos acima, é possivel ver que:

 - **Cartão** - É o método de pagamento mais utilizado, representando a maior parte das transações. Os valores estão mais próximos da mediana, indicando compras padronizadas, sem ocorrência frequente de valores extremamente altos ou muito baixos. 

 - **Dinheiro** - Apesar de ter uma participação significativamente menor nas transações, apresenta maior dispersão nos valores. Isso indica que, embora seja utilizado com menor frequência, é escolhido para compras pontuais que, em alguns casos, possuem valores elevados, aumentando a variação e distanciando parte das transações da mediana.

---

### Produtos mais Vendidos e Rentáveis

![Produtos Mais Vendidos](https://github.com/Czaarx/analise-dados-coffee_Sales/blob/main/graficos/10%20cafes%20mais%20vendidos.png?raw=true)
![Produtos Mais Rentáveis](https://github.com/Czaarx/analise-dados-coffee_Sales/blob/main/graficos/cafes%20mais%20rentaveis.png?raw=true)

Os gráficos acima revelam uma distinção importante entre volume de vendas e rentabilidade dos produtos da cafeteria.

O Americano With Milk é o café mais vendido, refletindo forte preferência dos clientes. No entanto, o Latte se destaca como o produto mais rentável, indicando que, apesar de vender menos, gera maior lucro por unidade.

Essa diferença sugere oportunidades estratégicas, como promover produtos de maior margem ou ajustar preços para equilibrar volume e rentabilidade.




---


### 🕛 Faturamento por Horário

![Faturamento por Horário](https://github.com/Czaarx/analise-dados-coffee_Sales/blob/main/graficos/faturamento%20por%20hora.png?raw=true)

Observando o gráfico de faturamento por horário de 2024 e 2025, notamos uma tendência de crescimento a partir das 6:00 horas, tornando-se mais acentuada entre as 8:00 horas e as 10:00 horas, onde é alcançado seu pico com o faturamento de R$12.000. Após isso, notamos uma leve queda, com variações no período da tarde.

Baseado nessa informação podemos:

- Utilizar esse período onde ocorre a crescente para aplicar estratégias que impulsionem as vendas. 
- Nos momentos de oscilação, podemos também procurar entender o público com o qual estamos lidando, a fim de alavancar o faturamento dentro desses horários.


---
### Faturamento por dia da semana (Apenas Mês de Março)
![Faturamento por dia da semana](https://github.com/Czaarx/analise-dados-coffee_Sales/blob/main/graficos/faturamento%20dia%20da%20semana.png?raw=true)


### Faturamento de Março 2024 x 2025
![Mediana Métodos de Pagamento](https://github.com/Czaarx/analise-dados-coffee_Sales/blob/main/graficos/faturamento%20mes.png?raw=true)

Ao comparar o faturamento do Mês de Março entre os anos de 2024 e 2025, podemos notar que houve uma queda de 16,67%, passando de aproximadamente R$12.000 para R$10.000.

 Embora as segundas e Quartas do mês tenham apresentado um valor superior em 2025, os domingos, terças e sabados apresentam quedas significativas impactando o resultado geral do mês.

---

### 📘 Conclusão

Como meu primeiro projeto após a Imersão Alura de Análise de Dados com Python, consegui relevar padrões que fazendo sentido e podem orientar decisões estratégias em ambientes cormerciais. 

A partir do dataset Coffee Sales, foi possível identificar oportunidades de otimização em horários, produtos e métodos de pagamento. 

O uso de ferramentas como Python, Pandas e Seaborn permitiu uma visualização clara e objetiva dos dados, tornando o processo analítico mais acessível e eficaz.
