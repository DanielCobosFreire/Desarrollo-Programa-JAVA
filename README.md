# Tarea: Aplicación de Conceptos de POO en Java

Este proyecto fue desarrollado como parte de la asignatura **Fundamentos de Programación Orientada a Objetos**, con el objetivo de aplicar los conceptos fundamentales de la POO en Java: **Clase, Objeto, Herencia, Encapsulación y Polimorfismo**.

---

## Objetivos

- Implementar clases en Java.
- Demostrar herencia entre clases.
- Aplicar encapsulación con atributos privados y métodos públicos.
- Aplicar polimorfismo mediante sobrescritura de métodos y uso de argumentos variables.

---

## Estructura del Proyecto

src/
├── Main.java // Contiene las clases: Empleado, Gerente y clase principal

---

## Tecnologías Usadas

- Lenguaje: Java
- IDE sugerido: IntelliJ IDEA, NetBeans o Eclipse
- Control de versiones: Git & GitHub

---

## Descripción del Programa

El programa implementa una clase base `Empleado` y una clase derivada `Gerente`, demostrando:

- **Herencia**: `Gerente` hereda de `Empleado`.
- **Encapsulación**: Atributos privados con métodos `get` y `set`.
- **Polimorfismo**: Uso de sobrescritura del método `mostrarInformacion()` y un método adicional `imprimirNombres()` que utiliza parámetros variables (`varargs`).

---

## Ejecución

Ejecuta la clase `Main.java` desde tu IDE o compila desde consola:

```bash
javac src/Main.java
java src/Main

Salida Esperada

Empleado: Carlos Pérez
Salario: $1500.0

Empleado: María Gómez
Salario: $2500.0
Departamento: Finanzas

--- Lista de Empleados ---
- Carlos Pérez
- María Gómez

Autor

[DANIEL COBOS FREIRE]
Estudiante de Tecnologías de la Información
Universidad Estatal Amazónica

Contacto

Email: [DANIELCOBOS@EMAIL.com]
GitHub: https://github.com/DanielCobosFreire/
