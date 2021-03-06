# Amplificador-Estereo-Vumetro-DIY
Amplificador de audio estéreo con vúmetro + parlantes (DIY)

**Materiales:**

*Circuito v1*

Amplificador:
- TDA7265 (x1) https://www.microjpm.com/products/ad39295/
- Conector de audio estéreo hembra (jack) de 3.5mm (1/8'') https://www.microjpm.com/products/jack-de-audio-de-3-5-mm-monoaural-encapsulado-para-chasis/
- Fuente de alimentación (+12V y -12V)
- Potenciómetro 50k (x2) o un solo potenciómetro doble de 50k *
- Resistencia 18k (x2)
- Resistencia 10k (x2) *
- Resistencia 1k (x2)
- Resistencia 4.7 (x2)
- Capacitor electrolítico 1000uF (x2)
- Capacitor electrolítico 1uF (x2)
- Capacitor 0.1uF (x4)

Vúmetro:
- LM3915 (x1) *también funciona con el LM3914* https://www.microjpm.com/products/lm3915/
- Capacitor electrolítico 2.2uF (x1)
- Resistencia 1k (x2) *
- Resistencia 470 (x1) *
- Diodo Zener 5.1V (x1) *Funciona cualquier valor entre 3.3V y +Vs* *

*Parlante*

Para 2 parlantes/cajas:
- Altavoces de 8 ohm (x2) https://www.microjpm.com/products/ad45315/
- Tubo de aire (Impreso en 3D)
- Disco para altavoz (Impreso en 3D)
- 2.576 m^2 de MDF o Plywood de 3mm (Corte laser)
- Pegamento para madera o *Super Glue
- Tornillo M4x10 con tuerca (x4)
- Tornillo M4x25 con tuerca (x4)

Notas:

El diagrama v2 no se ha probado en protoboard aún. Tampoco se han a agregado los componentes extra a la lista de materiales.

Se pueden variar los valores *
- Las resistencias de 10k regulan la ganancia del amplificador (valor mínimo recomendado: 560 ohm).
- Las resistencias del divisor de tensión del vúmetro (las de 1k) regulan la tensión Vref que satura a los diodos (ver hoja de datos para más detalles).
- La resistencia de 470 del vúmetro regula la cantidad de corriente de los diodos (si se calienta utilizar una de mayor valor).

**Próximas mejoras:**
- Diseño de caja impresa en 3D para el circuito amplificador (Listo)
- Perilla de control de ganancia. (En progreso, circuito v2)
- Circuito de alimentación para poder conectar el parlante al tomacorriente y no necesitar una fuente de tensión con +V y -V. (En progreso, circuito v2)
- Montaje en placa perforada

**Hojas de datos** con los circuitos de referencia:
- https://www.alldatasheet.com/datasheet-pdf/pdf/25084/STMICROELECTRONICS/TDA7265.html
- https://www.alldatasheet.com/datasheet-pdf/pdf/558236/TI/LM3915.html

**Créditos:**
- Diseño del circuito: Gabriel O. González Rodríguez y Matías Cedeño León.
- Archivos CAD y .stl: Gabriel O. González Rodríguez
