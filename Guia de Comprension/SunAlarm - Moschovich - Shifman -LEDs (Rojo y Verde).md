¿Qué tipo de dispositivo es (sensor o actuador)? Explicá brevemente su función principal.
 Actuador. Emite luz para indicar distintos estados del sistema.


¿Qué tipo de señal utiliza para comunicarse con Arduino?
 Señal digital.


¿Cuál es el rango de valores que puede entregar o recibir el componente?
 Recibe 0 V (apagado) o 5 V (encendido).


¿Qué pines de conexión tiene el componente? Ennumerar y describir su función.


Ánodo (+): conectado a un pin de Arduino a través de una resistencia de 220 Ω.


Cátodo (–): conectado a GND.


¿Qué pin o pines de Arduino utilizan para conectarlo? ¿Por qué elegiste esos pines?
 D9 para el LED verde y D8 para el LED rojo, ambos pines digitales para control de encendido y parpadeo.


Dibujá y explicá brevemente el esquema de conexión del componente con Arduino (incluyendo resistencias si son necesarias).
 Pin digital → resistencia 220 Ω → ánodo LED → cátodo → GND. La resistencia limita la corriente.


¿Cuál es el principio de funcionamiento del componente?
 Cuando circula corriente en sentido directo, el diodo emite luz.


¿Utiliza alguna librería particular para programarlo?
 No.


¿Cómo se interpreta el dato de entrada o salida del componente en el programa?
 DigitalWrite(pin, HIGH) lo enciende, digitalWrite(pin, LOW) lo apaga.


¿Qué limitaciones o precauciones eléctricas hay que tener en cuenta?
 Debe usarse siempre con resistencia de 220 Ω para limitar corriente y evitar que se queme.


¿Cómo verificarías que el componente funciona correctamente antes de incorporarlo al proyecto final?
 Cargar un código que haga parpadear el LED y comprobar que encienda y apague correctamente.


Simular en Tinkercad e incluir el link de la simulación.
 (Agregar enlace cuando se realice la simulación).


¿Qué valor o lectura esperás obtener en la simulación si el componente funciona correctamente?
 El LED debe encender y apagarse según el código cargado.


¿Cómo podría fallar el componente o cómo detectarías un mal funcionamiento en el código o en el circuito?
 Si no enciende, revisar polaridad o resistencia; si no apaga, revisar el código o si el pin quedó trabado en HIGH.
