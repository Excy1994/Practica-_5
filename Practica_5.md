
# PRACTICA_5  MI Primera Interfaz De Usuario Interactiva




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

<img src="Medios\21.PNG/">

## Edite el atributo text en Toast.

<img src="Medios\22.PNG/">

## Selecciona el segundo botón y edite su campo id a button_count.

<img src="Medios\23.PNG/">

## Edite el atributo text del segundo botón a Contar.

<img src="Medios\24.PNG/">

## Cambie el color de texto y de fondo a los botones.

<img src="Medios\24.PNG/">

##  Agregar el elemento TextView y sus atributos correspondientes.

## Desde el panel Palette y el apartado Common, agregue un elemento View TextView y establezca el atributo id a show_count.

<img src="Medios\26.PNG/">
<img src="Medios\25.PNG/">
<img src="Medios\27.PNG/">

## o Establezca las restricciones del TextView, la parte superior con el botón de Toast y su parte inferior con el botón contador.

<img src="Medios\28.PNG/">

## o Establezca las restricciones izquierda y derecha del elemento TextView al lado correspondiente al contenedor padre.

<img src="Medios\29.PNG/">

## o Establezca el valor text a 0

<img src="Medios\30.PNG/">

## o Establezca el valor textSize a 160sp.

<img src="Medios\31.PNG/">

## o Establezca el textStyle a bold.

<img src="Medios\32.PNG/">

## o Cambie layout_width y layout_height a match_constraint.

<img src="Medios\34.PNG/">

## o Establezca el textColor a @color/colorPrimary.

<img src="Medios\33.PNG/">

## o Establezca un valor preferido al atributo background, opcional el #0F49CD.

<img src="Medios\35.PNG/">

## o Establezca el valor gravity a center_vertical

<img src="Medios\36.PNG/">

## Tarea 1.4: Editando el layout en el XML


## Edite el fichero strings.xml que se encuentra en la carpeta res/values:

## Siga los siguientes pasos:

## o Abra el fichero activity_main.xml y cambie el modo solamente a código.

<img src="Medios\37.PNG/">

## o Cambie el valor de text del TextView a un @string/count_initial_value.

<img src="Medios\38.PNG/">

## o Cambie el valor de text del botón superior a @string/button_label_toast.

<img src="Medios\39.PNG/">

## o Cambie el valor de text del botón inferior a @string/button_label_count.

<img src="Medios\40.PNG/">

## Tarea 1.5: Agregar el manejador del evento onClick para los botones.

## o Establezca el siguiente código al botón que tenga como id button_toast, antes de cerrarlo.

<img src="Medios\41.PNG/">

## o Establezca el siguiente código al botón que tenga como id button_count, antes de cerrarlo.

<img src="Medios\42.PNG/">

## o Abra el MainActivity.kt y agregue el siguiente código.
<img src="Medios\43.PNG/">
## o Agregue el siguiente código al método showToast.

<img src="Medios\44.PNG/">

## o Pruebe los resultados ejecutando la aplicación y mostrando el mensaje generado con el valor Hola soy un Toast.

<img src="Medios\45.PNG/">

## o Agregue el siguiente código al método countUp.

<img src="Medios\46.PNG/">

## o Muestre la aplicación funcionando con el contador funcionando el contador y el mensaje Toast mostrándose cada vez que el usuario de Clic.

<img src="Medios\47.PNG/">
<img src="Medios\48.PNG/">