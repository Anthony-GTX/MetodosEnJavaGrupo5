# Práctica evaluativa: Clase Producto (Java)

Ejercicio de consolidación de métodos, parámetros, `void` vs. `return` y paso por valor (Clase N°03, Cierre de Grupo 2).

## Integrantes

- Anthony Armas
- Sandra Aululema
- Joselyn Guaman
- Valeria Ortiz
- Andres Vayas

## Ejercicio asignado

Completar la clase `Producto` identificando los espacios faltantes (`___`) en la firma de los métodos, el tipo de retorno y la palabra reservada correspondiente, y probarla desde la clase principal `Main`.

La clase `Producto` tiene:

| Elemento | Tipo | Descripción |
|---|---|---|
| `nombre` | `String` | Nombre del producto |
| `precio` | `double` | Precio del producto |
| `mostrarDetalles()` | `void` | Imprime en consola el nombre y el precio. Usa `void` porque solo realiza una acción y no devuelve ningún dato |
| `calcularPrecioFinal(double porcentajeDescuento)` | `double` | Recibe el descuento en porcentaje y devuelve el precio con el descuento aplicado. Usa `return` para entregar el resultado a `Main` |

### Archivos

- `Producto.java`: clase con los atributos y los dos métodos.
- `Main.java`: clase principal que instancia el objeto `Producto` y llama a los métodos.

## Instrucciones para ejecutar

Requisito: tener instalado el JDK de Java (versión 8 o superior).

1. Clonar el repositorio y entrar a la carpeta:

   ```bash
   git clone <URL-del-repositorio>
   cd <nombre-del-repositorio>
   ```

2. Compilar los archivos:

   ```bash
   javac Producto.java Main.java
   ```

3. Ejecutar el programa:

   ```bash
   java Main
   ```

Salida esperada:

```
Producto: Laptop | Precio: $800.0
Precio final con oferta: $680.0
```

## Casos de


-No asisten
Sandra Alulema
Valentina Valeria
Joselyn Guaman 
