
# AMALIA – Plataforma PowerFrames *Manual de usuario*

## Introducción
La plataforma de PowerFrames es una herramienta que tiene como propósito supervisión, pronostico y monitoreo de las descargas atmosféricas y la vulnerabilidad de los activos del pertenecientes al sistema eléctrico nacional.

La plataforma está basada en un sistema llamado AMALIA

## 1. [Entrada al aplicativo](./docs/Ingreso.md)

Este servicio es una aplicación web que se recomienda ser usada en navegadores basados en … como [Google Chrome.](https://www.google.com/intl/es/chrome/?brand=ALOY&ds_kid=43700059035616983&utm_source=bing&utm_medium=cpc&utm_campaign=1011197%20%7C%20Chrome%20Win10%20%7C%20DR%20%7C%20ESS01%20%7C%20GLOBAL%20%7C%20GLOBAL%20%7C%20es%20%7C%20Desk%20%7C%20SEM%20%7C%20BKWS%20-%20EXA%20%7C%20Txt&utm_term=descargar%20google%20chrome&utm_content=Desk%20%7C%20BING%20SEM%20%7C%20BKWS%20%7C%20Exact%20~%20Download%20Chrome&gclid=20024bb491c21712a0c429376e2f3ccd&gclsrc=3p.ds) Para acceder al aplicativo se debe ingresar a la URL [www.powerframes.co](http://www.powerframes.co/)

## 2. [Portal AMALIA](./docs/AMALIA/)

Ya dentro del aplicativo, AMALIA se encarga de dar la Bienvenida al usuario autenticado y mostrar los diferentes módulos dispuestos para ser usados, Predicciones, Supervisión y Reportes como se muestra en la [Figura3](./pictures/Imagen3.png)

![Figura 3](./pictures/Imagen3.png "Bienvenida")
**Figura 3.** *Bienvenida*

### 2.1 [Módulo de reportes](../Plataforma_PowerFrames/docs/AMALIA/Reportes/Reportes.md)

En esta opción el usuario puede consultar la correlación que existe entre la salida de una línea de transmisión y una descarga atmosferíca, con el fin de determinar la posibilidad de que la causa de la falla (salida de línea) sea consecuencia de un rayo. 

### 2.2. [Módulo de supervisión](./docs/AMALIA/Supervision/)
En este módulo AMALIA se encarga de brindarle al usuario en diferentes visualizaciones la información de recuento de rayos, densidad dinámica de rayos, probabilidades de falla, descargas atmosféricas, análisis de descargas, clusterización de las tormentas, ubicación de las torres, subestaciones y los trazados para rangos de tiempo y espacio definidos por el usuario.
La plataforma está configurado por defecto para que el usuario visualice el mapa de colombia con la información de **"Tiempo Real"**, el mapa se va a mostrar centrad y sin ningún filtro temporal, ni espacial como se muestra en [Figura7](./pictures/Imagen7.png).

*IMPORTANTE*: El tiempo real está definido como el tiempo relativo correspodiente a 60 minutos, es decir, muestra la información de 60 minutos antes hasta el tiempo presente.

*IMPORTANTE:* Las capas pueden no ser visibles por 2 razones
1. El zoom no tenga el ajuste necesario para la capa, ya sea porque esté muy cerca o muy lejos y será necesario modificar el zoom para ver la capa, cuando esto ocurre se ve el siguiente [símbolo](./pictures/Imagen12.png) ![Figura 12](./pictures/Imagen12.png "Ajuste de zoom para la capa")
2. Se haya apagado la visualización y en ese caso se verá el [símbolo](./pictures/Imagen11.png) ![Figura 13](./pictures/Imagen13.png "Capa apagada por el usuario")