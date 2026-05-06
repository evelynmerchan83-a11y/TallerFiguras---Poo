# Taller: Figuras Geométricas (POO en Python) 🐍

Este repositorio contiene la resolución del taller práctico de Programación Orientada a Objetos, siguiendo los requerimientos del diagrama de clases proporcionado.

## 🎯 Objetivos del Proyecto
*   **Encapsulamiento:** Atributos privados (`_ancho`, `_alto`) con validación mediante `@property` y `@setter`.
*   **Herencia:** Jerarquía de clases para Cuadrado y Rectángulo.
*   **Polimorfismo:** Implementación de funciones para sumar áreas y perímetros de una lista de objetos.

## 📂 Estructura de la Entrega
El proyecto está dividido en los siguientes archivos según el estándar PEP8:
*   `figura_geometrica.py`: Clase base con validaciones.
*   `cuadrado.py`: Clase hija especializada en cuadrados.
*   `rectangulo.py`: Clase hija especializada en rectángulos.
*   `main.py`: Programa principal con pruebas y funciones polimórficas.

## 🛠️ Explicación Breve de Clases
1.  **FiguraGeometrica:** Gestiona las dimensiones básicas y asegura que no sean negativas (lanza `ValueError`).
2.  **Cuadrado:** Recibe un solo lado y configura el ancho y alto automáticamente.
3.  **Rectangulo:** Implementa el cálculo de área y perímetro para dimensiones variables.

## 📸 Evidencia de Ejecución
Aquí se muestra la ejecución del programa, los resultados de los cálculos y la validación de errores:

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ad7bdee4-70ff-44bc-8830-8b0bab7b7cb8" />
