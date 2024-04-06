#include <stdio.h>

int main() {
	int tamanioCadena = 10;
	char nombre[tamanioCadena];
	char carrera;
	printf("Bienvenid@ a la FCA, SUAYED\n");
	printf("¿Cuál es tu nombre? ");    
	scanf("%s", nombre);
	printf("¡Hola, %s!\n", nombre);
	printf("¿A qué carrera ingresaste? Administración = a, Contaduría = c, Informática = i ");
	scanf(" %c", &carrera);  // Espacio antes de %c para ignorar el salto de línea residual
	if (carrera == 'a') {
		printf("Te deseo mucho éxito futuro administrador.\n");
	} else if (carrera == 'c') {
		printf("Te deseo mucho éxito futuro contador.\n");
	} else if (carrera == 'i') {
		printf("Wow, escogiste la mejor carrera. Mucho éxito futuro informático.\n");
	} else {
		printf("Carrera no reconocida.\n");
	}
	return 0;
}
