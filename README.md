# Universidad Politécnica Salesiana (UPS)
## Carrera: Computación
### Período Académico: 65
### Estudiante: Sebastian Francisco Guaman Torres

---

## **Proyecto: Cuarteto de Anscombe**

### **Descripción del Proyecto**
Este proyecto tiene como objetivo explorar y visualizar el **Cuarteto de Anscombe**, un conjunto de cuatro subconjuntos de datos que destacan la importancia de complementar las estadísticas descriptivas con gráficos. Fue introducido por **Francis Anscombe** en 1973 para demostrar cómo varios conjuntos de datos pueden compartir las mismas propiedades estadísticas (media, varianza y correlación) pero comportarse de manera muy diferente al ser visualizados.

### **Contenido del Proyecto**
1. **Carga del dataset**: El dataset de Anscombe es cargado desde un archivo CSV.
2. **Análisis Estadístico**: Se generan resúmenes estadísticos agrupados por cada conjunto de datos.
3. **Visualización Gráfica**:
   - Gráficas de dispersión (scatter plots) para cada conjunto.
   - Gráficas de boxplots para la distribución de los valores `x` e `y`.
4. **Conclusiones**: Se evidencia que los datos pueden ser malinterpretados si solo se utilizan estadísticas descriptivas sin la visualización adecuada.

---

### **Cuarteto de Anscombe**

El Cuarteto de Anscombe contiene los siguientes **cuatro subconjuntos**:
1. **Dataset I**: Relación lineal clara entre las variables.
2. **Dataset II**: Relación cuadrática entre las variables.
3. **Dataset III**: Contiene un outlier que afecta la regresión lineal.
4. **Dataset IV**: Relación aparentemente lineal, pero con un outlier extremo.

Este cuarteto demuestra que **medidas como la media, varianza y coeficientes de correlación pueden ser idénticos** en conjuntos distintos, y aún así presentar comportamientos radicalmente diferentes cuando se visualizan gráficamente.

---

### **Requerimientos**

- **Librerías Utilizadas**:
  - `pandas`
  - `seaborn`
  - `matplotlib`

- **Ejecución del Código**:
  1. Asegúrate de tener el archivo `anscombe.csv` en la misma carpeta que el notebook.
  2. Instala las dependencias necesarias:
     ```bash
     pip install pandas seaborn matplotlib
     ```
  3. Corre el notebook en Jupyter o Google Colab.

---

### **Conclusiones**

El Cuarteto de Anscombe resalta la **importancia de visualizar los datos** antes de realizar cualquier análisis o inferencia. Las estadísticas descriptivas no siempre revelan la complejidad subyacente en los datos, por lo que es esencial complementarlas con gráficos adecuados para evitar interpretaciones incorrectas.
