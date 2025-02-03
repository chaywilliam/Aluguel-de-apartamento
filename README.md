# Aluguel-de-apartamento
Este repositório contém um script Python para analisar dados de aluguel de imóveis, utilizando as bibliotecas Pandas para manipulação de dados e Seaborn para visualização. 
O código realiza diversas operações, desde a leitura e limpeza dos dados até a criação de gráficos para melhor compreensão das informações.

Arquivos
houses_rent.xlsx: Arquivo Excel contendo os dados de aluguel de imóveis.
analise_aluguel_imoveis.ipynb: Notebook Jupyter com o código Python comentado.
README.md: Este arquivo, contendo a descrição do projeto e instruções de uso.
Dependências
Para executar o código, é necessário ter as seguintes bibliotecas instaladas:

pandas
seaborn
openpyxl (para leitura de arquivos .xlsx)
Você pode instalar as dependências usando o pip:

Bash

pip install pandas seaborn openpyxl
Como usar
Clone este repositório:
Bash

git clone https://[endereço-do-repositório].git
Abra o notebook Jupyter analise_aluguel_imoveis.ipynb em seu ambiente local.

Certifique-se de que o arquivo houses_rent.xlsx esteja no mesmo diretório que o notebook.

Execute as células do notebook para realizar a análise e gerar os gráficos.

Descrição do código
O código realiza as seguintes operações:

Leitura e visualização inicial dos dados:

Lê o arquivo Excel houses_rent.xlsx utilizando o Pandas.
Exibe as primeiras e últimas linhas do DataFrame para inspeção inicial.
Limpeza e tratamento dos dados:

Renomeia colunas para um formato mais adequado (sem espaços).
Converte colunas de preço para o tipo numérico float.
Análise exploratória dos dados:

Exibe informações sobre o DataFrame (info()) e estatísticas descritivas (describe()).
Filtra os dados com base em critérios como preço total, aceitação de animais e número de quartos.
Agrupamento e agregação de dados:

Agrupa os dados por cidade e calcula a média do preço total.
Agrupa os dados por número de banheiros e quartos, calculando a média do preço total.
Visualização dos dados:

Cria gráficos de barras para visualizar a relação entre número de quartos/banheiros e preço.
Cria histogramas para visualizar a distribuição da área e do preço total.
Cria um histograma do preço total, com cores diferentes para cada cidade.
Cria um gráfico de barras para visualizar a média do preço por andar.
Resultados
Ao executar o código, serão gerados DataFrames com dados filtrados e agregados, além de gráficos que permitem visualizar as relações entre as variáveis. 
Os principais resultados incluem:

DataFrame com a média do preço total por cidade.
DataFrame com a média do preço total por número de banheiros e quartos.
Gráficos mostrando a relação entre número de quartos/banheiros e preço.
Histograma da distribuição da área dos imóveis.
Histograma da distribuição do preço total dos imóveis, separado por cidade.
Gráfico de barras mostrando a média do preço por andar.
Observações
Este código foi desenvolvido como um exemplo de análise exploratória de dados e pode ser adaptado para outras necessidades.
Certifique-se de que o arquivo houses_rent.xlsx esteja no formato correto e contenha as colunas esperadas.
Os gráficos gerados podem ser personalizados com mais opções do Seaborn.
Contato
Se você tiver alguma dúvida ou sugestão, entre em contato:

[Charles William]
[c_wasouza@outlook.com]

Sinta-se à vontade para modificar e adaptar este código para suas próprias análises!
