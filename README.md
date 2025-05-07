# Ruido-MNIST

# 🧠 Classificação de Dígitos MNIST com Redes Neurais Artificiais e Ruído Gaussiano

## 📘 Descrição do Projeto

Este projeto implementa uma Rede Neural Artificial (MLP - Perceptron Multicamadas) para realizar a **classificação supervisionada de imagens** do dataset MNIST, que contém dígitos manuscritos de 0 a 9.

O foco principal é **avaliar a robustez do modelo** frente à **adição de ruído gaussiano nos dados de entrada**, simulando condições mais desafiadoras e realistas de inferência. O modelo é otimizado e avaliado com diferentes intensidades de ruído, variando o desvio padrão da distribuição gaussiana.

A solução inclui:

- Treinamento de RNA com múltiplas camadas ocultas
- Otimização de hiperparâmetros via `GridSearchCV` com `KerasClassifier`
- Aplicação de ruído gaussiano com diferentes intensidades
- Geração de métricas quantitativas (acurácia, f1-score, etc.)
- Visualizações gráficas para validação da robustez do modelo

---
## ▶️ Como Executar

1. **Arquivo .py:**

Baixe o arquivo .py no repositório e depois execute um notebook no Google Colab com o arquivo mencionado -> projeto1_pablohenrique_ia.py

## 🧰 Bibliotecas Utilizadas

Biblioteca -> Finalidade
tensorflow -> Construção e treinamento da RNA
scikeras ->	Wrapper do Keras para uso com GridSearchCV
scikit-learn -> 	Métricas, otimização e divisão dos dados
numpy ->	Manipulação de arrays e inserção de ruído
matplotlib ->	Geração de gráficos
seaborn ->	Criação de mapas de calor (matriz de confusão)
