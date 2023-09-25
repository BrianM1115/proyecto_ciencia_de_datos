# Proyecto de ciencia de datos

Este proyecto tiene la finalidad de: ** ESTIMAR ÍNDICES DE DELINCUENCIA COMÚN POR COMUNA EN EL MUNICIPIO DE BUCARAMANGA Y PREDECIR INCREMENTOS DE DELITOS EN FECHAS FESTIVAS EN EL MUNICIPIO PARA DAR RESPUESTA A LA POSIBLE FLUCTUACIÓN DE CASOS DELICTIVOS:** 

Para su desarrollo, se tomo un dataset historico publico que contiene la cantidad de delitos que se presentaron en Bucaramanga, Colombia desde el 2010 - 2021. En base a esto, se tomo la iniciativa de comprobar e identificar como funcionaba la estructura delictiva en fechas festivas del mismo rango de años, generando toda la estructura que contiene este proyecto para poder hacer predicciones tanto de la cantidad y conducta delictiva en el año 2023.

Por ende, las personas que esten interesadas en correr desde su terminal cada notebook que compone la estructura debe hacer lo siguiente:
# Notebooks
```sh
git clone
cd Notebooks
```
Dentro de este, debe correr la estructura tal cual como son indicados:
- _1_Limpieza.ipynb
- _2_EDA_L.ipynb
- _3_Preparando_El_Modelo_De_Prediccion.ipynb
- _4_Prediciendo_Datos.ipynb

> Cada notebook debe correrse con los datasets correctos que se pueden visualizar desde la carpeta DataSet

Puedes utilizar tanto Google Colab  y JupyterNotebook para ejecutar cada uno de los archivos :tw-1f609:

# Despliegue
Si deseas visualizar por ti mismo el despligue de este proyecto tienes 2 opciones:

1. Visualizarlo desde la pagina de Tableau:
Como este proyecto su despligue se realizo por Tableau te doy los 2 links para que los veas por ti mismo.

    [Datos Historicos 2010 - 2021](https://public.tableau.com/app/profile/brian.moreno/viz/DatoshistoricosBucaramanga2010-2021/DelitosenfestividadesporcomunasBucaramanga-2010-20211 "Datos Historicos 2010 - 2021")
  [Predicciones 2023](https://public.tableau.com/app/profile/brian.moreno/viz/Prediccionesdelictivas-Bucaramanga2023/DelitosenfestividadesporcomunasBucaramanga-2023 "Predicciones 2023")
  
2. Si tienes Tableau en tu computadora lo que debes hacer:
- Abrir Datos_historicos_Bucaramanga_2010_-_2021.twb
- Abrir Predicciones_delectiva_-_Bucaramanga_2023.twb
- Si no tiene la fuente de datos correcta en cada uno de estos archivos, toca subiarla desde Tableau
- dfml.csv_Varias_conexiones.hyper esta es la fuente de dato para el Datos_historicos
- df_futuro_cantidad_sin_redondear.csv_Varias_conexiones.hyper es la fuente de datos para Predicciones_delectiva

