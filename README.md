# Projeto de ETL: Dados de Clima

Este projeto tem como objetivo demonstrar um exemplo simples de um processo ETL (Extração, Transformação e Carregamento) de dados climáticos.
É uma opção que não utiliza IA.

### Objetivo
O objetivo deste projeto é extrair dados climáticos de um determinado período, em seguida, criar um gráfico para visualizar os dados.

### Passos do Projeto

1. **Extração de Dados:**
   - Você pode obter os dados climáticos de uma fonte confiável, como um arquivo CSV contendo informações de temperatura diária ou algum histórico. Os dados podem incluir datas e temperaturas.

2. **Transformação de Dados:**
   - Use a biblioteca `pandas` para ler o arquivo CSV e criar um DataFrame.
   - Converta os dados corretamente.
   - Extraia somente os dados necessários, nesse caso, foi extraído somente os dados climáticos de 2016.
   
3. **Carregamento de Dados Transformados:**
   - Você pode carregar os dados transformados em um novo arquivo CSV, que conterá somente os dados de 2016.
   
4. **Visualização de Dados:**
   - Use a biblioteca `matplotlib` para criar um gráfico para visualizar climas de determinados meses do ano de 2016.

### Arquivos no Projeto

- `monitoramento_tempo.csv`: O arquivo de entrada contendo os dados climáticos do período  de 2012-10-01 a 2017-11-30.
- `etl.ipynb`: O código Python que realiza o processo ETL, lendo o arquivo CSV, extraindo somente os dados de determinado período e gerando um novo arquivo CSV com os resultados e o gráfico.
- `grafico.png`: A imagem do gráfico gerado para visualizar a temperatura de determinado mês em comparação a temperatura do ano inteiro.

### Como Executar o Projeto

1. Certifique-se de ter o Python instalado em seu sistema.
2. Instale as bibliotecas necessárias executando `pip install pandas matplotlib`.
3. Coloque o arquivo `monitoramento_tempo.csv` na mesma pasta do arquivo `etl.ipynb`.
4. Execute o arquivo `etl.ipynb`.
5. Após a execução, você encontrará o arquivo `dados_transformados.csv` com as temperaturas de determinado mês e o arquivo `grafico.png` com o gráfico gerado.

### Conclusão

Este projeto de ETL de dados climáticos é um exemplo básico de como extrair informações de um arquivo CSV, transformá-las para obter insights e visualizar esses insights por meio de gráficos. Você pode estender este projeto ao lidar com mais fontes de dados, realizar transformações mais complexas e explorar diferentes tipos de visualizações.
