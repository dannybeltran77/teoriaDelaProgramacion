# 📚 Algoritmos, Pseudocódigo y Diagrama de Flujo



## 🔹 Algoritmo

Un **algoritmo** es una serie de pasos ordenados que siguen una secuencia lógica para hallar una solución a un determinado problema.



## 📝 Pseudocódigo

El **pseudocódigo** es la forma de representar un algoritmo en un lenguaje que pueda ser entendido por las personas; en este caso, el **español o lenguaje natural**.

---

## 🔄 Diagrama de Flujo

El **diagrama de flujo** es la forma de describir un algoritmo mediante figuras como **romboides, rectángulos y flechas**, que permiten visualizar el proceso paso a paso.



## 🏥 Problema Planteado en Pseudocódigo

En un hospital existen tres áreas:

- **Ginecología**  
- **Pediatría**  
- **Traumatología**

El presupuesto anual del hospital se reparte conforme a la siguiente tabla:

| Área | Porcentaje |
|------|-------------|
| **Ginecología** | 40% |
| **Traumatología** | 30% |
| **Pediatría** | 30% |

**🎯 Objetivo:**  
Obtener la cantidad de dinero que recibirá cada área para cualquier monto presupuestal.



# 🧮 Análisis del Problema

Debemos determinar la cantidad de dinero que debe recibir cada área al obtener cierto monto de dinero.  
Para ello, establecemos lo siguiente:



## 📊 Datos

El presupuesto anual debe ser repartido entre tres áreas del hospital:

- **Ginecología:** 40%  
- **Traumatología:** 30%  
- **Pediatría:** 30%  

**Constantes:**  
- `G = 40%`  
- `T = 30%`  
- `P = 30%`



## ⚙️ Pseudocódigo

// Varriables
Definir sueldoG, sueldoT, sueldoP, pago Como Real;

// Datos de entrada
Escribir "Por favor ingrese el presupuesto total"
Leer pago;

// Proceso
sueldoG = (pago * 40) / 100
sueldoT = (pago * 30) / 100
sueldoP = (pago * 30) / 100

// Salida
Escribir "El sueldo que debe recibir cada área es de: ", sueldoG, " Ginecología, ", sueldoT, " Traumatología, ", sueldoP, " Pediatría"

FinAlgoritmo

📸 Pseudocódigo en Pseint

<img width="3183" height="1474" alt="Captura de pantalla (75)" src="https://github.com/user-attachments/assets/8827687c-8f97-42d5-827a-25cf3d1a89de" />


🔄 Representación en Diagrama de Flujo:

Se aplica la misma metodología que en el pseudocódigo, con la diferencia de que en el diagrama de flujo la información se organiza en figuras geométricas:

| Elemento                | Figura         | Descripción                           |
| ----------------------- | -------------- | ------------------------------------- |
| **Inicio / Fin**        | Óvalo          | Indica el inicio o fin del proceso    |
| **Variables**           | Rectángulo     | Declaración o asignación de variables |
| **Datos de entrada**    | Romboide rojo  | Entrada de información                |
| **Procesos**            | Rectángulo     | Cálculos o asignaciones               |
| **Resultados / Salida** | Romboide verde | Muestra los resultados                |


Este enfoque facilita la comprensión visual del algoritmo y permite identificar rápidamente el tipo de operación que se realiza en cada paso.

📊 Ejemplo de Diagrama de Flujo:

<img width="1330" height="2039" alt="Captura de pantalla (76)" src="https://github.com/user-attachments/assets/fbe333c4-baf5-4185-9eee-af01f9202c12" />

