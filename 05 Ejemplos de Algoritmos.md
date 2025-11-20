[🏠 Volver al inicio](index.md)

# 🔢 Problema número uno implementado en lengiaje C

## ⚙️ Compilación
La **compilación** consiste en traducir el *código fuente* a un lenguaje que la computadora pueda comprender.  
Durante este proceso, el compilador analiza el programa, identifica posibles errores de sintaxis y genera un archivo ejecutable o interpretable.

---

## ▶️ Ejecución
La **ejecución** es la fase en la que el programa se pone en marcha.  
En este punto, la computadora **interpreta y ejecuta las instrucciones** del programa, mostrando los resultados esperados o realizando las acciones establecidas.

---

> 💡 **Nota:** Ambas etapas son esenciales en el desarrollo de software, ya que garantizan que el código sea correcto y funcional antes de su uso final.

# 🧾 Pruebas de Escritorio 

| Prueba | Metros (`numero`) | Cálculo Kilómetros (`km`) | Cálculo Centímetros (`cm`) | Cálculo Milímetros (`mm`) | Resultado Esperado |
|--------|-----------------|---------------------------|----------------------------|---------------------------|------------------|
| 1      | 100             | 100 / 1000 = 0.1         | 100 * 100 = 10000          | 100 * 1000 = 100000       | km: 0.1, cm: 10000, mm: 100000 |
| 2      | 200             | 200 / 1000 = 0.2         | 200 * 100 = 20000          | 200 * 1000 = 200000       | km: 0.2, cm: 20000, mm: 200000 |
| 3      | 150             | 150 / 1000 = 0.15        | 150 * 100 = 15000          | 150 * 1000 = 150000       | km: 0.15, cm: 15000, mm: 150000 |


### 🖥️ Código Fuente del Algoritmo

En la siguiente imagen se muestra cómo el **algoritmo ha sido traducido a código fuente** utilizando un **lenguaje de programación**.

<img width="3840" height="2160" alt="Captura de pantalla (80)" src="https://github.com/user-attachments/assets/e05e9724-74df-4201-89fa-61a5995dcdc6" />

*Figura 15.Código fuente en Visual Studio.

## 🧠 Compilación del Código Fuente

Ahora vamos a **compilar nuestro código fuente**.  
Para realizar la compilación, debemos **abrir la terminal** y escribir el comando correspondiente según el nombre del archivo.

En este caso, la línea utilizada para compilar es la siguiente:

```bash
gcc .\convertirMetros.c -o convertirMetros
```

<img width="900" height="2160" alt="Captura de pantalla (98)" src="https://github.com/user-attachments/assets/7edc9914-ba43-4203-8f98-6eeff9f299f1" />

*Figura 16.Compilación de código.


## ▶️ Ejecución del Programa

Para **ejecutar el programa**, escribimos el siguiente comando en la terminal:

```bash
.\convertirMetros.exe
```

<img width="900" height="2160" alt="Captura de pantalla (99)" src="https://github.com/user-attachments/assets/46686910-54c8-4e57-ada7-653ca586b193" />

*Figura 17.Ejecución del programa.

## 🖥️ Ejecución de los 3 casos de ejercicios.

<img width="3840" height="2160" alt="Captura de pantalla (106)" src="https://github.com/user-attachments/assets/880064e1-b027-452c-adca-3334f0536c3d" />

*Figura 18.Resultados de los tres casos de Prueba de Escritorio trasladados a Studio Version.

# 🏥 Problema número dos implementado en lenguaje C

## 🧾 Pruebas de Escritorio — Distribución del Presupuesto

| Prueba | Presupuesto (`pago`) | Cálculo Ginecología (`sueldoG`) | Cálculo Traumatología (`sueldoT`) | Cálculo Pediatría (`sueldoP`) | Resultado Esperado |
|--------|---------------------|---------------------------------|----------------------------------|--------------------------------|------------------|
| 1      | 1000                | 1000 * 40 / 100 = 400           | 1000 * 30 / 100 = 300            | 1000 * 30 / 100 = 300          | G: 400, T: 300, P: 300 |
| 2      | 500                 | 500 * 40 / 100 = 200            | 500 * 30 / 100 = 150             | 500 * 30 / 100 = 150           | G: 200, T: 150, P: 150 |
| 3      | 750                 | 750 * 40 / 100 = 300            | 750 * 30 / 100 = 225             | 750 * 30 / 100 = 225           | G: 300, T: 225, P: 225 |



## 🖥️ Implementación en Visual Studio

<img width="3840" height="2160" alt="Captura de pantalla (78)" src="https://github.com/user-attachments/assets/ab06f435-ff1c-4f5c-86e9-d92316a51264" />

*Figura 19.Diseño de código fuente en Visual Studio.

## 🖥️ Código Fuente del Algoritmo

En la siguiente imagen se muestra cómo el **algoritmo ha sido traducido a código fuente** utilizando un **lenguaje de programación**.



## 🧠 Compilación del Código Fuente

Ahora vamos a **compilar nuestro código fuente**.  
Para realizar la compilación, debemos **abrir la terminal** y escribir el comando correspondiente según el nombre del archivo.

En este caso, la línea utilizada para compilar es la siguiente:

```bash
gcc .\presupuesto.c -o presupuesto
```
<img width="900" height="2160" alt="Captura de pantalla (100)" src="https://github.com/user-attachments/assets/939cef7c-de4c-41c5-a5a3-0dd79a85a295" />

*Figura 20.Compilación del programa.


## ▶️ Ejecución del Programa

Para **ejecutar el programa**, escribimos el siguiente comando en la terminal:

```bash
.\presupuesto.exe
```

<img width="900" height="2160" alt="Captura de pantalla (101)" src="https://github.com/user-attachments/assets/af547e46-735e-4f18-aaea-19a60adb0046" />

*Figura 21.Ejecución del programa.

## Ejecución de los 3 casos del código

<img width="3840" height="2160" alt="Captura de pantalla (105)" src="https://github.com/user-attachments/assets/266c0e98-4df8-422e-97e8-d927cc12e0e6" />
 
*Figura 22.Resultado de los 3 casos de Pruebas de Escritorio trasladados a Visual Studio.

<p align="center">
  <a href="04 Programación por Bloques.md">⬅️ Anterior</a> |
  <a href="index.md">🏠 Índice</a> |
  <a href="06 Programa en C con Estructuras Secuenciales.md">➡️ Siguiente</a>
</p>
