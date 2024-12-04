# Projeto: Implementação e Análise do Algoritmo de K-means com o Dataset Human Activity Recognition

## Objetivo do Projeto

O objetivo deste projeto é implementar e avaliar o algoritmo de K-means usando o dataset **Human Activity Recognition Using Smartphones**. O objetivo principal é agrupar as atividades humanas (como caminhar, subir escadas, etc.) com base em dados de sensores de acelerômetro e giroscópio coletados de smartphones.

Este projeto inclui as etapas de análise exploratória dos dados, escolha do número ideal de clusters, aplicação do algoritmo de K-means, visualização dos resultados e avaliação das métricas de desempenho.

## Instruções para Executar o Código

1. Acesse o [repositório do projeto](https://github.com/AlexCamposDosSantos/Human_Activity_Recognition) e faça o download do arquivo Human_Activity_Recognition.ipynb`.</br></br>
2. Carregue o arquivo no Google Colab:
   - No Colab, clique em **Arquivo > Abrir Notebook > Upload > Procurar > selecione `Human_Activity_Recognition.ipynb`** .</br></br>
3. Certifique-se de que os dados necessários estejam disponíveis no Colab:
   - Você pode usar a integração com o Google Drive para carregar os dados:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```
   - Certifique-se de realizar upload no drive dos arquivos: X_train.txt, subject_train.txt, y_train.txt.

## Principais Conclusões e Considerações sobre os Resultados

- O algoritmo K-means foi capaz de identificar padrões de atividades humanas a partir dos dados dos sensores.
- A escolha do número ideal de clusters foi realizada utilizando o método cotovelo e o silhouette score.
- A redução da dimensionalidade dos dados utilizando PCA facilitou a visualização dos clusters e a análise dos resultados.
- A avaliação das métricas de inércia e silhouette score indicou a coesão e separação dos clusters, proporcionando insights sobre as atividades diárias.

  ## Autores e Colaboradores
  
  Grupo 62:
  Alex Reginaldo Abreu Campos dos Santos
  Sara Sacramento de Mello
