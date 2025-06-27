TFG - Calibración de Sensores de Bajo Coste frente a Sensor Oficial
Autor: Hugo Toledo Escrivá
Fecha: Junio 2025

Estructura del Proyecto:
-------------------------
1. **memoria_Hugo_Toledo_Escriva.pdf**: Documento completo del TFG.
2. **codigo/**: Ficheros con código fuente y notebooks utilizados en el trabajo.
    - **R/**: Scripts en R (preprocesamiento, análisis exploratorio, etc.)
    - **Python/**: Notebooks en Python (modelado supervisado, XGBoost, etc.)
3. **datos/**: Ficheros CSV utilizados para el análisis y modelado.
4. **graficas/** y **graficas_2/**: Gráficas generadas durante el análisis y exportadas para la memoria.
5. **README.txt**: Guía para ejecutar el proyecto.

Instrucciones:
--------------
1. **Requisitos:**
   - Tener instalados los entornos de **R** y **Python**.
   - Para ejecutar los scripts en R, usar RStudio o el entorno de tu preferencia.
   - Para ejecutar los notebooks de Python, usar **Jupyter Notebook** o **Google Colab**.
   
2. **Cargar y procesar los datos:**
   - Los datos deben estar ubicados en la carpeta **`datos/`**.
   - Para los archivos **R**, asegúrate de que los CSV estén correctamente referenciados.
   
3. **Ejecución en R:**
   - Ejecuta los ficheros **Rmd** en RStudio para obtener los resultados de preprocesado y análisis exploratorio.
   - Los archivos más importantes:
     - **`preprocesado.Rmd`**: Carga y preprocesado de datos.
     - **`conversion.Rmd`**: Conversión de unidades.
     - **`analisis_explo.Rmd`**: Análisis exploratorio (EDA).
     - **`drift.Rmd`**: Análisis de drift y desviación temporal.
   
4. **Ejecución en Python:**
   - Abre y ejecuta los **notebooks** en Jupyter o Google Colab.
   - Los notebooks más importantes:
     - **`regresion.ipynb`**: Modelo base con regresión lineal.
     - **`avanzado.ipynb`**: Modelado avanzado con XGBoost y corrección de error.

5. **Visualización y resultados:**
   - Las gráficas generadas por los scripts de R y Python están en las carpetas de **`graficas/`**.
   - Asegúrate de tener las librerías adecuadas instaladas para poder visualizarlas (por ejemplo, **ggplot2** en R, **matplotlib** en Python).

6. **Guardar y procesar datos finales:**
   - Los resultados procesados y los modelos entrenados se guardan en la carpeta **`datos/`** para su posterior análisis.

7. **Notas importantes:**
   - El código está diseñado para ser modular y reproducible. Asegúrate de ejecutar los scripts en el orden indicado.
   - **No se ha incluido una de las carpetas de gráficas**, ya que se excedía la capacidad máxima permitida para la entrega.
   - Si tienes dudas sobre el funcionamiento de algún script, revisa los comentarios dentro de los mismos.


