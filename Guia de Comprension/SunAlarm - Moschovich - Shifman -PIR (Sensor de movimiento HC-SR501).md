¿Qué tipo de dispositivo es (sensor o actuador)? Explicá brevemente su función principal.
 Es un sensor. Detecta movimiento de personas u objetos mediante radiación infrarroja.


¿Qué tipo de señal utiliza para comunicarse con Arduino?
 Señal digital (HIGH o LOW).


¿Cuál es el rango de valores que puede entregar o recibir el componente?
 Entrega 0 V (sin movimiento) o 5 V (cuando detecta movimiento).


¿Qué pines de conexión tiene el componente? Ennumerar y describir su función.


VCC: alimentación de 5V.


GND: tierra.


OUT: salida digital al pin de Arduino.


¿Qué pin o pines de Arduino utilizan para conectarlo? ¿Por qué elegiste esos pines?
 Pin digital D3, porque permite leer la señal digital del sensor con digitalRead().


Dibujá y explicá brevemente el esquema de conexión del componente con Arduino (incluyendo resistencias si son necesarias).
 VCC → 5V, GND → GND, OUT → D3. No requiere resistencias externas.


¿Cuál es el principio de funcionamiento del componente?
 Detecta variaciones en la radiación infrarroja emitida por cuerpos calientes (como personas) dentro de su campo de visión.


¿Utiliza alguna librería particular para programarlo?
 No, se maneja con lecturas digitales básicas.


¿Cómo se interpreta el dato de entrada o salida del componente en el programa?
 Si digitalRead(D3) devuelve HIGH, significa que se detectó movimiento. Si devuelve LOW, no hay movimiento.


¿Qué limitaciones o precauciones eléctricas hay que tener en cuenta?
 Requiere entre 5 y 12 V. Al encender, necesita 30–60 segundos de calibración. Evitar colocar cerca de fuentes de calor.


¿Cómo verificarías que el componente funciona correctamente antes de incorporarlo al proyecto final?
 Cargar un código que encienda un LED cuando se detecte movimiento y comprobar que se active al pasar la mano.


Simular en Tinkercad e incluir el link de la simulación.
 (Agregar enlace cuando se realice la simulación).


¿Qué valor o lectura esperás obtener en la simulación si el componente funciona correctamente?
 HIGH (5 V) al detectar movimiento y LOW (0 V) sin movimiento.


¿Cómo podría fallar el componente o cómo detectarías un mal funcionamiento en el código o en el circuito?
 Si el sensor no cambia de estado o se mantiene activado constantemente, puede estar mal alimentado o mal calibrado.



