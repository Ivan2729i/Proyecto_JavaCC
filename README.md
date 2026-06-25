# 🧠 Virgulilla Compiler

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)
![JavaCC](https://img.shields.io/badge/JavaCC-Parser%20Generator-blue?style=for-the-badge)
![ASM](https://img.shields.io/badge/ASM-x86-purple?style=for-the-badge)
![TASM](https://img.shields.io/badge/TASM-Compatible-green?style=for-the-badge)
![DOSBox](https://img.shields.io/badge/DOSBox-Execution-black?style=for-the-badge)

**Virgulilla Compiler** es un compilador académico desarrollado en **Java** utilizando **JavaCC**, creado como proyecto para la materia de **Autómatas**.

El proyecto tiene como objetivo analizar un lenguaje personalizado, generar código intermedio, aplicar procesos de optimización y producir código ensamblador compatible con **TASM/DOSBox**.

---

## 📌 Descripción del proyecto

**Virgulilla** procesa instrucciones escritas en un lenguaje propio y las transforma a través de las fases principales de un compilador.

El flujo general del compilador incluye:

1. Análisis léxico
2. Análisis sintáctico
3. Generación de código intermedio
4. Generación de cuádruplos
5. Optimización de código
6. Generación de código ensamblador

Este proyecto permite comprender de forma práctica cómo una instrucción escrita en un lenguaje de alto nivel puede convertirse progresivamente en instrucciones de bajo nivel ejecutables por una computadora.

---

## 🚀 Tecnologías utilizadas

* **Java**
* **JavaCC**
* **ASM x86**
* **TASM**
* **DOSBox**
* **Git / GitHub**

---

## ⚙️ Características principales

* Análisis léxico mediante **JavaCC**.
* Análisis sintáctico del lenguaje **Virgulilla**.
* Generación de código intermedio.
* Manejo de variables temporales.
* Generación de cuádruplos.
* Soporte para estructuras de control.
* Aplicación de optimizaciones al código generado.
* Generación de código ensamblador.
* Ejecución del código ASM mediante **TASM** y **DOSBox**.

---

## 🧩 Estructuras soportadas

El compilador contempla estructuras básicas de programación como:

```txt
if
else
elseif
while
for
```

Estas estructuras son analizadas y transformadas en representaciones intermedias para posteriormente generar código ensamblador.

---

## 🔄 Flujo general del compilador

```text
Código fuente Virgulilla
        |
        v
Análisis léxico
        |
        v
Análisis sintáctico
        |
        v
Código intermedio
        |
        v
Cuádruplos
        |
        v
Optimización
        |
        v
Código ensamblador
        |
        v
Ejecución en DOSBox/TASM
```
---

## ▶️ Ejecución del proyecto

### 1. Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
cd NOMBRE_DEL_REPOSITORIO
```

### 2. Generar el parser con JavaCC

```bash
javacc Virgulilla.jj
```

### 3. Compilar los archivos Java

```bash
javac *.java
```

### 4. Ejecutar el compilador

```bash
java Main archivo_fuente.vg
```

### 5. Ejecutar el ASM generado en DOSBox

```asm
mount c C:\ruta\del\proyecto
c:
tasm salida.asm
tlink salida.obj
salida.exe
```
---

## 👨‍💻👤 Contacto

Desarrollado por **Ivan Paz Valladares**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ivan-paz-valladares-b8886a343)
---
