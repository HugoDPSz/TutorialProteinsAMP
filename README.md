# Protein Sequences Classification using AMP Dataset

Este projeto é uma implementação e adaptação de um tutorial para classificação de sequências de proteínas, com foco em peptídeos antimicrobianos (AMPs). O objetivo é treinar um modelo de aprendizado profundo capaz de distinguir entre sequências AMP e não-AMP.

## 🔍 Visão Geral

O notebook `tutorials_proteins_amp.ipynb` conduz as etapas de pré-processamento de dados, construção do modelo, treinamento, avaliação e visualização de resultados. Ele utiliza uma abordagem baseada em modelos de linguagem (transformers) para tarefas de classificação binária em sequências proteicas.

## 🧪 Tecnologias e Bibliotecas Utilizadas

- Python 3.11 (Colab)
- PyTorch
- HuggingFace Transformers
- Pandas, NumPy, Matplotlib
- scikit-learn
- tqdm

## 📁 Estrutura do Projeto

- `tutorials_proteins_amp.ipynb`: notebook principal com toda a pipeline do projeto.
- Dataset de peptídeos antimicrobianos (AMP) carregado via HuggingFace Datasets ou similar.

## 🚀 Etapas do Notebook

1. **Importação de bibliotecas**
2. **Carregamento e visualização dos dados**
3. **Tokenização e preparação das sequências proteicas**
4. **Divisão em treino, validação e teste**
5. **Criação do modelo com `AutoModelForSequenceClassification`**
6. **Treinamento com `Trainer`**
7. **Avaliação usando métricas como accuracy, precision, recall e F1**
8. **Visualizações (ex: matriz de confusão)**

## ⚙️ Como Executar

1. Acesse o notebook no Google Colab.
2. Instale as dependências necessárias com `pip install transformers datasets scikit-learn`.
3. Execute as células sequencialmente.

> Obs.: O código foi adaptado para evitar warnings relacionados ao uso de métodos obsoletos, como `DataFrame.append()`.

## 📝 Créditos

Baseado em tutoriais da HuggingFace e materiais educacionais de bioinformática com aprendizado de máquina. Customizações feitas por [Seu Nome Aqui].

## 📜 Licença

Este projeto é de uso educacional. Verifique a licença do tutorial original, se aplicável.
