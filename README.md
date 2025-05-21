# 🔁 Proyecto Java – Estructuras de Repetición

Este proyecto en Java presenta una serie de ejercicios prácticos que ilustran el uso de estructuras de repetición (`for`, `while`, `do-while`) y bucles anidados. Está pensado para reforzar conceptos fundamentales de programación estructurada y control de flujo en Java.

---

## 📚 Tabla de Contenidos

- [Parte 1: Contador con `for`](#parte-1-contador-con-for)
- [Parte 2: Suma con `while`](#parte-2-suma-con-while)
- [Parte 3: Validación con `do-while`](#parte-3-validación-con-do-while)
- [Parte 4: Tablas de multiplicar con bucles anidados](#parte-4-tablas-de-multiplicar-con-bucles-anidados)
- [Parte 5: Rectángulo de caracteres con bucles anidados](#parte-5-rectángulo-de-caracteres-con-bucles-anidados)
- [Conclusión](#conclusión)

---

## 🧩 Parte 1: Contador con `for`

Esta sección muestra cómo usar el bucle `for` para recorrer un rango numérico de forma controlada.

### ✨ Objetivo
Mostrar los primeros 10 números naturales (del 1 al 10).

### 📦 Clase involucrada
- `ContadorFor`

```java
for (int i = 1; i <= 10; i++) {
    System.out.println("Número: " + i);
}
```

---

## 🧩 Parte 2: Suma con `while`

Se demuestra el uso de `while` para acumular números introducidos por el usuario hasta que se ingrese el valor 0.

### ✨ Objetivo
Leer números por teclado y sumarlos mientras el número ingresado no sea 0.

### 📦 Clase involucrada
- `SumaWhile`

```java
while (numero != 0) {
    suma += numero;
    numero = sc.nextInt();
}
```

---

## 🧩 Parte 3: Validación con `do-while`

Se emplea `do-while` para asegurar que el usuario ingrese un número válido, en este caso, una edad positiva.

### ✨ Objetivo
Validar que el usuario ingrese una edad mayor a cero.

### 📦 Clase involucrada
- `ValidacionEdad`

```java
do {
    edad = sc.nextInt();
} while (edad <= 0);
```

---

## 🧩 Parte 4: Tablas de multiplicar con bucles anidados

Utiliza bucles `for` anidados para imprimir las tablas de multiplicar del 1 al 3.

### ✨ Objetivo
Generar las tablas de multiplicar del 1 al 3 hasta el 10.

### 📦 Clase involucrada
- `TablasMultiplicar`

```java
for (int tabla = 1; tabla <= 3; tabla++) {
    for (int i = 1; i <= 10; i++) {
        System.out.println(tabla + " x " + i + " = " + (tabla * i));
    }
}
```

---

## 🧩 Parte 5: Rectángulo de caracteres con bucles anidados

Un ejemplo más avanzado de bucles anidados que dibuja un rectángulo de caracteres a partir de un ancho y alto definidos por el usuario.

### ✨ Objetivo
Dibujar un rectángulo en consola con un carácter fijo y dimensiones validadas por el usuario.

### 📦 Clase involucrada
- `RectanguloCaracteres`

```java
for (int f = 1; f <= alto; f++) {
    for (int c = 1; c <= ancho; c++) {
        System.out.print(CARACTER);
    }
    System.out.println();
}
```

---

## ✅ Conclusión

Este proyecto sirve como una introducción sólida a las **estructuras de control repetitivas** en Java. Mediante ejercicios simples y progresivos se interiorizan conceptos como:

- Bucle controlado con `for`
- Acumulación con `while`
- Validación de entrada con `do-while`
- Bucles anidados para generar estructuras visuales

Estas estructuras son fundamentales en la programación de cualquier lenguaje y constituyen una base imprescindible para resolver problemas algorítmicos más complejos.

---

📌 Autor: GIOVANNI GIANNONI  
