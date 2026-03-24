**📊 Análisis de Videojuegos: Exploración y Limpieza de Datos**

**📖 Descripción**

Este proyecto consiste en un análisis exploratorio de datos (EDA) sobre
videojuegos utilizando dos datasets diferentes. El objetivo principal es
limpiar, transformar y combinar los datos para obtener insights
relevantes sobre la industria del gaming.

Se han aplicado técnicas de:

-   Limpieza de datos

-   Transformación de variables

-   Análisis estadístico

-   Visualización de datos

-   Integración de datasets

El análisis permite estudiar aspectos como precios, popularidad,
géneros, publishers y evolución temporal de los videojuegos.

**🗂️ Estructura del Proyecto**

├── data/ \# Datos originales (games.csv, games2.csv)\
├── notebooks/ \# Notebook con todo el análisis\
├── results/ \# Gráficos generados\
├── README.md \# Descripción del proyecto

**⚙️ Instalación y Requisitos**

Este proyecto utiliza Python y las siguientes librerías:

-   pandas

-   numpy

-   matplotlib

Puedes instalar las dependencias con:

pip install pandas numpy matplotlib

**📊 Resultados y Conclusiones**

A partir del análisis realizado:

-   La mayoría de los videojuegos tienen precios bajos o son gratuitos,
    como se observa en la distribución de precios .

-   Existe una gran concentración de juegos en categorías como
    *Single-player* y *Family Sharing*.

-   Se observa un crecimiento muy fuerte en el número de videojuegos
    publicados a partir de 2015, alcanzando un pico reciente .

-   No existe una relación clara entre el precio de un juego y sus
    recomendaciones.

-   Los juegos más populares (como Counter-Strike 2 o Dota 2) tienen un
    número extremadamente alto de usuarios simultáneos.

Además:

-   Se creó una nueva variable de rating basada en valoraciones
    positivas y negativas.

-   Se extrajo información de propietarios (owners_min y owners_max).

-   Se integraron dos datasets mediante el nombre del juego.

**🔄 Próximos Pasos**

-   Aplicar modelos predictivos para estimar el éxito de un videojuego.

-   Analizar el impacto del género en la popularidad.

-   Incluir más fuentes de datos para enriquecer el análisis.

-   Crear dashboards interactivos (Power BI o Tableau).

**✒️ Autor**

-   Javier Fernández Fernández
