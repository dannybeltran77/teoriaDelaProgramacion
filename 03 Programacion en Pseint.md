[🏠 Volver al inicio](index.md)

## 🔹 Algoritmo trasladado a Pseudocódigo

# 💼 Cálculo de Sueldos por Área del Hospital (PSeInt)

Este algoritmo en **PSeInt** calcula el **presupuesto asignado a tres áreas del hospital**:  
- **Gerencia**  
- **Terapia**  
- **Pediatría**  

El usuario ingresa el **presupuesto total**, y el programa distribuye los fondos según porcentajes establecidos.  
El algoritmo utiliza una **estructura secuencial**, donde las instrucciones se ejecutan en orden lógico: entrada → proceso → salida.



| **Etapa** | **Descripción en Pseudocódigo** |
|------------|---------------------------------|
| **🔹 Inicio** | `Inicio` |
| **📦 Declaración de Variables** | `// Variables: Definir sueldoG, sueldoT, sueldoP, pago Como Real;` |
| **📥 Datos de Entrada** | `// Datos de entrada: Escribir "Por favor ingrese el presupuesto total"; Leer pago;` |
| **⚙️ Proceso (Cálculos)** | `// Proceso: sueldoG = (pago * 40) / 100; sueldoT = (pago * 30) / 100; sueldoP = (pago * 30) / 100;` |
| **📤 Salida de Datos** | `// Salida: Escribir "El sueldo que debe recibir cada área es de: ", sueldoG, " Ginecología, ", sueldoT, " Traumatología, ", sueldoP, " Pediatría";` |
| **🏁 Fin del Algoritmo** | `FinAlgoritmo` |

---

## 🧾 Explicación
- El pseudocódigo muestra **la secuencia lógica** de pasos que realiza el algoritmo.  
- Se definen las variables necesarias (`sueldoG`, `sueldoT`, `sueldoP`, `pago`).  
- Se solicita el presupuesto total y se calculan los sueldos por área, distribuidos en **40%, 30% y 30%** respectivamente.  
- Finalmente, se muestra la salida con los resultados calculados.

---

## 🧩 Resultado Esperado
El algoritmo debe mostrar en pantalla los sueldos que corresponden a cada área del hospital, según el presupuesto ingresado por el usuario.


## Ejercicio dos de Pseudocódigo

## 📏 Conversión de Metros a Kilómetros, Centímetros y Milímetros

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

