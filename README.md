# Semaforo
// C++ code
//
void setup()
{
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(9, OUTPUT);
}

void loop()
{
  digitalWrite(7, HIGH);// Encender el Led Rojo
  delay(5000); // Esperar por 5000 milisegundos
  digitalWrite(7, LOW);// Apagar el Led Rojo
  delay(1000); // Esperar por 1000 milisegundos
  digitalWrite(7, HIGH);// Encender el Led amarillo
  delay(300); // Esperar por 300 milisegundos
  digitalWrite(7, LOW);// Apagar el Led amarillo
  delay(300);
  digitalWrite(7, HIGH);// Encender el Led amarillo
  delay(300);
  digitalWrite(7, LOW);// Apagar el Led amarillo
  delay(300);
  digitalWrite(8, HIGH);// Encender el Led amarillo
  delay(1000); // Esperar por 1000 milisegundos
  digitalWrite(8, LOW);// Apagar el Led amarillo
  delay(300);
  digitalWrite(8, HIGH);
  delay(500); 
  digitalWrite(8, LOW);
  delay(300);
  digitalWrite(8, HIGH);
  delay(500); 
  digitalWrite(8, LOW);
  delay(300);
  digitalWrite(9, HIGH);// Encender el Led verde
  delay(6000); // Esperar por 6000 milisegundos
  digitalWrite(9, LOW);// Apagar el Led verde
  delay(1000); // Esperar por 1000 milisegundos
  digitalWrite(9, HIGH);// Encender el Led amarillo
  delay(500); // Esperar por 500 milisegundos
  digitalWrite(9, LOW);// Apagar el Led amarillo
  delay(300);
  digitalWrite(9, HIGH);// Encender el Led amarillo
  delay(300); // Esperar por 300 milisegundos
  digitalWrite(9, LOW);// Apagar el Led amarillo
  delay(300);
  digitalWrite(8, HIGH);
  delay(1000); 
  digitalWrite(8, LOW);
  delay(300); 
  digitalWrite(8, HIGH);
  delay(500); 
  digitalWrite(8, LOW);
  delay(300);
   digitalWrite(8, HIGH);
  delay(500); 
  digitalWrite(8, LOW);
  delay(300);
}
