# Gestor_Alquileres

PROCESO PARA EJECUTAR EL PROYECTO

1. Instalar VisualWorks Smalltalk.
2. Crear un nuevo proyecto, puede ser de 32/64 bits.
3. Dentro de la ruta Base VisualWorks => UIBuilder => UIBuilder-Framework.
4. Buscamos ApplicationModel => binding y dentro de source, copiamos y pegamos el código que se encuentra dentro de codigo.txt
5. En package nos dirigimos al final, y sobre none hacemos click derecho -> New Package.
6. Sobre el paquete creado, hacemos click derecho y en file into... cargamos el paquete Gestor_Alquileres.st
7. Para ejecutar el programa, existen dos formas:
  1. Sobre la clase MenuPrincipal -> Sobre la pestaña Class -> Seleccionamos windowSpec -> abajo veremos una preview de la vista y le damos a Open.
  2. Dentro de la ventana principal hacemos click sobre new workspace -> y pegamos el siguiente código:
     1. MenuPrincipal new.
     2. MenuPrincipal open.
