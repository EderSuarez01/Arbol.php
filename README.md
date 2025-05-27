#Árbol Binario 

Este proyecto es una implementación sencilla de un **Árbol Binario de Búsqueda (ABB)** en PHP. Incluye métodos para insertar nodos y realizar recorridos en inorden, preorden y postorden. Es ideal para estudiantes o desarrolladores que buscan entender cómo funcionan las estructuras de datos jerárquicas de forma clara y estructurada.

---

##Estructura del Proyecto

El código se compone de dos clases principales:

- **`Nodo`**: Representa cada nodo del árbol. Contiene tres propiedades:
  - `valor`: El valor almacenado.
  - `izquierdo`: Referencia al hijo izquierdo.
  - `derecho`: Referencia al hijo derecho.

- **`ArbolBinario`**: Maneja la lógica del árbol. Contiene:
  - Una propiedad privada `raiz`, que almacena el nodo raíz.
  - Métodos para insertar nodos y recorrer el árbol en diferentes órdenes.

---

##Funcionalidades

- **Inserción de nodos (`insertar`)**: Inserta un valor respetando la regla del ABB:
  - Los valores menores al nodo actual van a la izquierda.
  - Los valores mayores van a la derecha.

- **Recorridos**:
  - `inOrden()`: Izquierda – Raíz – Derecha.
  - `preOrden()`: Raíz – Izquierda – Derecha.
  - `postOrden()`: Izquierda – Derecha – Raíz.

Estos recorridos permiten ver el contenido del árbol de distintas formas útiles para búsqueda, ordenamiento o análisis.



