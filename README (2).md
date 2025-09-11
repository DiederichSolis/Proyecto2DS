# 📊 Proyecto 2 – Análisis Exploratorio de Datos  
**Tema 12: Reconocimiento de deletreo manual en Lengua de Señas Americana (ASL)**  
Curso: CC3084 – Data Science  
Universidad del Valle de Guatemala – Semestre II, 2025  

---

## 👥 Integrantes
- Diederich Solis – 22952  
- Juan Cordón  
- Sebas Juarez  
- Sara Guzmán  

---

## 📌 Descripción del Proyecto
Este proyecto corresponde al **Proyecto 2 de la asignatura CC3084 – Data Science**.  
El objetivo es realizar un **análisis exploratorio de datos (EDA)** sobre el conjunto de datos **ASL Fingerspelling**, que contiene información de más de 100 personas que utilizan la Lengua de Señas Americana (ASL).  

Se busca comprender la estructura del dataset, analizar sus variables, identificar desbalances de clases, evaluar la contribución de los participantes y establecer implicaciones para fases posteriores de modelado.  

---

## 📂 Estructura del repositorio
```
├── Proyecto2.pdf                # Informe en formato académico (LaTeX → PDF)
├── ProyectoData2.ipynb          # Notebook en Jupyter con todo el análisis y gráficos
├── data/
│   └── supplemental_metadata.csv # Archivo de metadatos utilizado en el análisis
├── eda_outputs/                 # Carpeta generada con resultados de limpieza
│   ├── metadata_clean.csv
│   ├── freq_letters.csv
│   ├── freq_participants.csv
│   └── resumen_limpieza.csv
└── README.md                    # Este archivo
```

---

## ⚙️ Requisitos
Para ejecutar el notebook necesitarás tener instalado:

- Python 3.9 o superior  
- Librerías:  
  ```bash
  pip install pandas numpy matplotlib jupyter
  ```

---

## ▶️ Ejecución
1. Clonar el repositorio o descargar los archivos.  
2. Asegurarse de que el archivo `supplemental_metadata.csv` esté en la carpeta `data/`.  
3. Abrir el notebook:  
   ```bash
   jupyter notebook ProyectoData2.ipynb
   ```
4. Ejecutar las celdas para reproducir los análisis y gráficos.  

---

## 📈 Resultados principales
- El dataset contiene **43,998 secuencias**, **509 frases distintas** y **72 participantes**.  
- Se detectó un **desbalance significativo de letras**, con la letra `t` representando más del 24% de los ejemplos.  
- Algunas letras como `z`, `k` y `u` están subrepresentadas (menos del 1% de los datos).  
- La participación no es homogénea: algunos usuarios aportaron más de 900 secuencias, mientras que otros menos de 200.  
- El **índice de Gini** para la distribución de letras fue **0.487**, indicando un desbalance medio-alto.  

---

## 📚 Referencias
- World Health Organization (2021). *World Report on Hearing*.  
- Goldin-Meadow, S. (2010). *The Resilience of Language*. Psychology Press.  
