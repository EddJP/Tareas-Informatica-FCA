# Tareas-Algoritmos
#include <stdio.h>
//Calcular el área de un triángulo
int main() {
	float b, h;
	printf ("¡Bienvenido!, te puedo ayudar a calcular el área de un triángulo.");
	printf ("\nPrimero necesitare algunos datos.");
	printf ("\nDame la base: ");
	scanf ("%f", &b);
	printf ("\nAhora dame la altura \n(Recuerda que es un segmento de recta \nque empieza en el vértice más alto y termina en la base formando un ángulo de 90°): " );
	scanf ("%f", &h);
	printf ("¡Listo!, el área es igual a %f cm²", (b*h/2) );
	
	return 0;
}
