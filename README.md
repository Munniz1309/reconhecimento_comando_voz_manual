# Reconhecimento de Comando de Voz Manual

## Descrição do Projeto

Este projeto foca no desenvolvimento de um sistema de **Reconhecimento de Comando de Voz** implementado manualmente, sem o uso de bibliotecas prontas para a suavização ou extração de características. O objetivo é reconhecer comandos de voz a partir de amostras de áudio, processando os sinais e extraindo suas características de forma manual, com foco na compreensão e controle dos algoritmos utilizados. O projeto também incorpora técnicas de **suavização** do sinal para melhorar o reconhecimento e reduzir ruídos.

## Funcionalidades

- **Pré-processamento de Áudio Manual**: Implementação manual de filtros e normalização do sinal.
- **Extração de Características**: Extração de **MFCCs** e outras características importantes para o reconhecimento de comandos de voz.
- **Suavização de Sinais**: Aplicação de técnicas manuais para suavização de ruídos no sinal de entrada.
- **Classificação de Comandos de Voz**: Implementação de algoritmos de machine learning para classificar os comandos de voz.
- **Avaliação de Desempenho**: Análise dos resultados do reconhecimento de voz através de métricas como **Acurácia**, **Precisão**, **Recall** e **F1 Score**.

## Requisitos

Para executar este projeto, são necessárias as seguintes dependências:

- `Python 3.x`
- `numpy`
- `matplotlib`
- `scipy`
- `librosa` (opcional, para comparação de métodos)

## Descrição da Base de Dados

A base de dados utilizada no projeto contém amostras de áudio com diferentes comandos de voz. As amostras são pré-processadas manualmente e organizadas para extrair características relevantes, como **MFCCs**.

### Características da Base de Dados:

- **Áudio**: Amostras de áudio de comandos de voz (10 arquivos de áudio representando o comando "ligar", 10 arquivos de áudio representando o comando "fechar", 10 arquivos de áudio representando o comando "abrir").
- **Classes de Comandos**: Cada amostra é rotulada com o comando correspondente.
- **Extração Manual de Features**: As características do áudio, como **MFCCs**, são extraídas sem o uso de funções prontas, garantindo controle total sobre o processo de extração.

## Resultados

Os resultados mostram que o reconhecimento de comandos de voz manual pode atingir alta acurácia quando técnicas adequadas de pré-processamento e suavização de sinais são aplicadas. Com a implementação manual, é possível controlar cada aspecto do pipeline, resultando em um sistema robusto e ajustável.

### Principais Métricas:

- **Acurácia**: Percentual de acertos das predições.
- **Precisão**: Razão entre verdadeiros positivos e todos os positivos previstos.
- **Recall**: Razão entre verdadeiros positivos e todos os positivos reais.
- **F1 Score**: Média harmônica entre precisão e recall.

## Contato

Se você tiver dúvidas ou sugestões, entre em contato por [vitor13muniz09@gmail.com](mailto:vitor13muniz09@gmail.com).
