# 🧮 Construcción de un Programa en C con Estructuras Secuenciales

Este programa en lenguaje **C** realiza conversiones de una cantidad en **metros** a sus equivalentes en:
- **Kilómetros (km)**
- **Centímetros (cm)**
- **Milímetros (mm)**

  ## 💻 Código en C


```c
#include <stdio.h>

int main() {
    float numero, k, cm, mm;

    // Entrada de datos
    printf("Ingrese el valor en metros: ");
    scanf("%f", &numero);

    // Proceso
    k = numero / 1000;     // Conversión a kilómetros
    cm = numero * 100;     // Conversión a centímetros
    mm = numero * 1000;    // Conversión a milímetros

    // Salida
    printf("\nLos valores encontrados son:\n");
    printf("Kilómetros: %.3f\n", k);
    printf("Centímetros: %.2f\n", cm);
    printf("Milímetros: %.2f\n", mm);

    return 0;
}



# 💼 Cálculo de Sueldos por Área de Trabajo



Este programa en lenguaje **C** calcula el **sueldo asignado a diferentes áreas de trabajo**, tomando como base un **presupuesto total** proporcionado por el usuario.  

El propósito es distribuir equitativamente o proporcionalmente los fondos según el área, aplicando una estructura **secuencial** donde las operaciones se ejecutan paso a paso.


## 🧮 Descripción del programa

El usuario ingresa un **presupuesto general**, y el programa calcula el monto destinado a cada área de trabajo.  
Por ejemplo:
- **Administración**  
- **Producción**  
- **Ventas**  
- **Recursos Humanos**

Cada una recibe un porcentaje específico del presupuesto total.


## 💻 Código en C


#include <stdio.h>

int main() {

float g,t,p,numero;

// datos de entrada
printf("Escriba el presupuesto\n");
scanf("%f",&numero);
getchar();

// Proceso

g = (numero * 40)/100;
t = (numero * 30)/100;
p = (numero * 30)/100;

// Datos de salida

printf("El presupuesto para cada area es de:\n%f,%f,%f",g,t,p);

return 0;


}
