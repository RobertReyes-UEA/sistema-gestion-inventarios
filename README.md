# Sistema de Gestión de Inventarios

## Descripción

Este proyecto consiste en el desarrollo de un **Sistema de Gestión de Inventarios** para una tienda, implementado en Python aplicando los principios fundamentales de la **Programación Orientada a Objetos (POO)**.

El sistema permite gestionar productos mediante un menú interactivo en consola, ofreciendo funcionalidades para añadir, actualizar, eliminar, buscar y listar productos almacenados en el inventario.

---

## Objetivo del Proyecto

Desarrollar un sistema funcional que:

- Aplique correctamente los conceptos de clases y objetos.
- Utilice encapsulación.
- Implemente una estructura modular organizada.
- Valide entradas del usuario.
- Permita la gestión eficiente de productos en memoria.

---

## Estructura del Proyecto
sistema-gestion-inventarios/
│
├── modelos/
│ └── producto.py
│
├── servicios/
│ └── inventario.py
│
└── main.py

###  Descripción de Archivos

- **modelos/producto.py** → Contiene la clase `Producto`.
- **servicios/inventario.py** → Contiene la clase `Inventario` y la lógica de gestión.
- **main.py** → Punto de entrada del programa y menú interactivo.

---

##  Conceptos de POO Aplicados

### Clase Producto
Representa la entidad principal del sistema.

**Atributos:**
- ID (único)
- Nombre
- Cantidad
- Precio

Se aplica **encapsulación** mediante atributos privados y métodos getters y setters.

---

### Clase Inventario
Gestiona los productos almacenados en una lista.

**Funciones implementadas:**
- Añadir producto (validando ID único)
- Eliminar producto por ID
- Actualizar cantidad o precio
- Buscar productos por nombre (coincidencias parciales)
- Mostrar todos los productos

---

## Funcionalidades del Sistema

El menú en consola permite:

1. Añadir producto
2. Eliminar producto
3. Actualizar producto
4. Buscar producto
5. Listar inventario
6. Salir del sistema

---
