# 🧮 Construcción de un Programa en C con Estructuras Secuenciales

Este programa en lenguaje **C** realiza conversiones de una cantidad en **metros** a sus equivalentes en:
- **Kilómetros (km)**
- **Centímetros (cm)**
- **Milímetros (mm)**

  ## 💻 Código en C

  #include <stdio.h>

int main () {

    float numero, k, cm, mm;
    // Datos de entrada
    printf("Ingrese el valor: \n");
    scanf("%f", &numero);
    getchar();
// Proceso
    k = (1 * numero)/ 1000;
    cm = (numero * 100)/ 1;
    mm = (numero * 1000)/1;
//Salida
    printf("Los valores encontrados son: %f,%3.f,%f\n", k,cm,mm);

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
