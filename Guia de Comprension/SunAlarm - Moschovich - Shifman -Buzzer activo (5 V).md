Buzzer activo (5 V)
¿Qué tipo de dispositivo es (sensor o actuador)? Explicá brevemente su función principal.
 Actuador. Emite un sonido cuando se activa, usado como alarma.


¿Qué tipo de señal utiliza para comunicarse con Arduino?
 Señal digital.


¿Cuál es el rango de valores que puede entregar o recibir el componente?
 Recibe 0 V (apagado) o 5 V (encendido).


¿Qué pines de conexión tiene el componente? Ennumerar y describir su función.


Positivo (+): conectado al pin de salida digital de Arduino.


Negativo (–): conectado a GND.


¿Qué pin o pines de Arduino utilizan para conectarlo? ¿Por qué elegiste esos pines?
 Pin D10, porque es un pin digital que puede controlar directamente el buzzer con digitalWrite().


Dibujá y explicá brevemente el esquema de conexión del componente con Arduino (incluyendo resistencias si son necesarias).
 D10 → positivo del buzzer, negativo → GND. No requiere resistencias adicionales.


¿Cuál es el principio de funcionamiento del componente?
 Al aplicarle 5 V, el buzzer genera vibraciones internas que producen sonido.


¿Utiliza alguna librería particular para programarlo?
 No, se controla con señales digitales.


¿Cómo se interpreta el dato de entrada o salida del componente en el programa?
 HIGH activa el sonido, LOW lo apaga.


¿Qué limitaciones o precauciones eléctricas hay que tener en cuenta?
 No exceder los 5 V ni conectar sin respetar polaridad.


¿Cómo verificarías que el componente funciona correctamente antes de incorporarlo al proyecto final?
 Usar un código que lo active unos segundos y comprobar si emite sonido.


Simular en Tinkercad e incluir el link de la simulación.
 (Agregar enlace cuando se realice la simulación).


¿Qué valor o lectura esperás obtener en la simulación si el componente funciona correctamente?
 El buzzer debe emitir sonido cuando el pin esté en HIGH.


¿Cómo podría fallar el componente o cómo detectarías un mal funcionamiento en el código o en el circuito?
 Si no suena, revisar la polaridad y la conexión; si suena constantemente, revisar la lógica del programa.
