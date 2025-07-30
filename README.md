# ChallengeTelecomX2

---

## 🔧 Herramientas utilizadas

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 🔎 Principales pasos del análisis

1. **Tratamiento de Datos**:
   - Eliminación de columnas irrelevantes
   - One-hot encoding para variables categóricas
   - Normalización para modelos basados en distancia

2. **Análisis Exploratorio**:
   - Visualización de correlaciones
   - Detección de desbalance de clases
   - Análisis de cancelación según tipo de contrato, facturación y antigüedad

3. **Modelado Predictivo**:
   - Regresión Logística (con normalización)
   - Random Forest (sin normalización)
   - Evaluación con métricas: Accuracy, Recall, F1-score, AUC
   - Interpretación de coeficientes e importancia de variables

---

## 🏆 Resultados

- Mejor modelo: **Regresión Logística** (AUC: 0.84)
- Variables más relevantes:
  - Meses de antigüedad
  - Tipo de contrato
  - Tipo de Internet
  - Método de pago

---


## 📌 Autor

- **Juan Fernandez** - [@NicolasFercha](https://github.com/NicolasFercha)

---


