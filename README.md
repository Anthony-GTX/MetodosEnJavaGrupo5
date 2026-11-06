# Métodos en Java · APE 4

**Algoritmos y Lógica de Programación** · Ingeniería en Software · Primer Semestre, Paralelo "B"
**Universidad Técnica de Ambato (UTA)** · Facultad de Ingeniería en Sistemas, Electrónica e Industrial
**Ciclo académico:** julio – diciembre 2026 · **Docente:** Ing. José Rubén Caiza Caizabuano, Mg.

> SW-AyLP-APE-04: **Clases, Objetos y Métodos**

---

## 👥 Integrantes — Grupo 5

- Anthony Armas
- Sandra Alulema
- Joselyn Guamán
- Valeria Ortiz
- Andrés Vayas

---

## 📖 Descripción

Repositorio con los ejercicios de la **APE 4**, desarrollados en **Java**. El objetivo es crear programas con **clases, objetos y métodos**, lo que ayuda a reducir errores y a reutilizar el código.

Los 18 ejercicios están organizados en tres partes:

| Parte | Tema | Códigos |
|:---:|---|:---:|
| **A** | Métodos, parámetros, `void` vs. `return` y paso por valor | 01 – 08 |
| **B** | Integración de clases, objetos y métodos | 09 – 13 |
| **C** | Introducción a la programación orientada a objetos | 14 – 18 |

## 🗂️ Estructura del repositorio

Cada ejercicio está en su propia carpeta, numerada en orden, y se puede compilar y ejecutar de forma independiente.

```
Codigos_APE4/
├── Codigo_01_A1_Tipos_de_retorno/
├── Codigo_02_A2_Metodo_void_Bienvenida/
├── Codigo_03_A3_Parametros_vs_argumentos/
├── Codigo_04_A4_Paso_por_valor/
├── Codigo_05_A5_Multiples_parametros_Calculadora/
├── Codigo_06_A6_Validacion_verificarEdad/
├── Codigo_07_A7_Completar_clase_Producto/
├── Codigo_08_A8_Instanciacion_en_el_main/
├── Codigo_09_B1_Libro_y_Autor/
├── Codigo_10_B2_Rectangulo/
├── Codigo_11_B3_Producto_y_Venta/
├── Codigo_12_B4_Transferencias/
├── Codigo_13_B5_Biblioteca_Usuario_Libro_Prestamo/
├── Codigo_14_C1_Notas_del_curso/
├── Codigo_15_C2_Inventario_de_una_tienda/
├── Codigo_16_C3_Veterinaria/
├── Codigo_17_C4_Cuenta_de_ahorro/
├── Codigo_18_C5_Biblioteca/
└── LEEME.txt
```

## 📝 Ejercicios

### Parte A · Métodos, parámetros y paso por valor

| Código | Ejercicio | Concepto clave |
|:---:|---|---|
| 01 | Tipos de retorno | Todo método con tipo distinto de `void` debe usar `return` |
| 02 | Método `void` (Bienvenida) | Acciones directas sin devolver valor |
| 03 | Parámetros vs. argumentos | Parámetro = variable de la firma; argumento = valor enviado |
| 04 | Paso por valor | El método trabaja con una copia (imprime 15 dentro y 10 fuera) |
| 05 | Calculadora | Método con múltiples parámetros (`calcularPromedio`) |
| 06 | Validación de datos | `verificarEdad` retorna `true` / `false` |
| 07 | Clase Producto | Completar la clase con `calcularValorTotal()` |
| 08 | Instanciación en el `main` | Crear el objeto, asignar atributos e invocar métodos |

### Parte B · Integración de clases, objetos y métodos

| Código | Ejercicio | Concepto clave |
|:---:|---|---|
| 09 | Libro y Autor | Objeto como atributo |
| 10 | Rectángulo | Firmas de métodos con distintos tipos de retorno |
| 11 | Producto y Venta | Objeto como parámetro y control de stock |
| 12 | Transferencias | Método `transferir(Cuenta destino, double monto)` |
| 13 | Biblioteca | Colaboración entre `Usuario`, `Libro` y `Prestamo` |

### Parte C · Introducción a la POO

| Código | Ejercicio | Concepto clave |
|:---:|---|---|
| 14 | Notas del curso | Clase `Estudiante`, promedio y condicionales |
| 15 | Inventario de una tienda | Stock, alerta «Reponer» y valor total |
| 16 | Veterinaria | Referencias entre objetos (`Mascota m4 = m1;`) |
| 17 | Cuenta de ahorro | Ciclo `while` con depósitos mensuales |
| 18 | Biblioteca | Atributo `boolean` y contadores de préstamos |

## ⚙️ Requisitos

- **JDK 8 o superior** (probado con JDK 21)
- Terminal o un IDE como **Visual Studio Code**

## ▶️ Cómo ejecutar

Cada carpeta es independiente. Ejemplo con el Código 05:

```bash
cd Codigos_APE4/Codigo_05_A5_Multiples_parametros_Calculadora
javac -encoding UTF-8 *.java
java Main
```

Salida esperada:

```
Promedio: 16.333333333333332
```

## 🧰 Tecnologías

- Java
- Visual Studio Code
- Git y GitHub

---

<p align="center">Universidad Técnica de Ambato · Ingeniería en Software · 2026</p>
