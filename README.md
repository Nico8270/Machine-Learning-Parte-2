# Machine Learning · Visión Artificial

**Dataset:** BreastMNIST (MedMNIST v2) — ultrasonido de mama, clasificación binaria (Maligno vs Normal/Benigno).

## Notebooks

| Archivo | Descripción |
|---|---|
| `VFinal_sol2BreastMNIST (2).ipynb` | **Entrega 2.** Estudio comparativo de un par de CNN (CNN Casera + ResNet18) frente a un Transformer Visual (ViT-B/16), bajo dos resoluciones de entrada (28×28 y 128×128 px). Grid de 6 experimentos con métricas Accuracy, F1 y AUC, comparación cruzada, curvas y matrices de confusión. |
| `BreastMNIST_Entrega1_Barrientos (2).ipynb` | Entrega 1 (baseline EfficientNet, referencia). |

## Cómo ejecutar

1. Abrir `VFinal_sol2BreastMNIST (2).ipynb` en Google Colab con **GPU** (Runtime → Change runtime type → GPU).
2. Ejecutar M0 (instala `medmnist`) y luego todas las celdas en orden.
3. Ajustar hiperparámetros únicamente en el módulo **M1**.
4. El módulo **M8** entrena el grid completo; **M9** genera las figuras y tablas comparativas.
