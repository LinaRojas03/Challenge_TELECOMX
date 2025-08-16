# 📊 Análisis de Evasión de Clientes (Churn) – Telecom X

Este repositorio contiene el análisis completo de **evasión de clientes** (*churn*) para la empresa **Telecom X**.  
El objetivo es identificar los factores clave que llevan a la cancelación de servicios y proponer estrategias para reducir la tasa de churn.

---

## 📂 Contenido del repositorio

- **`TelecomX_Data.json`** → Archivo de datos original (formato JSON, con estructura anidada).
- **`TelecomX_diccionario.md`** → Diccionario de datos con descripción de cada columna.
- **`TelecomX_LATAM.ipynb`** → Notebook principal con:
  - Limpieza y tratamiento de datos
  - Análisis exploratorio
  - Visualizaciones y conclusiones
- **`README.md`** → Este archivo con instrucciones de uso.

---

## 🛠️ Requisitos

Antes de ejecutar el notebook, asegúrate de tener instaladas las siguientes dependencias en tu entorno de Python:

```bash
pip install pandas numpy matplotlib seaborn
```
---

## 📌 Instrucciones de Uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/LinaRojas03/Challenge_TELECOMX.git 
   cd Challenge_TELECOMX  

3. Abrir el notebook:  
   - Opción 1: Localmente en Jupyter Notebook:
     ```bash  
     jupyter notebook Challenge_TELECOMX.ipynb  
   - Opción 2: En Google Colab:  
     Sube los archivos del repositorio y abre el notebook.

4. Ejecutar el análisis:  
   - Paso 1: Importar y aplanar el JSON.  
   - Paso 2: Limpiar datos (tipos, nulos, crear `Cuentas_Diarias`).  
   - Paso 3: Estandarizar variables categóricas (`Yes/No` → `1/0`).  
   - Paso 4: Ejecutar EDA para encontrar patrones de churn.  
   - Paso 5: Revisar conclusiones y recomendaciones.

---

## 📊 Resultado Esperados
 
- Distribución general de churn.  
- Comparación por variables categóricas (género, contrato, método de pago, tipo de internet).  
- Comparación por variables numéricas (`tenure`, `account_Charges_Total`, `Cuentas_Diarias`).  
- Ranking de variables más correlacionadas con churn.  
- Informe final con conclusiones y recomendaciones.

---

## 📌 Notas
 
- Los datos son ficticios y con fines educativos.  
- Adaptable a otros datasets con estructura similar.  
- Las visualizaciones y métricas pueden modificarse editando el notebook.

---


