[🏠 Volver al inicio](index.md)

# 📚 Algoritmos, Pseudocódigo y Diagrama de Flujo



## 🔹 Algoritmo

Un **algoritmo** es una serie de pasos ordenados que siguen una secuencia lógica para hallar una solución a un determinado problema.

🧠 Algoritmos


Todo algoritmo tiene un principio y un final.
Es un conjunto de pasos ordenados que permiten resolver un problema o realizar una tarea específica.

---

# 🧩 Pasos para resolver un problema

---

## 🔍 1. Análisis

Consiste en estudiar bien el problema, identificando:

- 🧾 **Entradas:** Datos o información que el usuario ingresa al programa.
- ⚙️ **Procesos:** Operaciones o fórmulas necesarias para llegar a la solución.
- 📤 **Salidas:** Resultados obtenidos de la solución del problema.

---

## 🧱 2. Diseño del algoritmo

Consiste en estructurar el algoritmo mediante:

- ✍️ **Pseudocódigo**
- 🔄 **Diagrama de flujo**

Estas herramientas permiten visualizar la lógica antes de programar.

---

## 💻 3. Codificación

Proceso de traducir los algoritmos a un lenguaje de programación, convirtiéndolos en un programa ejecutable.

---

## 🧪 4. Pruebas

Etapa donde se verifica que el programa:

- No tenga errores 🐞
- Funcione correctamente ⚙️
- Cumpla con los resultados esperados
✅

---
# 🧮 Clasificación de los algoritmos

| Tipo | Descripción |
|------|------------|
| 🗣️ **Cualitativos** | Se expresan con frases o palabras. |
| 🔢 **Cuantitativos** | Utilizan fórmulas o procesos matemáticos. |

---

| Tipo de dato    | Representación | Descripción                                 |
| --------------- | -------------- | ------------------------------------------- |
| 🔢 **Entero**   | `int`          | Números enteros (positivos o negativos)     |
| 💧 **Real**     | `float`        | Números con decimales                       |
| ⚖️ **Lógico**   | `boolean`      | Verdadero o falso (`true` / `false`)        |
| 🔡 **Carácter** | `char`         | Un solo carácter, por ejemplo `'A'` o `'9'` |

## ⚙️ Operadores en Programación

| 🧮 Operador | Significado                     | Ejemplo  | Resultado |
| ----------- | ------------------------------- | -------- | --------- |
| `+`         | Suma                            | `5 + 3`  | `8`       |
| `-`         | Resta                           | `10 - 4` | `6`       |
| `*`         | Multiplicación                  | `6 * 2`  | `12`      |
| `/`         | División                        | `8 / 2`  | `4`       |
| `%`         | Módulo (residuo)                | `7 % 3`  | `1`       |
| `**`        | Potencia (en algunos lenguajes) | `2 ** 3` | `8`       |



| ⚙️ Operador | Significado     | Ejemplo       | Resultado   |
| ----------- | --------------- | ------------- | ----------- |
| `++`        | Incrementa en 1 | `x++` o `++x` | `x = x + 1` |
| `--`        | Decrementa en 1 | `x--` o `--x` | `x = x - 1` |


---

# 🏷️ Identificadores

Los identificadores son nombres que se usan para representar **variables** o **constantes** dentro de un programa.

---

## 🔸 Tipos

- **Variable:** Su valor puede cambiar durante la ejecución del programa.  
- **Constante:** Su valor permanece fijo durante toda la ejecución.

---

## ✍️ Recomendaciones

- Utilizar el formato **lowerCamelCase** para nombres (por ejemplo: `sumaTotal`, `edadUsuario`).  
- 🚫 Evitar espacios, acentos y caracteres especiales.  
- Usar el operador de asignación (`=`) para definir valores.

---

## 📝 Pseudocódigo

El **pseudocódigo** es la forma de representar un algoritmo en un lenguaje que pueda ser entendido por las personas; en este caso, el **español o lenguaje natural**.

---


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

## 🔍 Análisis

En este problema debemos determinar el **porcentaje en dólares** que recibe cada área de trabajo dado cierto presupuesto.

**Datos de entrada:**  
- Presupuesto ingresado por el usuario: `presupuesto`

**Proceso:**  
Se realiza una **regla de tres** para cada área:

- `sueldoG = (presupuesto * 40) / 100`  
- `sueldoT = (presupuesto * 30) / 100`  
- `sueldoP = (presupuesto * 30) / 100`

**Datos de salida:**  
- Cantidad de dinero que recibe cada área: `sueldoG`, `sueldoT` y `sueldoP`



---

# 🧮 Objetivo

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

## Prueba de Escritorio

Una prueba de escritorio es una técnica utilizada para verificar que un algoritmo o programa funciona correctamente antes de ejecutarlo en una computadora.

# 🧾 Pruebas de Escritorio — Distribución del Presupuesto (Valores Bajos)

| Prueba | Presupuesto (`pago`) | Cálculo Ginecología (`sueldoG`) | Cálculo Traumatología (`sueldoT`) | Cálculo Pediatría (`sueldoP`) | Resultado Esperado |
|--------|---------------------|---------------------------------|----------------------------------|--------------------------------|------------------|
| 1      | 1000                | 1000 * 40 / 100 = 400           | 1000 * 30 / 100 = 300            | 1000 * 30 / 100 = 300          | G: 400, T: 300, P: 300 |
| 2      | 500                 | 500 * 40 / 100 = 200            | 500 * 30 / 100 = 150             | 500 * 30 / 100 = 150           | G: 200, T: 150, P: 150 |
| 3      | 750                 | 750 * 40 / 100 = 300            | 750 * 30 / 100 = 225             | 750 * 30 / 100 = 225           | G: 300, T: 225, P: 225 |



## Primer ejercicio implementado en Pseint



<img width="3840" height="2160" alt="Captura de pantalla (102)" src="https://github.com/user-attachments/assets/a0c85479-91e1-42f1-98e8-97679b10a5ac" />
*Figura 1.La imagen muestra el diseño del algoritmo representado en pseudocódigo utilizando PSeInt

## Ejecución de pseudocódigo de Prueba de Escritorio.

![821d578c-6b32-456c-b8a9-1839f05975e2](https://github.com/user-attachments/assets/3f723722-8269-4df3-b0d2-13edd9adc579)

*Figura 2.Resultado de la ejecución del primer ejemplo de prueba de escritorio.

![bf3dcdfb-ac8d-4fe0-8eed-edaa3163945d](https://github.com/user-attachments/assets/05f83351-4b2b-4ec6-8070-6bb5f82fc550)

*Figura 3.Resultado de la ejecución del segundo ejemplo de prueba de escritorio.

![e1475c35-839f-484b-9c68-fa780c2c60f9](https://github.com/user-attachments/assets/f1cfe9b8-d03c-4a1b-839f-973ce4e12849)

*Figura 4.Resultado de la ejecución del tercer ejemplo de prueba de escritorio.

## ⚙️ Pseudocódigo segundo ejercicio


# 📏 Programa: Conversión de Metros

Realice un programa que, tomando una cantidad expresada en **metros**, la transforme a su equivalente en:

- **Kilómetros (km)**  
- **Centímetros (cm)**  
- **Milímetros (mm)**


## 🧠 Análisis Resumido: Entradas, Proceso y Salidas

### 📥 Entradas
Datos proporcionados por el usuario para que el algoritmo realice los cálculos.  
- Variable de entrada: `numero` (cantidad en metros)

### ⚙️ Proceso
Operaciones que transforman la entrada en los resultados solicitados.  
- Conversiones:  
  ```text
  km = numero / 1000
  cm = numero * 100
  mm = numero * 1000

### Salida
Son los resultados esperados en este caso: Km, CM, Mm.
```
| 🧩 **Etapa**                    | 💻 **Pseudocódigo (PSeInt)**                                                                                                                                    |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **🔹 Inicio** | ```pseudocode
``` |
| **📦 Declaración de Variables** | ```pseudocode
// Variables  
Definir sueldoG, sueldoT, sueldoP, pago Como Real;
``` |
| **📥 Datos de Entrada** | ```pseudocode
// Datos de entrada  
Escribir "Por favor ingrese el presupuesto total"  
Leer pago;
``` |
| **⚙️ Proceso (Cálculos)** | ```pseudocode
// Proceso  
sueldoG = (pago * 40) / 100  
sueldoT = (pago * 30) / 100  
sueldoP = (pago * 30) / 100
``` |
| **📤 Salida de Datos** | ```pseudocode
// Salida  
Escribir "El sueldo que debe recibir cada área es de: ", sueldoG, " ", sueldoT, " ", sueldoP, " 
``` |
| **🏁 Fin del Algoritmo** | ```pseudocode
FinAlgoritmo
``` |
```
---


# 🧾 Prueba de Escritorio — Conversión de Metros

| Prueba | Metros (`numero`) | Cálculo Kilómetros (`km`) | Cálculo Centímetros (`cm`) | Cálculo Milímetros (`mm`) | Resultado Esperado |
|--------|-----------------|---------------------------|----------------------------|---------------------------|------------------|
| 1      | 100             | 100 / 1000 = 0.1         | 100 * 100 = 10000          | 100 * 1000 = 100000       | km: 0.1, cm: 10000, mm: 100000 |
| 2      | 200             | 200 / 1000 = 0.2         | 200 * 100 = 20000          | 200 * 1000 = 200000       | km: 0.2, cm: 20000, mm: 200000 |
| 3      | 150             | 150 / 1000 = 0.15        | 150 * 100 = 15000          | 150 * 1000 = 150000       | km: 0.15, cm: 15000, mm: 150000 |



## 📸 Pseudocódigo en Pseint



<img width="3183" height="1474" alt="Captura de pantalla (75)" src="https://github.com/user-attachments/assets/8827687c-8f97-42d5-827a-25cf3d1a89de" />
*Figura 5.La imagen muestra el diseño del algoritmo representado en pseudocódigo utilizando PSeInt.

## Ejecución de pseudocódigo de los ejercicios de Prueba de Escritorio.

![63c3f3c8-6b11-454c-8626-4fa5fc8229b5](https://github.com/user-attachments/assets/0447e63d-95de-43bb-936a-9eb18c11a6a2)

*Figura 6.Resultado de la ejecución del primer ejemplo de prueba de escritorio.

![258f4e53-a5f4-4eb8-8522-186d0bc05551](https://github.com/user-attachments/assets/5a8d361a-aebf-4c91-ab2a-2f7225712742)

*Figura 7.Resultado de la ejecución del segundo ejemplo de prueba de escritorio.

![322f9f98-a42e-430c-8150-a8eacdac01e9](https://github.com/user-attachments/assets/3fae2da8-c565-4aa8-91e9-f7e07dfd8716)

*Figura 8.Resultado de la ejecución del tercer ejemplo de prueba de escritorio.

## 🔄 Diagrama de Flujo

El **diagrama de flujo** es la forma de describir un algoritmo mediante figuras como **romboides, rectángulos y flechas**, que permiten visualizar el proceso paso a paso.

## 🔄 Representación en Diagrama de Flujo:

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



<img width="500" height="2039" alt="Captura de pantalla (76)" src="https://github.com/user-attachments/assets/fbe333c4-baf5-4185-9eee-af01f9202c12" />
*Figura 9.En la presente imagen se muestra como esta estructurado un Diagrama de flujo.

<p align="center">
  <a href="01 Carátula.md">⬅️ Anterior</a> |
  <a href="index.md">🏠 Índice</a> |
  <a href="03 Programacion en Pseint.md">➡️ Siguiente</a>
</p>
