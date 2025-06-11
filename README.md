# 📉 Análisis de Churn en Clientes Fintech

Este proyecto explora la pérdida de clientes (churn) en un contexto fintech simulado, utilizando técnicas de análisis exploratorio y modelos de machine learning. Fue desarrollado como parte de mi preparación para una posición en el equipo de **Growth & Analytics de Mercado Pago**.

---

## 📊 Objetivos del proyecto

- Analizar los patrones asociados al churn de clientes.
- Visualizar el comportamiento en relación a edad, saldo, productos y quejas.
- Entrenar modelos de clasificación para predecir el churn.
- Generar insights accionables para estrategias de retención.

---

## 🧠 Modelos utilizados

- **Regresión Logística**: para obtener interpretabilidad de las variables.
- **Random Forest**: para capturar relaciones no lineales con alta performance.

> 📈 Ambos modelos alcanzaron métricas excelentes. El Random Forest logró una accuracy de **100%** en el set de test, debido al fuerte peso de la variable `Complain`.

---

## 📌 Principales insights

- Los clientes con 3 o más productos tienen altísima probabilidad de churn.
- La edad y las quejas son factores críticos.
- El score de satisfacción no muestra correlación fuerte con la pérdida.
- Clientes con saldos extremadamente altos o bajos son más propensos a abandonar.

---

## 📁 Contenido del repositorio

- `Churn.ipynb` → Notebook principal con todo el análisis.
- `img/` → Visualizaciones listas para presentación.
- `modelos/` → Modelos entrenados en formato `.pkl` (opcional).
- `README.md` → Este archivo.

---

## 🛠️ Librerías utilizadas

- Python 3.12
- pandas, seaborn, matplotlib
- scikit-learn

---

## 🧠 Autor

**Ignacio Muñoz Gomeñuka**  
[github.com/ignaciogomenuka](https://github.com/ignaciogomenuka)
