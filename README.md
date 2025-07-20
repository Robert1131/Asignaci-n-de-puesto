# Simulación de Asignación de Asientos en Atracción - C#

##  Descripción

Este proyecto simula la asignación de **30 asientos en orden de llegada** para una atracción en un parque de diversiones. Utiliza el lenguaje **C#** con **Programación Orientada a Objetos (POO)** para modelar a los visitantes, la cola de espera y la asignación secuencial de asientos.

---

## Objetivo

Asegurar que cada persona en la cola suba a la atracción respetando el **orden de llegada** hasta que todos los asientos estén ocupados.

---

## Características del Proyecto

- Asignación de asientos mediante una **estructura tipo cola (FIFO)**.
- Se admiten hasta **30 visitantes**, los adicionales no serán aceptados.
- Generación de un **reporte final** mostrando el asiento asignado a cada persona.
- Implementado en **C#** con uso de **clases, listas, colas y métodos**.

---

## Estructura de Datos Utilizada

- **Queue (Cola)**: Para representar el orden de llegada de los visitantes.
- **List**: Para almacenar los visitantes que han recibido su asiento.

### Ventajas

- Mantiene el orden FIFO (First In First Out).
- Ideal para simulaciones de espera o filas.

###  Desventajas

- Acceso secuencial (no permite acceder a elementos intermedios de forma directa).
- Una vez procesado un visitante, no puede volver a la cola sin reiniciar.

---

##  Análisis de Complejidad

- **Complejidad Temporal:** O(n), siendo n ≤ 30.
- **Complejidad Espacial:** O(n), por el almacenamiento en la cola y la lista.

