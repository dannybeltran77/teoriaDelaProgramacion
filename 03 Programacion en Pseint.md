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
    k <- numero / 1000       // Conversión a kilómetros
    cm <- numero * 100       // Conversión a centímetros
    mm <- numero * 1000      // Conversión a milímetros

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

