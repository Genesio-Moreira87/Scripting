# Scripting

Antes de começar

Faça login na sua conta da Google. Acesse o **Google Colab** e faça o download do arquivo notebook “Profissão Analista de dados M9 Material de apoio”. 

# Nesta tarefa, iremos praticar 3 exercícios. 

Prepare o ambiente

Para realizar essa atividade você vai precisar ter instalados em sua máquina o Python (versão 3.x) e o PIP. Além disso, deve instalar os seguintes pacotes:

pip install pandas==1.2.4 seaborn==0.11.1 requests==2.25.1

# 1º Exercício: Script de extração

O script para extrair a taxa CDI do site da B3 foi adaptado para ser executado 10 vezes para gerar nossa base de dados. Na sua máquina, crie o arquivo extracao.py com o script indicado no material de apoio e execute-o com o comando indicado.

No final, você deve ter o arquivo taxa-cdi.csv com os dados extraídos.

- a. Crie a variável data e hora

- b. Capte a taxa CDI do site da B3

- c. Verifique se o arquivo "taxa-cdi.csv" existe

- d. Salve dados no arquivo "taxa-cdi.csv"

# 2º Exercício: Script de visualização

O script para gerar um gráfico da taxa CDI do site da B3 foi adaptado para utilizar o pacote Pandas. Então, na sua máquina, crie o arquivo visualizacao.py com o script abaixo e execute-o com o comando indicado.

O script espera um parâmetro de entrada com o nome do gráfico, portanto substitua o nome-do-grafico pelo nome do seu gráfico. No final, você deve ter uma imagem no formato png com o nome passado via parâmetro contendo a visualização dos dados gerados pelo script de extração.

- a. Extraia as colunas hora e taxa

- b. Salve o gráfico

# 3º Exercício: Scripts de extração e visualização

- a. Combine os scripts visualizacao.py e extracao.py no arquivo analise.py e execute-o na sua máquina.

Ele deve retornar os mesmos resultados:

o arquivo csv;
a imagem no formato png com o título escolhido via parâmetro de entrada.
Procure seguir a organização proposta na aula (PEP8).

Além disso, copie o código na célula indicada e tire os prints da tela executando o script na máquina como evidência para que a tutoria possa avaliar sua atividade.

## Autor: Genésio Moreira Coutinho 
- Graduado: Bacharelado em Sistemas de Informação | Pós Graduando:  MBA em Gestão da Qualidade em Tecnologia da Informação |Analista de Dados| 1x Azure - AZ900
- Date Analyst | Cloud Infrastructure | Azure | Analista Cloud | Analista Dados | Infraestrutura Cloud | Python
- Linkedin: https://www.linkedin.com/in/genesio-coutinho-554733124/
- Kaggle:https://www.kaggle.com/genesiomoreira

- Notebook para execução dos códigos Google Collab:https://colab.research.google.com/drive/1X9XdwQPMYFSaGLmcRxe8igcVVoAzlAtE?usp=sharing#scrollTo=sdyhEmiW5MhZ
