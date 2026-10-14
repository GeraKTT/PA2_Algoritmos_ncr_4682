# README — Evaluación

> **Curso:** ALGORITMO Y ESTRUCTURA DE DATOS BASADOS EN INTELIGENCIA ARTIFICIAL  
> **Código:** 4682  
> **Evaluación:** PA2  
> **Equipo:** Grupo 4

## 1. Integrantes

| Integrante | Rol | Aporte principal |
|---|---|---|
| Geraldine Khatrina Tudela Theo | Desarrolladora | Resolución de la Actividad 1: Fundamentos y representación gráfica (Lista enlazada simple para el caso). |
| Mijail mendoza chavez | programador |Desarrollo de la Actividad 2: Algoritmos de recorrido completo e inserción de solicitudes al inicio, al final y después de un nodo específico en una lista enlazada simple. Elaboración de pseudocódigos, diagramas, análisis de complejidad y pruebas en Java. |
| Luis German Guerrero Peña | Analista | Resolución de la Actividad 3: Algoritmos de búsqueda, modificación y eliminación en lista enlazada simple, con comparación de eficiencia. |
| Victor Manuel Fabricio Quispe Gonzales | Analista | Resolución de la Actividad 4 |

## 2. Descripción y objetivo
**Problema:**
La organización requiere un sistema para gestionar una secuencia dinámica de solicitudes de atención. El registro cambia constantemente debido al ingreso de nuevos casos, la eliminación de solicitudes procesadas, la reubicación de turnos y la necesidad en ciertos módulos de navegar en ambos sentidos o mantener un ciclo continuo de revisión sin detener el sistema.

**Objetivo:**
Diseñar y modelar una solución técnica utilizando estructuras lineales dinámicas (listas enlazadas simples, dobles y circulares) para administrar las solicitudes, asegurando flexibilidad en la asignación de memoria y optimizando la eficiencia de las operaciones de inserción, eliminación y recorrido continuo.

**Solución desarrollada:**
El equipo diseñó la gestión del sistema en las siguientes etapas:
*   **Fundamentos y Modelado Base (Listas Simples):** Representación gráfica y lógica de una lista enlazada unidireccional, desarrollando los algoritmos principales para recorrer, buscar, modificar e insertar nuevas solicitudes al inicio, final o en puntos intermedios (Actividades 1, 2 y 3).
*   **Algoritmos de Eliminación:** Lógica para desvincular nodos reajustando los punteros adecuadamente para evitar fugas de memoria (Actividad 3).
*   **Estructuras Avanzadas (Listas Dobles y Circulares):** Sustentación técnica de módulos especializados (como auditoría de supervisores y monitores de sala de espera) donde una lista bidireccional ($O(1)$ para retrocesos) y un bucle continuo sin terminador `null` superan la eficiencia de una lista simple (Actividad 4).

```bash
# Escribir aquí los comandos necesarios
```

**Pasos de revisión:**
```bash
# 1. Clonar el repositorio en la máquina local
git clone [https://github.com/GeraKTT/PA2_Algoritmos_ncr_4682.git](https://github.com/GeraKTT/PA2_Algoritmos_ncr_4682.git)

# 2. Navegar al directorio del proyecto
cd PA2_Algoritmos_ncr_4682
```
> No publicar contraseñas, tokens, credenciales ni datos sensibles.

## 4. Evidencias

Agregar aquí capturas, resultados, pruebas o enlaces que demuestren el funcionamiento.

- Actividad 1 Fundamentos y representación de listas enlazadas:

- Actividad 2 Recorrido e inserción:

- Actividad 3 Lista enlazada simple: búsqueda, modificación y eliminación:
  
- Actividad 4 Listas dobles y circulares:


## 5. Matriz de participación

| Integrante | Desarrollo | Pruebas | Documentación | Exposición | Evidencia de participación |
|---|---|---|---|---|---|
| Geraldine Khatrina Tudela Theo | Alta | Alta | Media |  | Desarrollo de la Actividad 1, PDF y aporte al README. |
| Mijail mendoza chavez | alta | alta| media |  | Desarrollo de la Actividad 2, PDF y aporte al README. |
| Luis German Guerrero Peña | No | No | No | No | No|
| Victor Manuel Fabricio Quispe Gonzales | Alta | Alta | Media |  | Desarrollo de actividad 4 , evidencia , README |

## 6. Video de exposición

**Video público de YouTube:**

- [Actividad 3](https://youtu.be/Ncj-AChbx7o)
- [Actividad 4](https://youtu.be/aa_Sd9QqeMU)
 




## 7. Conclusiones

El diseño de este módulo de gestión de solicitudes demuestra que la elección del tipo de lista enlazada impacta directamente en el rendimiento algorítmico del sistema. Mientras que la lista enlazada simple es óptima para registrar y atender un flujo lineal básico, operaciones de retroceso frecuente o presentación en ciclo continuo (como en monitores públicos) revelan las limitaciones de la unidireccionalidad y del puntero nulo al final de la estructura.La integración de listas doblemente enlazadas y listas circulares permite resolver estos cuellos de botella al reducir la complejidad temporal (O(n) a O(1)) en las navegaciones inversas y eliminar procesos de reinicio manual, probando que las estructuras dinámicas deben elegirse basándose exclusivamente en el comportamiento y requerimientos de lectura de cada proceso en particular.

---
**Última actualización:** [13/10/2026]
