# ViT-Detection-TBC

# Detección de Tuberculosis en Radiografías de Tórax usando Vision Transformers

Este repositorio contiene el código y resultados para la detección automática de tuberculosis pulmonar en radiografías de tórax, utilizando modelos Vision Transformer (ViT) y transferencia de aprendizaje, como parte de mi tesis de licenciatura.


## 🖥️ Modelo y Dataset

- Modelo: ViT (Vision Transformer) preentrenado en ImageNet, ajustado para clasificación binaria (tuberculosis / normal).
- Dataset: 3500 radiografías de tórax con TB y 3500 normales (total 7000 imágenes).
- Framework: PyTorch + HuggingFace Transformers.

## 🚦 Resultados

- **Test Accuracy:** 98.55%
- **Test AUC:** 0.9999

**Matriz de confusión:**

|                | Predicted Normal | Predicted Tuberculosis |
|----------------|-----------------|-----------------------|
| Actual Normal  | 1605            | 1                     |
| Actual Tuberculosis | 16          | 1549                  |

## 📊 Visualizaciones

Ejemplo de matriz de confusión generada con seaborn (ver el notebook para más):

![Matriz de confusión](Resultados.png)
