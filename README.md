# Implementación de Constructores y Destructores en Python

## Descripción del programa
Este programa simula un caso de la vida real donde se maneja un archivo del sistema.
Se aplica Programación Orientada a Objetos utilizando una arquitectura de
Modelos y Servicios para demostrar el uso de constructores y destructores en Python.

El sistema crea un archivo, escribe información en él y libera correctamente
el recurso cuando el objeto deja de existir.

---

## Estructura del proyecto
- modelos/: contiene las clases del sistema (entidades)
- servicios/: contiene la lógica que gestiona los modelos
- main.py: punto de entrada del programa

---

## Cómo ejecutar el programa
1. Abrir el proyecto en PyCharm.
2. Ejecutar el archivo `main.py`.
3. Observar la salida en consola y el archivo generado en el proyecto.

---

## Uso de __init__ y __del__

- __init__:
  Se utiliza para inicializar el objeto Archivo y abrir el archivo del sistema
  cuando se crea la instancia.

- __del__:
  Se utiliza para cerrar el archivo y liberar el recurso cuando el objeto
  deja de existir o se elimina la referencia.

La ejecución de ambos métodos se evidencia en los mensajes mostrados en consola.
