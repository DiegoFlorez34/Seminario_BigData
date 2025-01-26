# Dashboard para Predicción del Precio Interno del Café

## Descripción del Proyecto
Este proyecto utiliza técnicas de aprendizaje automático para predecir el precio interno del café en Colombia. El modelo está implementado utilizando Python y varias bibliotecas como TensorFlow, Pandas y Matplotlib. El código está diseñado para ejecutarse en Google Colaboratory y presenta los resultados en un dashboard interactivo accesible a través de Flask y Ngrok.

## Tabla de Contenidos
1. [Requisitos](#requisitos)
2. [Instalación](#instalación)
3. [Ejecución del Proyecto](#ejecución-del-proyecto)

## Requisitos

- Cuenta de Google activa.
- Acceso al notebook de Google Colaboratory donde está alojado el código.
- Librerías y dependencias necesarias:
  - TensorFlow
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Flask
  - Ngrok

## Instalación

1. **Clonar el repositorio**:
   ```bash
      https://github.com/DiegoFlorez34/Seminario_BigData.git
   ```

2. **Cargar el notebook en Google Colaboratory**:
   - Accede a [Google Colaboratory](https://colab.research.google.com/).
   - Abre el archivo `.ipynb` del proyecto desde tu Google Drive o súbelo manualmente al google drive..

## Ejecución del Proyecto

1. **Preparar los datos**:
   - Descarga los datos del precio interno del café desde la [Federación Nacional de Cafeteros](https://federaciondecafeteros.org/app/uploads/2023/08/Precios-area-y-produccion-de-cafe-2.xlsx).
   - Realiza el preprocesamiento inicial en Google Sheets o Excel, según sea necesario usando el articulo previamente subido.
   - Descarga los datos preprocesados en un CSV
   - Carga los datos al entorno de Google Colaboratory.

2. **Ejecutar el modelo predictivo**:
   - Click en entrono de ejecucion / ejecutar todo

3. **Iniciar el dashboard web**:
   - Ejecuta las celdas correspondientes al servidor Flask y a la integración con Ngrok para obtener un enlace público.
   - Accede al enlace generado para interactuar con el dashboard.


