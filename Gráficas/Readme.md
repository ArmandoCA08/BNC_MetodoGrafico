# Carpeta de Gráficas

Esta carpeta contiene las figuras, capturas y archivo de Excel utilizados para documentar la obtención de las gráficas auxiliares empleadas en la aplicación **BNC_MetodoGrafico**.

Las gráficas corresponden al método gráfico de **bombeo neumático continuo con válvulas desbalanceadas**, principalmente:

- Gradientes para mezclas de agua salada y aceite.
- Carta OTIS para el peso de la columna de gas.
- Capturas de las gráficas integradas en la aplicación.

## Archivo de Excel

El archivo principal de apoyo es:

```text
Obtención de gráficas BNC válvulas desbalanceadas.xlsx
```

Este archivo contiene el ajuste y validación de las gráficas auxiliares usadas posteriormente dentro de la aplicación en **MATLAB App Designer**.

---

# Obtención de gráficas

## Gradientes para mezclas de agua salada

La siguiente figura corresponde a la gráfica base utilizada para estimar el gradiente del fluido producido en función de la densidad del aceite y el porcentaje de agua salada.

![Gráfica de gradientes para mezclas de agua salada](Gr%C3%A1fica%20de%20gradientes%20para%20mezclas%20de%20agua%20salada.PNG)

## Obtención de gráfica de gradientes con Excel

Esta imagen muestra la construcción y ajuste de la gráfica de gradientes de mezcla agua salada–aceite mediante Excel.

![Obtención de gráfica gradientes de mezcla agua salada - aceite con Excel](Obtenci%C3%B3n%20de%20gr%C3%A1fica%20gradientes%20de%20mezcla%20agua%20salada%20-%20aceite%20con%20Excel.png)

## Gráfica OTIS: peso de la columna de gas

La siguiente figura corresponde a la carta OTIS utilizada para estimar el peso de la columna de gas en función de la presión superficial y la densidad relativa del gas.

![Gráfica OTIS peso de la columna de gas](Gr%C3%A1fica%20OTIS%20peso%20de%20la%20columna%20de%20gas.PNG)

## Obtención de gráfica OTIS con Excel

Esta imagen muestra la construcción y ajuste de la gráfica OTIS mediante Excel, a partir de las ecuaciones utilizadas para representar las diferentes densidades relativas del gas.

![Obtención de gráfica OTIS con Excel](Obtenci%C3%B3n%20de%20gr%C3%A1fica%20OTIS%20con%20Excel.png)

---

# Gráficas integradas en la aplicación

Las siguientes imágenes muestran cómo se integran las gráficas auxiliares dentro de la aplicación desarrollada en **MATLAB App Designer**.

## Gradientes para mezclas de agua salada y aceite

Vista de la pestaña de gradientes para mezclas de agua salada y aceite dentro de la aplicación.

![Gráfica gradientes para mezclas agua salada - aceite](../Im%C3%A1genes/Tab%20group%20gr%C3%A1fica%20gradientes%20para%20mezclas%20agua%20salada%20-%20aceite.png)

## Gradientes con resultado de ejemplo

Vista de la pestaña de gradientes mostrando el resultado calculado para un caso de ejemplo.

![Gráfica gradientes para mezclas agua salada - aceite ejemplo](../Im%C3%A1genes/Tab%20group%20gr%C3%A1fica%20gradientes%20para%20mezclas%20agua%20salada%20-%20aceite%20ejemplo.png)

## Gráfica OTIS

Vista de la pestaña OTIS para el peso de la columna de gas dentro de la aplicación.

![Gráfica OTIS](../Im%C3%A1genes/Tab%20group%20gr%C3%A1fica%20OTIS.png)

## Gráfica OTIS con resultado de ejemplo

Vista de la pestaña OTIS mostrando los puntos de resultado correspondientes a la presión de operación y presión disponible.

![Gráfica OTIS ejemplo](../Im%C3%A1genes/Tab%20group%20gr%C3%A1fica%20OTIS%20ejemplo.png)

---

# Notas

Las gráficas auxiliares fueron incorporadas en la aplicación con el objetivo de visualizar los resultados intermedios del método gráfico. Las curvas base se muestran de forma permanente y, al presionar el botón **Calcular**, se agregan los puntos correspondientes al caso evaluado.
