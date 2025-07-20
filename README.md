# 📊 Cálculo de Métricas de Avaliação de Classificação

Este projeto tem como objetivo implementar, de forma manual, as principais **métricas de avaliação** utilizadas em modelos de classificação supervisionada, como:

- ✅ Acurácia
- 📈 Sensibilidade (Recall)
- 📉 Especificidade
- 🎯 Precisão
- 📊 F-Score

Além disso, é gerada uma **matriz de confusão em forma de gráfico (heatmap)** para melhor visualização dos dados.

---

## 📌 Fórmulas Utilizadas

As métricas são calculadas a partir da matriz de confusão com os valores:

- **VP**: Verdadeiros Positivos  
- **VN**: Verdadeiros Negativos  
- **FP**: Falsos Positivos  
- **FN**: Falsos Negativos  

As fórmulas são:

- **Acurácia** = (VP + VN) / (VP + VN + FP + FN)  
- **Sensibilidade (Recall)** = VP / (VP + FN)  
- **Especificidade** = VN / (VN + FP)  
- **Precisão** = VP / (VP + FP)  
- **F-Score** = 2 × (Precisão × Sensibilidade) / (Precisão + Sensibilidade)

---

## 🧪 Exemplo de Valores Utilizados

```python
VP = 70
FN = 20
FP = 10
VN = 100
