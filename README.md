# Guía Heap (Montículos)
## Ejercicios
### Parte I: Seguimientos

Dado el siguiente montículo de MÁXIMO (del cual sólo se muestran las prioridades de sus elementos):
```
         [25]
    [15]      [20]
  [6]  [10]
```

1. Ejecutar la siguiente secuencia: Insertar 45, Insertar 22, Remover, Insertar 5. Realice los dibujos del montículo luego de cada momento (tanto el árbol como el arreglo).

   Puede verificar sus pasos en visualgo.net/en/heap

2. En un montículo de MÍNIMO vacío, ejecutar la secuencia (de la cual sólo conocemos las prioridades de los elementos):

   10, 12, 1, 14, 6, 5, 8, 15, 3, 9, 7, 4, 11, 13, 2. Remover, Remover.


### Parte II: Modificando Montículos

Dado un Montículo de MÁXIMO:

3. Escriba un constructor alternativo `NuevoMonticuloMaxDesdeArreglo` que tome como parámetro un arreglo desordenado de elementos y devuelva un montículo que contenga esos elementos. Escriba los tests correspondientes (al menos 3).

4. Escriba una función que, dado un Montículo de tamaño M y un número entero n, con n >= 1 y n <= M,
devuelva el enésimo máximo del montículo (Ej: si n == 1, devolver el primer máximo). Escriba los tests correspondientes (al menos 3).

5. Escriba una función que, dados dos montículos, devuelva un tercero que sea la combinación de ambos. Escriba los tests correspondientes (al menos 3).

### Ejercicios extra

6. Resuelva los puntos anteriores de la Parte II para la Montículo de MÍNIMO.

7. Implementar una Cola de Prioridad utilizada en una clínica de emergencias. La misma debe tener la capacidad de agregar pacientes con su respectiva prioridad (un número entero, donde un número mayor indica mayor prioridad) y de atender al paciente con mayor prioridad. Utilizar un montículo genérico para implementar la cola de prioridad. Escriba los tests correspondientes (al menos 3).
