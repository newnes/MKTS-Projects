# Jump into Fractal Dispersion (JIFD) - Especificaciones Técnicas

## Visión General del Concepto

**JIFD** es un indicador avanzado que trasciende el análisis de volumen tradicional. No solo mide la *cantidad* de operaciones, sino que **mapea la huella fractal (dispersión) que los impulsos de volumen dejan en la estructura de precios**.

Identifica zonas de acumulación y distribución *reales* —que no necesariamente coinciden con picos o valles de precio— mediante la relación entre el flujo de capital (volumen) y la dispersión fractal del precio que este genera. Esto permite detectar la "manipulación silenciosa" y anticipar movimientos de reversión a la media de la huella de volumen.

## Base Matemática

### Núcleo del Cálculo: Huella de Volumen Fractal
El algoritmo propietario de JIFD opera en múltiples *timeframes* para calcular la **media hipotética de volumen operado** de un activo. A partir de esta base, identifica **impulsos alcistas y bajistas significativos** que dejan una "huella" en el precio.

**La innovación clave:** JIFD no asume que estos impulsos ocurran solo en máximos o mínimos. Detecta la huella de volumen en cualquier punto del recorrido del precio, revelando la dinámica real de la acumulación y distribución.


### Señales Visuales e Interpretación
El indicador se compone de tres líneas maestras que representan el valor numérico de la huella de volumen:

| Señal | Color | Descripción |
|:---|:---:|:---|
| **Línea de Huella Alcista** | `Lime` | Representa el límite numérico superior alcanzado por impulsos de volumen comprador. Una ruptura por arriba sugiere una posible continuación alcista **sostenible**. |
| **Línea de Media Hipotética** | `Cyan` | Actúa como el eje de equilibrio. Una reversión a esta línea después de un impulso confirma la fuerza de la huella inicial. |
| **Línea de Huella Bajista** | `Red` | Representa el límite numérico inferior alcanzado por impulsos de volumen vendedor. Una ruptura por debajo sugiere una posible continuación bajista **sostenible**. |


## Ventaja Técnica y Aplicación

### Dinámica de Mercado que JIFD Revela:
1.  **Acumulación/Distribución Encubierta:** Identifica grandes operaciones que no ocurren en los extremos, sino en el desarrollo de la tendencia.
2.  **Reversión a la Huella Media:** El precio suele revertir hacia la media hipotética (`Cyan`) después de probar una huella (`Lime`/`Red`), especialmente si no hay volumen suficiente para una ruptura sostenida.
3.  **Rupturas Sostenibles vs. Falsas:** Una ruptura *con volumen confirmatorio* más allá de una huella previa es una señal de alta confiabilidad de continuación.

### Aplicación en Trading:
- **Soporte/Resistencia Dinámicos:** Las líneas Lime y Red actúan como niveles de soporte y resistencia basados en volumen real.
- **Confirmación de Rupturas:** Una ruptura de precio acompañada de una ruptura de la huella de volumen confirma la validez del movimiento.
- **Detección de Debilidad:** Si el precio supera una huella pero no puede cerrar fuera de ella, indica agotamiento y una posible reversión.

## Limitaciones y Consideraciones

- El indicador es **lagging** por naturaleza, ya que requiere que el impulso de volumen ya haya ocurrido para formar la huella.
- Funciona mejor en activos con **alto volumen y liquidez** (índices, Forex mayores, grandes capitalizaciones).
- La "media hipotética" es dinámica y se adapta a las condiciones cambiantes del mercado.

---
*Última actualización: $(date +%Y-%m-%d)*