# Otimização de Modelos de Classificação

## Descrição  
Este repositório apresenta a construção e otimização de modelos de **classificação** utilizando técnicas modernas de **machine learning**. Esse segmento aborda desde a criação dos modelos iniciais até estratégias avançadas de ajuste de hiperparâmetros, com foco em encontrar o melhor desempenho para diferentes algoritmos.

## Objetivos Alcançados  
- Treinamento e avaliação de modelos iniciais de classificação.
- Compreensão de parâmetros e hiperparâmetros em modelos supervisionados.
- Aplicação de técnicas de otimização como **Grid Search**, **Random Search** e **Otimização Bayesiana**.
- Uso de **validação cruzada aninhada** para melhorar a seleção de modelos.
- Comparação entre diferentes algoritmos: Decision Tree, Logistic Regression e KNN.
- Interpretação e análise dos melhores resultados obtidos durante os testes.

## Tecnologias Utilizadas  
- **Python**  
- **scikit-learn** – para construção e avaliação de modelos.  
- **pandas & numpy** – para manipulação e análise de dados.  
- **scikit-optimize (skopt)** – para otimização bayesiana.  
- **Jupyter Notebook** – para experimentação e visualização.

## Estrutura da Seção  

1. **Modelos Iniciais**  
   - Leitura e análise exploratória dos dados.  
   - Treinamento dos modelos base: Decision Tree e Regressão Logística.  
   - Introdução aos conceitos de Recall, parâmetros e hiperparâmetros.  

2. **Busca em Grade (Grid Search)**  
   - Aplicação de `GridSearchCV` com validação cruzada.  
   - Avaliação dos melhores hiperparâmetros para os modelos.  
   - Uso de `StratifiedKFold` para particionamento estratificado.  

3. **Validação Cruzada Aninhada**  
   - Diferenças entre validação simples e aninhada.  
   - Implementação da validação aninhada com `cross_val_score` e `GridSearchCV`.  

4. **Busca Aleatória (Random Search)**  
   - Comparação entre busca em grade e aleatória.  
   - Uso de `RandomizedSearchCV` para otimizar hiperparâmetros com menos custo computacional.  

5. **Otimização Bayesiana**  
   - Introdução à otimização bayesiana com `BayesSearchCV`.  
   - Aplicação prática em Decision Tree, Regressão Logística e KNN.  
   - Utilização de `skopt.space` para definição dos espaços de busca.  

## Conclusão  
Este repositório demonstra o processo de otimização de modelos de classificação de forma prática e eficiente. Através de diferentes técnicas de ajuste de hiperparâmetros e validação, é possível alcançar melhores desempenhos e fazer escolhas mais assertivas na seleção de modelos de machine learning.

---

# Classification Model Optimization

## Description  
This repository presents the development and optimization of **classification models** using modern **machine learning** techniques. The course covers everything from building initial models to advanced hyperparameter tuning strategies, focusing on achieving the best performance across different algorithms.

## Achieved Objectives  
- Training and evaluation of initial classification models.  
- Understanding parameters and hyperparameters in supervised models.  
- Applying optimization techniques such as **Grid Search**, **Random Search**, and **Bayesian Optimization**.  
- Using **nested cross-validation** to improve model selection.  
- Comparing different algorithms: Decision Tree, Logistic Regression, and KNN.  
- Interpreting and analyzing the best results obtained during experiments.

## Technologies Used  
- **Python**  
- **scikit-learn** – for model building and evaluation.  
- **pandas & numpy** – for data manipulation and analysis.  
- **scikit-optimize (skopt)** – for Bayesian optimization.  
- **Jupyter Notebook** – for experimentation and visualization.

## Section Structure  

1. **Initial Models**  
   - Reading and exploring the dataset.  
   - Training baseline models: Decision Tree and Logistic Regression.  
   - Introduction to Recall, parameters, and hyperparameters.

2. **Grid Search**  
   - Applying `GridSearchCV` with cross-validation.  
   - Evaluating the best hyperparameters for each model.  
   - Using `StratifiedKFold` for stratified data splits.

3. **Nested Cross-Validation**  
   - Differences between standard and nested validation.  
   - Implementing nested validation with `cross_val_score` and `GridSearchCV`.

4. **Random Search**  
   - Comparing grid and random search strategies.  
   - Using `RandomizedSearchCV` to optimize with reduced computational cost.

5. **Bayesian Optimization**  
   - Introduction to Bayesian optimization with `BayesSearchCV`.  
   - Practical application on Decision Tree, Logistic Regression, and KNN.  
   - Using `skopt.space` to define search spaces.

## Conclusion  
This repository demonstrates the process of classification model optimization in a practical and efficient way. By leveraging different hyperparameter tuning and validation strategies, we can achieve better results and make more informed choices in machine learning model selection.