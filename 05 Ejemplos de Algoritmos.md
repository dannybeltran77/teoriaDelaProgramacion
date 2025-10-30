[🏠 Volver al inicio](index.md)

# 🔢 Ejemplos de Algoritmos con Estructuras Lineales/Secuenciales



## 📝 Problema

Realice un programa que, tomando una cantidad expresada en **metros**, la transforme a su equivalente en:

- **Kilómetros (km)**  
- **Centímetros (cm)**  
- **Milímetros (mm)**



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

# 🧩 Etapas del Proceso de Programación

## ⚙️ Compilación
La **compilación** consiste en traducir el *código fuente* a un lenguaje que la computadora pueda comprender.  
Durante este proceso, el compilador analiza el programa, identifica posibles errores de sintaxis y genera un archivo ejecutable o interpretable.

---

## ▶️ Ejecución
La **ejecución** es la fase en la que el programa se pone en marcha.  
En este punto, la computadora **interpreta y ejecuta las instrucciones** del programa, mostrando los resultados esperados o realizando las acciones establecidas.

---

> 💡 **Nota:** Ambas etapas son esenciales en el desarrollo de software, ya que garantizan que el código sea correcto y funcional antes de su uso final.

# 🧾 Prueba de Escritorio — Conversión de Metros

| Prueba | Metros (`numero`) | Cálculo Kilómetros (`km`) | Cálculo Centímetros (`cm`) | Cálculo Milímetros (`mm`) | Resultado Esperado |
|--------|-----------------|---------------------------|----------------------------|---------------------------|------------------|
| 1      | 100             | 100 / 1000 = 0.1         | 100 * 100 = 10000          | 100 * 1000 = 100000       | km: 0.1, cm: 10000, mm: 100000 |
| 2      | 200             | 200 / 1000 = 0.2         | 200 * 100 = 20000          | 200 * 1000 = 200000       | km: 0.2, cm: 20000, mm: 200000 |
| 3      | 150             | 150 / 1000 = 0.15        | 150 * 100 = 15000          | 150 * 1000 = 150000       | km: 0.15, cm: 15000, mm: 150000 |



## 🖥️ Implementación en Visual Studio

### 🖥️ Código Fuente del Algoritmo

En la siguiente imagen se muestra cómo el **algoritmo ha sido traducido a código fuente** utilizando un **lenguaje de programación**.

<img width="3840" height="2160" alt="Captura de pantalla (80)" src="https://github.com/user-attachments/assets/e05e9724-74df-4201-89fa-61a5995dcdc6" />

## 🧠 Compilación del Código Fuente

Ahora vamos a **compilar nuestro código fuente**.  
Para realizar la compilación, debemos **abrir la terminal** y escribir el comando correspondiente según el nombre del archivo.

En este caso, la línea utilizada para compilar es la siguiente:

```bash
gcc .\convertirMetros.c -o convertirMetros
```

<img width="900" height="2160" alt="Captura de pantalla (98)" src="https://github.com/user-attachments/assets/7edc9914-ba43-4203-8f98-6eeff9f299f1" />



## ▶️ Ejecución del Programa

Para **ejecutar el programa**, escribimos el siguiente comando en la terminal:

```bash
.\convertirMetros.exe
```

<img width="900" height="2160" alt="Captura de pantalla (99)" src="https://github.com/user-attachments/assets/46686910-54c8-4e57-ada7-653ca586b193" />



# 🏥 Problema 2: Distribución del Presupuesto en un Hospital


## 📝 Problema

En un hospital existen tres áreas: **Ginecología**, **Pediatría** y **Traumatología**.  
El presupuesto anual del hospital se reparte conforme a la siguiente tabla:

- **Ginecología:** 40%  
- **Traumatología:** 30%  
- **Pediatría:** 30%  

**Objetivo:** Obtener la cantidad de dinero que recibirá cada área para cualquier monto presupuestal.


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


# 🧾 Prueba de Escritorio — Conversión de Metros
# 🧾 Pruebas de Escritorio — Distribución del Presupuesto (Valores Bajos)

| Prueba | Presupuesto (`pago`) | Cálculo Ginecología (`sueldoG`) | Cálculo Traumatología (`sueldoT`) | Cálculo Pediatría (`sueldoP`) | Resultado Esperado |
|--------|---------------------|---------------------------------|----------------------------------|--------------------------------|------------------|
| 1      | 1000                | 1000 * 40 / 100 = 400           | 1000 * 30 / 100 = 300            | 1000 * 30 / 100 = 300          | G: 400, T: 300, P: 300 |
| 2      | 500                 | 500 * 40 / 100 = 200            | 500 * 30 / 100 = 150             | 500 * 30 / 100 = 150           | G: 200, T: 150, P: 150 |
| 3      | 750                 | 750 * 40 / 100 = 300            | 750 * 30 / 100 = 225             | 750 * 30 / 100 = 225           | G: 300, T: 225, P: 225 |



## 🖥️ Implementación en Visual Studio

<img width="3840" height="2160" alt="Captura de pantalla (78)" src="https://github.com/user-attachments/assets/ab06f435-ff1c-4f5c-86e9-d92316a51264" />

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



## ▶️ Ejecución del Programa

Para **ejecutar el programa**, escribimos el siguiente comando en la terminal:

```bash
.\presupuesto.exe
```

<img width="900" height="2160" alt="Captura de pantalla (101)" src="https://github.com/user-attachments/assets/af547e46-735e-4f18-aaea-19a60adb0046" />



<p align="center">
  <a href="04 Programación por Bloques.md">⬅️ Anterior</a> |
  <a href="index.md">🏠 Índice</a> |
  <a href="06 Programa en C con Estructuras Secuenciales.md">➡️ Siguiente</a>
</p>
