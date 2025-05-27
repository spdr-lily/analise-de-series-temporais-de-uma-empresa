## **Projeto de Análise de Séries Temporais**

### **1\. Objetivo**

O projeto tem como objetivo auxiliar uma empresa fictícia na previsão de suas vendas futuras, utilizando dados históricos de vendas mensais.

### **2\. Metodologia**

1. **Importação de Bibliotecas**: As bibliotecas `pandas`, `matplotlib.pyplot` e `numpy` foram importadas para manipulação de dados, geração de gráficos e operações numéricas, respectivamente.  
2. **Configuração do Ambiente**: O ambiente Colab foi configurado para exibir os gráficos inline, utilizando a diretiva `%matplotlib inline`.  
3. **Geração de Dados Fictícios**:  
   * Uma série temporal de 24 meses foi criada, com as datas variando de '2023-01-01' a '2024-12-31', utilizando a função `pd.date_range` com frequência mensal ('M').  
   * As vendas mensais foram geradas aleatoriamente entre 80.000 e 120.000 unidades, utilizando a função `np.random.randint`.  
4. **Criação do DataFrame**: Um DataFrame `df` foi criado para armazenar as datas e as vendas correspondentes.  
5. **Plotagem dos Dados**:  
   * Um gráfico de linha foi gerado para visualizar as vendas mensais ao longo do tempo.  
   * O gráfico inclui título ('Vendas Mensais da Empresa Fictícia'), rótulos para os eixos ('Data' para o eixo x e 'Vendas' para o eixo y) e uma grade para facilitar a leitura dos dados.

### **3\. Resultados**

O resultado principal do projeto é a visualização dos dados de vendas mensais em um gráfico de linha, permitindo uma análise inicial da tendência e variação das vendas ao longo do período de 24 meses.

### **4\. Conclusão**

Este estudo de caso demonstra um processo básico de geração e visualização de dados de séries temporais. Embora os dados sejam fictícios e gerados aleatoriamente, o código fornece um esqueleto para análise de dados reais de vendas. Para uma previsão mais precisa e útil para a tomada de decisões da empresa, seria necessário aplicar modelos de previsão de séries temporais mais avançados.
