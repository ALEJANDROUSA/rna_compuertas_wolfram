# 🧠 RNA para Compuertas Lógicas

Este proyecto implementa Redes Neuronales Artificiales (RNA) simples para simular el comportamiento de **compuertas lógicas** básicas usando *Wolfram Mathematica*.

---

## 📌 Objetivo
Entrenar una red neuronal para que aprenda la tabla de verdad de cada compuerta lógica (AND, OR, XOR) y pueda predecir su salida correctamente.

---

## ⚙️ Compuertas implementadas
1. **AND**
   - Entrada: (0,0), (0,1), (1,0), (1,1)
   - Salida esperada: 0, 0, 0, 1

2. **OR**
   - Entrada: (0,0), (0,1), (1,0), (1,1)
   - Salida esperada: 0, 1, 1, 1

3. **XOR**
   - Entrada: (0,0), (0,1), (1,0), (1,1)
   - Salida esperada: 0, 1, 1, 0

---

## 🛠️ Estructura de cada código
Cada archivo de Wolfram Mathematica incluye:
- Definición de las entradas y salidas reales.
- Creación de la red neuronal con `NetChain`.
- Entrenamiento de la red con `NetTrain`.
- Evaluación y predicción de resultados.
- Tabla comparativa entre salida real y salida predicha.

---

## 🚀 Cómo usar
1. Abre el archivo correspondiente en **Wolfram Mathematica**.
2. Ejecuta cada celda en orden.
3. Revisa la tabla de predicciones generada.
4. Compara los resultados con la tabla de verdad.

---

## 📂 Archivos
- `RNA_AND.nb` → Red neuronal para compuerta **AND**
- `RNA_OR.nb` → Red neuronal para compuerta **OR**
- `RNA_XOR.nb` → Red neuronal para compuerta **XOR**

---

## 📊 Resultados esperados
La red debe aprender correctamente el comportamiento de cada compuerta después del entrenamiento, mostrando coincidencia entre la **salida real** y la **predicción**.

---

✍️ Proyecto realizado como práctica de **Redes Neuronales Artificiales**.
