[🏠 Volver al inicio](index.md)


# 💼 Cálculo de Sueldos por Área del Hospital (PSeInt)

### 🏥 Distribución del Presupuesto en un Hospital

En un hospital existen tres áreas: **Ginecología, Pediatría y Traumatología**.  
El presupuesto anual del hospital se reparte conforme a la siguiente tabla:

- 🩺 **Ginecología:** 40%  
- 🦴 **Traumatología:** 30%  
- 🧒 **Pediatría:** 30%  

Obtener la cantidad de dinero que recibirá cada área para cualquier monto presupuestal.  

---
## 🧾 Análisis  

El usuario ingresa el **presupuesto total**, y el programa distribuye los fondos según porcentajes establecidos.  
El algoritmo utiliza una **estructura secuencial**, donde las instrucciones se ejecutan en orden lógico: entrada → proceso → salida.

- Se definen las variables necesarias (`sueldoG`, `sueldoT`, `sueldoP`, `pago`).  
- Se solicita el presupuesto total y se calculan los sueldos por área, distribuidos en **40%, 30% y 30%** respectivamente.  
- Finalmente, se muestra la salida con los resultados calculados.

  - **Datos de entrada:**  
  El valor que va a ingresar el usuario como variable: `numero`.  

## 🧩 Resultado Esperado
El algoritmo debe mostrar en pantalla los sueldos que corresponden a cada área del hospital, según el presupuesto ingresado por el usuario.

## 🔹 Algoritmo dos trasladado a Pseudocódigo

```pseudocode
Proceso Presupuesto_Hospital
    // Declaración de variables
    Definir sueldoG, sueldoT, sueldoP, presupuesto Como Real

    // Entrada de datos
    Escribir "Ingrese el presupuesto: ";
    Leer presupuesto;

    // ⚙️ Proceso
    sueldoG = (presupuesto * 40) / 100
    sueldoT = (presupuesto * 30) / 100
    sueldoP = (presupuesto * 30) / 100

    // 📤 Salida de resultados
    Escribir "El sueldo para cada área es de: "
    Escribir "Ginecología: ", sueldoG
    Escribir "Traumatología: ", sueldoT
    Escribir "Pediatría: ", sueldoP
FinProceso

```

---

## Ejercicio dos de Pseudocódigo

# 📏 Conversión de Metros a Otras Unidades

Realice un programa que, tomando una cantidad expresada en **metros**, la transforme a su equivalente en **kilómetros**, **centímetros** y **milímetros**.

## 🔍 Análisis

En el presente problema se pide determinar los valores en **km, cm y mm** dada cierta cantidad en metros.  

**Datos de entrada:**  
- Valor ingresado por el usuario como variable: `numero`

**Proceso:**  
Realizaremos una **regla de tres** para cada parámetro solicitado:

- `km = (1 * numero) / 1000`  
- `cm = (numero * 100) / 1`  
- `mm = (numero * 1000) / 1`

**Datos de salida:**  
- Resultados deseados: `km`, `cm` y `mm`


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


``` 



# 📏 Diagrama de Flujo: Conversión de Metros



<img width="3840" height="2160" alt="Captura de pantalla (94)" src="https://github.com/user-attachments/assets/737d8a23-2fc9-4737-a168-90e41683228b" />

*Figura 1.En este diagrama se estructura un algoritmo para calcular unidades en km, cm y mm dada una cantidad en metros.

# 💰 Diagrama de Flujo: Presupuesto


<img width="3840" height="2160" alt="Captura de pantalla (95)" src="https://github.com/user-attachments/assets/19369df3-0ba1-44c1-910f-f0ab75a882cd" />

*Figura 1.Y en el siguiente programa se representa un algoritmo para calcular el presupuesto que debe recibir determinadas áreas de trabajo dado un monto de dinero para todas las áreas.


<p align="center">
  <a href="02 Algoritmos, Pseudocódigo y diagrama de flujo.md">⬅️ Anterior</a> |
  <a href="index.md">🏠 Índice</a> |
  <a href="04 Programación por Bloques.md">➡️ Siguiente</a>
</p>

