# Ecuaciones lineales: métodos iterativos

Proyecto en Java que resuelve un sistema de ecuaciones lineales con los métodos de **Jacobi** y **Gauss-Seidel**.

## Requisitos
- Tener instalado el JDK de Java.
- Ejecutar los comandos desde la carpeta `ecuaciones_lineales` (la que contiene `MetodosIterativos.java`).

## Compilar
Desde la carpeta `ecuaciones_lineales`, ejecuta:

```bash
javac Defmatrix.java MetodosIterativos.java jacobi/MainJacobi.java gauss_seidel/MainGaussSeidel.java
```

## Ejecutar
Para probar el método de Jacobi:

```bash
java ecuaciones_lineales.jacobi.MainJacobi
```

Para probar el método de Gauss-Seidel:

```bash
java ecuaciones_lineales.gauss_seidel.MainGaussSeidel
```

Ambos programas muestran la solución aproximada y el número de iteraciones realizadas.
