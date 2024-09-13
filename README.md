¡Claro! Comencemos a aprender Python paso a paso, introduciendo los conceptos básicos de la programación. Este tutorial está diseñado para estudiantes que están iniciando en Python por primera vez.

---

## **1. Introducción a Python**

Python es un lenguaje de programación interpretado y de alto nivel, conocido por su sintaxis sencilla y legible. Es ideal para principiantes y se utiliza en diversas áreas como desarrollo web, ciencia de datos, inteligencia artificial y más.

## **2. Instalación de Python**

Antes de empezar, debes instalar Python en tu computadora:

1. **Descarga Python** desde la página oficial: [python.org/downloads](https://www.python.org/downloads/).
2. **Instálalo** siguiendo las instrucciones para tu sistema operativo (Windows, macOS o Linux).
3. **Verifica la instalación** abriendo una terminal o símbolo del sistema y escribiendo `python --version`.

## **3. Tu primer programa: "Hola, Mundo"**

Comencemos escribiendo un programa simple que imprima "Hola, Mundo" en la pantalla.

```python
print("Hola, Mundo")
```

**Explicación:**

- `print()` es una función que muestra el mensaje que colocamos entre paréntesis.
- Las comillas indican que estamos trabajando con una cadena de texto.

## **4. Variables y Tipos de Datos**

Las variables son espacios en la memoria donde almacenamos datos. En Python, no es necesario declarar el tipo de variable explícitamente.

### **Ejemplo:**

```python
# Declaración de variables
nombre = "Juan"
edad = 25
altura = 1.75
```

**Explicación:**

- `nombre` es una variable tipo cadena (str).
- `edad` es una variable tipo entero (int).
- `altura` es una variable tipo flotante (float).

## **5. Operaciones Básicas**

Puedes realizar operaciones matemáticas con variables numéricas.

### **Ejemplo:**

```python
a = 10
b = 5

suma = a + b
resta = a - b
producto = a * b
division = a / b

print("Suma:", suma)
print("Resta:", resta)
print("Producto:", producto)
print("División:", division)
```

## **6. Entrada de Datos**

Usamos la función `input()` para recibir datos del usuario.

### **Ejemplo:**

```python
nombre = input("¿Cómo te llamas? ")
print("Hola, " + nombre)
```

**Nota:** Por defecto, `input()` devuelve una cadena de texto.

## **7. Condicionales**

Las estructuras condicionales nos permiten ejecutar código basándonos en ciertas condiciones.

### **Ejemplo:**

```python
edad = int(input("Ingresa tu edad: "))

if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")
```

**Explicación:**

- Convertimos la entrada a entero usando `int()`.
- Utilizamos `if` y `else` para decidir qué bloque de código ejecutar.

## **8. Bucles**

### **8.1. Bucle While**

Se utiliza cuando no sabemos cuántas veces se ejecutará el bloque de código.

```python
contador = 0

while contador < 5:
    print("Contador:", contador)
    contador += 1
```

### **8.2. Bucle For**

Se utiliza para iterar sobre una secuencia (como una lista o rango).

```python
for i in range(5):
    print("Valor de i:", i)
```

**Explicación:**

- `range(5)` genera una secuencia de números de 0 a 4.

## **9. Listas**

Las listas son colecciones ordenadas que pueden cambiarse.

### **Ejemplo:**

```python
frutas = ["manzana", "banana", "cereza"]
print(frutas[0])  # Accede al primer elemento

frutas.append("naranja")  # Agrega un elemento al final
print(frutas)
```

## **10. Funciones**

Las funciones son bloques de código reutilizables que realizan una tarea específica.

### **Ejemplo:**

```python
def saludo(nombre):
    print("Hola, " + nombre)

saludo("Ana")
saludo("Luis")
```

**Explicación:**

- Definimos la función `saludo` que recibe un parámetro `nombre`.
- Llamamos a la función pasando diferentes nombres.

## **11. Ejercicio Práctico: Calculadora Sencilla**

Combina lo aprendido para crear una calculadora básica.

```python
def calculadora():
    print("Bienvenido a la calculadora")
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))

    print("Selecciona una operación:")
    print("1. Sumar")
    print("2. Restar")
    print("3. Multiplicar")
    print("4. Dividir")

    opcion = input("Ingresa el número de la operación: ")

    if opcion == "1":
        resultado = num1 + num2
        print("El resultado es:", resultado)
    elif opcion == "2":
        resultado = num1 - num2
        print("El resultado es:", resultado)
    elif opcion == "3":
        resultado = num1 * num2
        print("El resultado es:", resultado)
    elif opcion == "4":
        if num2 != 0:
            resultado = num1 / num2
            print("El resultado es:", resultado)
        else:
            print("Error: División por cero")
    else:
        print("Opción no válida")

calculadora()
```

## **12. Comentarios**

Los comentarios son notas que el intérprete de Python ignora, pero son útiles para explicar el código.

### **Ejemplo:**

```python
# Esto es un comentario de una sola línea

"""
Esto es un comentario
de varias líneas
"""
```

## **13. Buenas Prácticas**

- **Nombres descriptivos:** Usa nombres de variables y funciones que reflejen su propósito.
- **Indentación:** Python utiliza indentación para definir bloques de código. Asegúrate de ser consistente.
- **Comentarios:** Comenta tu código para facilitar su comprensión.

## **14. Próximos Pasos**

- **Explora módulos y librerías:** Python tiene una amplia gama de librerías estándar y de terceros.
- **Practica:** La mejor manera de aprender a programar es escribiendo código.
- **Proyectos pequeños:** Intenta crear pequeños programas que resuelvan problemas cotidianos.

---

¡Felicidades! Has dado tus primeros pasos en la programación con Python. Continúa practicando y explorando más características del lenguaje.