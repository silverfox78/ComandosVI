# Comandos VI
---

## Principales comandos

| **Contexto** | **Accion** | **Comando** |
| :--- | :---: | :---|
| archivo | crear/abrir archivo | vi [nombreArchivo] |
| archivo | Grabar y salir | ESC + :wq |
| archivo | Grabar y salir | ZZ |
| archivo | Salir sin Guardar | ESC + :q! |
| archivo | Descarta y recarga el archivo | :e! |
| archivo | Guarda el archivo | :w |
| archivo | Cierra el archivo | :x |
| modo | modo insercion | i |
| modo | modo comando | ESC |
| edicion | elimina palabra | dw |
| edicion | elimina linea actual | dd |
| edicion | Pega lo borrado, extraido o prolongado por debajo de la linea actual | p |
| edicion | elimina la cantidad de palabras especificadas en [numero] | [numero] + dw |
| edicion | deshacer la ultima accion | u |
| edicion | deshacer la ultima N° [veces] acciones hechas | [veces] + u |
| edicion | elimina el caracter | x |
| edicion | elimina los caracter informados | [numero] + x |
| edicion | elimina los caracter informados (hacia la izquierda) | [numero] + X |
| edicion | Elimina desde la posicion del cursor hasta el final de la linea | D |
| edicion | Une la linea actual a la siguiente | J |
| edicion | copia la palabra actual | yw |
| edicion | pasa a minuscula la letra | ~ |
| edicion | Crea una linea abajo de la actual | o |
| edicion | Crea una linea arriba de la actual | O |
| mover | Mueve el cursor una línea hacia abajo (igual que la flecha hacia abajo) | j |
| mover | Mueve el cursor una línea hacia arriba (igual que la flecha hacia arriba) | k |
| mover | Mueve el cursor un carácter a la derecha (igual que la flecha derecha) | l |
| mover | Mueve el cursor un carácter a la izquierda (igual que la flecha izquierda) | h |
| mover | Mueve el cursor al principio de la siguiente palabra | w |
| mover | Mueve el cursor al final de la palabra | e |
| mover | Mueve el cursor al principio de la palabra anterior | w |
| mover | Moverse hasta la palabra N | [numero] + w |
| mover | Mueve el cursor al final de la línea actual (igual que la tecla Fin ) | $ |
| mover | Mueve el cursor al inicio de la línea actual (igual que la tecla Inicio ) | 0 (zero) |
| mover | Salta a la tercera línea (nG salta a la enésima línea) | 3G |
| mover | Salta a la primera línea | 1G |
| mover | Salta a la última línea | Shift+G |
| mover | Mueve hasta contar N° [Numero] letras | [Numero] + l |
| accion | Busca y elimina la palabra | :%s/[palabra] //g |
| accion | Busca la palabra | /[palabra] |
| accion | Busca la palabra hacia atras | ?[palabra] |
| accion | Busca la siguiente palabra | n |
