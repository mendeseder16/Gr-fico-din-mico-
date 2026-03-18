# Gr-fico-din-mico-

Gráfico Dinâmico de "Análise por Dimensão"
Em vez de ter vários gráficos fixos, você cria um único visual onde o usuário escolhe o que quer ver no eixo X.

O que fazer: Vá em Modelagem > Novo Parâmetro > Campos. Selecione as colunas Segment, Country e Product.

O Visual: Use um Gráfico de Colunas Agrupadas. Arraste o parâmetro criado para o eixo X.

Resultado: O usuário terá um filtro (slicer) para alternar o gráfico inteiro entre "Vendas por Segmento", "Vendas por País" ou "Vendas por Produto".

2. Seletor de Métricas Dinâmicas (KPI Switcher)
Altere todos os visuais para mostrar Vendas, Lucro ou Unidades Vendidas simultaneamente.

O que fazer: Crie um novo parâmetro de campos e selecione suas medidas principais: Total Sales, Total Profit e Total Units Sold.

O Visual: Aplique este parâmetro no campo de Valores (Eixo Y) do seu gráfico de linha (Total Sales Trend by Date).

Resultado: Ao clicar no filtro de "Lucro", o gráfico de linha que hoje mostra vendas mudará automaticamente para mostrar a tendência de lucro mensal
