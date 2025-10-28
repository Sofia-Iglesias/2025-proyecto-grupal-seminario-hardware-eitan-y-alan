¿Qué tipo de dispositivo es (sensor o actuador)? Explica brevemente su función principal.
 Es un sensor. Su función es detectar la cantidad de luz ambiental para diferenciar entre día y noche.


¿Qué tipo de señal utiliza para comunicarse con Arduino?
 Señal analógica, ya que entrega valores de voltaje variables según la intensidad de la luz.


¿Cuál es el rango de valores que puede entregar o recibir el componente?
 Entrega valores entre 0 y 1023 en la lectura analógica de Arduino, equivalentes a variaciones de voltaje entre 0 y 5 V.


¿Qué pines de conexión tiene el componente? Enumerar y describir su función.


Un pin se conecta a 5V.


El otro pin se conecta al pin A0 del Arduino y a una resistencia de 10 kΩ hacia GND.


¿Qué pin o pines de Arduino utilizan para conectarlo? ¿Por qué elegiste esos pines?
 Se usa el pin A0 porque es un pin analógico capaz de leer variaciones de voltaje mediante analogRead().


Dibujá y explicá brevemente el esquema de conexión del componente con Arduino (incluyendo resistencias si son necesarias).
 5V → LDR → A0 → resistencia 10 kΩ → GND.
 Se usa un divisor de tensión para convertir los cambios de resistencia en variaciones de voltaje que Arduino pueda leer.


¿Cuál es el principio de funcionamiento del componente?
 Su resistencia disminuye cuando hay más luz y aumenta cuando hay oscuridad. Arduino mide el voltaje resultante para determinar el nivel de luminosidad.


¿Utiliza alguna librería particular para programarlo?
 No, se programa directamente con lecturas analógicas.


¿Cómo se interpreta el dato de entrada o salida del componente en el programa?
 A través del valor obtenido con analogRead(A0). Un valor alto indica luz (día) y uno bajo indica oscuridad (noche).


¿Qué limitaciones o precauciones eléctricas hay que tener en cuenta?
 No aplicar más de 5V. Debe usarse con una resistencia en serie (10 kΩ) para evitar cortocircuitos y lecturas erróneas.


¿Cómo verificarías que el componente funciona correctamente antes de incorporarlo al proyecto final?
 Con un programa que muestre en el monitor serie el valor leído por analogRead(A0) y observar si cambia al tapar o iluminar el sensor.


Simular en Tinkercad e incluir el link de la simulación.
 (Agregar enlace cuando se haga la simulación).


¿Qué valor o lectura esperás obtener en la simulación si el componente funciona correctamente?
 Valores cercanos a 900–1023 con mucha luz y 0–200 con oscuridad.


¿Cómo podría fallar el componente o cómo detectarías un mal funcionamiento en el código o en el circuito?
 Si el valor no cambia al variar la luz, puede estar mal conectado, tener una resistencia incorrecta o estar dañado.


