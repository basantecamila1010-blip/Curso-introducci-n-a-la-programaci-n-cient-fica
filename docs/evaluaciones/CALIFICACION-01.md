# Retroalimentación — Taller evaluativo 01

**Estudiante:** Maria Camila Vallejos Basante · **Taller:** Taller evaluativo 01 — Python y estructuras de datos
**Fecha límite:** 2026-10-14 23:59 · **Versión revisada:** commit `d007306`

Muy buen trabajo: la parte de programación está casi perfecta.

## Nota

| Criterio | Puntos |
|---|---|
| Variables, tipos y operadores (Ej. 1 a 4) | 16 / 20 |
| Condicionales y clasificación (Ej. 5) | 15 / 15 |
| Bucles, acumuladores y control de flujo (Ej. 6 a 8) | 30 / 30 |
| Estructuras de datos nativas (Ej. 9) | 15 / 15 |
| Ejecución sin errores | 8 / 10 |
| Documentación en celdas de texto | 4 / 5 |
| Entrega correcta | 2 / 5 |
| **Total** | **90 / 100** |
| **Nota (0–5)** | **4.50** |

Este taller aporta **13.5 %** de los 15 % del momento evaluativo.

## 1. Variables, tipos y operadores (16 / 20)
**Lo que hizo bien:**
- Las siete variables tienen el tipo correcto y los tipos se muestran con `type()`.
- En el Ejercicio 2 la conversión y los tres errores salen de operaciones, no de números escritos a mano.
- El Ejercicio 3 usa solo `//` y `%`, y el Ejercicio 4 usa `and` y `not` sin ningún `if`. Los resultados son los esperados.

**Lo que puede mejorar:**
- En el Ejercicio 1 cambió los datos de la guía: escribió `"EST_01"` en vez de `"EST-01"` y `"norte"` en vez de `"Norte"`.
- La variable de la altitud se llama `altitud`, y la guía pedía `altitud_m`. Siga los nombres exactos.

## 2. Condicionales y clasificación (15 / 15)
**Lo que hizo bien:**
- La cadena `if` / `elif` / `else` está ordenada de menor a mayor y cubre las cuatro categorías sin huecos.
- Para 41.8 da "Dañina para grupos sensibles", como se esperaba.

## 3. Bucles, acumuladores y control de flujo (30 / 30)
**Lo que hizo bien:**
- Ejercicio 6: descarta los dos `-999.0` con `continue` antes de acumular; quedan 10 lecturas válidas y el promedio es 22.55.
- Ejercicio 7: máximo 58.3, mínimo 7.5 y desviación con dos recorridos, sin `max()`, `min()` ni `sum()`.
- Ejercicio 8: el `while` actualiza la concentración dentro del bloque y termina (10 horas).

## 4. Estructuras de datos nativas (15 / 15)
**Lo que hizo bien:**
- Accede a los datos por clave, desempaqueta las coordenadas en dos variables y usa `get` con "no disponible", sin errores.
- Calcula y clasifica el promedio de cada estación correctamente.

## 5. Ejecución sin errores (8 / 10)
**Lo que hizo bien:**
- El notebook corre completo, de principio a fin, sin errores ni bucles infinitos.

**Lo que puede mejorar:**
- La celda de verificación debía quedar sin modificar, y usted cambió una línea (`altitud_m` por `altitud`) para que le funcionara. Es mejor ajustar su código al nombre pedido que cambiar la verificación.

## 6. Documentación en celdas de texto (4 / 5)
**Lo que hizo bien:**
- Los nueve ejercicios tienen su celda de texto previa y los nombres de variables son claros y en `snake_case`.

**Lo que puede mejorar:**
- El nombre `altitud` no sigue el pedido (`altitud_m`, con la unidad).

## 7. Entrega correcta (2 / 5)
**Lo que hizo bien:**
- El notebook está en `main`, se ve en GitHub y se subió antes del plazo.

**Lo que puede mejorar:**
- No siguió la estructura acordada: el notebook debe estar en la carpeta `ejercicios/` con el nombre exacto `taller-evaluativo-01-calidad-del-aire.ipynb`. Usted lo subió a la raíz del repositorio como `Taller_evaluativo_01_calidad_del_aire.ipynb`.

## ¿El notebook funciona?
Sí: corre completo sin errores y la celda de verificación imprime "Verificación completada sin errores.". Esto fue con una línea de esa celda modificada. Los resultados coinciden con los esperados.

## Para el próximo taller
- Cree la carpeta `ejercicios/` y use el nombre de archivo exacto que pide la guía.
- Copie los datos y los nombres de variables tal como aparecen en la guía.
- No modifique la celda de verificación: si falla, corrija su código.
- Ejecute "Reiniciar y ejecutar todas" antes de entregar, como ya lo hizo esta vez.
