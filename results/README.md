# Resultados

## Análisis EDA

![](./Perfiles%20carga%20electrica/Centroides.png)


Se observa que existentes tendencias de comportamiento en el consumo diario entre los distintos clientes que permiten naturalmente agrupar los datos, se debe tener en cuenta un proceso de normalización a fin de evitar el agrupamiento por escalas de consumo y aprovechar la dinámica de la señal para poder emplear esa información en determinar el comportamiento en el tiempo (t + 1), con el histórico de información funcionando como buffer o clases a priori de comportamiento.

Al utilizar series de tiempo como los perfiles de carga eléctrica, se recomienda tener un proceso de normalización a fin de tener los datos en una misma escala, dado que si se realiza un análisis de clustering o clasificación no se vea afectado por las escalas si lo que se desea comparar es la dinámica (tendencia) de las señales con respecto a las demás.

En el gráfico final se observan los centroides de los clústeres encontrados, estos se definen como la media del conjunto de datos o como punto de equilibrio "centro de gravedad" de los datos, estos centroides pueden ser empleados como clases a priori si lo que se desea buscar es una clasificación basada en los 8 patrones encontrados. 

## Streamlit & Altair

Se agregan los resultados de la integración de Streamlit y Altair con el análisis EDA, para desplegar gráficos interactivos y hacer la difusión del proyecto. Esta integración permite comunicar los resultados desde un aplicativo web. Los gráficos interactivos agregados en la sección de resultados permiten realizar los clústeres formados y visualizar las señales eléctricas agrupadas con base en la información del dataframe.

## Galeria de resultados

| Altair clusters |||
|----------|----------|----------|
| ![Imagen 1](./Altair%20clusters/Altair_Cluster_0.png) Gráfico del clúster 0 con Altair| ![Imagen 2](./Altair%20clusters/Altair_Cluster_1.png)  Gráfico del clúster 1 con Altair| ![Imagen 3](./Altair%20clusters/Altair_Cluster_2.png) Gráfico del clúster 2 con Altair |
| ![Imagen 4](./Altair%20clusters/Altair_Cluster_3.png) Gráfico del clúster 3 con Altair| ![Imagen 5](./Altair%20clusters/Altair_Cluster_4.png) Gráfico del clúster 4 con Altair | ![Imagen 6](./Altair%20clusters/Altair_Cluster_5.png) Gráfico del clúster 5 con Altair |
| ![Imagen 7](./Altair%20clusters/Altair_Cluster_6.png) Gráfico del clúster 6 con Altair| ![Imagen 8](./Altair%20clusters/Altair_Cluster_7.png) Gráfico del clúster 7 con Altair ||


| Boxplots |||
|----------|----------|----------|
| ![Imagen 1](./Boxplots/Boxplot1.png) Boxplot 1| ![Imagen 2](./Boxplots/Boxplot2.png) Boxplot 2 | ![Imagen 3](./Boxplots/BoxplotG1.png) Boxplot grupo 1 |
| ![Imagen 4](./Boxplots/BoxplotG2.png) Boxplot grupo 2 |||


| Matplotlib clusters |||
|----------|----------|----------|
| ![Imagen 1](./Matplotlib%20clusters/Cluster_1.png) Gráfico del clúster 1 con Matplotlib | ![Imagen 2](./Matplotlib%20clusters/Cluster_2.png) Gráfico del clúster 2 con Matplotlib  | ![Imagen 3](./Matplotlib%20clusters/Cluster_3.png) Gráfico del clúster 3 con Matplotlib|
| ![Imagen 4](./Matplotlib%20clusters/Cluster_4.png) Gráfico del clúster 4 con Matplotlib| ![Imagen 5](./Matplotlib%20clusters/Cluster_5.png) Gráfico del clúster 5 con Matplotlib  | ![Imagen 6](./Matplotlib%20clusters/Cluster_6.png) Gráfico del clúster 6 con Matplotlib |
| ![Imagen 7](./Matplotlib%20clusters/Cluster_7.png) Gráfico del clúster 7 con Matplotlib | ![Imagen 8](./Matplotlib%20clusters/Cluster_8.png) Gráfico del clúster 8 con Matplotlib  ||


| Perfiles de carga eléctrica |||
|----------|----------|----------|
| ![Imagen 1](./Perfiles%20carga%20electrica/BD.png) Perfiles de carga eléctrica con relación de la base de datos| ![Imagen 2](./Perfiles%20carga%20electrica/Centroides.png) Centroides | ![Imagen 3](./Perfiles%20carga%20electrica/Media.png) Distribución de la media de los datos|
| ![Imagen 4](./Perfiles%20carga%20electrica/Perfil_bus.png) Perfil bus| ![Imagen 5](./Perfiles%20carga%20electrica/Varianza.png) Distribución de la varianza de los datos | ![Imagen 6](./Perfiles%20carga%20electrica/Zscore.png) Distribución de los valores Z score|