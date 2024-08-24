# Proyecto Integrado: Análisis de Datos de Videojuegos

## Descripción del Proyecto

Trabajas para la tienda online Ice, que vende videojuegos en todo el mundo. Tienes acceso a datos sobre reseñas de usuarios y expertos, géneros, plataformas (como Xbox o PlayStation) y datos históricos de ventas de juegos. Tu tarea es identificar patrones que indiquen si un juego será exitoso o no, lo que te permitirá detectar proyectos prometedores y planificar campañas publicitarias.

Imaginemos que es diciembre de 2016 y estás preparando una campaña para 2017. A continuación, se detallan los pasos que debes seguir para completar este proyecto.

## Instrucciones para Completar el Proyecto

### Paso 1: Exploración Inicial de los Datos

1. **Abrir y Estudiar el Archivo de Datos**
   - Ruta del archivo: `/datasets/games.csv`
   - Descargar el dataset y revisar la información general.

2. **Preparar los Datos**
   - **Renombrar Columnas:** Cambiar nombres de columnas a minúsculas.
   - **Convertir Tipos de Datos:** Ajustar los tipos de datos necesarios y explicar los cambios.
   - **Manejo de Valores Ausentes:** Decidir cómo tratar los valores ausentes y explicar tus decisiones.
   - **Calcular Ventas Totales:** Sumar ventas en todas las regiones y añadir una columna con estas ventas totales.

### Paso 2: Análisis de Datos

1. **Análisis de Juegos por Año**
   - Contar cuántos juegos se lanzaron en diferentes años y evaluar la relevancia de los datos.

2. **Ventas por Plataforma**
   - Analizar cómo varían las ventas entre plataformas. Identificar plataformas con mayores ventas y examinar tendencias a lo largo del tiempo.

3. **Periodo de Datos Relevante**
   - Determinar qué periodo de datos es necesario para construir un modelo predictivo para 2017.

4. **Plataformas Líderes en Ventas**
   - Identificar las plataformas líderes en ventas y analizar su desempeño.

5. **Diagrama de Caja**
   - Crear un diagrama de caja para ventas globales por plataforma y analizar las diferencias en ventas.

6. **Impacto de Reseñas en Ventas**
   - Crear un gráfico de dispersión y calcular la correlación entre las reseñas de usuarios y ventas.

7. **Comparación de Ventas en Diferentes Plataformas**
   - Comparar las ventas de los mismos juegos en distintas plataformas.

8. **Distribución de Géneros**
   - Analizar la distribución de juegos por género y evaluar qué géneros son más rentables.

### Paso 3: Crear Perfiles de Usuario por Región

1. **Perfiles de Plataforma por Región**
   - Determinar las cinco principales plataformas en cada región (NA, UE, JP) y describir las variaciones.

2. **Perfiles de Género por Región**
   - Identificar los cinco géneros principales en cada región y explicar las diferencias.

3. **Impacto de las Clasificaciones ESRB**
   - Evaluar si las clasificaciones de ESRB afectan las ventas en las diferentes regiones.

### Paso 4: Prueba de Hipótesis

1. **Hipótesis a Probar**
   - Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.
   - Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.

2. **Formulación y Prueba de Hipótesis**
   - Formular hipótesis nula y alternativa.
   - Establecer el valor del umbral alfa y explicar el criterio para probar las hipótesis.

### Paso 5: Conclusiones

1. **Conclusiones Generales**
   - Resumir los hallazgos clave del análisis.
   - Presentar conclusiones sobre el éxito de los juegos basadas en los datos analizados.

## Formato del Proyecto

Completa el proyecto en un Jupyter Notebook. Inserta el código en celdas de código y las explicaciones en celdas Markdown. Aplica formato y agrega encabezados para una mejor claridad.

## Descripción de Datos

- **Name:** Nombre del juego
- **Platform:** Plataforma del juego
- **Year_of_Release:** Año de lanzamiento
- **Genre:** Género del juego
- **NA_sales:** Ventas en Norteamérica (en millones de dólares)
- **EU_sales:** Ventas en Europa (en millones de dólares)
- **JP_sales:** Ventas en Japón (en millones de dólares)
- **Other_sales:** Ventas en otros países (en millones de dólares)
- **Critic_Score:** Calificación de críticos (máximo 100)
- **User_Score:** Calificación de usuarios (máximo 10)
- **Rating:** Clasificación ESRB

Es posible que los datos de 2016 estén incompletos.

## Evaluación del Proyecto

Tu proyecto será evaluado en base a los siguientes criterios:

- Descripción de problemas identificados en los datos.
- Preparación del dataset para el análisis.
- Creación y explicación de gráficos de distribución.
- Cálculo de desviación estándar y varianza.
- Formulación y prueba de hipótesis.
- Explicación de resultados de pruebas de hipótesis.
- Estructura del proyecto y claridad del código.
- Comentarios y conclusiones finales.

¡Buena suerte con tu proyecto!
