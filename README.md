# 🐧 Análisis de Datos y Agrupamiento de Pingüinos

En este proyecto,exploramos dataset seaborn Penguins, analizamos las relaciones entre sus características físicas mediante técnicas como el Análisis de Componentes Principales (PCA) y Clustering.

## 📊 Puntos Clave del Análisis

### 1. Matriz de Correlaciones
- Calculamos y representamos gráficamente la matriz de correlaciones.
- Identificamos las variables más inversamente correlacionadas entre las características físicas de los pingüinos.

### 2. Análisis de Componentes Principales (PCA)
- Realizamos PCA sobre la matriz de correlaciones, evaluando el número adecuado de componentes.
- Estudiamos los autovalores y gráficos asociados para determinar la eficiencia en la representación de la variabilidad de las especies de pingüinos.
- Repetimos el PCA indicando el número de componentes seleccionados.
  - Gráficos de variables en los planos formados por las componentes.
  - Destacamos las especies de pingüinos en cada componente.
  - Proponemos la construcción de un índice que valore de forma conjunta las características físicas.

### 3. Técnicas de Agrupamiento
- Determinamos el número de grupos mediante agrupamiento jerárquico y dendrograma.
- Implementamos el algoritmo de agrupamiento K-Means, explorando diferentes valores de k.
- Evaluamos la calidad del agrupamiento utilizando métricas como la puntuación de silueta.
- Comparamos resultados entre agrupamiento jerárquico y K-Means.
- Proporcionamos interpretación de los grupos identificados en el contexto de las especies de pingüinos.
