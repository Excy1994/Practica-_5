
# PRACTICA_5  MI Primera Interfaz De Usuario Interactiva

## I. Visión general de la aplicación

<img src="Medios\1.PNG/">

### El resultado debe mostrar una captura semejante a esta pantalla siguiente:

## Abra activity_main.xml desde el panel Proyecto > Android si aún no está abierto. Si la pestaña Design (diseño) aún no está seleccionada, haga clic en ella.

<img src="Medios\2.PNG/">

## Si no hay ningún blueprint, haga clic en el botón Select design surface de la barra de herramientas (puede presionar la tecla B, para cambiar entre cada modo) y elija Design + blueprint.

<img src="Medios\3.PNG/">

## La herramienta Conexión automática también se encuentra en la barra de herramientas. Está habilitado de forma predeterminada. Para este paso, asegúrese de que la herramienta no está deshabilitada.

<img src="Medios\4.PNG/">

##  Haga clic en el botón de acercar para acercar los paneles de diseño y blueprint para ver de cerca.

<img src="Medios\5.PNG/">

## Seleccione TextView en el panel del árbol de componentes (Component tree). El "Hello World" se resalta en los paneles de diseño y blueprint y las restricciones para el elemento TextView son visibles.

<img src="Medios\6.PNG/">

##  A continuación, se muestra como establecer una restricción o constraint con el contenedor padre al lado derecho del TextView

<img src="Medios\7.PNG/">

##  Añadir un botón al layout

## Siga estos pasos para agregar el Button:

## Comience con una pizarra limpia. El elemento TextView no es necesario, por lo que mientras está seleccionado, pulse la tecla Supr o elija Edición > Eliminar. Ahora tiene un diseño completamente en blanco


<img src="Medios\8.PNG/">
<img src="Medios\9.PNG/">


## Arrastre un botón desde el panel Paleta a cualquier posición de la presentación. Si coloca el elemento Button en el área media superior de la presentación, pueden aparecer restricciones automáticamente. Si no es así, puede arrastrar restricciones a la parte superior, izquierda y derecha del diseño.


<img src="Medios\10.PNG/">

## Añada un segundo botón en la parte inferior del layout y del mismo modo cree las restricciones correspondientes con los elementos próximos a él.

<img src="Medios\11.PNG/">

## Pruebe borrar todos los constraints o restricciones de un elemento, seleccionando y pasando el puntero sobre este y seleccionar cleal all constraints.

<img src="Medios\12PNG.PNG/">
<img src="Medios\13.PNG/">

## Tarea 1.3: Cambiar los atributos de los elementos de la interfaz de usuario


## Cambiar el tamaño del Button.

## Seleccione el botón superior en el panel Árbol de componentes.

<img src="Medios\14.PNG/">

## Haga clic en la pestaña Atributos en el lado derecho de la ventana del editor de layout

<img src="Medios\15.PNG/">

## Haga clic en el control de ancho las veces que sea necesario; debe lograr el valor **match_constraint** para el **layout_width.

<img src="Medios\16.PNG/">

> *Realice la misma modificación para el botón inferior, el resultado es que ambos botones deben cubrir todo el ancho del constraint.*

<img src="Medios\17.PNG/">

*Establezca wrap_content al layout_height, también puede usar un valor fijo de 16dp*

<img src="Medios\18.PNG/">

## Siga los siguientes pasos:

##  Después de seleccionar el primer botón, edite el campo ID en la parte superior del panel Atributos a button_toast para el atributo android: id, que se usa para identificar el elemento en el layout.git

<img src="Medios\19.PNG/">

## Establezca el atributo de background en @color/colorPrimary. (A medida que ingresa @c, aparecen opciones para una fácil selección. Si no está establecido el color, hágalo en colors.xml

<img src="Medios\20.PNG/">

## Establezca el atributo textColor en @android:color/white.

## Edite el atributo text en Toast.

## Selecciona el segundo botón y edite su campo id a button_count.


## Edite el atributo text del segundo botón a Contar.


## Cambie el color de texto y de fondo a los botones.
