🛒 Projeto de Análise de Vendas — E-commerce Brasil
Este projeto tem como objetivo analisar dados de um e-commerce brasileiro, extraindo insights valiosos sobre pedidos, entregas, clientes, produtos, vendedores e avaliações.

📂 Estrutura dos Dados
O projeto utiliza os seguintes arquivos .csv:

01clientes.csv: informações dos clientes.

02localização.csv: dados de localização (não utilizado diretamente).

03itens.csv: itens comprados em cada pedido.

04ordem_pagamentos.csv: dados de pagamento (não utilizado diretamente).

05revisao_pedidos.csv: avaliações dos pedidos.

06ordem.csv: informações dos pedidos (data de compra, entrega, etc.).

07produtos.csv: produtos vendidos.

08vendedores.csv: dados dos vendedores.

09produto_categoria.csv: categorias de produtos.

▶️ Como Executar
🔧 Pré-requisitos
Você precisa do Python 3 instalado com os seguintes pacotes:

bash
Copiar
Editar
pip install pandas matplotlib seaborn
Se quiser criar dashboards interativos (opcional):

bash
Copiar
Editar
pip install plotly streamlit
📌 Executando o script principal
Baixe ou clone o repositório com os arquivos .csv e o script analise.py.

Execute o script no terminal ou em um notebook Jupyter:

bash
Copiar
Editar
python analise.py
📊 Resultados e Insights
1. 📈 Evolução das Vendas
O gráfico mostra o faturamento mensal.

É possível identificar sazonalidades e picos de vendas, úteis para planejamento de estoque e marketing.

2. 🗺️ Vendas por Estado
São destacados os estados com maior volume de vendas.

Ex: São Paulo (SP) e Rio de Janeiro (RJ) apresentam o maior faturamento.

3. ⏱️ Avaliação vs. Tempo de Entrega
Quanto maior o tempo de entrega, menor a avaliação.

Reforça a importância da logística na satisfação do cliente.

4. 🧑‍💼 Desempenho dos Vendedores
Foram identificados os 10 vendedores com maior faturamento.

Métricas como tempo médio de entrega e nota média de avaliação ajudam a definir padrões de qualidade.

5. 🔁 Clientes Recorrentes
A taxa de recorrência foi de 0%, indicando que praticamente todos os clientes compraram apenas uma vez.

Indica oportunidade para estratégias de fidelização.

6. 🚚 Previsão de Atraso
Um modelo simples de machine learning foi treinado para prever se um pedido será entregue com atraso.

A acurácia foi de ~92%, mas o modelo teve dificuldade em prever os atrasos (classe desbalanceada).

📌 Possíveis Expansões
Criar dashboards interativos com Plotly ou Streamlit.

Implementar análise geoespacial com mapas reais (usando GeoJSON).

Análise de churn e recomendação de produtos.

Melhorar modelo de previsão com balanceamento e novos algoritmos.

