### **1. ¿Qué es una variable?**

- **Definición**: Una variable es una **característica de interés** en un conjunto de datos. Es decir, es aquello que observamos, medimos o estudiamos en un grupo de elementos.
- **Ejemplo**: Si estamos estudiando un salón de clases, la **edad de los estudiantes** puede ser nuestra variable de interés.

---

### **2. ¿Cómo visualizar una variable en un contexto práctico?**

- Si imaginamos los datos en una hoja de cálculo (como Excel) o en un DataFrame de pandas (una herramienta de Python para manejar datos), **cada columna** en la tabla representaría una variable.
  - **Ejemplo**: En un archivo Excel con información de estudiantes, podríamos tener columnas como "Edad", "Nombre", "Género". Cada columna es una variable.

---

### **3. Tipos de variables según su uso en estadística**

No debemos confundir los **tipos de variables estadísticos** con los **tipos de datos de programación**. Los primeros nos ayudan a elegir qué análisis estadístico o visualización es adecuado.

Las variables estadísticas se dividen en dos grandes grupos:
1. **Categóricas (o cualitativas)**.
2. **Numéricas (o cuantitativas)**.

#### **3.1. Variables categóricas**
- Representan **cualidades** o **características** de los datos.
- En programación, suelen representarse como **cadenas de texto** (strings).
- Se subdividen en:
  - **Nominales**:
    - No tienen orden ni jerarquía.
    - **Ejemplos**:
      - Color de ojos: azul, verde, marrón.
      - Tipo de sangre: A, B, AB, O.
      - Nombre de una tienda o marca: "Amazon", "Walmart".
  - **Ordinales**:
    - Poseen un **orden lógico o jerarquía**, pero este orden depende del contexto o criterio del investigador.
    - **Ejemplos**:
      - Nivel de educación: primaria, secundaria, universidad.
      - Categoría de calidad: baja, media, alta.
      - Fechas dentro de un calendario (que siguen un orden cronológico).
    - **Restricciones**:
      - No podemos realizar operaciones matemáticas como sumas o divisiones con estos datos.

#### **3.2. Variables numéricas**
- Representan **valores numéricos** y permiten realizar operaciones matemáticas.
- Se subdividen en:
  - **Discretas**:
    - Tienen un conjunto **finito** de posibles valores.
    - Los valores suelen ser **contables**.
    - **Ejemplos**:
      - Número de estudiantes en un salón: 25, 30.
      - Stock de un producto en una tienda: 10, 20.
      - Calificaciones en un sistema (por ejemplo, 1, 1.5, 2.5 hasta 5).
  - **Continuas**:
    - Tienen un conjunto **infinito** de posibles valores dentro de un rango.
    - Los valores pueden ser números **reales** (incluir decimales).
    - **Ejemplos**:
      - Altura de una persona: 1.75 m.
      - Peso de un producto: 2.34 kg.
      - Distancia entre dos ciudades: 123.45 km.

> **Nota**: Las variables numéricas **discretas** no siempre son enteros. Por ejemplo, un sistema de calificación de restaurantes que permite puntuar en incrementos de 0.5 (1.0, 1.5, 2.0) sería **discreto** porque los valores son fijos y contables.

---

### **4. Relación entre el tipo de variable y las técnicas estadísticas**

El tipo de variable determina qué análisis o visualización se puede usar:
- **Categóricas**:
  - Usamos gráficos como barras o diagramas de pastel.
  - No se pueden calcular métricas como la media o la desviación estándar porque no hay valores numéricos.
- **Numéricas**:
  - Se pueden usar histogramas, gráficos de dispersión, entre otros.
  - Permiten cálculos matemáticos como media, mediana, desviación estándar.

---

### **5. Resumen de los conceptos**

1. Las variables representan columnas en un conjunto de datos.
2. Existen dos grandes grupos:
   - **Categóricas (nominales y ordinales)**.
   - **Numéricas (discretas y continuas)**.
3. Es importante diferenciar entre estos tipos para elegir el análisis adecuado.

---

### **6. Aplicación práctica**

Si te encuentras trabajando con un conjunto de datos, el primer paso es **identificar el tipo de cada variable**. Esto no solo te ayuda a entender los datos, sino que también facilita la elección de herramientas estadísticas y visualizaciones correctas.