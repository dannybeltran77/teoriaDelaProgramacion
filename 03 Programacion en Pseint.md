[🏠 Volver al inicio](index.md)

# 📏 Conversión de Metros a Kilómetros, Centímetros y Milímetros

Este programa en lenguaje **C** realiza conversiones de una cantidad en **metros** a sus equivalentes en:
- **Kilómetros (km)**
- **Centímetros (cm)**
- **Milímetros (mm)**

  ## 💻 Algoritmo en PSeInt

```pseint
Proceso Conversion_Metros
    // Declaración de variables
    Definir numero, k, cm, mm Como Real

    // Entrada de datos
    Escribir "Ingrese el valor en metros: "
    Leer numero

    // Proceso
    k = (1 * numero) / 1000;       
    cm = (numero * 100)/1;      
    mm = (numero * 1000)/1;     

    // Salida
    Escribir ""
    Escribir "Los valores encontrados son:"
    Escribir "Kilómetros: ", k
    Escribir "Centímetros: ", cm
    Escribir "Milímetros: ", mm
FinProceso


# 💼 Cálculo de Sueldos por Área del Hospital (PSeInt)

Este algoritmo en **PSeInt** calcula el **presupuesto asignado a tres áreas del hospital**:  
- **Gerencia**  
- **Terapia**  
- **Pediatría**  

El usuario ingresa el **presupuesto total**, y el programa distribuye los fondos según porcentajes establecidos.  
El algoritmo utiliza una **estructura secuencial**, donde las instrucciones se ejecutan en orden lógico: entrada → proceso → salida.

---

## 💻 Algoritmo en PSeInt

```pseint
Proceso Calculo_Sueldo_Hospital
    // Declaración de variables
    Definir presupuesto, sueldoG, sueldoT, sueldoP Como Real

    // Entrada de datos
    Escribir "Ingrese el presupuesto total del hospital: "
    Leer presupuesto

    // Proceso (Distribución del presupuesto)
    sueldoG <- (presupuesto * 40) / 100   // 40% para Gerencia
    sueldoT <- (presupuesto * 30) / 100   // 30% para Terapia
    sueldoP <- (presupuesto * 30) / 100   // 30% para Pediatría

    // Salida
    Escribir ""
    Escribir "Distribución del presupuesto:"
    Escribir "Gerencia: $", sueldoG
    Escribir "Terapia: $", sueldoT
    Escribir "Pediatría: $", sueldoP
FinProceso

``` 



# 📏 Diagrama de Flujo: Conversión de Metros

En este diagrama se estructura un algoritmo para calcular unidades en km, cm y mm dada una cantidad en metros.

<img width="3840" height="2160" alt="Captura de pantalla (94)" src="https://github.com/user-attachments/assets/737d8a23-2fc9-4737-a168-90e41683228b" />


# 💰 Diagrama de Flujo: Presupuesto

Y en el siguiente programa se representa un algoritmo para calcular el presupuesto que debe recibir determinadas áreas de trabajo dado un monto de dinero para todas las áreas.

<img width="3840" height="2160" alt="Captura de pantalla (95)" src="https://github.com/user-attachments/assets/19369df3-0ba1-44c1-910f-f0ab75a882cd" />


<p align="center">
  <a href="02 Algoritmos, Pseudocódigo y diagrama de flujo.md">⬅️ Anterior</a> |
  <a href="index.md">🏠 Índice</a> |
  <a href="04 Programación por Bloques.md">➡️ Siguiente</a>
</p>

