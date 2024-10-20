
# Naive Bayes con Dataset de Vinos

Este proyecto implementa el algoritmo **Naive Bayes** utilizando el conjunto de datos de reconocimiento de vinos disponible en scikit-learn. El objetivo es clasificar vinos en función de sus características químicas.

## Requerimientos
Este proyecto utiliza **Anaconda** para gestionar dependencias y ejecutar los notebooks en **Jupyter Notebook**.

### Instalación de Dependencias
1. Clona el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd nombre_proyecto
   ```

2. Crea un entorno virtual con Anaconda utilizando el archivo `environment.yml`:
   ```bash
   conda env create -f environment.yml
   conda activate naive_bayes_wine
   ```

3. Inicia Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Estructura del Proyecto
- **notebooks:** Contiene los notebooks Jupyter utilizados para el análisis.
- **data:** Archivos de datos utilizados (si los hay).
- **src:** Código fuente adicional, como funciones auxiliares.
- **results:** Salidas y resultados relevantes (ej. imágenes generadas).
- **reports:** Informes y documentos PDF relacionados con el proyecto.

## Archivos Importantes
1. **Naive_Bayes_Wine.ipynb:** Notebook principal donde se entrena y evalúa el modelo Naive Bayes.
2. **ES2_Naive_Bayes_Matias_Cavieres.pdf:** Informe del análisis realizado.

## Instrucciones de Uso
1. Navega a la carpeta `notebooks` y abre el notebook **Naive_Bayes_Wine.ipynb**.
2. Ejecuta las celdas en orden para reproducir el análisis. Esto incluye:
   - Importar las librerías necesarias.
   - Dividir el dataset en entrenamiento y prueba.
   - Entrenar el modelo y evaluar su rendimiento.
   - Visualizar la matriz de confusión.

## Resultados
El modelo Naive Bayes entrenado en este dataset tiene una **exactitud del 100%**. La matriz de confusión muestra una clasificación perfecta de todas las muestras de prueba.

## Contribuciones
Si deseas contribuir, crea un fork del repositorio, realiza tus cambios y envía un pull request.

## Licencia
Este proyecto está bajo la licencia MIT.

## Contacto
[Matías Francisco Cavieres Belmar](matcavieres@gmail.com)_
