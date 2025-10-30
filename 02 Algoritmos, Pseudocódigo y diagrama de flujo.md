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


| 🧠 Operador | Significado    | Ejemplo              | Resultado     |          |   |          |        |
| ----------- | -------------- | -------------------- | ------------- | -------- | - | -------- | ------ |
| `&&`        | AND (y lógico) | `(5 > 3) && (8 > 6)` | `true`        |          |   |          |        |
| `           |                | `                    | OR (o lógico) | `(5 < 3) |   | (8 > 6)` | `true` |
| `!`         | NOT (negación) | `!(5 == 3)`          | `true`        |          |   |          |        |



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



## ⚙️ planteamiento



| 🧩 **Etapa**                    | 💻 **Pseudocódigo (PSeInt)**                                                                                                                                    |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **🔹 Inicio**                   | `pseudocode Inicio `                                                                                                                                            |
| **📦 Declaración de Variables** | `pseudocode // Variables  Definir sueldoG, sueldoT, sueldoP, pago Como Real; `                                                                                  |
| **📥 Datos de Entrada**         | `pseudocode // Datos de entrada  Escribir "Por favor ingrese el presupuesto total"  Leer pago; `                                                                |
| **⚙️ Proceso (Cálculos)**       | `pseudocode // Proceso  sueldoG = (pago * 40) / 100  sueldoT = (pago * 30) / 100  sueldoP = (pago * 30) / 100 `                                                 |
| **📤 Salida de Datos**          | `pseudocode // Salida  Escribir "El sueldo que debe recibir cada área es de: ", sueldoG, " Ginecología, ", sueldoT, " Traumatología, ", sueldoP, " Pediatría" ` |
| **🏁 Fin del Algoritmo**        | `pseudocode FinAlgoritmo `                                                                                                                                      |
---

📸 Pseudocódigo en Pseint

La imagen muestra el diseño del algoritmo representado en pseudocódigo utilizando PSeInt

<img width="3183" height="1474" alt="Captura de pantalla (75)" src="https://github.com/user-attachments/assets/8827687c-8f97-42d5-827a-25cf3d1a89de" />

## 🔄 Diagrama de Flujo

El **diagrama de flujo** es la forma de describir un algoritmo mediante figuras como **romboides, rectángulos y flechas**, que permiten visualizar el proceso paso a paso.

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


En la presente imagen se muestra como esta estructurado un Diagrama de flujo.
<img width="500" height="2039" alt="Captura de pantalla (76)" src="https://github.com/user-attachments/assets/fbe333c4-baf5-4185-9eee-af01f9202c12" />


<p align="center">
  <a href="01 Carátula.md">⬅️ Anterior</a> |
  <a href="index.md">🏠 Índice</a> |
  <a href="03 Programacion en Pseint.md">➡️ Siguiente</a>
</p>
