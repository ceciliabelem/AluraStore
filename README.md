# Análise de Desempenho das Lojas - Recomendação para Venda

## Introdução

Este projeto realiza uma análise detalhada do desempenho de quatro lojas (Loja 1, Loja 2, Loja 3 e Loja 4) com o objetivo de fornecer uma recomendação ao Senhor João sobre qual loja seria a mais adequada para venda. A análise considera diversas métricas-chave para avaliar a performance de cada unidade.

## Objetivos

Os principais objetivos deste projeto são:

*   Analisar métricas financeiras, de produtos e de satisfação do cliente para cada loja.
*   Comparar o desempenho das quatro lojas com base nas métricas analisadas.
*   Gerar visualizações (gráficos e mapas) para facilitar a compreensão dos dados e dos resultados.
*   Elaborar uma recomendação clara e justificada sobre qual loja o Senhor João deve vender.

## Dados

Os dados utilizados nesta análise foram fornecidos em formato CSV e contêm informações sobre as vendas de cada uma das quatro lojas, incluindo:

*   Produto
*   Categoria do Produto
*   Preço
*   Frete
*   Data da Compra
*   Vendedor
*   Local da compra
*   Avaliação da compra
*   Tipo de pagamento
*   Quantidade de parcelas
*   Latitude (`lat`)
*   Longitude (`lon`)

## Análises Realizadas

As seguintes análises foram conduzidas para cada loja e comparadas entre elas:

*   **Faturamento Total:** Cálculo da receita total gerada por cada loja (Preço do produto + Frete).
*   **Vendas por Categoria:** Identificação das categorias de produtos mais vendidas em cada loja.
*   **Média de Avaliação dos Clientes:** Análise da satisfação geral dos clientes com base nas avaliações.
*   **Produtos Mais e Menos Vendidos:** Identificação dos produtos individuais com maior e menor volume de vendas.
*   **Frete Médio:** Cálculo do custo médio do frete por loja.
*   **Análise de Desempenho Geográfico:** Visualização da distribuição geográfica das vendas para entender as áreas de atuação de cada loja e possíveis sobreposições.

## Visualizações

Diversos gráficos e visualizações foram gerados para auxiliar na compreensão dos dados, incluindo:

*   Gráfico de Linha (ou Barras) comparando o faturamento total por loja.
*   Gráfico de Dispersão (ou Barras) da média de avaliação por loja.
*   Gráficos de Barras Horizontais para os produtos mais e menos vendidos (Top N e Bottom N) por loja.
*   Mapa Interativo (Folium) exibindo a distribuição geográfica das vendas de todas as lojas.

## Recomendação Final

Com base na análise aprofundada das métricas e visualizações, foi possível fazer a recomendação para o cliente fictício.

## Como Executar o Projeto

Para replicar esta análise, siga os passos abaixo:

1.  Certifique-se de ter o Python instalado.
2.  Instale as bibliotecas necessárias:
Use code with caution
bash pip install pandas matplotlib folium==0.14.0

3.  Faça o download dos arquivos CSV das lojas.
4.  Abra o notebook [Nome do Seu Notebook].ipynb no Google Colab ou em um ambiente Jupyter Notebook.
5.  Execute as células do notebook sequencialmente.

## Conclusão

Este projeto ofereceu insights valiosos sobre o desempenho das quatro lojas, permitindo uma recomendação informada para o Senhor João, o cliente fictício. A análise destacou as áreas de sucesso e os desafios de cada unidade, fornecendo uma base sólida para a decisão de venda.

## Autor(es)

Cecília Belém