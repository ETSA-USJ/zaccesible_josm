Conjunto de presets para [JOSM](http://josm.openstreetmap.de/) para etiquetar aspectos relacionados con la movilidad desde el punto de vista de la accesibilidad para utilizar en una próxima mapping party "Zaragoza Accesible - #Zaccesible" (fecha y lugares por determinar).

Los presets son una ayuda para marcar de forma rápida un conjunto predeterminado de etiquetas (tags) con sus valores. Si no estás familiarizado con ellos (y con el ahorro de tiempo y de errores que suponen), puedes leer una descripción en [este enlace de Learn OSM](http://learnosm.org/en/josm/josm-presets/)

## Instrucciones para instalación

Estas instrucciones dan por supuesto que tenemos JOSM instalado y funcionando en nuestro sistema. Si no es el caso puedes descargarlo desde la [web oficial](http://josm.openstreetmap.de/) y leer [este tutorial de Learn OSM](http://learnosm.org/en/josm/start-josm/).

 1. Colocar el archivo `zaccesibilidad-presets.xml` en el disco duro (podemos clonar el repositorio `git clone git@github.com:ccamara/zaccesible_josm.git` o  descargarlo desde [aquí](https://github.com/ccamara/zaccesible_josm/releases))
 1. Abrir JOSM y acceder a las preferencias (`F12`)
 1. Seleccionar la pestaña `Ajustes para la proyección del mapa y la interpretación de los datos`  ![Screenshot añadir presets](http://learnosm.org/images/en/editing/josm-presets/tagging-presets-menu.png)
 1. Seleccionar la subpestaña `Etiquetas de predefinidos` y hacer clic en el icono `+`
 1. Localizar el archivo que hemos descargado en el punto #1 y hacer clic en `Aceptar`
 1. JOSM se reiniciará.
 
## Instrucciones de utilización

1. Seleccionar un nodo, vía o área previamente creada.
1. Ir al menú `Predefinidos` y seleccionar el preset deseado.
1. En caso de el preset seleccionado tenga sentido para la selección de elementos realizada en el punto #1 se abrirá un cuadro de diálogo (de lo contrario se mostrará un mensaje de advertencia informando del tipo de geometría válido para el preset en cuestión)
1. Rellenar los campos del cuadro de diálogo.
1. Ver que los tags y valores añadidos a través del cuadro de diálogo son correctos y, opcionalmente, añadir cualquier otro tag que queramos añadir. 
