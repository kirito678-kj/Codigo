// Definimos los pines de los LEDs
const int ledRojo = 2;
const int ledAmarillo = 3;
const int ledVerde = 4;

void setup() {
    // Configuramos los pines como salidas
    pinMode(ledRojo, OUTPUT);
    pinMode(ledAmarillo, OUTPUT);
    pinMode(ledVerde, OUTPUT);
}

void loop() {
    // Encender luz verde
    digitalWrite(ledVerde, HIGH);
    delay(5000); // 5 segundos
    digitalWrite(ledVerde, LOW);

    // Encender luz amarilla
    digitalWrite(ledAmarillo, HIGH);
    delay(2000); // 2 segundos
    digitalWrite(ledAmarillo, LOW);

    // Encender luz roja
    digitalWrite(ledRojo, HIGH);
    delay(5000); // 5 segundos
    digitalWrite(ledRojo, LOW);
}
