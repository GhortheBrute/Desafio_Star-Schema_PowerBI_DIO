
# Desafio Star-Schema Power BI - DIO

Projeto para o Desafio de criar um modelo Star-Schema em Power BI, utilizando o modelo de exemplo "financials" como base.




## Processo de Criação
Conforme instruído no desafio, foram criadas planilhas com base na planilha de exemplo original "financials" do próprio Power BI.

D_Produtos: Duplicada de financials e agregada por produtos, trazendo Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda e um índice como ID_Produto.

D_Produto_Detalhe: Duplicada de financials, possui apenas dados de venda dos produtos, sem agregação, com a coluna ID_Produto mesclada da tabela D_Produtos.