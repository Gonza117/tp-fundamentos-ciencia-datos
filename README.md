# Trabajo Práctico Especial (TPE) - Fundamentos de la Ciencia de Datos (2026)

## Análisis Exploratorio, Limpieza y Pruebas de Hipótesis sobre la Encuesta de Desarrolladores de Stack Overflow

---

## Descripción del Proyecto

Este repositorio contiene la resolución integral del **Trabajo Práctico Especial (TPE)** de la asignatura *Fundamentos de la Ciencia de Datos (2026)*. 

El proyecto realiza un análisis exploratorio inicial de datos (EDA), la caracterización de atributos y diagnóstico de nulos estructurales, el preprocesamiento y depuración de inconsistencias u *outliers*, y la validación formal de hipótesis univariadas, bivariadas y multivariadas (mediante pruebas paramétricas $t$-Student, no paramétricas como Mann-Whitney U y Kruskal-Wallis, y algoritmos de agrupamiento no supervisado K-Means con reducción de dimensionalidad PCA).

---

## Estructura del Repositorio

```text
.
├── README.md                              # Instrucciones detalladas de instalación y ejecución local
├── requirements.txt                       # Lista de dependencias del entorno de Python
├── TPE_CienciaDeDatos_StackOverflow.ipynb # Notebook única de Jupyter estructurada por secciones
├── results.zip                            # Dataset crudo comprimido con las respuestas de la encuesta
└── schema.csv                             # Metadatos y diccionario de preguntas de la encuesta
```

---

## Requisitos Previos



- **Python:** Versión `3.10` o superior.
- **Git:** Para clonar el repositorio desde GitHub.
- **Visual Studio Code** (o Jupyter Lab / Jupyter Notebook) con la extensión de Jupyter instalada.

---

## Paso a Paso para la Instalación y Configuración Local

### 1. Clonar el Repositorio

Abre la terminal de tu sistema operativo y ejecuta:

```bash
git clone https://github.com/Gonza117/tp-fundamentos-ciencia-datos.git
cd TU_REPOSITORIO
```

### 2. Crear el Entorno Virtual (`.venv`)

Crea un entorno aislado para evitar conflictos con librerías globales del sistema:

- **En Windows (PowerShell / CMD):**
  ```powershell
  python -m venv .venv
  ```

- **En Linux / macOS (Bash/Zsh):**
  ```bash
  python3 -m venv .venv
  ```

### 3. Activar el Entorno Virtual

- **En Windows (PowerShell):**
  ```powershell
  .\.venv\Scripts\Activate.ps1
  ```
  *(Nota: Si arroja un error sobre la política de ejecución de scripts, ejecuta primero: `Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass`).*

- **En Windows (Command Prompt / CMD):**
  ```cmd
  .\.venv\Scripts\activate.bat
  ```

- **En Linux / macOS:**
  ```bash
  source .venv/bin/activate
  ```

Verifica que aparezca la etiqueta `(.venv)` a la izquierda del prompt de la terminal

### 4. Instalar las Dependencias del Proyecto

Con el entorno virtual activo, actualiza `pip` e instala de forma automática todas las librerías listadas en `requirements.txt`:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

## Instrucciones para Ejecutar la Notebook

Para asegurar que todo el código corra limpiamente de principio a fin sin errores:

1. **Abrir el proyecto en VS Code:**

2. **Seleccionar el Kernel del Entorno Virtual (`.venv`):**
   - En la esquina superior derecha del editor de notebooks en VS Code, haz clic en **"Select Kernel"**.
   - Selecciona **"Python Environments..."**.
   - Elige el entorno asociado a la carpeta `.venv` de este proyecto.

3. **Ejecutar secuencialmente:**
   - Presiona el botón **"Restart & Run All"** (Reiniciar y Ejecutar Todo) en la barra superior del notebook.
   - Todo el flujo de datos (cargado de datos crudos, limpieza, visualizaciones, pruebas estadísticas y conclusiones) se ejecutará secuencialmente sin interrupciones.

---

## Integrantes del Grupo

- **Gonzalo Lopez**
- **Cordoba Pablo Javier**
- **Maria Paz Scuncio**

**Docente / Ayudante Asignada:** Daniela Godoy  
