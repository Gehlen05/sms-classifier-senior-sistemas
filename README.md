
# SMS Classifier

## Objetivo
    Este projeto consiste em construir gráfico para analisar os dados disponíveis como entrada e desenvolver um modelo para classificar os sms como comun ou spam.

## Pré-requesitos de Execução
    Este projeto foi desenvolvido no coolab. Para executá-lo é necessário apenas clicar no "OPEN IN COLAB" no projeto. 
    Também é necessário que o arquivo csv esteja dentro do drive na pasta Colab Notebooks junto com o projeto.
    Caso não exista a pasta é só criar uma com o nome Colab Notebooks.
    Ele pedirá liberação para se conectar ao drive é necessário autorizar.

    
### Jupyter
    Para executar no Jupyter será necessário baixar o projeto e instalar algumas dependêcias e alterar o caminho de 
    entrada no projeto.
    
-   **df = pd.read_csv('sms_senior.csv')**
-   **pip install numpy**
-   **pip install wordcloud**
-   **pip install Pandas**
-   **pip install -U scikit-learn**
-   **pip install Matplotlib**
-   **pip install Counter**
-   **pip install statistics**


## Resultados
    O projeto foi separado em duas etapas, a de análise das estátisticas e desenvolvimento dos modelos de classificação.

**Estátisticas**
   
    É o projeto sms_classifier_estatisticas_senior_sistemas que gerará os gráficos.


**Classificação**
   
    Foram implementados dois projetos de classificação  o script 
    sms_classifier_regressao_logistica_floresta_decisao_token_senior_sistemas e o 
    sms_classifier_rede_neural_token_senior_sistemas.
    


