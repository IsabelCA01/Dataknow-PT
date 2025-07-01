# 🧠 Pruebas Técnicas de Ciencia de Datos para Dataknow

Este es un repositorio de pruebas técnicas relizadas para el cargo de Científico de Datos para Dataknow.io. 
Las dos pruebas técnicas están diseñadas para evaluar habilidades en analítica, ciencia de datos y uso de inteligencia artificial generativa en contextos aplicados.

Realizado por Isabel Castrillón Acosta.

---

## 📁 Estructura del Proyecto

```plaintext
DATKNOW-PT/
├── Prueba tecnica 1/
│   ├── Caso/
│   ├── Datos/
│   └── Resultados/
│       ├── 1_Exploracion_Inicial.ipynb
│       └── 2_Informe_Final.ipynb
│
├── Prueba tecnica 2/
│   ├── Caso/
│   ├── Datos/
│   │   └── sentencias_pasadas.xlsx
│   └── Resultados/
│       ├── 1_Exploracion_Inicial.ipynb
│       └── 2_Informe_Final.ipynb
│
├── .env
├── .gitignore
├── README.md
└── requirements.txt
```

## 🧪 Prueba Técnica 1 - Estimación de Costos de Equipos

### 📝 Descripción

Se desarrolló un modelo de predicción de precios futuros de tres materias primas usando series de tiempo (ARIMA), con el objetivo de mejorar la estimación de costos de equipos en proyectos de construcción.

### 📂 Archivos Clave

- `Datos/`: contiene los precios históricos de materias primas.
- `Resultados/1_Exploracion_Inicial.ipynb`: limpieza, exploración y visualización inicial de los datos.
- `Resultados/2_Informe_Final.ipynb`: modelado con ARIMA y visualización de predicciones.

---

## 🤖 Prueba Técnica 2 - Chatbot Legal con IA Generativa

### 📝 Descripción

Se diseñó un chatbot que responde preguntas legales frecuentes usando un archivo de sentencias judiciales. La solución utiliza **embeddings con FAISS** y generación de respuestas con **OpenAI GPT**.

### 💡 Caso de Uso

Asesorar automáticamente sobre demandas relacionadas con redes sociales, extrayendo información de una base de datos histórica.

### 📂 Archivos Clave

- `Datos/sentencias_pasadas.xlsx`: base de datos legal histórica.
- `Resultados/1_Exploracion_Inicial.ipynb`: carga y limpieza de los datos.
- `Resultados/2_Informe_Final.ipynb`: vectorización, integración con FAISS y chatbot.

---

## ⚙️ Instrucciones Generales

### 1️. Clonar el repositorio

```bash
git clone https://github.com/IsabelCA01/Dataknow-PT.git
cd Dataknow-PT
```

### 2️. Configurar el entorno
```bash
 python -m venv env
# Windows:
env\Scripts\activate
# macOS/Linux:
source env/bin/activate

```

### 3️. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 4️. Configurar las variables de entorno (Clave API de OpenAI)

Crea un archivo `.env` en la raíz del proyecto y añade tu clave API de OpenAI:

```plaintext
OPENAI_API_KEY="tu_clave_api_aqui"
```

### 5. Ejecutar los notebooks
Abre Jupyter Notebook o VS Code y navega a:

- Prueba tecnica 1/Resultados/1_Exploracion_Inicial.ipynb

- Prueba tecnica 2/Resultados/2_Informe_Final.ipynb

## Autor

Isabel Castrillón Acosta

Julio 2025

Proyecto de evaluación técnica para Dataknow


