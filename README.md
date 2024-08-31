# Análise de Dados Meteorológicos

Este projeto analisa dados meteorológicos provenientes do arquivo `dados_inmet.csv`, calculando e visualizando a temperatura média mensal e a precipitação total mensal. Além disso, são calculadas e exibidas as estatísticas históricas da temperatura média, como média, mediana e moda.

## Estrutura do Projeto

- **`dados_inmet.csv`**: Arquivo CSV contendo os dados meteorológicos.
- **`dados_metereologicos.py`**: Script Python que realiza a análise dos dados e gera gráficos para visualização.

## Funcionalidades

1. **Leitura de Dados**:
   - O script lê os dados de temperatura máxima, temperatura mínima e precipitação total para cada data do arquivo CSV.

2. **Cálculo de Temperatura Média**:
   - A temperatura média diária é calculada como a média aritmética entre as temperaturas máxima e mínima.

3. **Cálculo de Precipitação Total**:
   - A precipitação total mensal é calculada somando-se os valores diários.

4. **Agrupamento de Dados Mensais**:
   - Os dados são agrupados por mês, permitindo calcular a temperatura média mensal e a precipitação total mensal.

5. **Visualização dos Dados**:
   - São gerados gráficos de barras que mostram a temperatura média mensal e a precipitação total mensal.
   - Outro gráfico de barras é criado para exibir as estatísticas históricas da temperatura (média, mediana e moda).

## Como Executar

1. Certifique-se de ter o Python instalado em sua máquina.

2. Instale as dependências necessárias:
   ```bash
   pip install pandas matplotlib
   
5. Os gráficos serão exibidos automaticamente após a execução.

## Resultados Esperados

- **Gráfico de Temperatura Média Mensal**: Exibe a temperatura média para cada mês.
- **Gráfico de Precipitação Total Mensal**: Mostra a precipitação total acumulada para cada mês.
- **Gráfico de Estatísticas Históricas da Temperatura**: Apresenta a média, mediana e moda da temperatura média mensal ao longo do período analisado.

## Personalizações

Você pode personalizar o script para incluir outras análises ou para utilizar dados diferentes, bastando adaptar a leitura e o processamento dos dados no código.

## Considerações Finais

Este projeto fornece uma visão clara e concisa dos dados meteorológicos, permitindo identificar padrões sazonais e anomalias climáticas ao longo do tempo.
