# Machine Learning e Data Science com Python
Arquivos do curso de Data Science e Machine Learning com Python na Udemy, [clique aqui](https://www.udemy.com/course/machine-learning-e-data-science-com-python-y/?src=sac&kw=Machine+Learning+e+Data+Science+com+Python+de+A+à+Z) para acessá-lo. Estou com 80% do curso concluída.

<img width="1796" alt="dfddf" src="https://user-images.githubusercontent.com/97196457/151352851-1d298d4e-f8a0-42f6-86b6-a7ae2e17c8de.png">

## O curso é dividido em cinco grandes partes:
- Parte 1 - **Classificação**
    - Pré-processamento dos dados: visualização dos dados, tratamento da base de dados, divisão entre previsores e classe, escalonamento dos atributos, LabelEncoder e OneHotEncode;
    - Aprendizagem bayesiana;
    - Aprendizagem por árvores de decisão;
    - Aprendizagem baseada em instâncias;
    - Regressão logística;
    - Máquinas de vetores de suporte (SVM);
    - Redes neurais artificiais;
    - Avaliação de algoritmos de classificação;
    - Combinação e rejeição de classificadores.
- Parte 2 - **Regressão**
    - Regressão linear e Múltipla;
    - Regressão polinomial;
    - Regressão com árvores de decisão;
    - Regressão com random forest;
    - Regressão com vetores de suporte;
    - Regressão com redes neurais.
- Parte 3 - **Regras de Associação**
    - Algoritmo apriori;
    - Algoritmo ECLAT.
- Parte 4 - **Agrupamento (clustering)**
    - Agrupamento com k-means;
    - Agrupamento hierárquico;
    - DBSCAN.
- Parte 5 - **Tópicos Complementares**
    - Aprendizagem por reforço com Q-Learning;
    - Processamento de Linguagem Natural com spaCy e NLTK;
    - Visão computacional;
    - Tratamento de dados desbalanceados;
    - Seleção de atributos;
    - Redução de dimensinalidade;
    - Detecção de outliers;
    - Séries temporais.
## Base de dados utilizadas
### Credit Data
É uma base de dados histórica no qual nos fornece a renda (income), idade (age) e dívida (loan) de 2000 pessoas, junto com a informação se pagaria ou não o empréstimo (default). O objetivo aqui era treinar o algoritmo para prever se a pessoa pagaria ou não o empréstimo. Essa foi uma base de dados com valores faltantes (3 registros) e inconsistentes (3 registros) que precisaram ser tratados. A base usada foi adaptada [deste link](https://www.kaggle.com/laotse/credit-risk-dataset).

<img width="1396" alt="base credit" src="https://user-images.githubusercontent.com/97196457/155520655-05c03edc-babc-4e3e-949a-39d98ae39d71.png">

### Census
Uma base de dados no qual fornece informações sobre cada pessoa (idade, trabalho, educação, ocupação, relacionamento, raça...) com 32562 registros, junto com a informação se a renda anual seria >50K ou <50K de dólares. O objetivo aqui era prever a renda da pessoa com base em algumas informações/características sobre a pessoa. Ela pode ser encontrada [clicando aqui](https://archive.ics.uci.edu/ml/datasets/adult).

<img width="1396" alt="base census" src="https://user-images.githubusercontent.com/97196457/155520775-52799267-6c5a-4b2d-a4d9-372cfa4b51e6.png">

## Resultados Obtidos (Accuracy)
| Algoritmo | Credit Data | Census |
|-----------|-------------|--------|
|Naïve Bayes| 93,8% | 47,6% |
|Árvores de decisão| 98,2% | 81,0% |
|Random Forest| 98,6% | 85,0% |
|Regras| 97,4% | 78,9% |
|Majority learner| 85,8% | 75,9% |
|KNN| 98,6% | 82,9% |
|Regressão logística| 94,6% | 84,9% |
|SVM| 98,8% | 85,0% |
|Redes Neurais| 99,8% | 81,7% |

Em construção...
