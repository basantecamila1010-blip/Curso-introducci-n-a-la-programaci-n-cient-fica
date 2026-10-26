# Retroalimentación — Taller evaluativo 03 (NumPy)

**Estudiante:** Maria Camila Vallejos Basante · **Taller:** Taller evaluativo 03 — NumPy
**Fecha límite:** 2026-10-26 23:59 · **Versión revisada:** commit `4393659`

Excelente trabajo: casi todo el taller quedó correcto y coincide con los valores esperados.

## Nota

| Criterio | Puntos |
|---|---|
| Creación y atributos de arreglos (Ej. 1) | 10 / 10 |
| Indexación y slicing (Ej. 2) | 10 / 10 |
| Máscaras booleanas (Ej. 3) | 15 / 15 |
| Vectorización y broadcasting (Ej. 4) | 15 / 15 |
| Estadística por eje y funciones universales (Ej. 5 y 6) | 20 / 20 |
| Integración (Ej. 7) | 10 / 10 |
| Ejecución sin errores | 10 / 10 |
| Documentación | 4 / 5 |
| Entrega correcta | 1 / 5 |
| **Total** | **95 / 100** |
| **Nota (0–5)** | **4.75** |

Este taller aporta **14.3 %** de los 15 % del momento evaluativo.

## 1. Creación y atributos de arreglos (10 / 10)
**Lo que hizo bien:**
- `lecturas_crudas` se creó con `np.array` a partir de una lista de listas, y los atributos se leen del propio arreglo.
- `dias`, `pendientes` e `interceptos` son correctos.

## 2. Indexación y slicing (10 / 10)
**Lo que hizo bien:**
- Cada resultado sale de una sola expresión, con el índice negativo donde se pedía.
- El bloque tiene forma (3, 4) y los valores correctos.

## 3. Máscaras booleanas (15 / 15)
**Lo que hizo bien:**
- `es_util` une las dos comparaciones con `&` y paréntesis.
- Resultan 2 faltantes, 5 lecturas útiles y promedio 27.0, sin bucles.

## 4. Vectorización y broadcasting (15 / 15)
**Lo que hizo bien:**
- Convirtió pendientes e interceptos en columnas (5, 1) y calibró todo de una vez.
- La explicación en texto de por qué fallaba (5, 7) con (5,) es clara y correcta.
- El promedio calibrado de SBC-A da 31.9.

## 5. Estadística por eje y funciones universales (20 / 20)
**Lo que hizo bien:**
- Promedios por sensor y por día con el eje correcto, máximos y media sobre el límite correctos.
- `excedente`, `desvio_sensor_b` y `en_alerta` usan `np.maximum`, `np.abs`, `np.round` y una copia; quedan 8 celdas en alerta y `calibradas` no cambia.

## 6. Integración (10 / 10)
**Lo que hizo bien:**
- Los conteos son 9, 18, 7 y 1 (suman 35), sin lecturas sin categoría ni repetidas.
- `dia_pico` es 5 y las dos líneas de salida coinciden con lo pedido.

## 7. Ejecución sin errores (10 / 10)
**Lo que hizo bien:**
- El notebook corre completo sin errores y no dejó celdas de prueba que fallen.

## 8. Documentación (4 / 5)
**Lo que hizo bien:**
- Los siete ejercicios tienen su celda de texto previa y los nombres de variables siguen `snake_case`.

**Lo que puede mejorar:**
- La celda inicial solo tiene el título: faltan su nombre completo y la fecha.

**Cómo corregirlo:**
- Abra la primera celda de texto y, debajo del título, escriba su nombre completo y la fecha de entrega.

## 9. Entrega correcta (1 / 5)
**Lo que puede mejorar:**
- No siguió la estructura acordada: el notebook debe estar en la carpeta `ejercicios/` con el nombre exacto `taller-evaluativo-03-numpy.ipynb`. Usted lo subió a la raíz del repositorio como `taller_evaluativo_03_numpy.ipynb`.
- Lo mismo ocurre con los talleres anteriores, que también están fuera de `ejercicios/`.

**Cómo corregirlo:**
- Cree la carpeta `ejercicios/` en la raíz del repositorio, mueva allí el notebook y cámbiele el nombre a `taller-evaluativo-03-numpy.ipynb` (con guiones, no guiones bajos). Luego suba el cambio a la rama `main`.
- Mueva también los talleres anteriores a `ejercicios/` y revise que sus nombres coincidan con los indicados en cada guía.

## ¿El notebook funciona?
Sí. Corre completo sin errores, la celda de verificación imprime "Verificación completada sin errores." y todos los resultados coinciden con los esperados.

## Para el próximo taller
- Cree la carpeta `ejercicios/`, suba allí el notebook y verifique en GitHub que se vea en la rama `main`.
- Use el nombre exacto indicado en la guía, con guiones y minúsculas.
- Escriba en la primera celda el título, su nombre completo y la fecha.
- Ejecute "Reiniciar y ejecutar todas" antes de entregar, como hizo esta vez.
