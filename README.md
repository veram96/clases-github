# Actividad 1
Imaginemos que estamos desarrollando un nuevo módulo para la página web de
la empresa X en la que trabajamos. Este módulo muestra los países en
los que tiene presencia organizados por continente.

## Glosario de comandos
`git branch <branch>` <br/>
`git switch <branch>` <br/>
`git add` <br/>
`git commit -m` <br/>
`git push origin <branch>`

## 1. Crear el módulo para los países americanos
Vamos a simular que el módulo para los países américanos ya está listo y en producción (branch `main`).
### Instrucciones
1. Agregar una carpeta llamada `actividad1`.
2. Dentro de la carpeta crear un archivo llamado `américa`.
3. Llenar el archivo con los siguientes países americanos (sí, hay errores)
```
- México
- Colombia
- Argentina
- España
- Uruguay
```
4. Hacer push de los cambios a tu repositorio **a la branch indicada**.

## 2. Crear el módulo para los países europeos
Ahora comenzamos a trabajar en el módulo de países europeos
1. Crear una nueva branch llamada `actividad-1`.
2. Dentro de la carpeta `actividad1` crear un archivo llamado `europa`.
3. Dentro del archivo poner la siguiente lista (sí, está incompleta)
```
- España
- Francia
- Italia
-
-
```

## 3. ¡Tenemos Problemas!
Se recibe feedback de los clientes informando que hay un error en el 
módulo de los países americanos puesto que se esta mostrando un país que no
corresponde. El jefe te pide realizar un **hot-fix** directo en la rama `main`.
