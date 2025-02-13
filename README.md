# APROXIMACIÓN DEL NÚMERO PI POR EL MÉTODO DE MONTECARLO

## Breve descripción de la aplicación

* Resumen: el software que se publica en este repositorio permite
  [aproximar el número Pi mediante simulación](https://www.youtube.com/watch?v=ELetCV_wX_c)
* Versión: 1.0.

## Compilación del programa

Se ha incluido un `makefile` que define, entre otras tareas, la
generación de un `.jar`:

```console
make jar
```

## Ejecución del programa

```console
java -jar pi.jar <número_de_pasos>
```

## Ejemplo de Ejecución
```console
java -jar pi.jar 1000
```
Esto generará una salida similar a:
```console
El número PI es 3.12
```
## Cómo generar el HTML a partir del Javadoc

El HTML con los comentarios se puede obtener mediante la siguiente
sentencia:

```console
make javadoc
```

## Estructura del código

En esta [imagen](diagrama_clases.png) se puede ver un esquema de las clases existentes en el código

Existen dos clases: `Matematicas.java`, en el paquete `mates`, que
contiene el método que realiza la simulación; y `Principal.java`, en el
paquete `aplicacion`, que invoca el método de simulación.

## License

Este proyecto está bajo la [Licencia](LICENSE).

