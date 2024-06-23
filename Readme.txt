Integrantes:
- Ana Clara das Neves Barreto - 13672540
- Eloisa Antero Guisse - 13781924
- Marcos Martins de Oliveira Pacheco - 13672602
- Jamyle Gonçalves Rodrigues Silva - 13672338
- Lucca Pinto - 13781991 
- Sarah Klock Mauricio - 13673131

Descrição de cada arquivo:

- ep_ia_mlp.ipynb: contém o notebook com a implementação do MLP de fato.

- analises.ipynb: contém o notebook com gráficos gerados para análise do MLP.

- pesos_salvos.txt: contém um JSON que pode ser usado pelo método build_mlp() para construir as camadas 
  de um MLP sem a necessidade de treiná-lo novamente, junto com a lista de erros de treinamento e validação 
  por época registrados no treinamento do modelo e o conjunto de dados de teste que não foram usados no 
  treinamento.

- X.txt: contém os dados de entrada que usamos para treinar e testar o modelo.

- Y_letra.txt: contém as classes dos dados de entrada.

- csvs: pasta que contém arquivos .csv gerados para a construção dos gráficos de análise.

  - grid_search_results.csv: arquivo com a saída do primeiro grid search, que testou diversas combinações
    de hiperparâmetros e retornou a acurácia, erro médio, desvio padrão do erro e lista de erros de treinamento
    e validação por época de todos os modelos testados. 
  - com_dois.csv: arquivo com os dados de um treinamento do MLP com a implementação da inicialização Xavier e momentum.
  - com_momentum.csv: arquivo com os dados de um treinamento do MLP sem a inicialização Xavier, mas com momentum.
  - com_xavier.csv: arquivo com os dados de um treinamento do MLP com a inicialização Xavier, mas sem momentum.
  - sem_nada.csv: arquivo com os dados de um treinamento do MLP sem inicialização Xavier e sem momentum.
  - learning_rates.csv: arquivo com a saída de diversos testes do MLP com taxas de aprendizado diferentes.
  - proporcao_conjunto_teste.csv: arquivo com a saída de diversos testes do MLP para proporções de conjunto de testes diferentes.

  
