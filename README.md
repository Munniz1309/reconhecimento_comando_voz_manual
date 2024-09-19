# Descrição
Este projeto aplica técnicas de Machine Learning para classificar amostras de áudio de três categorias: LIGAR, FECHAR e ABRIR. Utilizamos a biblioteca Librosa para extrair características dos áudios como frequência, amplitude e tempo. Além disso, foi aplicado um modelo de One-vs-All com SVM para classificar e validação cruzada K-Fold e Grid Search para otimizar os hiperparâmetros do modelo e alcançar a melhor acurácia.

# Biblioteca
- Librosa: Para processamento e extração de características dos arquivos de áudio.
- Scikit-learn: Para os algoritmos de classificação e avaliação de desempenho.
- Imbalanced-learn (SMOTE): Para balanceamento de classes.
- Seaborn/Matplotlib: Para visualização dos dados e resultados.

# Dataset
Este projeto utiliza um conjunto de arquivos de áudio no formato .opus divididas em três categorias:

- LIGAR: 10 arquivos de áudio representando o comando "ligar".
- FECHAR: 10 arquivos de áudio representando o comando "fechar".
- ABRIR: 10 arquivos de áudio representando o comando "abrir".
