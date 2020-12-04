
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

## Tarea 1.3: Cambiar los atributos de los elementos de la interfaz de usuario

## En esta tarea, ingresa nuevos valores y cambia los valores de los atributos importantes de Button, que son aplicables a la mayoría de los tipos de vista.


## Cambiar el tamaño del Button.

## El editor de layout ofrece controles de cambio de tamaño en las cuatro esquinas de una view para que pueda cambiar el tamaño de la view rápidamente. Puede arrastrar los controladores en cada esquina de la View para cambiar su tamaño, pero al hacerlo, codifica las dimensiones de ancho y alto. Evite la codificación de tamaños para la mayoría de los elementos de Vista, porque las dimensiones codificadas no se pueden adaptar a diferentes tamaños de pantalla y contenido.


## En su lugar, use el panel Atributos en el lado derecho del editor de layout para seleccionar un modo de tamaño que no use dimensiones codificadas. El panel Atributos incluye un panel de tamaño cuadrado llamado inspector de vista en la parte superior. Los símbolos dentro del cuadrado representan la configuración de alto y ancho: