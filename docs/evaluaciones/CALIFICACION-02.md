# Retroalimentación — Taller evaluativo 02: Funciones y POO

**Estudiante:** Maria Camila Vallejos Basante · **Taller:** Taller evaluativo 02 — Funciones y POO
**Fecha límite:** 2026-10-21 00:00 · **Versión revisada:** commit `e4ed243`

Excelente trabajo: el código funciona y los resultados son los esperados.

## Nota

| Criterio | Puntos |
|---|---|
| Funciones: parámetros, valores por defecto y retorno (Ej. 1 a 3) | 19 / 20 |
| `map`, `filter` y `lambda` (Ej. 4) | 10 / 10 |
| Clases, atributos y métodos (Ej. 5 y 7) | 15 / 15 |
| Encapsulamiento y validación (Ej. 6) | 15 / 15 |
| `__repr__` y `__str__` (Ej. 6 a 8) | 10 / 10 |
| Integración de funciones y clases (Ej. 8) | 10 / 10 |
| Ejecución sin errores | 10 / 10 |
| Documentación | 1 / 5 |
| Entrega correcta | 1 / 5 |
| **Total** | **91 / 100** |
| **Nota (0–5)** | **4.55** |

Este taller aporta **13.7 %** de los 15 % del momento evaluativo.

## 1. Funciones: parámetros, valores por defecto y retorno (19 / 20)
**Lo que hizo bien:**
- `calibrar_lectura` tiene los valores por defecto en la firma y usa `return`.
- `es_lectura_valida` rechaza -999.0 y 600.0 y acepta 0.0 y 25.0.
- `promedio_valido` reutiliza `es_lectura_valida`, da 27.0 y devuelve `None` si no hay lecturas válidas. No usa variables globales.

**Lo que puede mejorar:**
- En el Ejercicio 2 probó con 25.5 en lugar de 25.0, que era el valor pedido.

## 2. `map`, `filter` y `lambda` (10 / 10)
**Lo que hizo bien:**
- Obtuvo las 5 lecturas calibradas (de 11.5 a 61.9) y las 2 excedencias, sin bucles ni comprensiones.

## 3. Clases, atributos y métodos (15 / 15)
**Lo que hizo bien:**
- `Lectura` guarda sus tres datos con valores por defecto, convierte mg/m3 a ug/m3 (25.2) y detecta el dato faltante.
- `Estacion` guarda objetos `Lectura` y `valores()` usa `a_microgramos()`, entregando los ocho valores esperados.

## 4. Encapsulamiento y validación (15 / 15)
**Lo que hizo bien:**
- `Sensor` lanza `ValueError` con mensajes claros para código vacío y pendiente menor o igual a cero, antes de guardar nada.
- Usa `_pendiente` e `_intercepto`, y `calibrar` reutiliza `calibrar_lectura`.
- No dejó celdas de prueba que fallen.

## 5. `__repr__` y `__str__` (10 / 10)
**Lo que hizo bien:**
- Los textos de `Sensor`, `Estacion` e `InformeEstacion` coinciden exactamente con lo pedido.

## 6. Integración de funciones y clases (10 / 10)
**Lo que hizo bien:**
- `InformeEstacion` reutiliza `es_lectura_valida`, `promedio_valido`, `categoria_pm25` y `calibrar` del sensor, y da 31.9 y "Moderada".
- `categoria_pm25` usa una sola cadena `if` / `elif` / `else`.
- Hizo además el reto opcional `excedencias`, con resultado correcto (2).

## 7. Ejecución sin errores (10 / 10)
**Lo que hizo bien:**
- El notebook corre completo desde cero sin errores y la celda de verificación imprime el mensaje final.

## 8. Documentación (1 / 5)
**Lo que hizo bien:**
- Cada ejercicio tiene una celda de texto previa que explica qué hace.
- Los nombres siguen `snake_case` y `PascalCase`.

**Lo que puede mejorar:**
- Ninguna función, clase ni método tiene docstring de una línea.
- La celda inicial solo tiene el título: faltan su nombre completo y la fecha.

## 9. Entrega correcta (1 / 5)
**Lo que puede mejorar:**
- No siguió la estructura acordada: el notebook debe estar en la carpeta `ejercicios/` con el nombre exacto `taller-evaluativo-02-funciones-y-poo.ipynb`. Usted lo subió a la raíz del repositorio con el nombre `taller_evaluativo_02_funciones_y_poo.ipynb`.
- Lo mismo ocurre con el notebook del taller 1, que también está en la raíz.
- Sí llegó a tiempo y en la rama `main`.

## ¿El notebook funciona?
Sí. Corre completo sin errores, la celda de verificación imprime "Verificación completada sin errores." y todos los resultados coinciden con los esperados.

## Para el próximo taller
- Guarde el notebook en `ejercicios/` con el nombre exacto que indica la guía.
- Escriba un docstring de una línea en cada función, clase y método.
- En la celda inicial incluya título, nombre completo y fecha.
- Pruebe con los valores exactos que pide la guía (por ejemplo, 25.0).
