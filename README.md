# README — Evaluación

> **Curso:** ALGORITMO Y ESTRUCTURA DE DATOS BASADOS EN INTELIGENCIA ARTIFICIAL  
> **Código:** 4682  
> **Evaluación:** PA2  
> **Equipo:** Grupo 4

## 1. Integrantes

| Integrante | Rol | Aporte principal |
|---|---|---|
| Victor Manuel Fabricio Quispe Gonzales | Analista | Resolución de la Actividad 4 |
| Geraldine Khatrina Tudela Theo | Desarrolladora | Resolución de la Actividad 2: Modelado, algoritmos de búsqueda (mayor/menor), inserción y ordenamiento (Burbuja) en vectores. |
| Luis German Guerrero Peña | Analista | Resolución de la Actividad 1: Análisis del problema y selección de estructura. |
| Mijail mendoza chavez | programador |diseño de la matriz, elaboración de algoritmos de recorrido, cálculo de totales, identificación de la mayor ocupación y desarrollo/prueba del código Java |

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
git clone [https://github.com/GeraKTT/PA1_Algoritmos_ncr_4682.git](https://github.com/GeraKTT/PA1_Algoritmos_ncr_4682.git)
# 2. Navegar al directorio del proyecto
cd PA1_Algoritmos_ncr_4682
```
> No publicar contraseñas, tokens, credenciales ni datos sensibles.

## 4. Evidencias

Agregar aquí capturas, resultados, pruebas o enlaces que demuestren el funcionamiento.

- [Evidencia 1]
- Actividad 2 (Vectores):
  ![Consola de Vectores](Actividad_2_Modelado_y_operaciones/evidencias/Evidencia_Actividad2.png)

  actividad 3 matrices y reciorridos base de datos : <img width="705" height="520" alt="Captura de pantalla 2026-09-22 231830" src="https://github.com/user-attachments/assets/109d1900-eded-471b-b6a2-920715e56e2c" />
- Actividad 4 (Matrices especiales):

  
  ![Grafico](Actividad_4_Matrices_especiales/Evidencia4.png)

## 5. Matriz de participación

| Integrante | Desarrollo | Pruebas | Documentación | Exposición | Evidencia de participación |
|---|---|---|---|---|---|
| Victor Manuel Fabricio Quispe Gonzales | Alta | Alta | Media | Sí | Desarrollo de actividad 4 , evidencia , README |
| Geraldine Khatrina Tudela Theo | Alta | Alta | Media | No | Desarrollo de actividad 2, código Java, evidencia de ejecución , aporte al README |
| Luis German Guerrero Peña | Media | Media | Media | No | [Commits, avances, etc.] |
| Mijail mendoza chavez | alta | alta| media | Sí | Desarrollo de la Actividad 3, código Java, pruebas de ejecución y aporte al README |


## 6. Video de exposición

**Video público de YouTube:**

- [Actividad 3](https://youtu.be/Ncj-AChbx7o)
- [Actividad 4](https://youtu.be/aa_Sd9QqeMU)
 




## 7. Conclusiones
El diseño de este módulo de gestión de solicitudes demuestra que la elección del tipo de lista enlazada impacta directamente en el rendimiento algorítmico del sistema. Mientras que la lista enlazada simple es óptima para registrar y atender un flujo lineal básico, operaciones de retroceso frecuente o presentación en ciclo continuo (como en monitores públicos) revelan las limitaciones de la unidireccionalidad y del puntero nulo al final de la estructura.La integración de listas doblemente enlazadas y listas circulares permite resolver estos cuellos de botella al reducir la complejidad temporal ($O(n)$ a $O(1)$) en las navegaciones inversas y eliminar procesos de reinicio manual, probando que las estructuras dinámicas deben elegirse basándose exclusivamente en el comportamiento y requerimientos de lectura de cada proceso en particular.
---

**Última actualización:** [13/10/2026]
