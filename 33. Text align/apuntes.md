para centrar el contenido de una caja se pude usar text-align siempre y cuando el contenido no tenga declarado el ancho.

text-align solo va a centrar contenido

el link es un elemento de linea por lo tanto para centrar se tiene que agregar display: block;  para posteriormente agregar text-align: center; (funciona porque no tiene un ancho declarado, se declara el ancho para volverlo en una caja, y para centrar se tiene que agregar los margenes left-auto y right-auto)


