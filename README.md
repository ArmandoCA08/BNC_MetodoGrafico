# Bombeo Neumático Continuo | Válvulas Desbalanceadas | Método Gráfico

![Estado](https://img.shields.io/badge/Estado-Terminado-brightgreen)
![MATLAB](https://img.shields.io/badge/MATLAB-App%20Designer-orange)
![HTML](https://img.shields.io/badge/HTML-Estado%20mec%C3%A1nico-blue)
![Área](https://img.shields.io/badge/%C3%81rea-Ingenier%C3%ADa%20Petrolera-darkgreen)
![BNC](https://img.shields.io/badge/M%C3%A9todo-Bombeo%20Neum%C3%A1tico%20Continuo-lightgrey)

Este repositorio contiene una aplicación desarrollada en **MATLAB App Designer** para el diseño gráfico de **bombeo neumático continuo con válvulas desbalanceadas**.

## Vista previa de la aplicación

La siguiente imagen muestra un ejemplo de la aplicación, donde se presenta el método gráfico, la tabla de resultados, la tabla de válvulas y el esquema de estado mecánico generado en HTML.

![Captura de pantalla BNC válvulas desbalanceadas ejemplo](Im%C3%A1genes/Captura%20de%20pantalla%20BNC%20v%C3%A1lvulas%20desbalanceadas%20ejemplo.png)

El proyecto incluye la aplicación principal `ValvulasDesbalanceadas.mlapp` y el archivo `Estado mecánico BNC válvulas desbalanceadas.html`, utilizado para representar de forma visual la posición de las válvulas dentro de la tubería de producción.

## Válvulas desbalanceadas

Las **válvulas desbalanceadas** se emplean en sistemas de bombeo neumático continuo para controlar la inyección de gas a diferentes profundidades del pozo.

Este tipo de válvulas se caracteriza por abrir a una determinada presión y cerrar con una presión inferior a la de apertura. Estas presiones son determinadas por las condiciones en las que se encuentra el pozo, tales como la presión de operación, la presión en cabeza, la profundidad, la temperatura, la densidad relativa del gas de inyección y el gradiente del fluido de control.

En el método gráfico, la ubicación de cada válvula se obtiene a partir de las intersecciones entre las líneas de presión de operación, presión disponible, presión en tubería y gradiente del fluido de control.

## Captura principal

![Captura de pantalla BNC válvulas desbalanceadas](Im%C3%A1genes/Captura%20de%20pantalla%20BNC%20v%C3%A1lvulas%20desbalanceadas.png)

## Referencias

Brown, K. E. (1984). The technology of artificial lift methods: Volume 2a, Introduction of artificial lift systems, beam pumping: Design and analysis, gas lift. PennWell Books.

Day, J. J., Byrd, J. P., Mach, J., Davis, J. B., Richards, B., Gomez, V., Hong, H., Marin, J., Esla, F., Regnault, P., De Moss, E., Faustinelli, J., Mitchell, V., Pacheco, J., Canalizo, C., & Thrash, P. J. (1984). Contributing authors. En K. E. Brown, The technology of artificial lift methods: Volume 2a, Introduction of artificial lift systems, beam pumping: Design and analysis, gas lift. PennWell Books.
