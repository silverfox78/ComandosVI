# Comandos VI
---

## Principales comandos

| **Contexto** | **Accion** | **Comando** |
| :--- | :---: | :---|
| archivo | crear/abrir archivo | vi [nombreArchivo] |
| archivo | Grabar y salir | ESC + :wq |
| archivo | Salir sin Guardar | ESC + :q! |
| edicion | modo insercion | i |
| mover | Mueve el cursor una línea hacia abajo (igual que la flecha hacia abajo) | j |
| mover | Mueve el cursor una línea hacia arriba (igual que la flecha hacia arriba) | k |
| mover | Mueve el cursor un carácter a la derecha (igual que la flecha derecha) | l |
| mover | Mueve el cursor un carácter a la izquierda (igual que la flecha izquierda) | h |
| mover | Mueve el cursor al principio de la siguiente palabra | w |
| mover | Mueve el cursor al final de la palabra | e |
| mover | Mueve el cursor al principio de la palabra anterior | w |
| mover | Mueve el cursor al final de la línea actual (igual que la tecla Fin ) | $ |
| mover | Mueve el cursor al inicio de la línea actual (igual que la tecla Inicio ) | 0 (zero) |
| mover | Salta a la tercera línea (nG salta a la enésima línea) | 3G |
| mover | Salta a la primera línea | 1G |
| mover | Salta a la última línea | Shift+G |

* Para crear un archivo

```{r, engine='sh', count_lines}
    vi [Nombre_archivo]
```

* Para entrar en el modo de **insercion**, se debe presionar la letra **i**




```{r, engine='sh', count_lines}

```