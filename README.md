# Analise_Pandas
# Análise de Dados em Pandas 
Esse projeto tem como foco fazer uma análise de dados utilizando a linguagem Python para a filtragem dos dados e a bibloteca Seaborn para a parte gráfica do projeto.

# Tabelas
O projeto contém 5 arquivos .csv com dados utilizados da plataforma Alura. Para poder testar os códigos é necessário que faça o download desses arquivos.

# Divisão do Projeto
Os arquivos que possuem código de análise estão divididos, no começo tem toda a parte dos códigos para fazer as filtragens dos dados e no final estão todos os resultados finais incluindo os gráficos.

# Execução do Projeto
Para testar o projeto é necessário acessar o Google Colaboratory, baixar os arquivos .csv, e colocar o caminho dos arquivos de dados no arquivo de análise:
from google.colab import drive
drive.mount('/content/drive')
import numpy as np
import pandas as pd
clientes = pd.read_csv('caminho do arquivo de dados de clientes', sep=';',  encoding='utf-8')
produtos =  pd.read_csv('caminho do arquivo de dados de produtos', sep=';',  encoding='utf-8')
vendedores =  pd.read_csv('caminho do arquivo de dados de vendedores', sep=';',  encoding='utf-8')
itens_notas_fiscais =  pd.read_csv('caminho do arquivo de dados de itens_notas_fiscais', sep=',',  encoding='utf-8')
notas_fiscais =  pd.read_csv('caminho do arquivo de dados de notas_fiscais', sep=',',  encoding='utf-8')
