<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
Se define la llave de seguridad 1001, utilizando ANDs y NOTs se compara la entrada cargada a los Flip Flops con esta llave de seguridad. La salida es 1 sí y sólo sí todas las entradas cargadas coinciden con la llave de seguridad.
476505217824789505

Se utiiza display tipo catódico. Al modificar los switches 1, 2, y 3, se obtiene en el display el número [SWITCH_1] * 1 + [SWITCH_2] * 2 + [SWITCH_3] * 4.
Donde [SWITCH_n] es 0 cuando está desactivado y 1 cuando está activado el switch n.
476596711437681665

## How to test
Simular, cambiar la entrada cargada modificando el pin1 del switch de 8 pines y haciendo pasar el clock con el botón Step.

Simular, cambiar los valores de los switches 1, 2 y 3, y ver como cambia el valor en el display.

## External hardware
LED
7-Segment Display
